# -LT-9_Console

Console adalah objek global yang tersedia dalam JavaScript yang dapat digunakan untuk menampilkan informasi di console browser atau debugger. Console sering digunakan untuk mencetak pesan log, mengecek nilai variabel, atau mengevaluasi ekspresi dalam kode JavaScript Anda.

Untuk menggunakan console, Anda dapat menggunakan perintah console.log() untuk mencetak pesan log ke console. Contoh:

    console.log("Ini adalah pesan log");

Anda juga dapat mencetak nilai variabel ke console dengan menggunakan console.log(), seperti ini:

    let x = 10;
    console.log(x);

Selain console.log(), ada juga beberapa perintah lain yang tersedia dalam console, seperti console.error() untuk mencetak pesan error ke console, console.warn() untuk mencetak pesan peringatan ke console, dan console.info() untuk mencetak pesan informasi ke console.

Selain menggunakan perintah-perintah seperti console.log() dan console.error(), Anda juga dapat menggunakan perintah-perintah lain yang tersedia dalam console untuk mengeksplorasi dan men-debug kode JavaScript Anda. Beberapa perintah yang sering digunakan adalah:

* console.dir(): Mencetak objek DOM yang dipilih dengan struktur yang dapat dikembangbiak.
* console.count(): Menghitung jumlah kali sebuah label telah dicetak ke console.
* console.time(): Memulai timer dengan label yang diberikan.
* console.timeEnd(): Menampilkan waktu yang telah berlalu dari timer yang diberikan label dengan console.time().
* console.table(): Mencetak tabel yang menyajikan data dalam bentuk array atau objek.

Contoh:

    let users = [
      { name: "John", age: 30 },
      { name: "Jane", age: 25 }
    ];

    console.table(users);

Output di console akan menampilkan tabel dengan kolom "name" dan "age" dan baris yang mewakili setiap objek dalam array. Selain menggunakan perintah-perintah console untuk mengeksplorasi dan men-debug kode JavaScript, Anda juga dapat menggunakan fitur-fitur yang tersedia di console untuk membantu proses debugging. Beberapa fitur yang sering digunakan adalah:

* Breakpoints: Menandai titik di kode JavaScript dimana Anda ingin menghentikan eksekusi kode dan memeriksa nilai-nilai yang ada.
* Step over: Melompati eksekusi kode yang ada di dalam fungsi saat debug.
* Step into: Masuk ke dalam fungsi saat debug dan melanjutkan eksekusi kode satu baris per satu baris.
* Step out: Keluar dari fungsi saat debug dan melanjutkan eksekusi kode setelah fungsi selesai dieksekusi.

