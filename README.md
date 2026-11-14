# terminal-snap-version

Berkas penunjuk versi untuk terminal-snap dan device-console.

| Berkas | Aplikasi |
| --- | --- |
| `versi.json` | terminal-snap |
| `device-console.json` | device-console |

Aplikasinya membaca berkasnya masing-masing saat dijalankan, lalu
membandingkannya dengan versi yang sedang berjalan untuk tahu apakah ada yang
lebih baru.

Repo ini sengaja publik dan isinya sengaja hanya nomor versi. Nomor versi
bukan informasi rahasia, sehingga aplikasinya tidak perlu membawa kredensial
apa pun untuk membacanya — dan tidak ada kredensial yang bisa diambil dari
berkas aplikasi yang dibagikan.

Kode sumber dan berkas aplikasinya tidak ada di sini.

## Cara merilis

Naikkan nomor di berkas milik aplikasinya, commit, push. Itu saja yang dibaca
aplikasi.
