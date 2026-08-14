# ✈️ Phân Tích Hành Vi Khách Hàng Hàng Không (Airline Customer Behavior Analysis)

## 📌 Giới thiệu dự án (Introduction)
Dự án này tập trung vào việc phân tích hành vi của khách hàng trong lĩnh vực hàng không, từ đó rút ra những thông tin (insight) quan trọng nhằm cải thiện chất lượng dịch vụ và nâng cao trải nghiệm khách hàng. Dự án bao gồm toàn bộ quy trình vòng đời dữ liệu, từ khâu thu thập, tiền xử lý, phân tích khám phá (EDA), áp dụng mô hình Học máy (Machine Learning) cho đến việc trực quan hóa bằng dashboard tương tác trên Power BI.

## 👤 Thông tin tác giả
- **Tác giả:** Trần Cẩm Tú
- **Vai trò:** Thực hiện toàn bộ quy trình dự án một mình, bao gồm: Tiền xử lý dữ liệu, Khai phá dữ liệu, Xây dựng mô hình Machine Learning, Xây dựng Power BI Dashboard và Viết báo cáo tổng kết.

## 📂 Cấu trúc thư mục (Folder Structure)
Dự án được tổ chức theo cấu trúc sau:

- `data/`: Thư mục chứa các tệp dữ liệu dự án.
  - `raw/`: Chứa các dữ liệu thô ban đầu (ví dụ: dữ liệu review khách hàng, thông tin booking...).
  - `processed/`: Chứa dữ liệu đã qua quá trình làm sạch, sẵn sàng cho việc phân tích và trực quan hóa.
- `notebooks/`: Chứa các file Jupyter Notebook ghi lại source code của quá trình phân tích, xử lý dữ liệu và chạy mô hình học máy.
- `powerbi/` và file `.pbix`: Chứa file Power BI thiết kế dashboard trực quan hóa dữ liệu và báo cáo.
- `requirements.txt`: Danh sách các thư viện Python (dependencies) cần thiết để chạy dự án.

## 🛠️ Công nghệ & Công cụ sử dụng (Technologies & Tools)
- **Ngôn ngữ lập trình:** Python
- **Thư viện Python:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,...
- **Công cụ:** 
  - Jupyter Notebook (viết code phân tích và mô hình hóa)
  - Microsoft Power BI Desktop (trực quan hóa dữ liệu)
- **Kỹ năng ứng dụng:** Data Cleaning, Exploratory Data Analysis (EDA), Predictive Modeling.

## 🚀 Hướng dẫn cài đặt và sử dụng (How to run)

1. **Clone repository về máy local:**
   ```bash
   git clone https://github.com/trancamtu3518/Airline-Customer-Behavior-Analysis.git
   cd Airline-Customer-Behavior-Analysis
   ```

2. **Cài đặt các thư viện cần thiết:**
   Đảm bảo bạn đã cài đặt Python. Sau đó chạy lệnh sau trong terminal để tải các thư viện:
   ```bash
   pip install -r requirements.txt
   ```

3. **Chạy source code phân tích:**
   Mở Jupyter Notebook và truy cập vào các file `.ipynb` (trong thư mục `notebooks` hoặc `test.ipynb`) để chạy và xem chi tiết quá trình làm sạch dữ liệu, phân tích biểu đồ và huấn luyện mô hình.

4. **Xem Dashboard trực quan hóa:**
   Dữ liệu sạch đã được xuất ra thư mục `data/processed/`. Để xem Dashboard, bạn cần cài đặt **Microsoft Power BI Desktop**, sau đó mở file `Airline-Customer-Behavior-Analysis.pbix` (hoặc các file trong thư mục `powerbi/`) để tương tác trực tiếp với các biểu đồ báo cáo.

---
*Cảm ơn bạn đã ghé thăm dự án của tôi!*