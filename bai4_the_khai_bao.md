# Thẻ `<title>`
> Thẻ `title` có tác dụng khai báo tên tài liệu web đang soạn

# Thẻ `<meta>`
> Là thẻ đặc biệt không có thẻ đóng có tác dụng khai báo dữ liệu như mô tả, từ khóa, tên tác giả, ...
1. Thuộc tính `charset` (chữ cái): có nhiệm vụ khai báo cho trình duyệt biết bảng mã ký tự siêu văn bản bên trong tài liệu là gì. Và hiện nay hầu hết chúng ta đều sử dụng bảng mã UTF-8 cho tất cả ngôn ngữ bao gồm các ngôn ngữ tiếng latin, chữ Hán – Nôm và các ngôn ngữ đọc từ phải sang trái (Right to Left – RTL) như tiếng Ả-Rập chẳng hạn.

        <html><meta charset="UTF-8" /></html>

2. Thuộc tính `name` : thuộc tính name thì thẻ meta của bạn phải có hai thuộc tính, đó là thuộc tính name và content, trong đó thuộc tính content được xem là thiết lập nội dung cho thuộc tính name

   - `content=author`: khai báo tên tác giả

            [html]<meta name="author" content="Nguyen Tuan" />[/html]

    - `content=description`: Khai báo mô tả của tài liệu

            [html]<meta name="description" content="thẻ khai báo" />[/html]

    - `content=keyword`: Khai báo từ khóa của tài liệu, các từ khóa giúp các trình tìm kiếm tìm được trang web

            [html]<meta name="keyword" content="hoc_html,html" />[/html]

    - `content=application-name`: Tên ứng dụng đại diện của tài liệu web.

    - `content=generator`: Khai báo tên ứng dụng tạo ra tài liệu.