# LAPORAN PRAKTIKUM DESAIN WEB

## Identitas

| Data          | Keterangan                          |
| ------------- | ----------------------------------- |
| Nama          | Ridho Sachlan                       |
| NPM           | 4525210066                          |
| Kelas         | A                         |
| Program Studi | Teknik Informatika                  |
| Mata Kuliah   | Prak. Desain Web                    |
| Tema          | Company Profile PT GoTo Gojek Tokopedia Tbk |

---

## Fitur & Komponen HTML Form

1. **5 Tipe Input Utama**:
   - `text`: Input untuk Nama Lengkap.
   - `email`: Input untuk Email dengan validasi format bawaan browser.
   - `password`: Input untuk Kata Sandi (karakter disamarkan).
   - `number`: Input untuk Nilai Rata-rata UN/Akses (dengan batas `min="0"`, `max="100"`, dan presisi desimal `step="0.01"`).
   - `date`: Input pemilih tanggal untuk Tanggal Lahir.

2. **3 Tipe Button**:
   - `type="submit"` (`btn-primary`): Mengirimkan data form.
   - `type="reset"` (`btn-reset`): Mengosongkan/mereset seluruh isian form.
   - `type="button"` (`btn-secondary`): Tombol aksi kustom/kembali.

3. **Elemen Form Tambahan**:
   - `<select>`: Elemen dropdown pilihan Program Studi.
   - `<textarea>`: Input area teks serbaguna untuk Alamat Lengkap.

4. **Aksesibilitas & Backend Readiness**:
   - Setiap elemen `<label>` terhubung langsung ke kontrol input menggunakan pasangan atribut `for` dan `id`.
   - Menggunakan `method="post"` untuk pengiriman data yang lebih aman melalui HTTP request body.
   - Setiap elemen input memiliki atribut `name` sebagai *key* data yang dikirimkan.


## Ringkasan 

> **Ringkasan Perubahan, Masalah, dan Solusi**
>
> Pada praktikum ini, dilakukan penyesuaian prototipe Form Pendaftaran Mahasiswa Baru agar memenuhi kebutuhan panitia penerimaan dan instruksi modul. Perubahan utama terletak pada penambahan field input `nilai` bertipe `number` yang dilengkapi dengan atribut `min="0"`, `max="100"`, serta `step="0.01"`. Hal ini melengkapi persyaratan 5 tipe input utama, yaitu `text` (nama), `email`, `password`, `number` (nilai), dan `date` (tanggal lahir). Selain itu, terdapat 3 jenis button, yaitu `submit` untuk mengirimkan data, `reset` untuk mengosongkan form, dan `button` biasa untuk navigasi kembali.
>
> Masalah yang ditemui selama pengerjaan adalah inkonsistensi keterhubungan antara elemen `<label>` dan elemen kontrol input. Solusinya adalah memastikan setiap elemen `<label>` memiliki atribut `for` yang nilainya persis sama dengan atribut `id` pada masing-masing kontrol input. Hal ini meningkatkan fleksibilitas aksesibilitas pengguna. Penggunaan `method="post"` dipilih karena data yang dikirimkan berisi informasi sensitif seperti password dan data diri calon mahasiswa, sehingga tidak terekspos pada URL browser. Seluruh elemen juga telah dibekali atribut `name` yang sesuai agar siap diintegrasikan dengan backend di masa mendatang.


---

## 🛠️ Struktur Folder

```text
Pertemuan7/
├── contoh1/
│   ├── css/
│   │   └── style.css
│   └── Index.html
├── contoh2/
│   ├── css/
│   │   └── style.css
│   └── Index.html
├── materi/
│   ├── Desain Web_7 (code).pdf
│   └── Desain Web_7.pdf
├── tugas7/
│   ├── css/
│   │   └── style.css
│   ├── img/
│   │   ├── Dekstop.png
│   │   ├── mobile1.png
│   │   └── mobile1-2.png
│   └── Index.html
└── README.md
```

## Deskripsi Proyek


## Bukti Pengerjaan


- **Tampilan Desktop:** ![Desktop](/Tugas5/img/web.png)
- **Tampilan Mobile:** ![Mobile](/Tugas5/img/mobile.png)