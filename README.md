#include<iostream>

using namespace std;

// ini adalah prototype function
void penjumlahan ( int x, int y){
	cout << (x + y);}
void pengurangan ( int a, int b){
	cout << (a - b);}
double pembagian ( double c, double d){
	cout << (c / d);}
void perkalian ( int angka1, int angka2){
	cout << (angka1 * angka2);}

int main (){
	satu:
	int pilih;
	char pilih1;
	cout<<"Menu Aritmatika"<<endl;
	cout<<"1. Penjumlahan"<<endl;
	cout<<"2. pengurangan"<<endl;
	cout<<"3. Pembagian"<<endl;
	cout<<"4. perkalian"<<endl;
	cout<<"Masukan pilihan :";cin>>pilih;
	if (pilih==1) {
	 cout<<"Penjumlahan (60+35)"<<endl;
	 penjumlahan (60,35);}
	else if (pilih==2) {
	 cout<<"pengurangan (30-15)"<<endl;
	 pengurangan (30,15);}
	else if (pilih==3) {
	 cout<<"Pembagian (60/4)"<<endl;
	 pembagian (60,4);}
	else if (pilih==4) {
	 cout<<"perkalian (50*4)"<<endl;
	 perkalian (50,4);}
	else {
		cout<<"\nMaaf angka yang anda masukan salah, program akan di ulang"<<endl;
		goto satu;
		}			
}
