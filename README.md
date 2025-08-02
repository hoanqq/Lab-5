# Nhập Môn Xử Lý Ảnh Số - Lab 5  
## **Phát Hiện Biên Cạnh Bằng Các Toán Tử Gradient (Sobel, Prewitt, Canny)**  
**Sinh viên thực hiện:** Nguyễn Khắc Huy Hoàng  
**MSSV:** 2374802010151  
**Môn học:** Nhập môn Xử lý ảnh số  
**Giảng viên:** Đỗ Hữu Quân  

---

## Giới thiệu

Lab 5 hướng đến việc **phát hiện biên cạnh trong ảnh số** sử dụng các toán tử gradient nổi bật như:
- **Sobel**
- **Prewitt**
- **Canny**

Biên cạnh đóng vai trò quan trọng trong các bài toán như phát hiện đối tượng, phân đoạn ảnh và thị giác máy tính.

---

## Nội dung chính

### 1. Toán tử Sobel
- Tính gradient theo phương ngang và dọc
- Tăng cường độ nhạy với biên cạnh trong ảnh

### 2. Toán tử Prewitt
- Tương tự Sobel nhưng dùng mặt nạ đơn giản hơn
- Thường dùng để so sánh kết quả với Sobel

### 3. Phát hiện biên Canny
- Là thuật toán phát hiện biên phổ biến và hiệu quả
- Gồm các bước: làm mịn ảnh, tính gradient, áp dụng ngưỡng kép và loại bỏ biên yếu

---

## Công nghệ sử dụng

- **Python**
- **NumPy**
- **OpenCV (cv2)**
- **Matplotlib**

---

## Hướng dẫn thực hiện

### 1. Cài đặt thư viện

```bash
pip install numpy opencv-python matplotlib
2. Mở và chạy Notebook
Dùng Jupyter Notebook hoặc Google Colab mở file .ipynb

Chạy lần lượt các cell để quan sát kết quả phát hiện biên

Có thể thay đổi ảnh đầu vào hoặc ngưỡng trong thuật toán Canny để kiểm tra kết quả

Kết luận
Thông qua bài Lab này, sinh viên hiểu được nguyên lý hoạt động của các phương pháp phát hiện biên và đánh giá được ưu nhược điểm của từng phương pháp trong thực tế.

Tài liệu tham khảo
Digital Image Processing – Rafael C. Gonzalez

https://docs.opencv.org

Slide bài giảng môn Nhập môn Xử lý ảnh số – Văn Lang University
