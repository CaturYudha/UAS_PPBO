// Class: Mobil
class Mobil {
    private String merk;
    private String warna;
    private int tahunProduksi;

    // Constructor untuk inisialisasi objek Mobil
    public Mobil(String merk, String warna, int tahunProduksi) {
        this.merk = merk;
        this.warna = warna;
        this.tahunProduksi = tahunProduksi;
    }

    // Getter untuk mendapatkan merk mobil
    public String getMerk() {
        return merk;
    }

    // Setter untuk mengubah warna mobil
    public void setWarna(String warna) {
        this.warna = warna;
    }

    // Metode untuk menampilkan informasi mobil
    public void tampilkanInfo() {
        System.out.println("Merk: " + merk);
        System.out.println("Warna: " + warna);
        System.out.println("Tahun Produksi: " + tahunProduksi);
    }
}

// Class: Main
public class Main {
    public static void main(String[] args) {
        // Membuat objek mobil
        Mobil mobil1 = new Mobil("Toyota Avanza", "Silver", 2019);
        Mobil mobil2 = new Mobil("Honda Civic", "Hitam", 2020);

        // Memanggil metode tampilkanInfo() untuk setiap objek mobil
        mobil1.tampilkanInfo();
        mobil2.tampilkanInfo();

        // Mengubah warna mobil1
        mobil1.setWarna("Merah");

        // Menampilkan merk mobil1 setelah perubahan warna
        System.out.println("Merk Mobil 1 setelah perubahan warna: " + mobil1.getMerk());
    }
}
