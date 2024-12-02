# Tên đề tài: Shop bán sách online (MERN-stack)
## Cách chạy dự án này:

### Cho Frontend 
Thực hiện theo các bước dưới đây để chạy dự án: 
- Đầu tiên sao chép hoặc giải nén thư mục.
*Chuyển đến thư mục frontend bằng cách sử dụng lệnh sau ``` cd frontend ```.
* * Tạo file **.env.local** trong thư mục backend root có cùng cấp độ với **package.json** và giữ các biến môi trường sau ở đó:
```
>>> Tăng cường ứng dụng firebase và định cấu hình môi trường

VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_Auth_Domain="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDERID= "205632822247"
VITE_APPID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"
```
+ Sau đó run `` npm install `` commend để cài đặt node dependencies.
-Cuối cùng, để chạy dự án, hãy sử dụng ``npm run dev`` command.


### Cho Backend
Thực hiện theo các bước dưới đây để chạy dự án:
- Đầu tiên sao chép hoặc giải nén thư mục.
* Chuyển đến thư mục backend bằng cách sử dụng lệnh sau ``` cd backend```.
+ Sau đó run `` npm install `` commend để cài đặt node dependencies.
* Tạo file **.env** trong thư mục backend root có cùng cấp độ với **package.json** và giữ các biến môi trường sau ở đó:
  
DB_URL = "mongodb+srv://helpyourassistant:pqam0Mwv3Vwv8Off@cluster0.qc3bq.mongodb.net/book-store?retryWrites=true&w=majority&appName=Cluster0"

JWT_SECRET_KEY = 'bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'


- Cuối cùng, để chạy dự án, hãy sử dụng ``npm run start:dev`` command.

  **Kết quả đạt được**
- Thiết lập và ứng dụng MERN-stack ( REACT JS, NODE JS, MONGO DB) xây dựng được một website bán sách với các chức năng đơn giản để tạo nền móng phát triển các dự án sau này.
