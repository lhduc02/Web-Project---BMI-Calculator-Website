# Web-Project---BMI-Calculator-Website

Mô tả: Xây dựng trang web để tính chỉ số BMI

1. Frontend (Giao diện người dùng):
+ HTML: Tạo cấu trúc cơ bản của trang web.
+ CSS: Thiết kế giao diện trang web, làm cho trang web trông đẹp và thân thiện với người dùng.
+ JavaScript: Xử lý logic tính toán BMI trên trình duyệt (có thể thực hiện tính toán trực tiếp mà không cần gửi dữ liệu đến server). Gửi dữ liệu chiều cao và cân nặng của người dùng đến backend qua API (sử dụng Fetch API hoặc Axios).

2. Backend (Xử lý logic và lưu trữ dữ liệu):
+ Python (Flask hoặc Django), Node.js (Express.js).
+ Xử lý yêu cầu từ frontend.
+ Tính toán BMI (nếu không thực hiện trên frontend).
+ Lưu trữ dữ liệu chiều cao và cân nặng vào cơ sở dữ liệu.
+ RESTful API: Tạo các endpoint để nhận dữ liệu từ frontend và gửi phản hồi (kết quả BMI).

3. Database (Lưu trữ dữ liệu):
+ PostgreSQL
+ Lưu trữ thông tin chiều cao, cân nặng và có thể thêm thông tin ngày giờ nhập liệu.

4. Server Hosting (Lưu trữ trang web và backend):
+ AWS EC2, Heroku, hoặc Vercel: Để triển khai ứng dụng của bạn lên internet.
+ S3 (AWS): Nếu bạn cần lưu trữ các file tĩnh như hình ảnh hoặc CSS.

5. Quy trình tổng quan:
+ Frontend: Người dùng nhập chiều cao và cân nặng → Gửi dữ liệu đến backend qua API.
+ Backend: Nhận dữ liệu → Tính toán BMI → Lưu vào database → Trả kết quả về frontend.
+ Frontend: Hiển thị kết quả BMI cho người dùng.
