# 💻 pplg-team

## 📌 Tentang Kami

Organisasi ini merupakan pusat kolaborasi resmi jurusan **Rekayasa Perangkat Lunak (RPL)** dan **Pengembangan Perangkat Lunak dan Gim (PPLG)**.

Repository ini dibangun sebagai sistem manajemen proyek terpusat untuk:

* Pengelolaan proyek akhir siswa
* Dokumentasi teknis dan arsitektur sistem
* Kolaborasi pengembangan berbasis tim
* Implementasi standar rekayasa perangkat lunak
* Arsip dan portofolio digital jurusan

Organisasi ini dirancang untuk membentuk kultur engineering yang profesional, sistematis, dan siap industri.

---

## 🎯 Tujuan Organisasi

1. Menyentralisasi seluruh proyek akhir jurusan dalam satu sistem version control terstruktur
2. Menerapkan praktik Software Engineering yang sesuai standar industri
3. Meningkatkan kolaborasi lintas tim dan lintas angkatan
4. Mendokumentasikan karya siswa secara profesional dan berkelanjutan
5. Menjadi portofolio resmi jurusan untuk kebutuhan akreditasi dan publikasi

---

## 🏗️ Struktur Organisasi Repository

Struktur umum repository dalam organisasi ini:

```
final-project-[tahun]-[nama-tim]
learning-resources
discussion-notes
templates
organization-guidelines
```

Contoh:

```
final-project-2026-team-a
final-project-2026-team-b
```

---

## 📁 Standar Struktur Repository Proyek Akhir

Setiap repository proyek akhir WAJIB memiliki struktur minimal berikut:

```
/docs
/src
/public (jika web project)
/assets
/tests (opsional)
/README.md
/.env.example
/.gitignore
```

---

## 📘 Standar README Proyek Akhir

README proyek wajib memuat:

* Deskripsi Proyek
* Latar Belakang
* Tujuan Sistem
* Fitur Utama
* Teknologi yang Digunakan
* Struktur Folder
* Diagram (ERD, UML, Arsitektur)
* Cara Instalasi
* Cara Menjalankan Project
* Role & Tim Pengembang
* Lisensi (jika ada)

---

## 🔄 Standar Version Control & Workflow

Organisasi ini menerapkan praktik berikut:

### 1. Branching Strategy

Menggunakan salah satu dari:

* Git Flow
* Trunk-Based Development

Branch minimum:

* `main` → production-ready
* `develop` → integration branch
* `feature/nama-fitur`
* `fix/nama-bug`

### 2. Pull Request Policy

* Semua perubahan wajib melalui Pull Request
* Tidak diperbolehkan commit langsung ke branch `main`
* Minimal 1 reviewer sebelum merge

### 3. Commit Convention (Disarankan)

Menggunakan Conventional Commit:

```
feat: menambahkan fitur login
fix: memperbaiki bug validasi
docs: update dokumentasi API
refactor: perbaikan struktur controller
```

---

## 🧪 Standar Kualitas Kode

Setiap tim wajib memperhatikan:

* Clean code
* Naming convention konsisten
* Struktur folder terorganisir
* Tidak menyimpan file sensitif (.env, credential)
* Dokumentasi fungsi penting

---

## 📊 Manajemen Proyek

Disarankan menggunakan:

* GitHub Issues untuk tracking task
* GitHub Projects untuk manajemen sprint
* Milestones untuk timeline proyek
* GitHub Discussions untuk forum diskusi teknis

---

## 🤝 Prosedur Kontribusi

Langkah kontribusi standar:

1. Buat branch baru dari `develop`
2. Lakukan perubahan
3. Commit sesuai standar
4. Push ke repository
5. Buat Pull Request
6. Tunggu proses review
7. Merge setelah disetujui

---

## 🔐 Aturan Keamanan

* Dilarang mengunggah file `.env`
* Dilarang mengunggah API key atau credential
* Gunakan `.env.example`
* Aktifkan branch protection pada `main`
* Gunakan role permission GitHub dengan tepat

---

## 👨‍💻 Struktur Kepengurusan

Organisasi ini dikelola oleh:

* Ketua Jurusan / Guru Pembimbing (Owner)
* Koordinator Proyek (Maintainer)
* Admin GitHub Organization
* Lead Developer per Tim

---

## 📅 Skema Pengelolaan Lintas Angkatan

Organisasi ini dirancang untuk digunakan lintas angkatan dengan pola:

```
final-project-2026-*
final-project-2027-*
final-project-2028-*
```

Dengan demikian, repository akan menjadi arsip berkelanjutan dan dokumentasi historis jurusan.

---

## 🚀 Visi Jangka Panjang

Menjadi pusat dokumentasi dan portofolio digital resmi jurusan RPL/PPLG yang:

* Berstandar industri
* Siap audit akademik
* Siap dipresentasikan ke mitra industri
* Menjadi showcase kemampuan siswa
* Membangun budaya engineering yang disiplin dan profesional

---

## 📌 Nilai Utama Organisasi

* Kolaboratif
* Terstruktur
* Profesional
* Transparan
* Berorientasi kualitas
