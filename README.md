print("SELEKSI BEASISWA CERDAS BANGSA")
Nama= input("Masukkan nama siswa")
Nilai_UTS=int(input("Masukkan nilai UTS(0-100):"))
Nilai_UAS=int(input("Masukkan nilai UAS(0-100):"))
Kehadiran=int(input("Masukkan persentase kehadiran(0-100):"))
pernah_melanggar_input=input("Apakah pernah melanggar_disiplin?(y/t):")
pernah_melanggar=pernah_melanggar_input.lower()=='y'
print("HASIL ANALISIS")
Nilai_Akhir=((Nilai_UTS * 0.4)+(Nilai_UAS * 0.6))
if not pernah_melanggar and Nilai_Akhir >=90 and Kehadiran>= 95:
	print("Selamat! Anda lolos seleksi beasiswa Kategori A")
if not pernah_melanggar and Nilai_Akhir>=80 and Kehadiran>=85:
	print("Selamat! Anda lolos beasiswa Kategori B")
else:
	print("Mohon maaf Anda tidak lolos seleksi")
