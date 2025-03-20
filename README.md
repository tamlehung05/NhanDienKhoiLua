# 🔥 AI NHẬN DIỆN KHÓI VÀ LỬA  

[![DNU Logo](![image](https://github.com/user-attachments/assets/bc63eb3d-7808-4299-a129-eceff639c430)
)
)]([[https://dainam.edu.vn](https://github.com/chinhliki/Nhan-dien-khuon-mat/blob/main/Screenshot%202025-03-17%20205953.png?raw=true)](https://raw.githubusercontent.com/chinhliki/Nhan-dien-khuon-mat/refs/heads/main/Screenshot%202025-03-17%20205953.png))



## 📌 Giới thiệu  
Dự án này sử dụng công nghệ AI để nhận diện khói và lửa trong hình ảnh hoặc video theo thời gian thực. Bằng cách ứng dụng Deep Learning và xử lý ảnh, hệ thống có thể phát hiện nguy cơ cháy nổ một cách nhanh chóng và chính xác, giúp nâng cao khả năng cảnh báo cháy tự động.  

---

## 🚀 Tính năng  
✅ **Phát hiện khói và lửa** trong hình ảnh và video.  
✅ **Cảnh báo sớm** khi có dấu hiệu cháy nổ.  
✅ **Chạy trên GPU** để xử lý nhanh hơn.  
✅ **Tích hợp dễ dàng** vào hệ thống giám sát an ninh.  
✅ **Hỗ trợ nhiều định dạng dữ liệu**, bao gồm camera trực tiếp và video lưu trữ.  
✅ **Gửi cảnh báo qua email/SMS hoặc điều khiển thiết bị IoT.**  

---

## 🛠️ Cài đặt  
### Yêu cầu hệ thống  
- Python 3.8+  
- Hệ điều hành: Windows/Linux/macOS  
- GPU (khuyến nghị) để tăng tốc xử lý  

---

## 🎯 Mô hình  
Mô hình nhận diện khói và lửa được xây dựng dựa trên:  
- **CNN (Convolutional Neural Networks)** để phát hiện đặc điểm hình ảnh.  
- **YOLOv8 / Faster R-CNN** để phát hiện vật thể trong thời gian thực.  
- **Dataset**: Sử dụng bộ dữ liệu huấn luyện gồm hình ảnh khói, lửa và cảnh thông thường để giảm false positive.  

---

## 📦 Cài đặt thư viện  
Trước khi chạy dự án, cần cài đặt các thư viện cần thiết:  
```bash
pip install -r requirements.txt
