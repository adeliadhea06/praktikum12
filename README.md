# Praktikum 12

Nama : Dhea Dwi Adelia

NIM  : 312210116

Kelas : TI.22.A.1

## Python String
### Latihan
    txt = 'Hello Word'
- Hitung jumlah karakternya
- Ambil karakter terakhir
- Ambil karakter index ke-2 sampai index ke-4 (llo)
- Hilangkan spasi pada text tersebut(HelloWord)
- Ubah text menjadi huruf besar
- Ubah text menjadi huruf kecil
- Ganti karakter H dengan karakter J

## Penjelasan

### Hitung jumlah karakternya

- Fungsi len() digunakan untuk mengidentifikasi dan mengetahui seberapa panjang jumlah item atau anggota pada suatu objek.

        data1='Hello Word'
        print (data1)
        print ("Jumlah karakter :",len(data1))
        
![image](https://user-images.githubusercontent.com/115794875/209493365-6e3e2d05-da05-4ec3-a98e-588e60c19ae9.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209493524-8b384329-b105-49d8-9144-9091c8fca559.png)

### Ambil karakter terakhir

- data1[9] yaitu untuk mengambil karakter ke-9 di variabel data1='Hello Word'

        print("Karakter terakhir:",data1[9])
        
![image](https://user-images.githubusercontent.com/115794875/209493752-e139a81e-6b75-439c-bb36-13c802bf332a.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209493827-f68c051c-3895-48bb-b8e8-5c5cf6d0ccba.png)

### Ambil karakter index ke-2 sampai index ke-5 (llo)

        print("Index ke 2 sampai 4:",data1[2:5])
        
![image](https://user-images.githubusercontent.com/115794875/209494052-5cfbd5a2-ae21-4315-9d99-4cee046e4d67.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209494091-00e46c52-0fd7-4b7f-bfa0-ecd3a91895f2.png)

### Hilangkan spasi pada text tersebut(HelloWord)

- Fungsi replace() untuk mengganti kemunculan karakter substring tertentu dalam string dengan karakter substring tertentu.

        data1='Hello Word'
        x=data1.replace(" ", "")
        print(x)

![image](https://user-images.githubusercontent.com/115794875/209494387-4544f30b-97f9-47be-a75c-11fb08205c96.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209494422-7e13f2ce-4f28-4125-9a40-58b44b51cde7.png)

### Ubah text menjadi huruf besar

- Fungsi upper() adalah fungsi integral dalam Python untuk mengubah huruf menjadi huruf besar

        data1='Hello Word'
        print(data1.upper())

![image](https://user-images.githubusercontent.com/115794875/209494659-abdf7100-08d4-4472-b6ac-63feb38c42e8.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209494695-12d9168a-2d87-4ef2-9a6e-c3c4343747bd.png)

### Ubah text menjadi huruf kecil

- Fungsi lower() yaitu untuk mengkonversikan huruf besar menjadi huruf kecil

        data1='Hello Word'
        print(data1.lower())
        
![image](https://user-images.githubusercontent.com/115794875/209494966-9e7a9db3-c27e-4148-a9d5-462239eb08a5.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209495003-8027ccf4-d325-4505-8139-43c2c2c193fb.png)

### Ganti karakter H dengan karakter J

        data1='Hello Word'
        kata_baru=data1.replace('H', 'J')
        print(kata_baru)
        
![image](https://user-images.githubusercontent.com/115794875/209495156-f832ad15-fd76-4823-a52a-4feaea8f5fff.png)

- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209495185-9d884851-990c-448a-a78d-486374cc0791.png)

### Latihan
- Lengkapi kode berikut:

        umur = 24
        txt = 'Hello, nama saya john, dan umur saya adalah
        ... tahun'

        print(txt.format(umur))
 
        umur='24'
        txt='Hallo, nama saya john, dan umur saya adalah', umur, 'tahun'
        
        print(txt.format(umur))
        
- Berikut hasil run

![image](https://user-images.githubusercontent.com/115794875/209496068-799cb1a0-94f3-411d-9918-7513c8d41454.png)

## Sekian, Terima Kasih.

