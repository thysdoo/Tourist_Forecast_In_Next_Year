# 📌 Dự báo Lượng Khách Du Lịch  
**Python, SQL, Machine Learning**  

## 📌 Mô tả dự án  
Dự án này nhằm dự báo số lượng khách du lịch đến Singapore trong 12 tháng tới bằng cách sử dụng dữ liệu từ tập `singapore_tourist_new.csv`.  
Mục tiêu là xây dựng mô hình dự báo chính xác dựa trên dữ liệu lịch sử để hỗ trợ lập kế hoạch du lịch và quản lý tài nguyên.  

---

## 📁 Cấu trúc thư mục  

tourist_forecast_project/ 

│── EDA by python.ipynb: Phân tích dữ liệu khám phá (EDA) và kiểm tra dữ liệu trước khi đưa vào mô hình

│── Tourist forecast result visualization.ipynb: Trực quan hóa kết quả dự báo và so sánh với dữ liệu thực tế

│── SQL code/: Chứa mã SQL được sử dụng để truy vấn dữ liệu

│── EDA data.csv: Dữ liệu đã xử lý và làm sạch sau bước phân tích khám phá

│── data.csv: Dữ liệu gốc trước khi tiền xử lý

│── Forecast result.csv: Kết quả dự báo số lượng khách du lịch trong 12 tháng tiếp theo

│── README.md: Tài liệu mô tả dự án

---

## 🛠️ Công nghệ sử dụng  
- Python  
- SQL  
- Pandas, NumPy  
- Scikit-Learn  
- Matplotlib, Seaborn (Visualization)  
- ARIMA (Time Series Forecasting)  

---

## 📊 Các bước thực hiện  

### 1️⃣ Phân tích dữ liệu (EDA)  
- File **EDA by python.ipynb** chứa quá trình khám phá dữ liệu, kiểm tra giá trị khuyết, ngoại lệ và phân tích xu hướng.  
- Kết quả cho thấy dữ liệu có xu hướng tăng theo thời gian với tính chất mùa vụ rõ ràng.  

### 2️⃣ Tiền xử lý dữ liệu  
- Kiểm tra và xử lý giá trị thiếu (không có giá trị thiếu trong tập dữ liệu).  
- Thực hiện các chuyển đổi cần thiết (differencing) để ổn định phương sai và đạt tính dừng.  

### 3️⃣ Xây dựng mô hình dự báo  
- Sử dụng các mô hình **Time Series Forecasting** như:  
  - **ARIMA (AutoRegressive Integrated Moving Average)**: Mô hình hóa xu hướng và mùa vụ.  
- Đánh giá mô hình qua các chỉ số **RMSE (Root Mean Square Error)** và **MAE (Mean Absolute Error)**.  

### 4️⃣ Đánh giá và trực quan hóa kết quả  
- So sánh giá trị thực tế và giá trị dự báo.  
- File **Tourist forecast result visualization.ipynb** chứa biểu đồ trực quan về sự chênh lệch giữa dự báo và thực tế.  

### 5️⃣ Kết quả dự báo  
- File **Forecast result.csv** chứa dự báo số lượng khách du lịch trong 12 tháng tiếp theo.  

---

## 📌 Kết quả mô hình  
📊 **Dự báo cho thấy xu hướng khách du lịch tiếp tục tăng, với các đỉnh theo mùa rơi vào các tháng du lịch cao điểm.**  
📌 **Chi tiết kết quả được lưu trong file `Forecast result.csv` và có thể xem trực quan trong `Tourist forecast result visualization.ipynb`.**  
