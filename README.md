# 🎓 Sistem Seleksi Beasiswa Cerdas Bangsa

Program berbasis Python sederhana untuk melakukan analisis kelayakan dan seleksi penerima beasiswa secara otomatis berdasarkan nilai akademik, tingkat kehadiran, dan catatan kedisiplinan siswa.

## 🚀 Fitur Utama
* **Bobot Nilai Otomatis**: Menghitung Nilai Akhir berdasarkan pembobotan nilai UTS (40%) dan nilai UAS (60%).
* **Validasi Kedisiplinan**: Mengecek rekam jejak pelanggaran disiplin siswa sebagai syarat mutlak kelolosan.
* **Kategori Beasiswa Ganda**: Menyeleksi siswa ke dalam Beasiswa Kategori A atau Kategori B berdasarkan kriteria nilai dan kehadiran yang berbeda.

## 📋 Kriteria Kelolosan Beasiswa
1. **Beasiswa Kategori A**:
   * Tidak pernah melanggar disiplin.
   * Nilai Akhir $\ge$ 90.
   * Persentase Kehadiran $\ge$ 95%.
2. **Beasiswa Kategori B**:
   * Tidak pernah melanggar disiplin.
   * Nilai Akhir $\ge$ 80.
   * Persentase Kehadiran $\ge$ 85%.

## 💻 Cara Menjalankan
Jalankan file `beasiswa.py` di lingkungan Python kamu (seperti Pydroid 3), masukkan data nilai serta kehadiran siswa, dan program akan langsung mengeluarkan hasil analisis kelolosan seleksi.
