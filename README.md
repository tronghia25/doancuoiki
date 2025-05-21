# Đồ án cuối kỳ: Ứng dụng AI vào máy tính tiền
## Thư viện sử dụng
Ứng dụng máy tính dùng Python để xử lý ảnh và gửi dữ liệu đến Arduino. Các thư viện chính gồm:
- **pyserial**: Giao tiếp Serial với Arduino.
- **opencv-python (cv2)**: Mở webcam, đọc và hiển thị ảnh.
- **tensorflow**: Chạy mô hình AI để nhận diện món ăn.
- **numpy**: Xử lý mảng dữ liệu ảnh.
- **time**: Thêm độ trễ để đồng bộ hệ thống.
## Mô tả đề tài
-Tích hợp Arduino vào máy tính tiền, nhận diện tiền Việt Nam thông qua camera và nhận diện bằng model CNN, kết hợp Arduino điều khiển các thành phần vật lý như servo, cảm biến siêu âm, hồng ngoại và LCD để tạo ra một máy tính tiền tự động.
## Thành phần chính
- 3 servo MG90S
- cảm biến hồng ngoại
- cảm biến siêu âm HC-SR04
- màn hình LCD 16x2 tích hợp I2C
- Arduino UNO
- Webcam
- Đèn LED chiếu sáng
- Mô hình AI nhận diện tiền
## Mô hình AI
- Kiểu: CNN / MobileNetV2
- Framework: TensorFlow 
- Định dạng: .h5
- Tải mô hình tại: [Google Drive](https://drive.google.com/file/d/1Xu-GQAL4C40Y0cCA1pOngeNBJBMNdicv/view?usp=sharing)
## Video
[Demo trên YouTube](https://youtube.com/shorts/pvQ0PyGk9uU?si=j1ldiX44rAExibp5)
## Thư mục
- /firmware/: Code Arduino
- /ai_model/: Mô hình AI
- /hardware/: Sơ đồ mạch và kết nối
- /report/: Báo cáo & Poster
- /communication/: Giao tiếp với Arduino
## Sơ đồ mạch điện
-[Google Drive](https://drive.google.com/file/d/1SmoSDjhZMcJzUHJl8t_o4Vg0lUr6SPvU/view?usp=sharing)
## Thư viện sử dụng
Ứng dụng máy tính dùng Python để xử lý ảnh và gửi dữ liệu đến Arduino. Các thư viện chính gồm:
- **pyserial**: Giao tiếp Serial với Arduino.
- **opencv-python (cv2)**: Mở webcam, đọc và hiển thị ảnh.
- **tensorflow**: Chạy mô hình AI để nhận diện món ăn.
- **numpy**: Xử lý mảng dữ liệu ảnh.
- **time**: Thêm độ trễ để đồng bộ hệ thống.
## Cài đặt môi trường
Chạy lệnh sau để cài đặt các thư viện cần thiết:

```bash
pip install pyserial opencv-python tensorflow numpy
