# Tugas-OOP-// Nama: Serlin Selviana Giay
// NIM: 251410030
// Tugas: Pemrograman Berorientasi Objek

// 1. Membuat Class Hewan sesuai permintaan soal No. 3
class Hewan {
  // Atribut: nama
  String nama;

  // Konstruktor: Untuk mengisi nama saat objek dibuat
  Hewan(this.nama);

  // Metode: bersuara()
  void bersuara() {
    print('Hewan $nama sedang bersuara: Meow... Guk... Rauurrr!');
  }
}

void main() {
  print('--- Tugas OOP Dart - Serlin Selviana Giay ---');
  
  // 2. Membuat Objek dari Class Hewan
  // Kita beri nama objeknya 'kucing'
  var kucing = Hewan('Kucing');
  
  // 3. Menampilkan Nama (Atribut)
  print('Nama Objek: ${kucing.nama}');
  
  // 4. Memanggil Metode bersuara
  kucing.bersuara();
  
  print('-------------------------------------------');
  
  // Contoh objek lain
  var singa = Hewan('Singa');
  print('Nama Objek: ${singa.nama}');
  singa.bersuara();
}
