# Sayı tahmin oyunu

import random

def tahmin_oyunu():
    # Rastgele bir sayı üret
    sayi = random.randint(1, 100)

    # Oyuncudan tahminini al
    tahmin = int(input("Bir sayı tahmin et: "))

    # Tahmini doğru mu kontrol et
    if tahmin == sayi:
        print("Tebrikler! Tahmininiz doğru.")
    else:
        print("Tahmininiz yanlış. Doğru sayı:", sayi)

if __name__ == "__main__":
    tahmin_oyunu()
