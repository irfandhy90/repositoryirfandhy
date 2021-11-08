# repositoryirfandhy

soal

pada lab2 latihan1 saya di beri tugas seperti di bawah ini :

![img](gambar/ss1.png)

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

dari proses di atas saya mendapatkan output :

![img](gambar/gambar1.png)

Lab 2 latihan 2 

soal 

pada lab 2 latihan 2 saya mendapat soal berikut :

![img](gambar/ss2.png)

    data = []
    for i in range (5):
        x =int(input("masukan bilangan : "))
        data.append(x)
    print('data sebelum diurutkan: ',data)
    list.sort(data)
    print('data setelah diurutkan: ',data)

hasil output 

![img](gambar/gambar2.png)

Lab 3 latihan 1 

pada lab 3 latihan 1 saya mendapat soal berikut :

![img](gambar/ss3.png)

untuk mengerjakan saya menggunakan syntax di bawah :

    baris = 10
    kolom = baris

    for bar in range(baris):
        for col in range(kolom):
            tab = bar+col
            print("{0:>5}".format(tab), end='')
        print()

dari contoh yg di atas saya mendapat output seperti di bawah ini :

![img](gambar/gambar3.png)

Lab 3 latihan 2 

Soal 

pada lab 3 latihan ke 2 saya di beri soal berikut : 

![img](gambar/ss4.png)

untuk mengerjakan soal di atas saya menggunakan syintax berikut : 

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)

dari proses di atas saya mendapat output di bawah ini :

![img](gambar/gambar4.png)

Terima Kasih 


