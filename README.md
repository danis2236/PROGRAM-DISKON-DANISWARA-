#include <iostream>
using namespace std;

int main() {
	// deklarasi variabel
	double hargaBarang, diskonPersen, besarnyaDiskon, hargaSetelahDiskon;

	// input harga barang
	cout << "MASUKAN HARGA BARANG : ";
	cin >> hargaBarang;

	// input diskon dalam persen
	cout << "MASUKAN DISKON : ";
	cin >> diskonPersen;
	
	// menghitung besarnya diskon
	besarnyaDiskon = (diskonPersen / 100) * hargaBarang;

	//menghitung harga barang setelah diskon 
	hargaSetelahDiskon = hargaBarang - besarnyaDiskon;

	// output hasil
	cout << "harga barang sebelum diskon: Rp " << hargaBarang << endl;
	cout << "besarnya diskon: Rp " << besarnyaDiskon << endl;
	cout << "harga barang setelah diskon: Rp " << hargaSetelahDiskon << endl;

	return 0;

}
