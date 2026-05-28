# Instruksi Menjalankan Program

PPERSYARATAN
-----------
  - Java Development Kit (JDK) versi 8 atau lebih baru
  - Terminal / Command Prompt / IDE (IntelliJ, Eclipse, VS Code)

  Cek instalasi:
    java -version

  Download JDK:
    https://www.oracle.com/java/technologies/downloads/


CARA MENJALANKAN
----------------
  1. Masuk ke folder project:

       cd path/to/SistemPerpus

  2. Kompilasi program:

       javac SistemPerpus.java

  3. Jalankan program:

       java SistemPerpus

  4. Ikuti menu yang tampil di layar:
       - Gunakan angka untuk navigasi menu
       - Tekan Enter setelah memilih angka
       - Tekan 0 untuk kembali atau keluar


  Cara cepat (kompilasi + jalankan sekaligus):

       javac SistemPerpus.java && java SistemPerpus


STRUKTUR FILE
-------------
  SistemPerpus.java   → Source code utama
  SistemPerpus.class  → Hasil kompilasi (otomatis terbuat)
  data_perpus.txt     → File data (otomatis terbuat)
  README.txt          → Instruksi ini


FORMAT FILE DATA (data_perpus.txt)
-----------------------------------
  # Baris diawali # adalah komentar
  # Format: ID|NAMA|KATEGORI|JUMLAH
  1|Matematika Dasar|Sains|15
  2|Fisika Modern|Sains|8


CATATAN
-------
  - File data_perpus.txt akan dibuat otomatis
    di direktori yang sama saat memilih Simpan Data
  - Load Data akan menggantikan seluruh data
    yang ada di memori dengan data dari file
  - Simpan data terlebih dahulu sebelum keluar
    agar data tidak hilang
  - Jalankan program dari folder yang sama
    dengan SistemPerpus.java agar fitur simpan
    dan load data berjalan dengan benar


TROUBLESHOOTING
---------------
  ERROR: 'javac' is not recognized
    → JDK belum terinstall atau belum ditambahkan ke PATH
    → Solusi: install JDK dan atur JAVA_HOME

  ERROR: Class names are only accepted if...
    → Nama file tidak sesuai dengan nama class
    → Solusi: rename file menjadi SistemPerpus.java

  ERROR: Could not find or load main class
    → Solusi: jalankan dengan perintah 'java SistemPerpus'
              (tanpa ekstensi .java maupun .class)

  ERROR: Program berhenti saat input menu
    → Solusi: ketik angka saja saat diminta memilih menu

================================================================
