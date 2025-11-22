# Sales Dashboard Pro - Phân tích Doanh thu Siêu trực quan

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.30%2B-red)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-blue)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-green)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app-link.streamlit.app)

> **Dashboard phân tích dữ liệu bán hàng mạnh mẽ, trực quan và dễ sử dụng** – 100% Python + Streamlit.

![Dashboard Preview](assets/demo.png)
_Có thể thêm nhiều ảnh screenshot vào thư mục `assets/` để trông chuyên nghiệp hơn_

## Tính năng nổi bật

- Biểu đồ tương tác 100% với **Plotly** (zoom, hover, click để lọc)
- Lọc dữ liệu theo **ngày/tháng/quý/năm**, khu vực, nhân viên, sản phẩm, khách hàng
- Top 10 sản phẩm / khách hàng / nhân viên bán chạy nhất
- So sánh **doanh thu thực tế vs mục tiêu** (Target vs Actual)
- Tự động tính các chỉ số quan trọng:
  - Doanh thu, lợi nhuận gộp, tỷ suất lợi nhuận
  - Tăng trưởng YoY & MoM
  - AOV, số đơn hàng trung bình/ngày
- Giao diện đẹp, responsive, hỗ trợ **Dark Mode** tự động
- Tốc độ tải siêu nhanh nhờ `@st.cache_data` & `@st.cache_resource`
- Xuất báo