# Đồ án Bài tập lớn Nhập môn Học máy (FIT4013)
## Đề tài 15: Dự đoán điểm chất lượng rượu vang (Wine Quality Prediction)

### 👥 Thông tin nhóm
* **Tên nhóm:** Nhóm 4
* **Thành viên:** Phạm Danh Thái - Ngô Văn Hiếu - Phạm Anh Quân


---

### 📂 Cấu trúc Repository
nhom4/
│
├── wine+quality/              # Thư mục chứa mã nguồn và dữ liệu
│   ├── winequality-white.csv  # Tập dữ liệu rượu vang trắng (UCI)
│   └── wine_model.ipynb       # Jupyter Notebook chứa toàn bộ pipeline ML
│
├── report/                    # Thư mục chứa báo cáo (LaTeX / PDF)
│   └── report.pdf             # Bản báo cáo hoàn chỉnh của đồ án
│
├── README.md                  # Hướng dẫn chi tiết về đồ án
└── requirements.txt           # Danh sách các thư viện Python cần thiết
---

### 📊 Giới thiệu đề tài & Dữ liệu
* **Mô tả bài toán:** Xây dựng mô hình học máy (Machine Learning) dạng Hồi quy (Regression) để dự đoán điểm chất lượng cảm quan của rượu vang trắng dựa trên các chỉ số hóa học đầu vào.
* **Nguồn dữ liệu:** Sử dụng bộ dữ liệu **Wine Quality Dataset** từ UCI Machine Learning Repository.
* **Đặc trưng đầu vào:** Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.
* **Biến mục tiêu (Target):** Điểm chất lượng (`quality`) trên thang đo từ 0 đến 10.

---

### 🛠️ Công nghệ sử dụng (Tech Stack)
* **Ngôn ngữ:** Python
* **Môi trường:** Jupyter Notebooks (VS Code)
* **Thư viện chính:** 
  * `pandas`, `numpy` (Xử lý và phân tích dữ liệu)
  * `matplotlib`, `seaborn` (Trực quan hóa dữ liệu và ma trận tương quan)
  * `scikit-learn` (Xây dựng pipeline, chuẩn hóa dữ liệu, mô hình Linear Regression, Decision Tree và GridSearchCV)

---

### ⚙️ Hướng dẫn cài đặt và chạy chương trình (Tái lập kết quả)

1. **Clone repository về máy:**
   ```bash
   git clone [https://github.com/PhamDanhThai/nhom4.git](https://github.com/PhamDanhThai/nhom4.git)
   cd nhom4
