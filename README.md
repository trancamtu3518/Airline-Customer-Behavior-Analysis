# ✈️ Phân Tích Hành Vi Khách Hàng Hàng Không (Airline Customer Behavior Analysis)

## 📌 Giới thiệu dự án (Introduction)
Dự án này tập trung vào việc phân tích hành vi của khách hàng trong lĩnh vực hàng không, từ đó rút ra những thông tin (insight) quan trọng nhằm cải thiện chất lượng dịch vụ và nâng cao trải nghiệm khách hàng. Dự án bao gồm toàn bộ quy trình vòng đời dữ liệu, từ khâu thu thập, tiền xử lý, phân tích khám phá (EDA), kiểm định thống kê (ANOVA), áp dụng các mô hình Học máy (Machine Learning) cho đến việc trực quan hóa bằng dashboard tương tác trên Power BI.

## 👤 Thông tin tác giả
- **Tác giả:** Trần Cẩm Tú
- **Vai trò:** Thực hiện toàn bộ quy trình dự án cá nhân, bao gồm: Tiền xử lý dữ liệu, Khai phá dữ liệu, Xây dựng mô hình Machine Learning, Xây dựng Power BI Dashboard và Viết báo cáo tổng kết.

## 📂 Cấu trúc thư mục (Folder Structure)
Dự án được tổ chức theo cấu trúc sau:

- `data/`: Thư mục chứa dữ liệu đầu vào.
  - `raw/`: Dữ liệu thô (ví dụ: review khách hàng, thông tin hành khách `Passanger_booking_data.csv`).
  - `processed/`: Dữ liệu đã qua làm sạch, sẵn sàng cho việc phân tích và trực quan hóa (ví dụ: `CAR.csv`, `CPS.csv`).
- `notebooks/`: Chứa các file Jupyter Notebook về phân tích và xây dựng mô hình:
  - `01_data_exploration.ipynb`: Tiền xử lý dữ liệu, EDA và kiểm định giả thuyết.
  - `02_modeling_trieu.ipynb` / `version2.ipynb`: Huấn luyện và đánh giá các mô hình học máy (Logistic Regression, Decision Tree, Linear Regression).
  - Các hình ảnh xuất ra từ mô hình: biểu đồ phân phối (`target_distribution.png`), ma trận nhầm lẫn (`logistic_confusion_matrix.png`),...
- `powerbi/` & `Airline-Customer-Behavior-Analysis.pbix`: File Power BI thiết kế dashboard trực quan hóa dữ liệu và báo cáo tương tác.
- `requirements.txt`: Danh sách các thư viện Python cần thiết để chạy dự án.

## 🛠️ Công nghệ & Kỹ thuật áp dụng (Technologies & Techniques)
- **Ngôn ngữ lập trình:** Python
- **Thư viện Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Mô hình học máy áp dụng:**
  - Cây quyết định (Decision Tree)
  - Hồi quy tuyến tính (Linear Regression)
  - Hồi quy Logistic (Logistic Regression)
- **Công cụ:** 
  - Jupyter Notebook (viết code phân tích và mô hình hóa)
  - Microsoft Power BI Desktop (trực quan hóa dữ liệu)
- **Kỹ năng ứng dụng:** Data Cleaning, Exploratory Data Analysis (EDA), Statistical Testing (ANOVA), Predictive Modeling.

## 🚀 Hướng dẫn cài đặt và sử dụng (How to run)

1. **Clone repository về máy local:**
   ```bash
   git clone https://github.com/trancamtu3518/Airline-Customer-Behavior-Analysis.git
   cd Airline-Customer-Behavior-Analysis
   ```

2. **Cài đặt các thư viện cần thiết:**
   Đảm bảo bạn đã cài đặt Python. Sau đó chạy lệnh sau trong terminal:
   ```bash
   pip install -r requirements.txt
   ```

3. **Chạy mã nguồn phân tích (Notebooks):**
   Mở Jupyter Notebook và truy cập vào các file trong thư mục `notebooks` để xem chi tiết:
   - Chạy `01_data_exploration.ipynb` để xem cách dữ liệu được làm sạch và biểu diễn trực quan.
   - Chạy các file modeling để theo dõi quy trình huấn luyện và đánh giá mô hình học máy.

4. **Xem Dashboard trực quan hóa (Power BI):**
   Mở file `Airline-Customer-Behavior-Analysis.pbix` bằng phần mềm **Microsoft Power BI Desktop**. Hệ thống Dashboard sẽ được nạp dữ liệu từ thư mục `data/processed/` để cho phép bạn tương tác trực tiếp với các biểu đồ báo cáo.

---
*Cảm ơn bạn đã ghé thăm dự án của tôi!*