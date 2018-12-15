---
description: Các câu hỏi thường gặp bạn cần biết
---

# Câu hỏi thường gặp

**ClickGumshoe theo dõi được bao nhiêu click chuột?**

> Phần mềm theo dõi click chuột không giới hạn từ quảng cáo Google.

**Tại sao cần kết nối tài khoản Google Ads của bạn qua API của tôi?**

> Kết nối tài khoản Google Ads bằng cách cho phép Clickgumshoe.com quản lý chiến dịch Adwords của bạn, phần mềm sẽ tự động thêm IP vào khung chặn IP trong chiến dịch. Việc này hoàn toàn tự động qua API và theo chính sách bảo mật [**AdWords OAuth 2.0**](https://developers.google.com/adwords/api/docs/guides/authentication) của Google, không ảnh hưởng đến cài đặt chiến dịch cũng như tối ưu quảng cáo của bạn.
>
> > **CẢNH BÁO!** Một số Tool trên thị trường \(như autoads.asia, chaanclickao.com, fff.com.vn..\) họ yêu cầu làm người quản lý tài khoản Google Ads của bạn để chặn IP bằng cách gửi lời mời quản lý thủ công qua email của bạn. Điều này rất nguy hiểm, chỉ có những ai bạn thật tin tưởng thì mới chia sẻ Full quyền quản lý cho họ. Bằng cách này, thông tin chiến dịch của bạn sẽ hiển thị trong tài khoản MCC của họ và có thể sửa xóa mà bạn không được kiểm soát.

**IP click ảo sẽ bị chặn sau bao lâu kể từ khi bị phát hiện?**

> Hệ thống sẽ chặn IP click ảo trong vòng 5s kể từ khi phát hiện. Bạn có thể kiểm tra dữ liệu IP được thêm trong chiến dịch Google Ads của bạn.

**Nếu ngưng sử dụng phần mềm, tôi muốn gỡ kết nối API thì làm thế nào?**

> Rất đơn giản. Trong tab Kết nối GoogleAds, nhấn lại nút "Đã Kết Nối Google Ads" và chọn menu "Thu hồi Adwords API" là xong.

**Thêm chiến dịch mới thì có phải cập nhật chiến dịch mới trong kết nối Google Ads không?**

> Có, nếu bạn thay đổi chiến dịch thì vào lại tab Kết nối GoogleAds &gt; sau đó nhấn "Làm tươi" để chọn chiến dịch mới, sau đó nhấn "Lưu" để hoàn tất.
>
> Dưới danh sách chiến dịch là nút "Cập nhật quảng cáo", tính năng này khi chiến dịch của bạn thay đổi để cập nhật tên chiến dịch /nhóm quảng cáo.

**Tại sao có sự chênh lệch số liệu giữa hệ thống chặn click ảo và Google Ads?**

> Số Click Google Ads của phần mềm là số tổng \(gồm cả thật + ảo\). 2. Độ lệch &lt;= 20% giữa phần mềm và Google Ads là hiện tượng bình thường, do: + Có nhiều nguồn truy cập vào link ngoài Google Ads. + Lệch do lỗi mạng của khách click quảng cáo \(1 trong 2 bên không ghi nhận được\)?

**Tại sao bạn không nhận được email báo cáo hàng ngày?**

> Nếu bạn không nhận được báo cáo gửi qua mail, bạn hãy kiểm tra lại cấu hình SMTP đã đúng chưa. Xem hướng dẫn [**tại đây**](https://help.clickgumshoe.com/bat-dau-cai-dat/cau-hinh-website/smtp).

**Tại sao tôi đã stop chiến dịch nhưng phần mềm vẫn thống kê click chuột?**

> Ngoài theo dõi nhấp chuột từ quảng cáo Google Ads, Clickgumshoe.com còn theo dõi click chuột tìm kiếm tự nhiên \(S.E.O\). Muốn ngưng theo dõi, bạn chỉ cần xóa đoạn mã theo dõi đặt trên website.

**Gắn mã theo dõi có ảnh hưởng đến website của tôi?**

> Không, mã code theo dõi tương tự như code của Google Analytic. Việc cài mã này hoàn toàn không ảnh hưởng đến website của bạn và có thể sử dụng song song các mã theo dõi khác.

