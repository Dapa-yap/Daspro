**#Dasar Pemograman**
### Daffa Dwi Nugroho
### TI 1C/10

**####Pseudocode soal 1**

Mulai
    Tampilkan "Apakah membawa kartu mahasiswa? (ya/tidak)"
    Input kartu

    Tampilkan "Apakah sudah registrasi online? (ya/tidak)"
    Input registrasi

    Jika (kartu == "ya") ATAU (registrasi == "ya") maka
        Tampilkan "Boleh masuk ke perpustakaan"
    Jika tidak
        Tampilkan "Ditolak masuk"
    Akhir Jika
Selesai
**####Pseudocode soal 2**

Mulai
    Tampilkan "Masukkan jenis pengguna (dosen/mahasiswa/lainnya): "
    Input jenis_pengguna

    Jika jenis_pengguna == "dosen" maka
        Tampilkan "Akses WiFi diberikan (dosen)"
    Jika tidak
        Jika jenis_pengguna == "mahasiswa" maka
            Tampilkan "Masukkan jumlah SKS yang diambil: "
            Input sks
            Jika sks >= 12 maka
                Tampilkan "Akses WiFi diberikan (mahasiswa aktif)"
            Jika tidak
                Tampilkan "Akses ditolak, SKS kurang dari 12"
            Akhir Jika
        Jika tidak
            Tampilkan "Akses ditolak"
        Akhir Jika
    Akhir Jika
Selesai
![Flowchart 1](https://github.com/Dapa-yap/Daspro/blob/main/Tugas_Daspro/img/FlowChart1.png?raw=true)

![Flowchart 2](https://github.com/Dapa-yap/Daspro/blob/main/Tugas_Daspro/img/Flowchart2.png?raw=true)



