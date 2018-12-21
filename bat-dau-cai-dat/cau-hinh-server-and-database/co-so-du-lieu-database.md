---
description: CSDL là nơi lưu thông tin IP và lịch sử nhấp chuột.
---

# Cơ sở dữ liệu \(CSDL\)

> Google Firebase là một dịch vụ cơ sở dữ liệu thời gian thực hoạt động trên nền tảng đám mây được cung cấp bởi Google. Phần mềm ClickGumshoe sử dụng Firebase để lưu trữ CSDL và hiển thị báo cáo cho bạn. \(xem thêm tại [wikipedia](https://en.wikipedia.org/wiki/Firebase)\)

### Tạo CSDL

Để tạo CSDL, bạn truy cập Firebase \(Google\) [https://firebase.google.com](https://firebase.google.com/) và đăng nhập với tài khoản gmail bạn thêm ở phần [thêm website](https://help.clickgumshoe.com/bat-dau-cai-dat/tao-tai-khoan#them-website). Sau đó bạn nhấn vào "**GO TO CONSOLE**" như hình dưới.

![](../../.gitbook/assets/uwwunnchrpsw6wqd8le1fwyq4upjoylorit5fhcmlwtftg9yewd7tpmxfy1bz1jjphunhlpyvh61lsttps_cxmkkvbx0k7t6nhzn.bin)

Tiếp đến, nhấn vào “**Add project**” để tạo CSDL.

![](../../.gitbook/assets/6cevputmdhc12q5ds4-bnxddd6_jdovmo8tqgkf7beu-r9vxteq6wxqen7uklu6fr6e-eznpqy30ks-ojh3cijdvzy1f0efnlqt3.bin)

Tiếp đến, bạn điền tên CSDL vào trường “Project name”. Lưu ý: tên này bạn copy ở mục Name. Ví dụ như hình dưới:

![](../../.gitbook/assets/csdl.png)

Giống như thế này:

![](../../.gitbook/assets/csdl2.png)

Nhấn nút “**Create project**” để tạo CSDL. Lưu ý: Project ID phải cùng tên này.

### Kết nối CSDL \(Firebase\)

Tiếp theo, bạn lấy thông tin **Token** & **Service account** của CSDL vừa tạo ở trên.

![](../../.gitbook/assets/lay-ma-firebase.png)

Để lấy mã **Token**, bạn nhấn vào liên kết “**Lấy mã**” ở trường Token, liên kết này sẽ mở trang cấu hình CSDL của Firebase. Dê chuột vào vùng Secret và nhấn nút "Show" để thấy thông tin.

![](../../.gitbook/assets/csdl4.png)

Copy chuỗi này và dán vào trường **Token**.

Tiếp đến, để lấy thông tin Service account, bạn làm tương tự. Nhấn vào liên kết “**Lấy mã**” ở trường Service account hoặc ở ngay hình trên nhấn vào tab “**Firebase Admin SDK**” như hình dưới:

![](../../.gitbook/assets/sdk.png)

Nhấn nút “**Generate new private key**” & nhấn tiếp “**Generate key**” để tải file .json về máy tính.

![](../../.gitbook/assets/yslspiqvdhfapxnelutuldnunauibafv0bqvjhw8ddbumg58ri7-yydrbei50ej1nvfquo4mjsaepvc2dn6nhvsd08lw8rwzpcqc.bin)

Mở file này với notepad hoặc notepad++, và copy nội dung trong file vào trường Service account.

Cuối cùng, bạn nhấn nút “**Test API**” để kiểm tra thông tin CSDL đã chính xác chưa. Nếu thành công sẽ báo như hình dưới.

![](../../.gitbook/assets/csdl-thanhcong.png)

