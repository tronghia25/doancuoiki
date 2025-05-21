# doancuoiki
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
## Video
[Demo trên YouTube](https://youtube.com/shorts/pvQ0PyGk9uU?si=j1ldiX44rAExibp5)
## Thư mục
- /firmware/: Code Arduino
- /ai_model/: Mô hình AI
- /hardware/: Sơ đồ mạch và kết nối
- /report/: Báo cáo & Poster
- /communication/: Giao tiếp với Arduino
