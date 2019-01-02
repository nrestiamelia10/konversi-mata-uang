#include <iostream>

using namespace std;

int main()
{
    float rupiah, euro, yen, dollar, ringgit, pound; int pilih;
    cout<<"\t\t\t==============================\t\t\n";
    cout<<"\t\t\tKonversi Mata Uang\t\t\n"<< endl;
    cout<<"\t\t\t==============================\t\t\n";
    cout<<"1. Rupiah Ke Dollar Amerika"<<endl;
    cout<<"2. Rupiah ke Euro"<< endl;
    cout<<"3. Rupiah ke Pound Ingrris"<< endl;
    cout<<"4. Rupiah ke Yen Jepang "<< endl;
    cout<<"5. Rupiah ke Ringgit Malaysia"<<endl;
    cout<<"\t\t\t==============================\t\t\n";
    cout<<endl;
    cout<<"Input Pilihan Anda    :";cin>>pilih;
    if(pilih==1)
    {
        cout<< "n.1 Rupiah Ke Dollar Amerika"<<endl;
        cout<< "----------------------------";
        cout<< "Input Nilai Rupiah   :";cin>>rupiah;
        dollar=rupiah*0.00013;
        cout<< "Nilai Dollar Amerika :"<<dollar<<endl;
    }
    else if (pilih==2)
    {
        cout<< "n.2 Rupiah Ke Euro"<<endl;
        cout<< "Input Nilai Rupiah   :";cin>>rupiah;
        euro=rupiah*0.00007;
        cout<< "Nilai Euro           :"<<euro<<endl;
    }
    else if(pilih==3)
    {
        cout<< "n.3 Rupiah ke Pound Inggris"<<endl;
        cout<< "Input Nilai Rupiah   :";cin>>rupiah;
        pound=rupiah*0.0005;
        cout<< "Nilai Pound"<<pound<<end;
    }
    return 0;
}
