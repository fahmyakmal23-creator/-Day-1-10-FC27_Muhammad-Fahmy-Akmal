# -Day-1-10-FC27_Muhammad-Fahmy-Akmal
Tugas Osjur
# Day-1-10_FC27_Muhammad Fahmy Akmal

## 👤 Informasi Peserta
* **Nama Lengkap:** Muhammad Fahmy Akmal
* **Kelompok:** 10_FC27

---

## 📌 Deskripsi & Tujuan Repository
* **Deskripsi:** Repository ini berisi dokumentasi resmi, catatan ringkas materi, dan rangkuman pembelajaran dari kegiatan **Workshop Day 1: "Building with AI, Managing Change with GitHub"** yang dibawakan oleh Nugi Farhan (Senior Product Designer).
* **Tujuan:** Sebagai media dokumentasi mandiri, pelaporan pengerjaan tugas praktik pembuatan aplikasi web sederhana (*Student Task Planner*), serta integrasi version control menggunakan Git dan GitHub.

---

## 📑 Dokumentasi & Rangkuman Materi Workshop

### 1. Informasi Kegiatan
* **Nama Workshop:** Day 1 — Building with AI, Managing Change with GitHub
* **Pemateri:** Nugi Farhan (Senior Product Designer)
* **Objektif Pembelajaran:**
  1. Memahami cara merancang prompt AI spesifik untuk menghasilkan luaran kode/aplikasi yang optimal.
  2. Mengidentifikasi komponen Git: Repository, Commit, Branch, dan Pull Request.
  3. Memahami perbedaan dasar antara Git dan GitHub.
  4. Melakukan *version controlling* pada proyek perangkat lunak.

---

### 2. Rangkuman & Catatan Materi

#### A. Prompt Engineering (Building with AI)
Prompt Engineering adalah seni merancang instruksi agar model AI memberikan jawaban yang tepat, relevan, dan terstruktur.
* **Struktur Prompt Efektif (4 Elemen Utama):**
  1. **Role:** Menentukan peran/keahlian AI (contoh: *"You are a senior web developer..."*).
  2. **Task:** Instruksi utama tugas yang harus diselesaikan (contoh: *"Create a student task planner..."*).
  3. **Context:** Latar belakang, batasan, atau audiens (contoh: *"For first-year university students..."*).
  4. **Format:** Bentuk luaran yang diinginkan (contoh: *"HTML, CSS, and Vanilla JavaScript..."*).
* **Keuntungan:** Meningkatkan performa model AI, mengurangi bias, serta meningkatkan kontrol dan ketepatan hasil (*predictability*).

#### B. Git vs GitHub
* **Git:** Sistem *Distributed Version Control System* (DVCS) lokal untuk melacak perubahan berkas/kode (diciptakan oleh Linus Torvalds pada 2005).
* **GitHub:** Platform berbasis web/cloud untuk mengunggah repository Git, memfasilitasi kolaborasi, dan *code review*.

#### C. Alur Kerja Git (Git Workflow)
1. **Working Directory:** Area kerja lokal tempat kita membuat dan mengubah berkas.
2. **Staging Area (Index):** Area penampungan sementara untuk menandai berkas yang akan dimasukkan ke commit berikutnya (`git add`).
3. **.git Directory (Repository):** Database permanen tempat Git menyimpan riwayat snapshot versi proyek (`git commit`).

---

### 3. Poin-Poin Penting & Command Git yang Dipelajari

#### A. Command Dasar Git & GitHub
* `git init` : Memulai repository Git baru di folder lokal.
* `git config --global user.name "Nama"` : Mengatur identitas nama pengguna.
* `git config --global user.email "email@example.com"` : Mengatur email pengguna.
* `git add .` atau `git add -A` : Memindahkan seluruh perubahan berkas ke Staging Area.
* `git commit -m "pesan commit"` : Menyimpan snapshot versi ke repository lokal.
* `git remote add origin <URL>` : Menghubungkan repo lokal ke repo remote GitHub.
* `git push -u origin main` : Mengunggah branch lokal ke GitHub.
* `git pull origin main` : Mengunduh dan menggabungkan update terbaru dari GitHub.

#### B. Autentikasi SSH Key (Ed25519)
* Membuat SSH Key aman: `ssh-keygen -t ed25519 -C "email@domain.com"`
* Menambahkan key ke agent & macOS Keychain.
* Menguji koneksi ke GitHub: `ssh -T git@github.com`

---

## 🛠️ Proyek Praktik: Student Task Planner
Selama workshop, dilakukan praktik pembuatan aplikasi **Student Task Planner** menggunakan bantuan AI (Claude / ChatGPT / AntiGravity) yang mencakup fitur:
* Menampilkan daftar tugas kuliah beserta tenggat waktu (*due date*).
* Mengubah status tugas menjadi selesai (*completed*).
* Filter tugas (All, Pending, Completed).
