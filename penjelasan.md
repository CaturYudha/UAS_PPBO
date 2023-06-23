
class Mobil: Mendefinisikan kelas "Mobil" yang memiliki atribut "merk", "warna", dan "tahunProduksi". Atribut ini dideklarasikan sebagai private agar hanya dapat diakses di dalam kelas "Mobil".

Mobil(String merk, String warna, int tahunProduksi): Constructor digunakan untuk membuat objek Mobil dan menginisialisasi nilai atribut "merk", "warna", dan "tahunProduksi" dengan nilai yang diberikan.

public String getMerk(): Getter digunakan untuk mendapatkan nilai atribut "merk" dari objek Mobil.

public void setWarna(String warna): Setter digunakan untuk mengubah nilai atribut "warna" dari objek Mobil.

public void tampilkanInfo(): Metode ini digunakan untuk menampilkan informasi (merk, warna, dan tahun produksi) dari objek Mobil.

Mobil mobil1 = new Mobil("Toyota Avanza", "Silver", 2019);: Membuat objek mobil1 dengan menggunakan constructor kelas Mobil dan memberikan nilai "Toyota Avanza" untuk merk, "Silver" untuk warna, dan 2019 untuk tahun produksi.

mobil1.tampilkanInfo();: Memanggil metode "tampilkanInfo()" pada objek mobil1 untuk menampilkan informasi mobil tersebut.

mobil1.setWarna("Merah");: Menggunakan setter untuk mengubah warna mobil1 menjadi "Merah".

`System.out.println("Merk Mobil 1 setelah perubahan warna: " + mobil1.getM
