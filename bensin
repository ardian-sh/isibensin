import os
import time

os.system("cls")

harga = 9000
liter = 0
full = 10
pembelian = int(input("masukan jumlah pembelian : Rp. "))
total_liter = pembelian / harga

print("{:<6}  {:<6}".format("Liter","Rupiah"))
while (liter <= round(total_liter)):
    if(liter != round(total_liter)):
        print("{:<6}  {:<6}".format(liter,(str(harga*liter)+".0")))
        time.sleep(0.8)
    else:
        print("{:<6}  {:<6}".format(round(total_liter,1),(harga*total_liter)))
        time.sleep(0.8)

    if(liter == full):
        print("penyimpanan bahan bakar sudah terisi penuh")
        print("uang kembali: {0}".format(pembelian - (harga*liter)))
        break;

    liter+=1
