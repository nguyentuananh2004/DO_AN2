🌦️ Bộ Dữ Liệu Thời Tiết – Weather Dataset
Bộ dữ liệu này chứa thông tin thời tiết chi tiết được thu thập từ các nguồn dự báo đáng tin cậy. Dữ liệu có thể được sử dụng để phân tích xu hướng thời tiết, dự báo mưa, và phát triển các mô hình học máy liên quan đến khí tượng.

🗂️ Cấu Trúc Dữ Liệu
Cột dữ liệu	Mô tả

time	Thời gian đo/ghi nhận dữ liệu (theo định dạng ISO 8601 hoặc datetime)

temperature_2m	Nhiệt độ không khí ở độ cao 2 mét (°C)

relative_humidity_2m	Độ ẩm tương đối ở độ cao 2 mét (%)

dew_point_2m	Điểm sương ở độ cao 2 mét (°C)

apparent_temperature	Nhiệt độ cảm nhận (°C) – tính đến gió và độ ẩm

precipitation_probability	Xác suất có mưa (%)

precipitation	Tổng lượng mưa (mm)

rain	Lượng mưa riêng (mm) – không bao gồm tuyết hoặc mưa đá

📌 Ứng Dụng
📈 Phân tích xu hướng thời tiết trong ngày/tuần

🤖 Huấn luyện mô hình dự báo mưa hoặc nhiệt độ

📊 Trực quan hóa dữ liệu khí hậu địa phương

🌱 Hỗ trợ các ứng dụng trong nông nghiệp, du lịch, logistics

🔗 Nguồn Dữ Liệu
Dữ liệu được thu thập tự động từ các API như:

Open-Meteo API

Các công cụ Python như requests, pandas, matplotlib v.v.
