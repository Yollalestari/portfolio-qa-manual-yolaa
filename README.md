# Portofolio QA Manual – Yola Lestari

## 👩‍💻 Tentang Saya
Saya Yola Lestari, QA Manual Tester yang menguasai tools seperti Postman, Trello, dan Google Sheets.

## ✅ Test Scenario (REST API)
| ID   | Endpoint     | Test Case              | Test Data                          | Expected Result                  |
|------|--------------|------------------------|-------------------------------------|----------------------------------|
| TC01 | POST /login  | Login berhasil         | { "user": "yola", "pass": "123" }   | 200 OK + Token                   |
| TC02 | POST /login  | Login gagal (no pass)  | { "user": "yola" }                  | 400 Bad Request + error message  |
| TC03 | GET /items   | Lihat semua item       | Token valid                         | 200 OK + JSON list               |

## 🧪 Test Case Manual
**TC-LOGIN-01 – Login Sukses**  
1. Buka halaman login  
2. Masukkan username & password valid  
3. Klik tombol "Login"  
**Expected**: Masuk ke dashboard

## 🐞 Contoh Bug Report
ID: BR-001  
Title: Tombol login tidak merespon  
Steps:
1. Buka halaman login  
2. Isi username & password  
3. Klik Login  
Actual: Tidak ada reaksi  
Expected: Masuk dashboard  
Severity: High  
Status: Open
