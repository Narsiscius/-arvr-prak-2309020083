# Praktikum AR/VR - Pertemuan 1
- Nama : Arya Adji Pratama
- NIM : 2309020083
- Link demo : https://github.com/Narsiscius/-arvr-prak-2309020083.git
- github pages : https://narsiscius.github.io/-arvr-prak-2309020083/
- ss scene : https://github.com/Narsiscius/-arvr-prak-2309020083/blob/main/Screenshot%20Scene.png

1. Mengapa z negatif?
Di A-Frame dan three.js, sumbu z positif mengarah ke pengguna, sedangkan kamera secara default menghadap ke arah z negatif. Jadi objek harus diletakkan di z negatif supaya berada di depan kamera dan terlihat.

2. Mengapa WebXR hanya aktif di HTTPS atau localhost?
WebXR mengakses data sensitif seperti gerakan kepala dan sensor perangkat, sehingga browser mewajibkan secure context agar data tidak bisa disadap atau dipalsukan. Localhost dikecualikan karena lalu lintasnya tidak keluar dari komputer sendiri, jadi aman untuk pengujian.

3. Perbedaan WebXR Device API, three.js, dan A-Frame
WebXR Device API menghubungkan browser dengan perangkat VR/AR dan data pelacakannya, tetapi tidak menggambar apa pun. three.js bertugas menggambar objek 3D, sedangkan A-Frame berada di atas three.js dan membuat scene cukup dengan tag HTML.

Project ini berisi scene WebXR pertama menggunakan A-Frame 1.7.1.