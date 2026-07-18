# Sistem Informasi Persuratan Sekolah

Aplikasi web untuk mengelola alur surat masuk dan keluar sebuah sekolah, mencakup proses upload surat, tanda tangan digital, revisi, hingga pengiriman surat ke pihak terkait via WhatsApp.

**Proyek:** Tugas Kelompok — Mata Kuliah MPTI (Manajemen Proyek Teknologi Informasi)
**Peran saya:** System Analyst
**Klien:** Sebuah sekolah (atas permintaan dinas terkait)

> ⚠️ **Catatan Kerahasiaan & Kepemilikan**
> Source code aplikasi ini merupakan hak milik pihak sekolah selaku klien dan tidak dapat dipublikasikan. Repositori ini berisi **dokumentasi, alur sistem, dan tampilan antarmuka** yang saya susun dan kembangkan bersama tim sebagai bukti proses kerja dan hasil akhir aplikasi.

---

## Peran Saya sebagai System Analyst

- Merancang **flowchart alur sistem** untuk tiap peran pengguna (Kepala Sekolah & Divisi Surat)
- Menyusun **dokumen kebutuhan (requirement)** aplikasi berdasarkan permintaan klien
- Membuat **buku panduan penggunaan** aplikasi secara lengkap untuk pengguna akhir
- Menjembatani kebutuhan pihak sekolah dengan tim developer selama proses pengembangan

---

## Alur Login & Registrasi

| Akses Website | Registrasi Akun |
|---|---|
| ![Akses Website](images/01-akses-website.png) | ![Register](images/02-register.png) |

| Form Data Diri | Login |
|---|---|
| ![Form Register](images/03-form-register.png) | ![Login](images/04-login.png) |

Setelah login, pengguna diarahkan ke tampilan yang berbeda sesuai peran/jabatan masing-masing.

---

## Alur Kepala Sekolah

Kepala Sekolah dapat meninjau, menandatangani secara digital, atau merevisi surat yang masuk.

![Dashboard Kepala Sekolah](images/05-dashboard-kepsek.png)
*Halaman utama menampilkan surat yang perlu ditandatangani, surat terbaru, dan jumlah surat masuk dalam 1 minggu terakhir.*

![Konfirmasi Surat](images/06-konfirmasi-surat.png)
*Daftar surat yang menunggu tanda tangan.*

![Daftar Surat](images/07-daftar-surat-ttd.png)

![Tanda Tangan Digital](images/08-ttd-digital.png)
*Menekan tombol "Terima" akan otomatis membuat barcode tanda tangan digital pada surat.*

![Surat Terkonfirmasi](images/09-surat-terkonfirmasi.png)
*Status surat otomatis berubah menjadi "sudah ditandatangani".*

![Form Revisi](images/10-form-revisi.png)
*Jika surat ditolak, sistem menampilkan form revisi yang otomatis terkirim ke Divisi Surat.*

---

## Alur Divisi Surat

Divisi Surat bertugas mengelola seluruh siklus dokumen: upload, edit, arsip, hingga pengiriman surat.

![Dashboard Divisi Surat](images/11-dashboard-divisi-surat.png)
*Ringkasan proses persuratan minggu berjalan: surat ditandatangani, dokumen baru, dan surat direvisi.*

![Tambah Dokumen](images/12-tambah-dokumen.png)

![Form Upload Surat](images/13-form-upload-surat.png)
*Form pengisian data surat sebelum dikirim ke Kepala Sekolah untuk ditandatangani.*

![Arsip Surat](images/14-arsip-surat.png)

![Daftar Arsip](images/15-daftar-arsip-surat.png)
*Seluruh riwayat surat yang pernah diupload.*

![Edit Surat](images/16-edit-surat.png)

![Form Edit Surat](images/17-form-edit-surat.png)
*Pembaruan data surat yang memerlukan revisi.*

![Konfirmasi Hapus](images/18-hapus-surat.png)
*Pop-up konfirmasi sebelum data surat dihapus permanen.*

![Kirim Surat](images/19-kirim-surat.png)

![Daftar Kontak](images/20-daftar-kontak.png)
*Daftar nama dan nomor WhatsApp penerima surat.*

![Tombol Hubungi](images/21-tombol-hubungi.png)

![Integrasi WhatsApp](images/22-integrasi-whatsapp.png)
*Sistem otomatis mengarahkan ke WhatsApp untuk mengirimkan surat langsung ke pihak terkait.*

---

## Insight & Pembelajaran

Melalui proyek ini saya belajar menyusun alur sistem multi-role (Kepala Sekolah & Divisi Surat) yang saling terhubung, menerjemahkan kebutuhan klien non-teknis menjadi dokumen requirement dan flowchart yang bisa diimplementasikan tim developer, serta menyusun dokumentasi pengguna akhir yang mudah dipahami oleh staf sekolah yang awam teknologi.

---

## Kontak
Synthia Wulandari — [Synthiawln@gmail.com](mailto:Synthiawln@gmail.com) · [LinkedIn](https://linkedin.com/in/synthia-wln)
