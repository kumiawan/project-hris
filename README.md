# Project HRIS x KARISMA
# Feature :
1. Konsep Umum HRIS
HRIS (Human Resource Information System) dirancang sebagai portal internal perusahaan dengan
sistem akun dan kata sandi individual untuk setiap karyawan.
## Tujuan utamanya:
 Transparansi data karyawan
 Efisiensi administrasi HR
 Mengurangi proses manual (kertas, Excel, Whatsapp)
2. Struktur Pengguna & Hak Akses
A. Karyawan (Employee User)
Setiap karyawan memiliki:
 User ID & password pribadi
 Akses hanya ke data milik sendiri
## Fitur yang dapat diakses karyawan:
1. Data Pribadi
o Nama, NIK, alamat, kontak darurat
o Jabatan, divisi, status karyawan
o Tanggal masuk & masa kerja
2. Administrasi Kepegawaian
o Absensi/Pengajuan cuti (tahunan, sakit, izin resmi, NWNP)
o Nilai KPI, SS
o Riwayat cuti & sisa cuti
o Riwayat perubahan jabatan
3. Payroll & Benefit
o Rincian potongan gaji
o Nomor BPJS Kesehatan & Ketenagakerjaan
o Status kepesertaan BPJS
4. Keamanan Akun
o Ganti password sendiri
o Logout otomatis (session timeout)
5. Pengajuan Cuti
B. Admin HRD (HR Administrator)
HRD bertindak sebagai super admin / admin sistem.
## Hak & tanggung jawab HRD:
1. Manajemen Data Karyawan
o Input & update data karyawan
o Aktivasi / nonaktif akun karyawan
o Reset password
2. Manajemen Cuti
o Menyetujui / menolak pengajuan cuti
o Mengatur jenis cuti & kuota cuti
o Melihat laporan cuti
3. Payroll Management
o Upload rincian potongan gaji
o Atur komponen gaji & potongan
o Update data BPJS
4. Kontrol Konten HRIS
o Menentukan data apa saja yang ditampilkan atau disembunyikan dari karyawan
o Upload pengumuman / kebijakan HR (opsional)
5. Reporting
o Rekap data karyawan
o Rekap cuti, gaji, dan kepesertaan BPJS
3. Alur Kerja Sederhana (Flow)
Contoh: Pengajuan Cuti
1. Karyawan login HRIS
2. Karyawan mengajukan cuti
3. Sistem notifikasi ke atasan langsung
4. Atasan langsung approve / reject
5. Sistem notifikasi ke Kepala Departemen
6. Kepala Departemen approve / reject
7. Sistem notifikasi ke HRD
8. HRD approve / reject dan memberi tanda approval direksi
9. Status cuti otomatis terupdate & terlihat karyawan
4. Keamanan & Privasi Data
 Sistem role-based access (karyawan vs HRD)
 Data karyawan tidak bisa dilihat oleh karyawan lain
 Password terenkripsi
 Audit log untuk perubahan data oleh HRD
