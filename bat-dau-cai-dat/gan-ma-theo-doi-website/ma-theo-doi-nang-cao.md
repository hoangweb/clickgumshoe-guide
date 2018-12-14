---
description: Sử dụng PHP (dành cho người biết lập trình php)
---

# Cách 2 \(PHP\)

> * **Ưu điểm**: Theo dõi được click chuột nếu người dùng thoát website quá nhanh \(1-2s\)
> * **Nhược điểm**: Dành cho người biết lập trình php.

Lựa chọn thứ 2 là bạn sẽ tải bộ code plugin của chúng tôi lên hosting, nơi chứa website của bạn và tích hợp cùng với mã nguồn của website \(vd: PHP code thuần, wordpress,..\).

Để thực hiện, bạn làm theo các bước sau:

1. Tải bộ code tại đây: [https://github.com/clickgumshoe/clickgs-php-lite/archive/master.zip](https://github.com/clickgumshoe/clickgs-php-lite/archive/master.zip)

2. Giải nén vào một thư mục nào đó trên web, vd: {document\_root}/clickgs

3. Mở file đầu vào index.php và thêm dòng dưới đây ở đầu file:

```text
include "{document_root}/clickgs/bootstrap.php";
```

4. Cuối cùng, chèn mã theo dõi trong thẻ &lt;head.

```text
<head>
<?php hcgs_head();?>
</head>
```

Chú ý: thay biến {document\_root} bằng đường dẫn root của host.

