---
description: Cấu hình nâng cao cho tài khoản MCC
---

# Nâng cao

**Lưu ý**: Cấu hình này không bắt buộc. Dành cho tài khoản MCC quản lý các tài khoản của chính mình hoặc cho khách hàng.

Để cấu hình cài đặt nâng cao, bạn đăng nhập vào Clickgumshoe và chọn website để sửa cấu hình. Chọn tab "_Kết nối Google ads_", kéo thanh cuộn phần "_Nâng cao_".

### Cấu hình này là gì?

Cấu hình này bạn sẽ điền thông tin APIs mà bạn đăng ký với Google Ads trên tài khoản Adwords của bạn. API Token này được sử dụng để thêm/loại bỏ IP trong phần nhập IP chặn của google ads. 

### Tại sao một số người cần cấu hình này?

Nếu để trống, chúng tôi sẽ sử dụng chung token cho tất cả các khách của clickgumshoe. 

Mặc định tất cả các người dùng của clickgumshoe có sử dụng chung API mà chúng tôi có đăng ký với Google Ads. Do đó nếu tần xuất sử lý IP của các website đăng ký với clickgumshoe ngày một tăng lên, API của chúng tôi sẽ sử lý quá mức cho phép \(được giới hạn bởi Google\) và kết quả IP sẽ không được thêm vào khung chặn Google Adwords của bạn.

> Cảnh báo: khi sử dụng chung Token, bot đôi khi hoạt động không chính xác do việc chia sẻ token với nhiều khách hàng, do đó API của chúng tôi sẽ bị chặn LIMIT bởi google và được reset ở chu kỳ mới. Vì lý do này đôi khi bạn thấy IP không được thêm vào danh sách chặn. 
>
> Lời khuyên: Tốt nhất, bạn nên sử dụng token của riêng mình

### Cấu hình

Chúng ta cần 3 thông số: Developer Token, Client ID, Client Secret

Để lấy mã **developer token**, vui lòng xem [hướng dẫn này](https://chongclicktac.com/huong-dan/dang-ky-lay-ma-developer-token-adwords-api/).

Để lấy mã **Client Id** & **Client Secret**, vui lòng xem [hướng dẫn này](https://chongclicktac.com/huong-dan/huong-dan-lay-client-id-va-client-secret-tu-google/).

Sau đó sao chép và dán 3 thông tin này vào trang cấu hình của clickgumshoe, rồi nhấn nút "Lưu".

Bước cuối cùng, vẫn tại trang đó hãy kết nối lại tài khoản Google Ads của bạn, bằng cách nhấn nút "Xác thực lại Adwords". Bước này sẽ xác nhận thông tin API bạn điền đã chính xác chưa, nếu có lỗi hãy xem lại hướng dẫn và thực hiện một lần nữa.

