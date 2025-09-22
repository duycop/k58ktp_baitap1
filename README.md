# k58ktp - Môn: Phát triển ứng dụng trên nền web #

## BÀI TẬP VỀ NHÀ 01: ##

### TẠO SOLUTION GỒM CÁC PROJECT SAU: ###
1. DLL đa năng, keyword: c# window library -> **Class Library (.NET Framework)**: giải bài toán bất kỳ, độc lạ càng tốt, phải có dấu ấn cá nhân trong kết quả, biên dịch ra DLL. DLL độc lập vì nó ko nhập, ko xuất, nó nhận input truyền vào thuộc tính của nó, và trả về dữ liệu thông qua thuộc tính khác, hoặc thông qua giá trị trả về của hàm. Nó độc lập thì sẽ sử dụng được trên app dạng console (giao diện dòng lệnh - đen sì), cũng sử dụng được trên app desktop (dạng cửa sổ), và cũng sử dụng được trên web form (web chạy qua iis).
2. Console sử dụng được DLL trên: nhập được input, gọi DLL, hiển thị kết quả, phải có dấu án cá nhân. keyword: c# window Console => **Console App (.NET Framework)**, biên dịch ra EXE
3. Windows Form Application sử dụng được DLL đa năng trên, kéo các control vào để có thể lấy đc input, gọi DLL truyền input để lấy đc kq, hiển thị kq ra window form, phải có dấu án cá nhân; keyword: c# window Desktop => **Windows Form Application (.NET Framework)**, biên dịch ra EXE
4. Web đơn giản,  sử dụng web server là IIS, dùng file hosts để tự tạo domain, gắn domain này vào iis, file index.html có sử dụng html css js để xây dựng giao diện nhập được các input cho bài toán, dùng mã js để tiền xử lý dữ liệu, js để gửi lên backend. backend là api.aspx, trong code của api.aspx.cs thì lấy được các input mà js gửi lên, rồi sử dụng được DLL đa năng trên. kết quả gửi lại json cho client, js phía client sẽ nhận được json này hậu xử lý để thay đổi giao diện theo dữ liệu nhận dược, phải có dấu án cá nhân. keyword: c# window web => **ASP.NET Web Application (.NET Framework)** + tham khảo link chatgpt thầy gửi. project web này biên dịch ra DLL, phải kết hợp với IIS mới chạy được.

### CÁCH LÀM: ###
1. trên Github, (tạo tài khoản nếu chưa có), sau đó: Create a new repository, đặt tên repository tuỳ ý, nhớ bật README, nhớ để truy cập PUBLIC
<img width="1040" height="963" alt="image" src="https://github.com/user-attachments/assets/45b66ccb-d99a-4708-a2b0-7a9e28c98fc1" />
2. Edit file README trên 1 tab của trình duyệt, đồng thời với việc code trên Visual Studio. khi cần chụp hình ảnh: sử dụng Snipping tool có sẵn của window để chụp, sau đó sang tab README.md để paste hình ảnh vào.

<img width="648" height="324" alt="image" src="https://github.com/user-attachments/assets/c37d0e50-93bc-4c4d-92df-55e8656f785e" />
 
 khi rời máy nhớ Commit changes... để lưu file README lại
 
<img width="442" height="265" alt="image" src="https://github.com/user-attachments/assets/667be689-2b2e-4e72-bf92-3588ddd7636f" />

khi quay lại làm tiếp trên Visual studio thì lại edit file README

<img width="387" height="430" alt="image" src="https://github.com/user-attachments/assets/353c4d07-cc03-4357-8114-e40407a141b1" />

khi chạy từng project trong sulution: nhớ chụp hình và paste kq vào README, chú ý khi paste vào readme thì nó chỉ hiện ra thẻ img như này thôi

<img width="1190" height="811" alt="image" src="https://github.com/user-attachments/assets/7e94c622-d9ae-467f-aed2-1a9252b82faf" />

3. khi xong code như bài tập yêu cầu: upload toàn bộ thư mục chứa code lên github, cùng repository chứa file readme này

### CHÚ Ý ###
1. ĐƯỢC THAM KHẢO AI
2. KO ĐƯỢC CLONE BÀI BẠN KHÁC VỚI BẤT KỂ LÝ DO GÌ
3. Thời gian trên github ko fake được, mọi thay đổi đều lưu vết thời gian và nội dung sửa đổi.
4. mọi project đều phải có dấu ấn cá nhân (tự do sáng tạo dấu ấn cá nhân, ko có bất kỳ khuôn mẫu nào!)
5. deadline: 2025-09-28 (dấu thời gian sau ngày này là dead), cuối kì thầy sẽ tổng hợp link các repository này để chấm điểm.
6. mọi hình thức vi phạm, chỉ cần 1 lần: đều bị cấm thi, miễn thi lại.





