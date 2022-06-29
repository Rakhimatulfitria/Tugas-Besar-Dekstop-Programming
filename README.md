# Tugas-Besar-Dekstop-Programming
Aplikasi Deteksi Wajah

Disini terdapat 2 menu untuk mendeteksi wajah yaitu : Pertama dengan cara memilih photo di perangkat dan kedua menggunakan kamera.

# Aplikasi Deteksi Wajah dengan Memilih Photo
File aplikasi nya terdapat di dalam folder "dist" dengan nama "Deteksi_Wajah2.jar". Aplikasi ini merupakan aplikasi deteksi wajah dengan cara memilih photo di perangkat. Jadi ketika mengklik button "Choose Photo", aplikasi akan mengarahkan anda untuk memilih salah satu photo di perangkat. Ketika photo sudah terpilih maka wajah dalam photo tersebut akan dihitung jumlahnya. Wajah yang akan terdeteksi yaitu wajah yang dominan menghadap kedepan.

Jika photo tidak dapat tampil di frame yang disediakan maka usahakan untuk libraries opencv yang dalam format .dll sudah ada di dalam folder "C:\Program Files\Java" lalu paste file tersebut di dalam folder "bin" nya dari folder "java" tersebut. Untuk lebih detail mengenai penggunaan aplikasi dapat dilihat didalam aplikasi pada button "Info Aplikasi". 

# Aplikasi Deteksi Wajah Menggunakan Kamera
File aplikasi nya terdapat di dalam folder "dist" dengan nama "Deteksiwajah.jar". Aplikasi ini merupakan aplikasi deteksi wajah dengan menggunakan kamera. Untuk menyalakan kamera laptop, terlebih dahulu mengklik button "Start Counting", lalu kamera laptop akan menyala sehingga wajah terlihat didalam frame perhitungan sehingga aplikasi akan menghitung jumlah wajah yang terdapat didalam frame. Jika wajah terdeteksi maka akan tertera kalimat "Wajah Terdeteksi" dan usahakan untuk menghadap kedepan atau kamera agar wajah terdeteksi.

Jika wajah tidak dapat tampil di frame ketika kamera menyala maka usahakan untuk libraries opencv yang dalam format .dll sudah ada di dalam folder "C:\Program Files\Java" lalu paste file tersebut di dalam folder "bin" nya dari folder "java" tersebut. Untuk lebih detail mengenai penggunaan aplikasi dapat dilihat didalam aplikasi pada button "Info Aplikasi".

# Soure Code
Untuk saoure code kedua aplikasi terdapat didalam folder "src" pada setiap foldernya. Jika pada aplikasi yang memilih photo nama filenya yaitu "Choosephoto.java" sedangkan untuk yang kamera nama filenya yaitu "cam.java".

# Libraries opencv
Jika belum memiliki libraries opencv maka dapat mendownload zip tersebut yaitu dengan cara klik "extract to" yang nantinya file dengan nama "opencv_java455.dll" dapat ditambahkan ke dalam folder java pada program files. Selain itu, terdapat juga opencv dalam format jar yang dapat didownload jika membutuhkan.
