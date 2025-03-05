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

## Langkah 2: Install SSH di client
