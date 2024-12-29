# docker-laravel

## Langkah-langkah Menjalankan Aplikasi

### 1. Clone Repositori

Langkah pertama adalah meng-clone repositori ke mesin lokal Anda:

git clone https://github.com/fian39870/docker-laravel.git
cd docker-laravel

### 2. Konfigurasi Variabel Lingkungan
cp .env.example .env

### 3. Pull Docker Images
docker pull ahmadsofian/laravel-app:v1
docker pull ahmadsofian/laravel-nginx:v1
docker pull mysql:8.0

### 4. Membangun dan Menjalankan Kontainer
docker-compose up

