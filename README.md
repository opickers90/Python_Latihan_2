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
# Definisikan class RekeningBank di sini

# Uncomment untuk menguji class
# rekening = RekeningBank()
# rekening.deposit(1000)
# rekening.penarikan(500)
# rekening.tampilkan_saldo()  # harus mencetak "Saldo saat ini: 500"
24.	Decorator: Buat decorator fungsi yang mencetak waktu eksekusi dari fungsi yang dihiasinya. 
# Definisikan decorator di sini

# Uncomment untuk menguji decorator
# @decorator_waktu_eksekusi
# def fungsi_test():
#     # Kode untuk menguji waktu eksekusi
# fungsi_test()  # harus mencetak waktu eksekusi fungsi_test


25.	Generator: Buat generator angka_genap() yang menghasilkan angka genap dari 0 hingga limit yang diberikan. 
# Definisikan generator angka_genap di sini

# Uncomment untuk menguji generator
# for angka in angka_genap(10):
#     print(angka)  # harus mencetak angka genap dari 0 sampai 10
26.	List Comprehension: Buat fungsi kuadrat_list() yang menggunakan list comprehension untuk mengambil sebuah list angka dan mengembalikan list tersebut dengan setiap elemen dikuadratkan. 
# Definisikan fungsi kuadrat_list di sini

# Uncomment untuk menguji fungsi
# print(kuadrat_list([1, 2, 3, 4]))  # harus mencetak [1, 4, 9, 16]
27.	Dictionary Comprehension: Buat fungsi buat_dict_kuadrat() yang menggunakan dictionary comprehension untuk membuat dictionary dengan kunci angka dari 1 sampai n dan nilai kuadrat dari kunci tersebut. 
# Definisikan fungsi buat_dict_kuadrat di sini

# Uncomment untuk menguji fungsi
# print(buat_dict_kuadrat(4))  # harus mencetak {1: 1, 2: 4, 3: 9, 4: 16}
28.	Set dan Operasinya: Buat fungsi gabung_dan_hitung_unik() yang menggabungkan dua set dan mengembalikan jumlah elemen unik dari kedua set tersebut. 
# Definisikan fungsi gabung_dan_hitung_unik di sini

# Uncomment untuk menguji fungsi
# print(gabung_dan_hitung_unik({1, 2, 3}, {3, 4, 5}))  # harus mencetak 5
29.	Map, Filter, dan Reduce: Buat fungsi hitung_total() yang menggunakan fungsi reduce untuk menghitung total dari sebuah list angka. 
# Definisikan fungsi hitung_total di sini

# Uncomment untuk menguji fungsi
# print(hitung_total([1, 2, 3, 4]))  # harus mencetak 10
30.	Regular Expressions: Buat fungsi cari_email() yang menggunakan regular expressions untuk menemukan dan mengembalikan semua alamat email dalam sebuah string. 
# Definisikan fungsi cari_email di sini

# Uncomment untuk menguji fungsi
# print(cari_email("Kontak saya di example@example.com dan test@test.com"))  # harus mencetak ['example@example.com', 'test@test.com']
31.	Sorting Algorithms: Buat fungsi sort_list() yang menerapkan algoritma pengurutan bubble sort untuk mengurutkan list. 
# Definisikan fungsi sort_list di sini

# Uncomment untuk menguji fungsi
# print(sort_list([4, 3, 1, 2]))  # harus mencetak [1, 2, 3, 4]
32.	Searching Algorithms: Buat fungsi cari_linear() yang menggunakan algoritma pencarian linear untuk menemukan elemen dalam list. 
# Definisikan fungsi cari_linear di sini

# Uncomment untuk menguji fungsi
# print(cari_linear([1, 2, 3, 4], 3))  # harus mencetak True
# print(cari_linear([1, 2, 3, 4], 5))  # harus mencetak False
33.	Data Structures: Stack: Buat class Stack dengan metode push, pop, dan peek.
# Definisikan class Stack di sini

# Uncomment untuk menguji class
# stack = Stack()
# stack.push(1)
# stack.push(2)
# print(stack.peek())  # harus mencetak 2
# print(stack.pop())   # harus mencetak 2
# print(stack.pop())   # harus mencetak 1
34.	Data Structures: Queue: Buat class Queue dengan metode enqueue, dequeue, dan peek. 
# Definisikan class Queue di sini

# Uncomment untuk menguji class
# queue = Queue()
# queue.enqueue(1)
# queue.enqueue(2)
# print(queue.peek())  # harus mencetak 1
# print(queue.dequeue()) # harus mencetak 1
# print(queue.dequeue()) # harus mencetak 2
35.	Data Structures: Linked List: Buat class LinkedList dengan metode insert, delete, dan display. 
# Definisikan class LinkedList dan Node di sini

# Uncomment untuk menguji class
# linked_list = LinkedList()
# linked_list.insert(1)
# linked_list.insert(2)
# linked_list.display()  # harus mencetak 1 -> 2
# linked_list.delete(1)
# linked_list.display()  # harus mencetak 2
36.	Data Structures: Graph: Buat class Graph yang memiliki metode untuk menambahkan simpul dan sisi serta menampilkan graf. 
# Definisikan class Graph di sini

# Uncomment untuk menguji class
# graph = Graph()
# graph.add_node("A")
# graph.add_node("B")
# graph.add_edge("A", "B")
# graph.display()  # harus mencetak sisi graf dari A ke B
37.	Data Structures: Tree: Buat class Tree dengan metode untuk menambahkan node dan menampilkan struktur pohon. 
# Definisikan class Tree dan TreeNode di sini

# Uncomment untuk menguji class
# tree = Tree()
# tree.add("Root")
# tree.add("Child1", "Root")
# tree.add("Child2", "Root")
# tree.display()  # harus mencetak struktur pohon dengan Root sebagai akar
38.	Data Analysis with Pandas: Buat fungsi analisis_data() yang menggunakan pandas untuk membaca file CSV dan mengembalikan ringkasan data. 
# Definisikan fungsi analisis_data di sini

# Uncomment untuk menguji fungsi
# analisis_data("data.csv")  # harus membaca file data.csv dan mencetak ringkasan data
39.	Data Visualization with Matplotlib: Buat fungsi plot_data() yang menggunakan matplotlib untuk membuat grafik dari data numerik.
# Definisikan fungsi plot_data di sini

# Uncomment untuk menguji fungsi
# plot_data([1, 2, 3, 4], [10, 20, 30, 40])  # harus membuat grafik dengan data yang diberikan
40.	Web Scraping with BeautifulSoup: Buat fungsi scrape_website() yang menggunakan BeautifulSoup untuk mengekstrak dan mencetak judul dari sebuah halaman web. 
# Definisikan fungsi scrape_website di sini

# Uncomment untuk menguji fungsi
# scrape_website("https://example.com")  # harus mengekstrak dan mencetak judul dari halaman web example.com
