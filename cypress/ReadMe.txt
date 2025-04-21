# Cara Penggunaan Project Cypress

1. **Clone Repository**
    Clone repository ini ke komputer Anda menggunakan perintah berikut:
    ```
    git clone <repository-url>
    ```

2. **Masuk ke Direktori Project**
    Pindah ke direktori project:
    ```
    cd cypress_mentoring/cypress
    ```

3. **Install Dependencies**
    Pastikan Anda sudah menginstall Node.js. Kemudian jalankan perintah berikut untuk menginstall dependencies:
    ```
    npm install
    ```

4. **Buka Cypress**
    Untuk membuka Cypress GUI Test Runner, jalankan perintah:
    ```
    npx cypress open
    ```

5. **Menjalankan Test**
    Pilih salah satu test yang ingin dijalankan di Cypress Test Runner, atau jalankan semua test secara headless dengan perintah:
    ```
    npx cypress run => menjalankan semua skenario yang ada di cypress/e2e
    npx cypress run --spec "cypress/e2e/<file skenario>.cy.js" => menjalankan skenario  1 file
    ```

6. **Melihat Hasil Test**
    Setelah test selesai dijalankan, Anda dapat melihat hasilnya di terminal atau membuka laporan hasil test jika tersedia.

7. **Konfigurasi Tambahan**
    Jika diperlukan, sesuaikan konfigurasi di file `cypress.config.js` sesuai kebutuhan project Anda.

Selamat mencoba!