# Python_Latihan_2

LATIHAN PEMOGRAMAN PYTHON PART II
1.	Menampilkan Teks: Buat fungsi tampilkan_teks() yang ketika dipanggil akan mencetak "Hello, Python!" ke layar.
```python
# Definisikan fungsi tampilkan_teks di sini
def tampilkan_teks():
    print("Hello, Python!")

# Uncomment untuk menguji fungsi
# tampilkan_teks()  # harus mencetak "Hello, Python!"
```

2.	Input dan Output: Buat fungsi hitung_umur() yang meminta pengguna untuk memasukkan tahun lahir dan menghitung umur pengguna berdasarkan tahun saat ini (2023).
```python
# Definisikan fungsi hitung_umur di sini
def hitung_umur():
    tahun_lahir = int(input("Masukkan tahun lahir Anda: "))
    umur = 2023 - tahun_lahir
    print(f"Umur Anda adalah {umur} tahun.")

# Uncomment untuk menguji fungsi
# hitung_umur()  # Contoh output jika tahun lahir adalah 1990: "Umur Anda adalah 33 tahun."
```

3.	Variabel: Buat fungsi tukar_variabel(a, b) yang menukar nilai dari dua variabel yang diberikan dan mengembalikan keduanya. 
```python
# Definisikan fungsi tukar_variabel di sini
def tukar_variabel(a, b):
    return b, a

# Uncomment untuk menguji fungsi
# print(tukar_variabel(3, 7))  # harus mencetak (7, 3)
```

4.	Kalkulator Sederhana: Buat fungsi kalkulator_sederhana() yang meminta pengguna untuk memasukkan dua angka dan sebuah operator (+, -, *, /) dan kemudian mengembalikan hasil operasi tersebut. 
```python
# Definisikan fungsi kalkulator_sederhana di sini
def kalkulator_sederhana():
    angka1 = float(input("Masukkan angka pertama: "))
    angka2 = float(input("Masukkan angka kedua: "))
    operator = input("Masukkan operator (+, -, *, /): ")

    if operator == '+':
        hasil = angka1 + angka2
    elif operator == '-':
        hasil = angka1 - angka2
    elif operator == '*':
        hasil = angka1 * angka2
    elif operator == '/':
        hasil = angka1 / angka2
    else:
        hasil = "Operator tidak valid"

    print(f"Hasil: {hasil}")
# Uncomment untuk menguji fungsi
# kalkulator_sederhana()  # Contoh input/output: "Masukkan angka pertama: 5", "Masukkan angka kedua: 8", "Masukkan operator: +", "Hasil: 13"
```

5.	Conditional Statement (if): Buat fungsi cek_genap_ganjil() yang meminta pengguna untuk memasukkan sebuah angka dan mengidentifikasi apakah angka tersebut genap atau ganjil. 
```python
# Definisikan fungsi cek_genap_ganjil di sini
def cek_genap_ganjil():
    angka = int(input("Masukkan sebuah angka: "))
    if angka % 2 == 0:
        print(f"Angka {angka} adalah genap.")
    else:
        print(f"Angka {angka} adalah ganjil.")

# Uncomment untuk menguji fungsi
# cek_genap_ganjil()  # Contoh output jika angka adalah 4: "Angka 4 adalah genap."
```

6.	Loop (for): Buat fungsi cetak_angka() yang mencetak angka 1 sampai 5 menggunakan loop for. 
```python
# Definisikan fungsi cetak_angka di sini
def cetak_angka():
    for i in range(1, 6):
        print(i)

# Uncomment untuk menguji fungsi
# cetak_angka()  # harus mencetak angka dari 1 sampai 5
```

7.	Loop (while): Buat fungsi hitung_mundur() yang meminta pengguna untuk memasukkan sebuah angka dan kemudian mencetak hitungan mundur dari angka tersebut sampai 1 menggunakan loop while. 
```python
# Definisikan fungsi hitung_mundur di sini
def hitung_mundur():
    angka = int(input("Masukkan sebuah angka: "))
    while angka > 0:
        print(angka)
        angka -= 1
# Uncomment untuk menguji fungsi
# hitung_mundur()  # jika pengguna memasukkan 5, harus mencetak: 5 4 3 2 1
```

8.	List dan Operasinya: Buat fungsi tambah_elemen_list() yang menerima sebuah list dan sebuah elemen baru yang akan ditambahkan ke dalam list tersebut, kemudian mengembalikan list baru setelah penambahan. 
```ptyhon
# Definisikan fungsi tambah_elemen_list di sini
def tambah_elemen_list(list_awal, elemen_baru):
    list_awal.append(elemen_baru)
    return list_awal

# Uncomment untuk menguji fungsi
# print(tambah_elemen_list([1, 2, 3], 4))  # harus mencetak [1, 2, 3, 4]
```

9.	Tuple dan Operasinya: Buat fungsi hitung_tuple() yang menghitung dan mengembalikan jumlah semua elemen numerik dalam sebuah tuple. 
```python
# Definisikan fungsi hitung_tuple di sini
def hitung_tuple(tup):
    total = 0
    for item in tup:
        if isinstance(item, (int, float)):
            total += item
    return total

# Uncomment untuk menguji fungsi
# print(hitung_tuple((1, 2, 'a', 'b', 3)))  # harus mencetak 6
```

10.	Dictionary dan Operasinya: Buat fungsi cari_nilai_dictionary() yang menerima sebuah dictionary dan sebuah kunci, kemudian mengembalikan nilai yang terkait dengan kunci tersebut dari dictionary. 
```python
# Definisikan fungsi cari_nilai_dictionary di sini
def cari_nilai_dictionary(dict, kunci):
    return dict.get(kunci)

# Uncomment untuk menguji fungsi
# print(cari_nilai_dictionary({'a': 1, 'b': 2, 'c': 3}, 'b'))  # harus mencetak 2
```

11.	Fungsi dengan Argumen: Buat fungsi hitung_perkalian() yang menerima dua argumen numerik dan mengembalikan hasil perkaliannya. 
```python
# Definisikan fungsi hitung_perkalian di sini
def hitung_perkalian(angka1, angka2):
    return angka1 * angka2

# Uncomment untuk menguji fungsi
# print(hitung_perkalian(4, 5))  # harus mencetak 20
```

12.	Fungsi dengan Return Value: Buat fungsi maksimum_dua_angka() yang menerima dua angka dan mengembalikan angka yang lebih besar. 
```python
# Definisikan fungsi maksimum_dua_angka di sini
def maksimum_dua_angka(angka1, angka2):
    return max(angka1, angka2)

# Uncomment untuk menguji fungsi
# print(maksimum_dua_angka(4, 5))  # harus mencetak 5
```

13.	Fungsi Rekursif: Buat fungsi rekursif faktorial() yang menghitung faktorial dari sebuah angka. 
```python
# Definisikan fungsi faktorial di sini
def faktorial(n):
    if n == 0:
        return 1
    else:
        return n * faktorial(n - 1)

# Uncomment untuk menguji fungsi
# print(faktorial(5))  # harus mencetak 120
```

14.	Menggunakan Modul Eksternal: Gunakan modul math untuk membuat fungsi hitung_akar_kuadrat() yang menghitung akar kuadrat dari sebuah angka. 
```python
# Definisikan fungsi hitung_akar_kuadrat di sini
import math

def hitung_akar_kuadrat(angka):
    return math.sqrt(angka)

# Uncomment untuk menguji fungsi
# print(hitung_akar_kuadrat(16))  # harus mencetak 4.0
```

15.	Pembuatan Class Sederhana: Buat class Mobil dengan constructor yang menerima merk dan warna, dan method tampilkan_info() yang mencetak informasi mobil tersebut. 
```python
# Definisikan class Mobil di sini
class Mobil:
    def __init__(self, merk, warna):
        self.merk = merk
        self.warna = warna

    def tampilkan_info(self):
        print(f"Merk: {self.merk}, Warna: {self.warna}")

# Uncomment untuk menguji class
# mobil_saya = Mobil('Toyota', 'Merah')
# mobil_saya.tampilkan_info()  # harus mencetak "Merk: Toyota, Warna: Merah"
```

16.	Pengolahan String: Buat fungsi balik_string() yang menerima sebuah string dan mengembalikan string tersebut dalam urutan terbalik. 
```python
# Definisikan fungsi balik_string di sini
def balik_string(s):
    return s[::-1]

# Uncomment untuk menguji fungsi
# print(balik_string("python"))  # harus mencetak "nohtyp"
```

17.	File Handling (Membaca File): Buat fungsi baca_file() yang membaca isi dari sebuah file dengan nama 'data.txt' dan mencetak isinya. 
```python
# Definisikan fungsi baca_file di sini
def baca_file():
    with open('data.txt', 'r') as file:
        isi = file.read()
        print(isi)

# Uncomment untuk menguji fungsi
# baca_file()  # harus mencetak isi dari 'data.txt'
```

18.	File Handling (Menulis File): Buat fungsi tulis_file() yang menulis sebuah string ke dalam sebuah file dengan nama 'output.txt'. 
```python
# Definisikan fungsi tulis_file di sini
def tulis_file(teks):
    with open('output.txt', 'w') as file:
        file.write(teks)

# Uncomment untuk menguji fungsi
# tulis_file("Ini adalah teks yang ditulis ke dalam file.")  # harus membuat atau menulis ulang 'output.txt' dengan teks yang diberikan
```

19.	Error Handling (try...except): Buat fungsi bagi_dua_angka() yang membagi dua angka dan menggunakan error handling untuk menangani pembagian dengan nol. 
```python
# Definisikan fungsi bagi_dua_angka di sini
def bagi_dua_angka(a, b):
    try:
        return a / b
    except ZeroDivisionError:
        return "Error: Tidak bisa membagi dengan nol"

# Uncomment untuk menguji fungsi
# print(bagi_dua_angka(10, 2))  # harus mencetak 5.0
# print(bagi_dua_angka(10, 0))  # harus mencetak "Error: Tidak bisa membagi dengan nol"
```

20.	Lambda Functions: Buat fungsi lambda yang menghitung kuadrat dari sebuah angka dan simpan dalam variabel bernama kuadrat. 
```python
# Definisikan fungsi lambda di sini dan simpan dalam variabel kuadrat
kuadrat = lambda x: x ** 2

# Uncomment untuk menguji fungsi
# print(kuadrat(5))  # harus mencetak 25
```

21.	Inheritance dalam Class: Buat class Kendaraan dengan properti umum dan class Mobil yang mewarisi properti dari Kendaraan serta menambahkan properti khusus untuk mobil. 
```python
# Definisikan class Kendaraan dan class Mobil di sini
class Kendaraan:
    def __init__(self, merk):
        self.merk = merk

class Mobil(Kendaraan):
    def __init__(self, merk, warna, tipe):
        super().__init__(merk)
        self.warna = warna
        self.tipe = tipe

    def tampilkan_info(self):
        print(f"Merk: {self.merk}, Warna: {self.warna}, Tipe: {self.tipe}")

# Uncomment untuk menguji class
# mobil_saya = Mobil('Toyota', 'Merah', 'SUV')
# mobil_saya.tampilkan_info()  # harus mencetak "Merk: Toyota, Warna: Merah, Tipe: SUV"
```

22.	Polimorfisme: Buat dua class, Burung dan Pesawat, yang keduanya memiliki method terbang() tetapi dengan implementasi yang berbeda. 
```python
# Definisikan class Burung dan Pesawat dengan method terbang di sini
class Burung:
    def terbang(self):
        print("Burung terbang menggapai langit")

class Pesawat:
    def terbang(self):
        print("Pesawat lepas landas menuju awan")

# Uncomment untuk menguji class
# merpati = Burung()
# merpati.terbang()  # harus mencetak "Burung terbang menggapai langit"
# garuda = Pesawat()
# garuda.terbang()  # harus mencetak "Pesawat lepas landas menuju awan"
```

23.	Encapsulation: Buat class RekeningBank dengan enkapsulasi yang memungkinkan deposit dan penarikan uang sambil menyembunyikan detail saldo dari pengguna. 
```python
# Definisikan class RekeningBank di sini
class RekeningBank:
    def __init__(self):
        self.__saldo = 0

    def deposit(self, jumlah):
        self.__saldo += jumlah

    def penarikan(self, jumlah):
        if jumlah <= self.__saldo:
            self.__saldo -= jumlah
        else:
            print("Saldo tidak cukup")

    def tampilkan_saldo(self):
        print(f"Saldo saat ini: {self.__saldo}")

# Uncomment untuk menguji class
# rekening = RekeningBank()
# rekening.deposit(1000)
# rekening.penarikan(500)
# rekening.tampilkan_saldo()  # harus mencetak "Saldo saat ini: 500"
```

24.	Decorator: Buat decorator fungsi yang mencetak waktu eksekusi dari fungsi yang dihiasinya. 
```python
# Definisikan decorator di sini
import time

def decorator_waktu_eksekusi(func):
    def wrapper(*args, **kwargs):
        mulai = time.time()
        hasil = func(*args, **kwargs)
        berakhir = time.time()
        print(f"Waktu eksekusi: {berakhir - mulai} detik")
        return hasil
    return wrapper

@decorator_waktu_eksekusi
def fungsi_test():
    # Simulasikan tugas berat
    time.sleep(1)

# Uncomment untuk menguji decorator
# fungsi_test()  # harus mencetak waktu eksekusi fungsi_test
```

25.	Generator: Buat generator angka_genap() yang menghasilkan angka genap dari 0 hingga limit yang diberikan. 
```python
# Definisikan generator angka_genap di sini
def angka_genap(limit):
    for i in range(0, limit+1, 2):
        yield i

# Uncomment untuk menguji generator
# for angka in angka_genap(10):
#     print(angka)  # harus mencetak angka genap dari 0 sampai 10
```

26.	List Comprehension: Buat fungsi kuadrat_list() yang menggunakan list comprehension untuk mengambil sebuah list angka dan mengembalikan list tersebut dengan setiap elemen dikuadratkan. 
```python
# Definisikan fungsi kuadrat_list di sini
def kuadrat_list(list_angka):
    return [x**2 for x in list_angka]

# Uncomment untuk menguji fungsi
# print(kuadrat_list([1, 2, 3, 4]))  # harus mencetak [1, 4, 9, 16]
```

27.	Dictionary Comprehension: Buat fungsi buat_dict_kuadrat() yang menggunakan dictionary comprehension untuk membuat dictionary dengan kunci angka dari 1 sampai n dan nilai kuadrat dari kunci tersebut. 
```python
# Definisikan fungsi buat_dict_kuadrat di sini
def buat_dict_kuadrat(n):
    return {i: i**2 for i in range(1, n+1)}

# Uncomment untuk menguji fungsi
# print(buat_dict_kuadrat(4))  # harus mencetak {1: 1, 2: 4, 3: 9, 4: 16}
```

28.	Set dan Operasinya: Buat fungsi gabung_dan_hitung_unik() yang menggabungkan dua set dan mengembalikan jumlah elemen unik dari kedua set tersebut. 
```python
# Definisikan fungsi gabung_dan_hitung_unik di sini
def gabung_dan_hitung_unik(set1, set2):
    gabungan_set = set1.union(set2)
    return len(gabungan_set)

# Uncomment untuk menguji fungsi
# print(gabung_dan_hitung_unik({1, 2, 3}, {3, 4, 5}))  # harus mencetak 5
```

29.	Map, Filter, dan Reduce: Buat fungsi hitung_total() yang menggunakan fungsi reduce untuk menghitung total dari sebuah list angka. 
```python
# Definisikan fungsi hitung_total di sini
from functools import reduce

def hitung_total(list_angka):
    return reduce(lambda a, b: a + b, list_angka)

# Uncomment untuk menguji fungsi
# print(hitung_total([1, 2, 3, 4]))  # harus mencetak 10
```

30.	Regular Expressions: Buat fungsi cari_email() yang menggunakan regular expressions untuk menemukan dan mengembalikan semua alamat email dalam sebuah string. 
```python
# Definisikan fungsi cari_email di sini
import re

def cari_email(teks):
    pattern = r'\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b'
    return re.findall(pattern, teks)

# Uncomment untuk menguji fungsi
# print(cari_email("Kontak saya di example@example.com dan test@test.com"))  # harus mencetak ['example@example.com', 'test@test.com']
```

31.	Sorting Algorithms: Buat fungsi sort_list() yang menerapkan algoritma pengurutan bubble sort untuk mengurutkan list. 
```python
# Definisikan fungsi sort_list di sini
def sort_list(list_angka):
    n = len(list_angka)
    for i in range(n):
        for j in range(0, n-i-1):
            if list_angka[j] > list_angka[j+1]:
                list_angka[j], list_angka[j+1] = list_angka[j+1], list_angka[j]
    return list_angka

# Uncomment untuk menguji fungsi
# print(sort_list([4, 3, 1, 2]))  # harus mencetak [1, 2, 3, 4]
```

32.	Searching Algorithms: Buat fungsi cari_linear() yang menggunakan algoritma pencarian linear untuk menemukan elemen dalam list. 
```python
# Definisikan fungsi cari_linear di sini
def cari_linear(list_angka, target):
    for angka in list_angka:
        if angka == target:
            return True
    return False

# Uncomment untuk menguji fungsi
# print(cari_linear([1, 2, 3, 4], 3))  # harus mencetak True
# print(cari_linear([1, 2, 3, 4], 5))  # harus mencetak False
```

33.	Data Structures: Stack: Buat class Stack dengan metode push, pop, dan peek.
```python
# Definisikan class Stack di sini
class Stack:
    def __init__(self):
        self.items = []

    def push(self, item):
        self.items.append(item)

    def pop(self):
        return self.items.pop()

    def peek(self):
        return self.items[-1] if self.items else None

# Uncomment untuk menguji class
# stack = Stack()
# stack.push(1)
# stack.push(2)
# print(stack.peek())  # harus mencetak 2
# print(stack.pop())   # harus mencetak 2
# print(stack.pop())   # harus mencetak 1
```

34.	Data Structures: Queue: Buat class Queue dengan metode enqueue, dequeue, dan peek. 
```python
# Definisikan class Queue di sini
class Queue:
    def __init__(self):
        self.items = []

    def enqueue(self, item):
        self.items.insert(0, item)

    def dequeue(self):
        return self.items.pop()

    def peek(self):
        return self.items[-1] if self.items else None
# Uncomment untuk menguji class
# queue = Queue()
# queue.enqueue(1)
# queue.enqueue(2)
# print(queue.peek())  # harus mencetak 1
# print(queue.dequeue()) # harus mencetak 1
# print(queue.dequeue()) # harus mencetak 2
```

35.	Data Structures: Linked List: Buat class LinkedList dengan metode insert, delete, dan display. 
```python
# Definisikan class LinkedList dan Node di sini
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class LinkedList:
    def __init__(self):
        self.head = None

    def insert(self, data):
        new_node = Node(data)
        new_node.next = self.head
        self.head = new_node

    def delete(self, data):
        current = self.head
        prev = None
        while current and current.data != data:
            prev = current
            current = current.next
        if prev is None:
            self.head = current.next
        elif current:
            prev.next = current.next
            current.next = None

    def display(self):
        elems = []
        current = self.head
        while current:
            elems.append(current.data)
            current = current.next
        print(' -> '.join(map(str, elems)))

# Uncomment untuk menguji class
# linked_list = LinkedList()
# linked_list.insert(1)
# linked_list.insert(2)
# linked_list.display()  # harus mencetak 2 -> 1
# linked_list.delete(1)
# linked_list.display()  # harus mencetak 2
```

36.	Data Structures: Graph: Buat class Graph yang memiliki metode untuk menambahkan simpul dan sisi serta menampilkan graf. 
```python
# Definisikan class Graph di sini
class Graph:
    def __init__(self):
        self.graph = {}

    def add_node(self, node):
        if node not in self.graph:
            self.graph[node] = []

    def add_edge(self, node1, node2):
        if node1 in self.graph:
            self.graph[node1].append(node2)

    def display(self):
        for node in self.graph:
            for neighbour in self.graph[node]:
                print(f"{node} -> {neighbour}")
# Uncomment untuk menguji class
# graph = Graph()
# graph.add_node("A")
# graph.add_node("B")
# graph.add_edge("A", "B")
# graph.display()  # harus mencetak sisi graf dari A ke B
```

37.	Data Structures: Tree: Buat class Tree dengan metode untuk menambahkan node dan menampilkan struktur pohon. 
```python
# Definisikan class Tree dan TreeNode di sini
class TreeNode:
    def __init__(self, data):
        self.data = data
        self.children = []

    def add_child(self, child):
        self.children.append(child)

class Tree:
    def __init__(self):
        self.root = None

    def add(self, data, parent_data=None):
        new_node = TreeNode(data)
        if self.root is None:
            self.root = new_node
        else:
            parent_node = self._find_node(self.root, parent_data)
            if parent_node:
                parent_node.add_child(new_node)

    def _find_node(self, node, data):
        if node.data == data:
            return node
        for child in node.children:
            found = self._find_node(child, data)
            if found:
                return found
        return None

    def display(self, node=None, level=0):
        if node is None:
            node = self.root
        print(' ' * level * 2 + str(node.data))
        for child in node.children:
            self.display(child, level + 1)

# Uncomment untuk menguji class
# tree = Tree()
# tree.add("Root")
# tree.add("Child1", "Root")
# tree.add("Child2", "Root")
# tree.display()  # harus mencetak struktur pohon dengan "Root" sebagai akar
```

38.	Data Analysis with Pandas: Buat fungsi analisis_data() yang menggunakan pandas untuk membaca file CSV dan mengembalikan ringkasan data. 
```python
# Definisikan fungsi analisis_data di sini
import pandas as pd

def analisis_data(file_path):
    df = pd.read_csv(file_path)
    print(df.describe())  # Ringkasan statistik
    print(df.head())      # Menampilkan beberapa baris pertama

# Uncomment untuk menguji fungsi
# analisis_data("data.csv")  # harus membaca file data.csv dan mencetak ringkasan statistik
```

39.	Data Visualization with Matplotlib: Buat fungsi plot_data() yang menggunakan matplotlib untuk membuat grafik dari data numerik.
```python
# Definisikan fungsi plot_data di sini
import matplotlib.pyplot as plt

def plot_data(x, y):
    plt.plot(x, y)
    plt.xlabel('X Axis')
    plt.ylabel('Y Axis')
    plt.title('Plot Data')
    plt.show()

# Uncomment untuk menguji fungsi
# plot_data([1, 2, 3, 4], [10, 20, 30, 40])  # harus membuat grafik dengan data yang diberikan
```

40.	Web Scraping with BeautifulSoup: Buat fungsi scrape_website() yang menggunakan BeautifulSoup untuk mengekstrak dan mencetak judul dari sebuah halaman web. 
```python
# Definisikan fungsi scrape_website di sini
import requests
from bs4 import BeautifulSoup

def scrape_website(url):
    response = requests.get(url)
    soup = BeautifulSoup(response.text, 'html.parser')
    title = soup.find('title').text
    print(title)

# Uncomment untuk menguji fungsi
# scrape_website("https://example.com")  # harus mengekstrak dan mencetak judul dari halaman web example.com
```
