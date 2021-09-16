# web-assignment-skilvul
Module 1 - Unix Command Line
1.	membuat sebuah folder kosong dengan nama-mu sendiri
2.	mkdir Singgih
 ![image](https://user-images.githubusercontent.com/61181279/133593323-28bd8771-8903-4948-a0ae-39cec4075200.png)

3.	didalam folder tersebut buatlah
o	folder sekolah
o	folder kerja
4.	mkdir Singgih/sekolah
5.	mkdir Singgih/kerja
6.	cd Singgih
 ![image](https://user-images.githubusercontent.com/61181279/133593414-f73afd57-ac6c-4804-ba40-a04d997e1f8d.png)

7.	masuk kedalam folder sekolah
8.	cd sekolah
o	buat file dengan nama ijazah.txt, yang mana file tersebut akan memiliki teks seperti:
o	Perkenalkan namaku $NAMA
o	
o	Aku berasal dari $DAERAH
o	
o	Salam Kenal :D
o	touch ijazah.txt
o	tampilkan isi dari file tersebut menggunakan CLI command
o	cat ijazah.txt
 ![image](https://user-images.githubusercontent.com/61181279/133593451-7b4992e6-cf1d-43d2-b088-235a7e75f4f9.png)

o	kemudian buat 1 file lagi dengan nama portfolio.txt, yang mana file tersebut akan memiliki teks seperti:
o	Saya pernah bekerja pada beberapa perusahaan salah satu 
o	diantaranya ialah
o	
o	- $PERUSAHAAN
o	- $PERUSAHAAN
o	- $PERUSAHAAN
o	touch portfolio.txt
 ![image](https://user-images.githubusercontent.com/61181279/133593474-1d844cdc-cf48-4a6c-8f75-e50cc98c8f55.png)

9.	keluar dari folder sekolah
10.	cd ..
11.	masuk ke dalam folder kerja
12.	cd kerja
o	buat file dengan nama cv.txt, yang mana hal tersebut akan memiliki teks seperti:
o	Salam,
o	
o	 Perkenalkan namaku $NAMA, saya memiliki kegemaran
o	 - $HOBBY
o	 - $HOBBY
o	 - $HOBBY
o	touch cv.txt
o	tampilkan isi dari file tersebut menggunakan CLI command
o	cat cv.txt
 ![image](https://user-images.githubusercontent.com/61181279/133593507-83146d64-a789-4d63-b7ba-40c2c8a13357.png)

13.	Pada tahap ini kamu lupa jika sebenarnya file portfolio.txt serahusnya tidak berada pada folder sekolah, jadi kamu harus memindahkannya kedalam folder kerja
14.	cd ../sekolah
15.	mv portfolio.txt ../kerja
 ![image](https://user-images.githubusercontent.com/61181279/133593522-282582a8-02eb-40bf-a806-561a00d384a2.png)


