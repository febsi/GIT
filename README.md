GIT

Git adalah sistem kontrol versi terdistribusi yang memungkinkan Anda untuk melacak perubahan dalam kode sumber selama pengembangan perangkat lunak. Ini memungkinkan beberapa pengembang untuk bekerja pada proyek yang sama tanpa mengganggu satu sama lain. 

Pre-Requisites



### Di Windows

1. Unduh installer Git dari [situs resmi Git](https://git-scm.com/download/win).
2. Jalankan installer dan ikuti petunjuk di layar.
3. Setelah instalasi selesai, buka Command Prompt atau Git Bash untuk mulai menggunakan Git.

### Di Linux

1. Buka terminal.
2. Jalankan perintah berikut sesuai dengan distribusi Linux Anda:

   - Untuk Ubuntu/Debian:

     ```bash
     sudo apt-get update
     sudo apt-get install git
     ```

   - Untuk Fedora:

     ```bash
     sudo dnf install git
     ```

   - Untuk Arch Linux:

     ```bash
     sudo pacman -S git
     ```

3. Setelah instalasi selesai, Anda dapat mulai menggunakan Git melalui terminal.

## Konfigurasi Awal

Setelah menginstal Git, Anda perlu mengkonfigurasi informasi pengguna Anda. Jalankan perintah berikut di terminal atau Command Prompt:

```bash
git config --global user.name "Nama Anda"
git config --global user.email "email@anda.com"
Informasi tentang lisensi proyek ini.