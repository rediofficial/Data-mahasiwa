# Data-mahasiwa
rule = "+-----------------------------------------------+" print(rule) space = " " print("|\t** APLIKASI HITUNG NILAI MATAKULIAH ** \t|") print("|\t ** PROGRAM STUDI SISTEM INFORMASI **\t|") print(rule) print("") nim = int(input("Nim : ")) nama = input("Nama : ") kelas = input("Kelas : ") print(space) Mat_Kuliah = input("Mata Kuliah : ") N_Presensi = int(input("Nilai Presensi : ")) N_Tugas = int(input("Nilai Tugas : ")) N_UTS  = int(input("Nilai UTS : ")) N_UAS  = int(input("Nilai UAS : "))  def nilai():     ntotal = N_Presensi*0.2 + N_Tugas*0.25 + N_UTS*0.25 + N_UAS*0.3     print(int(ntotal))  def ntotal(ket) :     if ntotal >=60:         ket = ("Keterangan : Lulus")         return print(ket)     else :         ket = ("Keterangan : Gagal")         return print(ket)  def grade(ntotal) :     if ntotal (80-100):         grade = "A"         print(grade)     elif ntotal (70-79):         grade = "B"         print(grade)     elif ntotal (60-60):         grade = "C"         print(grade)     elif ntotal (21-59):         grade = "D"         print(grade)     else :         grade = "E"         print(grade)  print("------------Total Nilai------------") nilai() print(ket) grade()
