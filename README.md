# terminal-snap-version

Berkas penunjuk versi untuk terminal-snap.

Aplikasinya membaca `versi.json` saat dijalankan, lalu membandingkannya dengan
versi yang sedang berjalan untuk tahu apakah ada yang lebih baru.

Repo ini sengaja publik dan isinya sengaja hanya nomor versi. Nomor versi
bukan informasi rahasia, sehingga aplikasinya tidak perlu membawa kredensial
apa pun untuk membacanya — dan tidak ada kredensial yang bisa diambil dari
berkas aplikasi yang dibagikan.

Kode sumber dan berkas aplikasinya tidak ada di sini.

## Cara merilis

Naikkan nomor di `versi.json`, commit, push. Itu saja yang dibaca aplikasi.
