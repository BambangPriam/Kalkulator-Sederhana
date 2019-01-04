# Kalkulator-Sederhana
    #include<iostream>
    #include<conio.h>
    using namespace std;

    int main()
    {
        int bil1, bil2, pilihan;
        cout << "\n\n\n";

        cout << "Pilih fungsi yang akan digunakan:\n";
        cout << "1. Penjumlahan\n";
        cout << "2. Pengurangan\n";
        cout << "3. Perkalian\n";
        cout << "4. Pembagian\n";
        cout << "Pilihan fungsi: ";
        cin >> pilihan;

        cout << "\n\n\n";
        cout<< "Masukkan bilangan pertama: ";
        cin >>bil1;
        cout << "Masukkan bilangan kedua: ";
        cin >> bil2;

        switch(pilihan)
        {
        case 1:
            cout << "Hasil penjumlahan dari " << bil1 << " dan " << bil2 << " adalah " << bil1+bil2 << endl;
            break;
        case 2:
            cout << "Hasil pengurangan dari " << bil1 << " dan " << bil2 << " adalah " << bil1-bil2 << endl;
            break;
        case 3:
            cout << "Hasil perkalian dari " << bil1 << " dan " << bil2 << " adalah " << bil1*bil2 << endl;
            break;
        case 4:
            cout << "Hasil pembagian dari " << bil1 << " dan " << bil2 << " adalah " << bil1/bil2 << endl;
            break;
            default:

        return 0;
    }
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Kalkulator-Sederhana/master/Kalkulator%20Sederhana.png)
