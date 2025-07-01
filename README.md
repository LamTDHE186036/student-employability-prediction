# student-employability-prediction
# Dự đoán việc làm sinh viên sau tốt nghiệp

Dự án sử dụng các mô hình học máy để dự đoán khả năng **có việc làm/không có việc làm** của sinh viên sau khi tốt nghiệp, dựa trên dữ liệu từ bộ IMDB đã được xử lý lại phù hợp cho bài toán phân loại.

# Mục tiêu

- Xây dựng mô hình dự đoán nhị phân: **Có việc làm** (`1`) hoặc **Không có việc làm** (`0`)
- So sánh độ chính xác giữa hai mô hình:
  - Logistic Regression
  - Random Forest Classifier
- Nhập một câu mô tả thông tin sinh viên để mô hình dự đoán kết quả

---

# Data
- Thu thập trên Kaggle
- Được lưu trong thư mục `data/` dưới dạng file `.rar`
- Cần giải nén file `IMDB_Dataset.rar` để sử dụng

# Code
## Train
- Xử lý dữ liệu:Tách đặc trưng (X) và nhãn (y), Mã hóa nhãn (Label Encoding), Chuẩn hóa dữ liệu (StandardScaler),...
- Chia tập huấn luyện và kiểm tra

- Huấn luyện mô hình:
  - Logistic Regression
  - Random Forest Classifier
  - So sánh độ chính xác giữa hai mô hình
  - Lưu model tốt nất .pkl
## Test 
  - Sử dụng model .pkl đã lưu đưa ra dự đoán
## Kết quả 
![image](https://github.com/user-attachments/assets/7e2185cb-a966-4cdf-94cd-5ec4bdb4075f)
