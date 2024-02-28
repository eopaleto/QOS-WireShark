**TUTORIAL CARA QOS WIRESHARK WINDOWS**

Langkah-Langkah:
1. Buka Aplikasi WireShark di Windows anda.Dan pilih port intenet paling atas.
   ![1](https://github.com/eopaleto/QOS-WireShark/assets/126212773/e1d157e9-0422-44c6-a843-ee0076949fbd)
2. Masukan IP ADDRESS yang ingin dipantau. kemudian klik `enter`
   ![2](https://github.com/eopaleto/QOS-WireShark/assets/126212773/ad259fa0-9bc6-4ea0-8777-e9c0702d6663)
3. Tunggu hingga 5-10 tergantung berapa lama ingin kamu pantau.Kemudian buka `Stastistik` > `Capture File Properties`.
   ![3](https://github.com/eopaleto/QOS-WireShark/assets/126212773/ea4fafbc-bc3c-49d5-9c4a-4252fb1095fe)
4. Perhatikan pada 5 nilai berikut :
   ![4](https://github.com/eopaleto/QOS-WireShark/assets/126212773/d7f44f23-afca-4b99-918b-eedcfd02a6ad)
5. Lakukan Perhitungan Bytes (Throughtput):

   ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/41343bdf-f366-4547-999a-6121d8e5c69e)
7. Lakukan Perhitungan Packet Loss :

   ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/1114b6e9-1fe9-42f1-8bb3-fee17d4914ff)
8. Lakukan perhitungan Delay dan Jitter dengan mengunduh Data Excel CSV. dengan mengklik `File` > `Export Packet Dissections` > `As CSV..`
   ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/aa6cd11d-a837-44a9-86a9-3fef6ad81a83)
9. Berikut ini hasil Data CSV nya :
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/47f9aea8-cb14-4d3c-ac86-c53f901f96a5)
10. Rapihkan Data dan sisakan kolom *No* dan *Time*.
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/39148de2-156c-4af6-ac50-93b539ae39f0)
11. Pilih `Next`
    ![6](https://github.com/eopaleto/QOS-WireShark/assets/126212773/f0848225-9b2f-4ed0-8a39-01b0bc5550ab)
12. Ceklis `Comma` agar terbentuk tabel, Kemudian `Next`
    ![7](https://github.com/eopaleto/QOS-WireShark/assets/126212773/0618643f-9158-431d-8d83-fdcc7b932571)
13. Blok kolom C , D , E , F DAN G dan klik tombol `delete` di keyboard
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/a1f3a11f-c0c0-4790-9c73-3ee623b7f624)
14. Berikut hasilnya:
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/7376dc8e-368f-4e15-8fbe-a4eec4845cb1)
15. Hasil Perhitungan Delay dan Jitter
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/bbcb096a-4bda-431b-ae65-1a16500fb0b8)
16. Rumus Perhitungan Delay :
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/f99d6baf-e171-426c-8202-cf2175fcc1b6)
17. Perhitungan Delay dan Rata-rata Delay
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/3800b600-fcb5-4ebc-9060-3d5d00948c53)
18. Rumus Perhitungan Jitter :
    ![image](https://github.com/eopaleto/QOS-WireShark/assets/126212773/74c41df8-9bec-4f15-ad59-9b3bcba1b317)
19. Perhitungan Jitter
    ![Uploading image.png…]()


    
