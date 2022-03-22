#include<iostream>

using namespace std;

int main(){
	string nama,pertamax,pertalite;
	int kode,ptx,ptl,jml,tot,kbl,byr;
	cout<<"        SPBU       "<<endl;
    cout<<"============================================"<<endl;
    cout<<"Jenis Bensin        Harga"<<endl;
    cout<<"1. Pertamax        Rp. 9.000"<<endl;
    cout<<"2. Pertalite       Rp. 7.000"<<endl;
    cout<<"============================================"<<endl;
    cout<<"Nama Pelanggan :";
	cin>>nama;
    cout<<"Masukan Pilihan : ";
    cin>>kode;
    
    switch (kode){
    case 1:
        cout<<"PERTAMAX"<<endl;
        ptx=9000;
        cout<<"Jumlah Liter:";
        cin>>jml;
            tot=ptx*jml;
        cout<<"Total harganya : Rp. "<<tot<<endl;
        cout<<"DIBAYAR : Rp. ";
        cin>>byr;
           kbl=byr-tot;
        cout<<"KEMBALI : Rp. "<<kbl<<endl;
        break;
    case 2:
        cout<<"PERTALITE"<<endl;
            ptl=7000;
        cout<<"Jumlah Liter :";
        cin>>jml;
            tot=ptl*jml;
        cout<<"Total harganya : Rp. "<<tot<<endl;
        cout<<"DIBAYAR : Rp. ";
        cin>>byr;
           kbl=byr-tot;
        cout<<"KEMBALI : Rp. "<<kbl<<endl;
        break;
	}
	cout<<"			Struk		"<<endl;
	cout<<"================================="<<endl;
	cout<<"Nama		: "<<nama<<endl;
	//cout<<"Jenis Bensin : "<<
	cout<<"Total Liter	: "<<jml<<endl;
	cout<<"Total Harga	: "<<tot<<endl;
	cout<<"Dibayar		: "<<byr<<endl;
	cout<<"Kembalian	: "<<kbl<<endl;
	cout<<"Terimaksih ";
	return 0;	
}
