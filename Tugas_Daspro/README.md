# Dasar Pemograman
### Daffa Dwi Nugroho
### TI 1C/10

**Pseudocode soal 1**

    Mulai
    Tampilkan_"Apakah membawa kartu mahasiswa?_(ya/tidak)_"
    Input kartu

    Tampilkan_"Apakah sudah registrasi online?_(ya/tidak)_"
    Input registrasi

    Jika (kartu == "ya") ATAU (registrasi == "ya") maka
        Tampilkan "Boleh masuk ke perpustakaan"
    Jika tidak
        Tampilkan "Ditolak masuk"
    Akhir Jika
    Selesai
**Pseudocode soal 2**

    Mulai
    Tampilkan_"Masukkan jenis pengguna_(dosen/mahasiswa/lainnya): "
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

**Flowchart soal 1**

![Flowchart 1](https://github.com/Dapa-yap/Daspro/blob/main/Tugas_Daspro/img/FlowChart1.png?raw=true)

**Flowchart soal 2**

![Flowchart 2](https://github.com/Dapa-yap/Daspro/blob/main/Tugas_Daspro/img/FLowchart2.png?raw=true)



