# Latihan OOP JavaScript (ES6+)

Implementasi dua soal latihan dari materi `materi_oop_javascript.pdf`.

## Konsep yang digunakan
- **Encapsulation:** `#saldo` pada `BankAccount` hanya dapat diakses melalui method.
- **Inheritance:** `ProdukElektronik extends Produk` dan memanggil `super(...)`.
- **Polymorphism:** `ProdukElektronik` melakukan override method `getInfo()`.

## Struktur proyek
- `BankAccount.js` — solusi soal 1.
- `Produk.js` — solusi soal 2.
- `index.js` — contoh penggunaan dan pengujian manual.

## Menjalankan
Membutuhkan Node.js.

```bash
node index.js
```

## Aturan validasi
- `deposit(jumlah)` hanya menerima jumlah lebih besar dari 0.
- `withdraw(jumlah)` hanya berhasil jika jumlah lebih besar dari 0 dan saldo mencukupi.
- Saldo awal yang tidak positif diinisialisasi menjadi 0.
