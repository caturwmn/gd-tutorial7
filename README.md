# Latihan Mandiri Tutorial 7
### Catur Wira Mukti Nugroho - 2206083483
#### Implementasi fitur latihan mandiri:
1. Fitur Sprint:
   
   Implementasi sprint dilakukan dengan menambahkan input mapping sprint dengan menggunakan tombol shift sebagai salah satu mappingnya. Untuk perubahan kecepatan dilakukan dengan menambahkan conditional if tambahan untuk menentukan fungsi lerp apa yang digunakan untuk kecepatan pada Player.gd dimana jika pemain menekan tombol sprint, maka kecepatan akan menggunakan run_speed daripada speed.

2. Fitur Crouch:
   
   Fitur crouch mengikuti implementasi fitur sprint dimana ditambahkan statement elif setelah statement if untuk sprint dan input mapping baru untuk crouch dengan ctrl sebagai salah satu key yang di map ke crouch. Selain itu, ditambahkan juga perubahan properti scale pada node CharacterBody3D ketika tombol crouch ditekan yang akan melakukan scaling ukuran pada arah y (atas) menjadi 0.8 sehingga pemain tampak tunduk. Ditambahkan juga deklarasi scale default di baris pertama fungsi _physics_process(delta) agar pemain kembali semula apabila crouch tidak di tekan.

### Referensi
[ChatGPT](https://chatgpt.com/): Untuk mencari properti yang mengatur scale playerw

[Dokumentasi Godot Engine](https://docs.godotengine.org/en/stable/tutorials): Untuk tutorial tambahan
