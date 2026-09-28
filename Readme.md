# Praktikum 2 - HTML Lanjutan

Repository ini berisi hasil pengerjaan Praktikum 2 Pemrograman Web.

## Identitas

- Nama: Ramadan
- NIM: 312510256
- Program Studi: Teknik Informatika
- Mata Kuliah: Pemrograman Web
- Praktikum: 2 - HTML Lanjutan

---

## Tujuan Praktikum

Praktikum ini bertujuan untuk mempelajari:

1. Penggunaan tabel pada HTML.
2. Penggunaan form dan berbagai jenis input HTML.
3. Penggunaan Semantic HTML.
4. Penambahan elemen multimedia.
5. Validasi form dasar menggunakan atribut HTML.

---

## 1. Membuat Tabel Data Mahasiswa

Pada praktikum ini dibuat tabel untuk menampilkan data mahasiswa.

### Screenshot Hasil di Browser
![Latihan 1 Browser](Screenshot%202026-09-28%20134513.png)

---

## 2. Mengembangkan Tabel

Tabel dikembangkan menggunakan:
- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `colspan`

### Screenshot di VS code
![Latihan 2 VS code](Screenshot%202026-09-28%20150314.png)

### Screenshot Hasil di Browser
![Latihan 2 Browser](Screenshot%202026-09-28%20150941.png)

---

## 3. Membuat Form Registrasi Mahasiswa

Form digunakan untuk menerima data dari pengguna.

Input yang digunakan:
- Nama
- Email
- Password
- Tanggal Lahir
- Tombol Daftar
- Tombol Reset

### Screenshot di VS code
![Latihan 3 VS code](<Screenshot 2026-09-28 151325.png>)

### Screenshot Hasil di Browser
![Latihan 3 Browser](<Screenshot 2026-09-28 151352.png>)

---

## 4. Radio Button dan Checkbox

Radio button digunakan untuk memilih satu pilihan, sedangkan checkbox digunakan untuk memilih satu atau beberapa pilihan.

Contoh:
- Jenis Kelamin
- Keahlian HTML
- Keahlian CSS
- Keahlian JavaScript

### Screenshot di VS code
![Latihan 4 VS code](<Screenshot 2026-09-28 151554.png>)

### Screenshot Hasil di Browser
![Latihan 4 Browser](<Screenshot 2026-09-28 152135.png>)

---

## 5. Select dan Textarea

Pada latihan ini digunakan:
- `<select>` untuk memilih Program Studi.
- `<textarea>` untuk memasukkan Alamat.

### Screenshot di VS code
![Select dan Textarea](<Screenshot 2026-09-28 151833.png>)

### Screenshot Hasil di Browser
![Select dan Textarea Browser](<Screenshot 2026-09-28 152005.png>)
---

## 6. Validasi Form

Validasi dasar diterapkan menggunakan beberapa atribut HTML, yaitu:
- `required`
- `minlength`
- `min`
- `max`
- `type`

Validasi digunakan agar data yang dimasukkan pengguna sesuai dengan ketentuan form.

### Hasil Praktikum
![Validasi Form](<Screenshot 2026-09-28 152602.png>)

---

## 7. Semantic HTML

Semantic HTML digunakan untuk membuat struktur halaman menjadi lebih jelas.

Elemen yang digunakan:
- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

### Hasil Praktikum
![Semantic HTML](<Screenshot 2026-09-28 152847.png>)

---

## 8. Multimedia

Pada praktikum ini ditambahkan elemen multimedia berupa audio dan video menggunakan:
- `<audio>`
- `<video>`

File multimedia disimpan di dalam folder `media`.

### Hasil Praktikum
![Multimedia](<Screenshot 2026-09-28 152903.png>)

---

## 9. Proyek Mini - Biodata Mahasiswa

Proyek mini merupakan penggabungan materi yang telah dipelajari.

Halaman biodata mahasiswa menggunakan:
- Semantic HTML
- Tabel
- Form
- Input HTML
- Select
- Textarea
- Validasi form
- Multimedia

File proyek mini terdapat pada:
`biodata.html`

### Hasil Proyek Mini
![Biodata Mahasiswa](<Screenshot 2026-09-28 152935.png>)
---

## Pertanyaan dan Jawaban

1. **Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?**
   - `<table>`: Membuat struktur tabel.
   - `<tr>`: Membuat baris pada tabel.
   - `<th>`: Membuat sel header/judul kolom.
   - `<td>`: Membuat sel data.

2. **Apa perbedaan `<th>` dan `<td>`?**
   - `<th>` digunakan untuk header (teks tebal dan rata tengah), sedangkan `<td>` untuk data biasa (teks normal dan rata kiri).

3. **Apa fungsi `colspan` pada tabel?**
   - Menggabungkan beberapa kolom menjadi satu secara horizontal.

4. **Apa fungsi `<form>` dalam HTML?**
   - Wadah untuk menerima dan mengumpulkan input dari pengguna.

5. **Apa perbedaan radio button dan checkbox?**
   - Radio button hanya membolehkan memilih 1 opsi, sedangkan checkbox membolehkan memilih lebih dari 1 opsi.

6. **Mengapa `<label>` sebaiknya terhubung dengan `id` input melalui atribut `for`?**
   - Agar saat label diklik, inputan terkait langsung aktif/terfokus.

7. **Apa perbedaan `<textarea>` dengan `<input type="text">`?**
   - `<input type="text">` untuk satu baris teks, sedangkan `<textarea>` untuk banyak baris teks.

8. **Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?**
   - Memberikan makna dan struktur yang jelas pada bagian-bagian halaman web.

9. **Apa fungsi `required`, `min`, `max`, dan `minlength`?**
   - `required`: Wajib diisi.
   - `min` & `max`: Batas angka/tanggal minimal dan maksimal.
   - `minlength`: Minimal jumlah karakter teks.

10. **Apa perbedaan elemen `<audio>` dan `<video>`?**
    - `<audio>` memutar file suara, `<video>` memutar file video beserta suara.

---

## Struktur Repository

```text
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.mp3
│   └── video.mp4
├── media/screenshot/
└── README.md