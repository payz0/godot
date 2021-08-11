# godot noted
RUntutan kerja godot
1. Menentukan sifat objec, lalu pada sub di tentukan collision dan Mesh instance. sifat ini bisa berupa static, rigid, ataupun kinematic
2. Untuk kinematic bisa bikin scene baru dengan penentuan sama pada point pertama, lalu di link atau import dalam scene game agar bisa tampil. sifat kinematic untuk pergerakkan bebas, baik untuk player ataupun enemy
3. Untuk texture atau material bisa di import dari blender yg berextensi .gltf, hasil dari import akan berupa seperti scene baru, di mana kita rubah sisi import yg sebelumnya berupa spatial menjadi kinematic atau sesuai kebutuhan lalu pada scene root di rubah typenya jadi kinematic atau sesuai kebutuhan. setelah itu di simpan menjadi asset baru, yang nantinya bisa di pakai untuk mesh instance object lain. atau bisa langsung di link atau masuk dalam scene game. begitu juga dengan material yg sudah di simpan bisa di pakai untuk texture object lain.
4. Untuk script bisa pilih object lalu pilih attach new script. dan script selanjutnya bisa lihat di documentasi godot
5. Untuk tampil butuh camera dalam scene, ada yang standar ada camera yg dinamis smooth, msalnya interpolateCamera follow objectnya seperti real,
6. Untuk posisi kamera di interpolatecamera butuh spatial dalam sub object target kamera agar jatunya posisi kamera masuk dalam spatial tidak dalam mesh instance.
7. Lighting bisa di tambah agar lebih real dan object memiliki shadow
8. untuk dunia game bisa di atur pada pengaturan camera environtment, dan bisa di simpan untuk di jadikan environtment default
9. Pada mesh instance bisa di tambah texture pada material plih newSpatialMeterial lalu custom pada normal map yg sudah di enable, lalu untuk scale dan lebih real pada UV1 centang trapnalar, jika perlu tambah lagi texture pada Roughness
