Nama : Nabila Asyura Chandra Putri <br>
NIM : 09030582327098 <br>
Kelas : TK4C <br>
Mata Kuliah : Praktikum Jaringan Komputer <br>

# Konfigurasi server dan client menggunakan linux
## Langkah 1: Install SSH di server ubuntu(nabila)
### 1. Buka terminal
### 2. Update package list
```
sudo apt update
```
![Image](https://github.com/user-attachments/assets/e9fdf0ea-6d45-4bf1-8789-0cf8a6881352)
### 3. Install openssh server
```
sudo apt install openssh-server
```
![Image](https://github.com/user-attachments/assets/e7b4b552-c4a5-4b11-b202-f4369eb7fffc)
### 4. Verifikasi SSH service
```
sudo systemctl status ssh
```
![Image](https://github.com/user-attachments/assets/80a0550a-ce9d-4e42-8617-4b80bfffc65f)

## Langkah 2: Install SSH di client(vina)
### 1. Buka terminal
### 2. Update package list
### 3. Install openssh client

## Langkah 3: Menghubungkan client ke server
### 1. Dapatkan alamat IP server(server)
### 2. Menghubungkan ke server menggunakan IP server(client)
### 3. Masukkan password
Jika menggunakan password authentication, masukkan password user server.
### 4. 

## Langkah 3: Pengujian
Setelah server dan client terhubung dengan SSH, Mari kita coba membuat proyek sederhana untuk menguji koneksi tersebut.
### 1. Buat script
```
nano test_ssh.sh
```
### 2. Isi script
Isilah file test_ssh.sh di text editor nano pada server:
```
echo [isi]
```
### 3. Beri hak akses eksekusi
Beri izin eksekusi pada script:
```
chmod +x test_ssh.sh
```
### 4. Jalankan script di client
Jalankan script untuk memastikan server dan client sudah terhubung:
