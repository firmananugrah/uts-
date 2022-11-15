print("Nama :Firman Anugrah Burhanudin ")
print("Kelas : TI J 22")
print("Nim : 20220040038")

print("\n")

def LuasSegitiga():
    print("======Hitung Luas Segitiga======")
    alas = float(input("Masukan alasnya: "))
    tinggi= float(input("Masukan tingginya: "))
    luas = 1/2*alas*tinggi
    print("Luas Segitiga Adalah: ", luas, ("cm2"))
    
def LuasPersegiPanjang():
    print("======Hitung Luas Persegi Panjang======")
    panjang=int(input("Masukan tingginya: "))
    lebar =int(input("Masukan lebarnya: "))
    luas= panjang*lebar
    print("Luas Persegi Panjang Adalah :", luas,("cm2"))
    
def MenentukanBilanganGanjildanGenap():
    print("======Menentukan Bilangan Ganjil dan Genap======")
    bil=int(input("Masukan Bilangan: "))
    if bil % 2 == 0:
        print ("%d adalah bilangan genap" %bil)
    else:
        print ("%d adalah bilangan ganjil" %bil)
            
while True:
    print("====== Program kalkulator Sederhana ======")
    userinput =int(input(
        "Menu \n1. Luas Segitiga \n2. Luas Persegi Panjang \n3. Tentukan Number Ganjil Genap \n4. Quit \n Pilih Nomor: " ))
    if (userinput == 1):
        LuasSegitiga()
    elif (userinput == 2):
        LuasPersegiPanjang()
    elif (userinput == 3):
        MenentukanBilanganGanjildanGenap()
    else :
        print("PROGRAM SELESAI TERIMAKASIH TELAH MEMAKAI APLIKASI KAMI🤞")
        
