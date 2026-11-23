# Analisis Jobdesk dan Aktivitas Repetitif

Dokumen ini memetakan pekerjaan yang mungkin dibantu AI Agent. Otomatisasi harus mengikuti SOP dan persetujuan instansi.

## 1. Administrasi perkantoran dinas pemerintahan daerah

**Jobdesk:** menerima dan mencatat surat masuk, menyiapkan surat keluar, mengarsipkan dokumen, mengatur agenda rapat/kegiatan, merekap data, serta menyusun laporan administrasi.

**Aktivitas repetitif:**
- Membaca surat dan mengisi metadata (nomor, tanggal, pengirim, perihal).
- Mengelompokkan surat berdasarkan jenis/unit/tingkat prioritas.
- Membuat draf surat dari template baku.
- Memberi nama file dan mengelompokkan arsip.
- Menyusun agenda dan pengingat.
- Merekap kegiatan dan laporan rutin.

**Peran agent:** ekstraksi metadata, klasifikasi, pembuatan draf, penamaan arsip, ringkasan, dan rekap. Petugas memverifikasi isi dan pejabat berwenang menandatangani surat.

## 2. Klinik dokter — registrasi dan anamnesa

**Jobdesk:** mendaftarkan pasien, memverifikasi identitas dan jadwal, mencatat keluhan awal, mengelola antrean, serta merekap kunjungan.

**Aktivitas repetitif:**
- Mengisi formulir registrasi dan mengecek kolom wajib.
- Mencocokkan data pasien untuk mengurangi duplikasi.
- Mengumpulkan keluhan melalui pertanyaan anamnesa yang disetujui klinik.
- Menyusun ringkasan jawaban pasien tanpa menambah interpretasi.
- Mengirim informasi antrean dan membuat rekap kunjungan.

**Peran agent:** administrasi dan dokumentasi awal saja. Identitas pasien harus diverifikasi sesuai SOP; anamnesa ditinjau tenaga medis. Agent tidak mendiagnosis, memberi resep, menentukan triase darurat, atau menggantikan tenaga kesehatan.

## 3. Digital marketing agency

**Jobdesk:** riset audiens dan tren, menyusun ide konten, copywriting, kalender konten, koordinasi materi, memantau performa, dan membuat laporan kampanye.

**Aktivitas repetitif:**
- Mengubah brief menjadi daftar ide konten.
- Membuat variasi caption/headline sesuai panduan merek.
- Mengelompokkan konten berdasarkan kanal dan tujuan.
- Menyusun kalender publikasi.
- Menghitung metrik dasar (reach, engagement rate, CTR) dari data yang tersedia.
- Membuat ringkasan performa mingguan/bulanan.

**Peran agent:** menghasilkan draf dan analisis awal. Persetujuan klien/editor diperlukan sebelum publikasi atau penggunaan anggaran iklan.

## 4. HRD perusahaan kelapa sawit

**Jobdesk:** mengelola data karyawan, absensi, administrasi cuti, dokumen rekrutmen, orientasi, rekap lembur, serta laporan SDM kantor dan lokasi operasional.

**Aktivitas repetitif:**
- Memeriksa kelengkapan formulir dan dokumen.
- Memperbarui data karyawan berdasarkan dokumen yang disetujui.
- Merekap absensi, keterlambatan, cuti, dan lembur.
- Menyusun daftar kandidat berdasarkan kriteria administratif yang relevan.
- Membuat laporan jumlah karyawan dan kehadiran.

**Peran agent:** membantu administrasi dan perhitungan berdasarkan aturan yang disediakan. Jangan membuat keputusan otomatis terkait penerimaan, pemutusan hubungan kerja, disiplin, atau hak karyawan. Lindungi data pribadi dan batasi akses peran.

## 5. Bank — bagian kredit

**Jobdesk:** menerima aplikasi kredit, memeriksa kelengkapan dokumen, memasukkan data, menyusun ringkasan penghasilan/kewajiban, menyiapkan berkas analisis, dan memantau status proses.

**Aktivitas repetitif:**
- Mencatat data permohonan dan daftar dokumen.
- Mengecek keberadaan, keterbacaan, dan masa berlaku dokumen.
- Mengekstrak data yang relevan untuk diverifikasi.
- Menghitung rasio keuangan dari angka terverifikasi dengan rumus/SOP yang diberikan.
- Membuat ringkasan administrasi dan daftar kekurangan berkas.

**Peran agent:** dukungan administratif dan kalkulasi transparan, bukan pemberi keputusan kredit. Jangan menyimpulkan kelayakan final, menetapkan limit, menyetujui/menolak kredit, atau menggunakan atribut sensitif/proksi diskriminatif. Data nasabah tidak boleh digunakan di layanan AI publik tanpa dasar hukum dan persetujuan yang sesuai.

## Matriks ringkas

| Bidang | Input utama | Output agent | Pemeriksaan manusia |
|---|---|---|---|
| Administrasi dinas | Surat, template, agenda | Metadata, draf, arsip, laporan | Validasi isi dan tanda tangan |
| Klinik | Formulir dan jawaban pasien | Data registrasi, ringkasan keluhan, antrean | Verifikasi identitas dan review klinis |
| Marketing | Brief, brand guide, metrik | Ide, caption, kalender, analisis | Persetujuan brand/klien |
| HRD sawit | Data absensi, formulir, SOP | Rekap, daftar berkas, laporan | Validasi HR dan keputusan kepegawaian |
| Kredit bank | Aplikasi dan dokumen kredit | Checklist, ekstraksi, kalkulasi, ringkasan | Verifikasi analis dan keputusan pejabat kredit |

## Catatan implementasi
Sebelum go-live, lakukan pemetaan proses aktual, klasifikasi data, penilaian risiko, pengujian akurasi, pencatatan audit, serta uji penerimaan pengguna. Otomatisasi hanya boleh dilakukan pada sistem yang diizinkan organisasi.
