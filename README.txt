TDP WORKSHOP APP - STARTER

PENTING:
Ini adalah starter awal untuk menghubungkan halaman aplikasi dengan proyek Supabase.
Belum merupakan aplikasi operasional lengkap. Modul SPK dan PM perlu disesuaikan dengan struktur tabel aktual.
Jangan gunakan untuk operasional sebelum pengujian hak akses selesai.

CARA PAKAI:
1. Ekstrak ZIP.
2. Hosting folder ini pada alamat HTTPS (misalnya layanan hosting web statis).
3. Buka website, masukkan Project URL dan anon/publishable key dari Supabase.
4. Jangan pernah memasukkan service_role key ke aplikasi/browser.
5. Login memakai email dan password yang sudah dibuat di Supabase Authentication.

CATATAN:
- File ini memakai Supabase JavaScript v2 dari CDN, jadi perlu internet.
- Koneksi disimpan di browser perangkat tersebut.
- Login bergantung pada tabel public.profiles dan RLS Supabase.
- Admin tidak diberi tombol tambah/edit unit di starter ini; pembatasan sebenarnya wajib ditegakkan oleh RLS database.
- Jangan membagikan Project URL bersama secret/service_role key.
