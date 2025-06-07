# Daftar Perintah Bot Profesional

Selamat datang di dokumentasi resmi untuk Bot Profesional kami. Semua perintah di bawah ini menggunakan format Slash Command (`/`).

Argumen yang ditandai dengan `<kurung_lancip>` bersifat **wajib**, sedangkan yang ditandai dengan `[kurung_siku]` bersifat **opsional**.

---

## 🛡️ Perintah Moderasi

Perintah untuk membantu admin dan moderator menjaga ketertiban server.

| Perintah | Deskripsi | Izin yang Dibutuhkan (User) |
| :--- | :--- | :--- |
| `/ban <user> [alasan]` | Mem-ban seorang pengguna secara permanen dari server. | `Ban Members` |
| `/kick <user> [alasan]` | Mengeluarkan seorang pengguna dari server. | `Kick Members` |
| `/mute <user> <durasi> [alasan]` | Mencegah pengguna mengirim pesan untuk durasi tertentu (misal: `10m`, `1h`, `7d`). | `Moderate Members` |
| `/unmute <user>` | Menghapus status mute dari pengguna. | `Moderate Members` |
| `/warn <user> <alasan>` | Memberikan peringatan resmi kepada pengguna. Peringatan akan disimpan. | `Moderate Members` |
| `/warnings [user]` | Melihat daftar peringatan yang dimiliki oleh seorang pengguna. | `Moderate Members` |
| `/clear <jumlah>` | Menghapus sejumlah pesan terakhir di channel (antara 1-100). | `Manage Messages` |

---

## 👋 Perintah Selamat Datang & Perpisahan

Mengatur pesan otomatis saat ada anggota yang bergabung atau meninggalkan server.

| Perintah | Deskripsi | Izin yang Dibutuhkan (User) |
| :--- | :--- | :--- |
| `/set welcome channel <channel>` | Mengatur channel tempat pesan selamat datang akan dikirim. | `Manage Server` |
| `/set welcome message <pesan>` | Mengatur template pesan selamat datang. Gunakan `{user_mention}` atau `{user_name}`. | `Manage Server` |
| `/set goodbye channel <channel>` | Mengatur channel tempat pesan perpisahan akan dikirim. | `Manage Server` |
| `/set goodbye message <pesan>` | Mengatur template pesan perpisahan. Gunakan `{user_name}`. | `Manage Server` |
| `/toggle welcome <on/off>` | Mengaktifkan atau menonaktifkan fitur selamat datang. | `Manage Server` |
| `/toggle goodbye <on/off>` | Mengaktifkan atau menonaktifkan fitur perpisahan. | `Manage Server` |
| `/test welcome` | Mengirim pesan selamat datang percobaan di channel yang telah diatur. | `Manage Server` |

---

## ✨ Perintah Reaction Roles

Membuat sistem di mana pengguna bisa mendapatkan role dengan mengklik reaksi emoji.

| Perintah | Deskripsi | Izin yang Dibutuhkan (User) |
| :--- | :--- | :--- |
| `/createreactionrole <channel> <message_id> <emoji> <role>` | Menambahkan satu konfigurasi reaction role pada sebuah pesan. | `Manage Roles` |
| `/removeractionrole <message_id> <emoji>` | Menghapus satu konfigurasi reaction role dari sebuah pesan. | `Manage Roles` |
| `/listreactionroles` | Menampilkan semua konfigurasi reaction role yang aktif di server. | `Manage Roles` |

---

## 🛠️ Perintah Utilitas

Perintah umum yang berguna untuk semua pengguna.

| Perintah | Deskripsi | Izin yang Dibutuhkan (User) |
| :--- | :--- | :--- |
| `/ping` | Mengetes latensi dan waktu respons bot. | Tidak ada |
| `/serverinfo` | Menampilkan informasi detail tentang server saat ini. | Tidak ada |
| `/userinfo [user]` | Menampilkan informasi detail tentang diri sendiri atau pengguna lain. | Tidak ada |
| `/avatar [user]` | Menampilkan gambar avatar pengguna dalam ukuran besar. | Tidak ada |
| `/invite` | Mengirimkan link untuk mengundang bot ke server lain. | T|
| `/support` | Menampilkan informasi kontak support. | Tidak ada |
