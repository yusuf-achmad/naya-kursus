# Pemrograman Fungsional
Pembahasan:

1. Anonymous function
2. Arrow function
3. Closure
4. Higher-order functions
5. Konsep side effects dan immutability
Pemrograman Fungsional pada JS sudah lama digunakan dan dikembangkan sampai saat ini. Pemrograman fungsional merupakan salah satu paradigma model pemrograman. Pemrograman fungsional adalah dimana kita mengelola fungsi-funsi kita.

## Anonymous function
Fungsi yang tidak memiliki identitas. Merupakan fungsi yang dibuat dan langsung dipanggil. penulsannya adalah (function(){}), untuk menampilkan hasilnya adalah (function(){})();. Jenis FUngsi ini hanya digunakan ketika ada IFF, selain itu fungsi ini tidak ada gunanya.

## Arrow Function
Sudah pasti anonymous penulisannya hanya menggantikan function menjadi =>.

## Closure
Fungsi yang me-return fungsi lain.

## Higher-order functions (Callback)
Fungsi yang konstantanya berupa fungsi lagi

## Konsep side effects dan immutability
Side effect adalah hal lain yang terjadi di luar proses itu sendiri. contohnya operasi penjulahan yang di console.log. Console log bukan dalam lingkup penjumlahan. contoh lain: document.write, window.close dsb.

Immutability adalah fungsi tidak memengaruhi keadaan di luarnya, contohnya memakai return pada fungsi yang mana return mengembalikan nilai dari fungsi itu sendiri yang berupa data yang ditampung. Immutable artinya mempertahankan nilai.

Tambahan: Fungsi bisa diconsole.log meski fungsinya tidak dijalankan.Barati fungsi fungsi yang bodynya satu dan langsug direturn namanya Lambda.