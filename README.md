#nomer 1 
awal = int(input("masukkan nilai awal: "))
akhir = int(input("masukkan nilai akhir"))

while awal < akhir:
    if awal%2:
        print(awal)
    awal +=1



    #nomer 2
masukkan = int(input("masukkan jumlah mahasiswa"))
for i in range (masukkan):
    print(f"mahasiswa ke- {i+1}:")
    matkul = int(input("banyak mata kuliah yang di ambil:"))
    total_nilai=0

    for j in range(matkul):
        nilai=float(input(f"input nilai matkulke- {j+1}:"))
        total_nilai += nilai
    rata= total_nilai/matkul
    print("rata-rata",rata)

print("--------------------------\n")
