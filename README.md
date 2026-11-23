# AI Agent Skills untuk 5 Studi Kasus Magang

Repository ini berisi rancangan AI Agent Skills untuk mengotomatisasi aktivitas repetitif pada lima lingkungan magang: administrasi pemerintahan daerah, registrasi klinik, digital marketing agency, HRD perusahaan sawit, dan bagian kredit bank.

## Tujuan
- Memetakan jobdesk dan proses kerja berulang.
- Menentukan aktivitas yang aman untuk dibantu atau diotomatisasi AI Agent.
- Menyediakan instruksi skill yang dapat dipakai sebagai dasar implementasi agent.

## Struktur
```
.
├── README.md
├── docs/
│   └── analisis-jobdesk.md
└── skills/
    ├── government-admin-assistant/SKILL.md
    ├── clinic-registration-assistant/SKILL.md
    ├── digital-marketing-assistant/SKILL.md
    ├── plantation-hr-assistant/SKILL.md
    └── banking-credit-assistant/SKILL.md
```

## Ringkasan agent

| Studi kasus | Nama AI Agent | Fokus otomatisasi |
|---|---|---|
| Administrasi dinas | Government Administration Assistant | Surat, arsip, agenda, laporan |
| Klinik | Clinic Registration Assistant | Registrasi, validasi data, pengumpulan anamnesa, antrean |
| Digital marketing | Digital Marketing Assistant | Riset konten, caption, kalender, laporan |
| HRD perusahaan sawit | Plantation HR Assistant | Data karyawan, absensi, berkas rekrutmen, rekap HR |
| Kredit bank | Banking Credit Assistant | Administrasi aplikasi, kelengkapan dokumen, ringkasan keuangan |

## Cara menggunakan
1. Pilih folder skill sesuai kebutuhan.
2. Baca file `SKILL.md` dan sesuaikan nama sistem, format dokumen, SOP, serta aturan organisasi.
3. Hubungkan agent dengan aplikasi internal melalui API atau tools yang telah mendapat izin.
4. Uji menggunakan data dummy terlebih dahulu.
5. Terapkan persetujuan manusia sebelum tindakan berdampak penting.

Setiap file skill menggunakan struktur instruksi berbasis Markdown dengan metadata YAML sederhana. Skill ini adalah rancangan/panduan implementasi, bukan aplikasi produksi yang sudah terhubung ke sistem instansi.

## Prinsip keamanan dan batasan
- Gunakan data dummy saat demonstrasi tugas.
- Jangan mengunggah data pribadi, rekam medis, data karyawan, dokumen identitas, atau data keuangan nasabah ke repository publik.
- Terapkan akses minimum, pencatatan aktivitas, enkripsi, dan kebijakan retensi data.
- AI boleh menyiapkan draf, mengelompokkan, memeriksa kelengkapan, dan menghitung berdasarkan aturan yang diberikan; keputusan resmi tetap pada petugas berwenang.
- Untuk klinik, diagnosis dan keputusan medis dilakukan tenaga kesehatan.
- Untuk bank, keputusan persetujuan/penolakan kredit dan penilaian risiko final dilakukan analis/pejabat berwenang.
- Untuk HRD, keputusan perekrutan, sanksi, dan tindakan kepegawaian tetap melalui penilaian manusia.

## Contoh instansi
Rancangan ini bersifat generik dan dapat disesuaikan untuk lingkungan seperti kantor dinas/kominfo, operator telekomunikasi, museum, klinik, agensi, perusahaan perkebunan, atau bank. Nama instansi pada contoh tidak menyatakan bahwa instansi tersebut telah menggunakan agent ini.

## Lisensi
MIT — lihat file LICENSE.
