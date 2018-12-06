# Praktikum_8

# Latihan 1 (Buatlah fungsi fibonacci dengan cara iteratif)

```
1.mulai program
2.int iteratif (int suku, int a, int b, int c)
3.a=0, b=1;
4.if (suku == 1) return b;
5.if (suku == 0) return a;
6.else
7.for(int i=2; i<=suku; i++){
8.c = a + b;
9.a = b;
10.b = c;
11.int suku, a, b,c;
12.cout<<"Masukkan nilai suku ke-: ";
13.cin>>suku;
14.cout<<"\nBilangan fibonaccinya untuk "<<suku<<" adalah ";
15.cout<< iteratif ( suku,  a,  b,  c);
16.selesai

``` 

Hasil Screenshot






![alt text](https://github.com/etrianmartianto/Praktikum_8/blob/master/Fungsi_fibonacci_dengan_cara_iteratif/ss_fungsi_fibonacci_dengan_cara_iteratif.png)


# Latihan 2 (Buatlah fungsi rekursif untuk perkalian dua buah bilangan dengan cara penjumlahan)

```

1.mulai program
2.faktorial dengan rekursif
3.int faktorial(int n){
4.if (n==0 || n==1){
5.cout << "1\n";
6.return 1;
7.} else 
8.cout << n << "*";
9.return n * faktorial (n-1);
10.int main()
11.int n;
12.cout << "\nMasukkan nilai n! ";
13.cin >> n;
14.cout << n << "! = ";
15.cout << "Maka nilai " << n << " faktorial dengan rekursif: " << faktorial(n) << endl << endl;
16.selesai

```

Hasil Screenshoot





![alt text](https://github.com/etrianmartianto/Praktikum_8/blob/master/Latihan_2/ss_latihan_2.png)



# Latihan 3 (Carilah kasus lain yang bisa diselesaikan dengan cara rekursif dan iteratif)

```

1.mulai program
2.int kali1(int a, int b){
3.int hasil =0;
4.for(int i=0;i<b;i++){
5.hasil=hasil+a;
 }
6.return hasil;
 }
7.int kali2(int a, int b){
8.if(b==0)
9.return 1;
10.else if(b==1)
11.return a;
12.else
13.return a+kali2(a,b-1);
 }
14.int main(int argc, char *argv[])
 {
15.int a,b;
16.cout<<"masukkan a :";
17.cin>>a;
18.cout<<"masukkan b :";
19.cin>>b;
20.cout<<"secara ITERATIF :"<<endl;
21.cout<<kali1(a,b)<<endl;
22.cout<<"secara REKURSIF"<<endl;
23.cout<<kali2(a,b)<<endl;
24.system("PAUSE");
25.return EXIT_SUCCESS;
 }
26.selesai

```

Hasil Screenshoot







![alt text](https://github.com/etrianmartianto/Praktikum_8/blob/master/Latihan_3/ss_latihan_3.png)






Fibonacci






![alt text](https://github.com/etrianmartianto/Praktikum_8/blob/master/Latihan_1/ss_latihan_1.png)






Fungsi Iterasi






![alt text](https://github.com/etrianmartianto/Praktikum_8/blob/master/Fungsi_iterasi/ss_fungsi_iterasi.png)

