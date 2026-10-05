# Nabila-Pertiwi-Putri_09011382530165_Tugas5

1) Lihat peralatan I/O, character device yang ada di sistem komputer : 
   <img width="800" height="600" alt="no 1" src="https://github.com/user-attachments/assets/acab1726-1532-4bc9-8c05-8e8cc551d982" />
   <img width="800" height="600" alt="nmr 1" src="https://github.com/user-attachments/assets/44597eb0-2177-49fb-8d61-6dee2db67c2e" />

2) Buat sub direktori januari, februari, maret pada direktori latihan 5 :
   <img width="800" height="143" alt="no 2" src="https://github.com/user-attachments/assets/a17fef03-cc1b-421c-bd8f-f58413d2e574" />

3) Buat file dataku yang berisi nama, NIM, dan alamat pada sub direktori januari dan copy file dataku ke sub direktori februari dan maret :
   <img width="800" height="235" alt="nmr 3" src="https://github.com/user-attachments/assets/9f818682-b6bd-433a-bd70-ace2751854d9" />

4) Ubah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write :
   <img width="800" height="79" alt="no 4" src="https://github.com/user-attachments/assets/7665cc31-d528-4928-aebf-6e952326cff8" />

5) Ubahlah ijin akses file dataku pada sub direktori februari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute :
   <img width="800" height="62" alt="no 5" src="https://github.com/user-attachments/assets/d86d93a6-52e3-4f6f-99df-faac3e1f64fd" />

6) Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute :
   <img width="800" height="62" alt="no 6" src="https://github.com/user-attachments/assets/5d9fc25b-5065-4b28-898b-312ba7dfc4b9" />

7) Hapuslah direktori maret :
   <img width="800" height="68" alt="no 7" src="https://github.com/user-attachments/assets/60ffd6cb-55be-4dfd-9e46-cea31fba2453" />

8) Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari :
   <img width="800" height="58" alt="no 8" src="https://github.com/user-attachments/assets/6906eca5-c03e-4f79-a3d7-5a4bcd8f7750" />

9) Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya :
    <img width="800" height="57" alt="no 9" src="https://github.com/user-attachments/assets/fc5a672e-7cce-4661-8609-a246a20e6332" />
Nilai awal file = 666
umask = 027
Karena umask merupakan masker izin, izin yang diblokir adalah :
- 0 : tidak memblokir izin user
- 2 : memblokir write pada group
- 7 : memblokir read, write, execute pada others

Maka :
- User : 6 = rw-
- Group : 6 - 2 = 4 = r--
- Others : 6 - 7 = 0 = ---
  Sehingga nilai defaultnya adalah 640 (rw-r-----) 

10) Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah :
    <img width="800" height="177" alt="no 10" src="https://github.com/user-attachments/assets/5659670d-cc7b-4ca2-a5d0-822ae9b1bda0" />
