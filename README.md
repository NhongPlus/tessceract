Bước 1: Chuẩn bị
  Đảm bảo MongoDB đang chạy: Mở terminal, gõ mongod --dbpath C:\DataMonThu3 (thay đường dẫn nếu khác) và giữ terminal này mở.
  Kích hoạt môi trường ảo (venv): Vào thư mục project, chạy venv\Scripts\activate (Windows) hoặc source venv/bin/activate (Linux/Mac). Bạn sẽ thấy (venv) trước dòng lệnh.

Bước 2: Chạy Flask
  Đặt biến môi trường: set FLASK_APP=app.py (Windows) hoặc export FLASK_APP=app.py (Linux/Mac).
  Chạy ứng dụng: flask run.
  Bạn sẽ thấy thông báo: * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit).

Bước 3: Test
  Mở trình duyệt, vào http://localhost:5000.
  Chọn "Tiền điện" hoặc "Tiền nước" từ dropdown, upload ảnh hóa đơn, rồi kiểm tra danh sách file.
