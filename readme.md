
## Penjelasan Kode 💻

Kode tersebut ditulis dalam bahasa pemrograman **Java** dan berfungsi untuk **menghitung luas persegi panjang** sederhana.

| Baris Kode | Penjelasan |
| :--- | :--- |
| `public class Main { ... }` | Mendefinisikan kelas utama program bernama `Main`. Dalam Java, eksekusi program dimulai dari dalam sebuah kelas. |
| `public static void main(String[] args) { ... }` | Ini adalah **metode utama** (main method). Ini adalah titik awal (entry point) eksekusi program Java. |
| `double panjang = 8.5;` | Mendeklarasikan sebuah variabel bertipe data **`double`** bernama `panjang` dan memberikan nilai awal **`8.5`**. Tipe `double` digunakan karena memungkinkan penggunaan angka desimal. |
| `double lebar = 4.2;` | Mendeklarasikan variabel bertipe **`double`** bernama `lebar` dengan nilai awal **`4.2`**. |
| `double luas = panjang * lebar;` | Menghitung luas persegi panjang dengan mengalikan nilai variabel `panjang` dan `lebar`, kemudian menyimpan hasilnya ke variabel bertipe **`double`** bernama `luas`. |
| `System.out.println("...");` | Perintah untuk **mencetak (menampilkan) teks atau nilai variabel** ke konsol (layar). |
| `System.out.println("Panjang : " + panjang);` | Mencetak teks "Panjang : " diikuti dengan nilai yang tersimpan di variabel `panjang` (yaitu 8.5). Operator `+` digunakan untuk menggabungkan (konkatenasi) teks dan nilai variabel. |

-----

## README.md

````markdown
# Program Menghitung Luas Persegi Panjang Sederhana

Program ini adalah contoh dasar dalam bahasa pemrograman Java untuk menghitung luas sebuah persegi panjang dengan nilai panjang dan lebar yang sudah ditentukan (_hardcoded_).

## 🚀 Fitur Utama

* Menghitung luas persegi panjang.
* Menampilkan detail perhitungan di konsol.

## 🛠️ Teknologi

* **Java**

## 📂 Struktur Kode

Kode ini terdiri dari satu file utama:

| File | Deskripsi |
| :--- | :--- |
| `Main.java` | Berisi kelas `Main` dan metode `main()` yang menjalankan logika perhitungan. |

## 💻 Cara Menjalankan

1.  Pastikan Anda telah menginstal **Java Development Kit (JDK)** di sistem Anda.
2.  Simpan kode di atas sebagai file bernama `Main.java`.
3.  Buka terminal atau command prompt.
4.  Kompilasi kode menggunakan perintah:
    ```bash
    javac Main.java
    ```
5.  Jalankan program menggunakan perintah:
    ```bash
    java Main
    ```

## 📄 Output Program

Program akan menghasilkan output di konsol sebagai berikut:

````

\=== Program Menghitung Luas Persegi Panjang ===
Panjang : 8.5
Lebar   : 4.2
Luas    : 35.7

```

## 💡 Logika Perhitungan

* Panjang (`panjang`) ditetapkan sebesar **8.5**.
* Lebar (`lebar`) ditetapkan sebesar **4.2**.
* Luas (`luas`) dihitung dengan rumus:
    $$Luas = Panjang \times Lebar$$
    $$Luas = 8.5 \times 4.2 = 35.7$$
```