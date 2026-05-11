# pki_project
Đây là báo cáo cuối kỳ môn Nhập môn Bảo mật thông tin nhóm 01 - HK2/2025-2026
- sever.py: Chứa mã nguồn python, dùng để chạy HTTPS sever khi đã có khóa công khai và khóa riêng tư
- BMTT_TẠO KEY.txt: Prompt dùng để tạo key và chứng chỉ số, biến sever thành một Root CA

- rootCA.crt: Chứng chỉ cho thấy sever hiện tại chính là một Root CA
- rootCA.key: Khóa riêng tư (Private key) của RootCA
- rootCA.srl: Số serial của RootCA, dùng để phân biệt tránh trường hợp ký nhiều chứng chỉ

- sever.crt: Chứng chỉ của sever
- sever.csr: Yêu cầu cấp chứng chỉ Root CA của sever
- sever.key: Khóa của sever để đối chiếu với khóa Root CA được tạo sẵn

- v3.ext: Một số thuộc tính mở rộng của chứng chỉ 
- style.css: Định dạng lại trang web cho đẹp và bắt mắt