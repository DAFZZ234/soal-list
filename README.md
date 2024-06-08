inventaris = ["laptop", "printer", "scanner", "monitor"]

print(inventaris)

item_baru = "keyboard"

inventaris.append(item_baru)

print(inventaris)
  
karyawan = ["andi", "budi", "dewi", "citra"]

print(karyawan)

karyawan_baru = "Eka"

karyawan.append(karyawan_baru)

print(karyawan)

harga_produk = [50000, 150000, 250000, 750000]

print(harga_produk)

harga_baru = 100000

harga_produk.append(harga_baru)

print(harga_produk)

inventaris.remove("scanner")

print(inventaris)
karyawan.remove("budi")
print(karyawan)
print(len(inventaris))
print(len(karyawan))


boarding_level7 = ("jeki", "akhdan", "alghar", "ukek")

boarding_level8 = ("alpat", "athat", "agem", "banyu api", "satria")

boarding_level9 = ("dzaki", "yapi", "iting")

suku_techno = boarding_level7 + boarding_level8 + boarding_level9

print(suku_techno)
