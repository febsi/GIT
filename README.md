### GIT

Git adalah sistem kontrol versi terdistribusi yang memungkinkan Anda untuk melacak perubahan dalam kode sumber selama pengembangan perangkat lunak. Ini memungkinkan beberapa pengembang untuk bekerja pada proyek yang sama tanpa mengganggu satu sama lain. 

### Pre-Requisites
1. Dijalankan di github 22.04.5.
2. Instal Git version (2.34.1).
3. memiliki akun github.

### Instalasi GIT

1. untuk isntalasi git pada ubuntu 22.04.5 bisa menggunakan perintah.
    ```bash
     sudo apt-get Update
     sudo apt-get install git
     ```

2. Setalah melakukan intsall, coba cek versi git dengan perintah berikut.
    ```bash
     git --version
     ```
    ![Screenshot Terminal](Gambar/gambar1.png)

3. kemudia kita tambah identitas username dan email yang akan dikenali oleh git.

    username 
    ```bash
     git config --global user.name "nama anda" 
     ```
     email
     ```bash
     git config --global user.email "email anda" 
     ```

4. untuk melihat penambahan identitas berhasil dapat kita lihat dengan perintah.
    
    ```bash
     git config --list --show-origin 
     ```
    ![Screenshot Terminal2](Gambar/gambar2.png)

### Perintah dasar Git

berikut adalah beberapa printah dasar Git. 

   - inisialisasi Repositori baru:

     ```bash
     git init 
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