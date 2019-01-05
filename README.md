# C-Konversi-Detik

    #include <iostream>

    using namespace std;

    int main()
    {
    int hari,jam,menit,sisa,detik;

    cout << "\t\t\Pelita bangsa\n\n" << endl;
    cout << "==========================================\n" << endl;
    cout << "Nama : Rafi Alwan Setyawan \nNIM  : 311810325\n" << endl;
    cout << "==========================================\n" << endl;

    cout << "\t     Konversi Detik\n" << endl;


    cout<<"Masukkan detik      =  ";
    cin>>detik;

    hari=detik/86400;
    sisa=detik%86400;
    jam=sisa/3600;
    sisa=detik%3600;
    menit=sisa/60;
    sisa=sisa%60;

    cout<< "\n==========================================\n" <<endl;
    cout<<"Jadi, "<<detik<<" detik  =\n"<<endl;
    cout<<"- "<<hari<<" hari"<<endl;
    cout<<"- "<<jam<<" jam "<<endl;
    cout<<"- "<<menit<<" menit "<<endl;
    cout<<"- "<<sisa<<" detik\n"<<endl;

    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Konversi-Detik/blob/master/C++%20Konversi%20Detik.png?raw=true)
