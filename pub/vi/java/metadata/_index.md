---
translation: true
template: /_templates/metadata-java.md
title: Chỉnh sửa nhà xuất bản | Siêu dữ liệu PUB | Java
description: Đọc Siêu dữ liệu nhà xuất bản bằng Giải pháp API PUB Java. Native Java API cung cấp cho bạn quyền truy cập vào các thuộc tính SummaryInfo và DocSummaryInfo.
url: /java/metadata/pub/
metakeywords: chỉnh sửa siêu dữ liệu pub java, siêu dữ liệu tệp pub java, trình chỉnh sửa siêu dữ liệu nhà xuất bản java, đọc siêu dữ liệu tệp pub java, đọc siêu dữ liệu pub java
family: pub
platformtag: java
feature: metadata
aliases: / java / siêu dữ liệu /
---

{{<section banner>}}
---
h1: Chỉnh sửa siêu dữ liệu PUB
h2: Đọc tệp MS Publisher. API biên tập PUB Metatada dành cho Java
---

{{<section overview>}}
---
p1: Microsoft <sup> ® </sup> Định dạng tệp tài liệu dành cho nhà xuất bản được sử dụng để tạo các loại ấn phẩm khác nhau như bản tin, tài liệu quảng cáo, tờ rơi và bưu thiếp và được sử dụng trong Email và Trang web. Tệp Pub chứa văn bản cũng như dữ liệu đồ họa vector và bitmap.
p2: Siêu dữ liệu nhà xuất bản là các thuộc tính (thông tin) mô tả tài liệu PUB. Chúng là các thuộc tính tiêu chuẩn như nhà xuất bản, tiêu đề, tác giả cuối cùng, tổ chức, URL, ngôn ngữ và các thông tin tương tự khác. Ngoài ra còn có dữ liệu được tạo tự động sau khi làm việc với tệp như kích thước của tệp hoặc lần chỉnh sửa cuối cùng. Thông tin hữu ích này được lưu trữ cùng với tài liệu.
p3: Cùng với chức năng Chuyển đổi và Đọc, giải pháp PUB API cho Java này cho phép bạn chỉnh sửa siêu dữ liệu chuẩn bằng các lớp DocSummaryInfo và SummaryInfo như được hiển thị trong mẫu mã sau. Bạn cũng có thể sử dụng API để tạo ứng dụng Trình chỉnh sửa siêu dữ liệu của riêng mình.
p4: Trước khi mã hóa Siêu dữ liệu, bạn cần tích hợp API Siêu dữ liệu Java PUB. Ví dụ sau sẽ chỉ cho bạn cách chỉnh sửa thuộc tính "Ngôn ngữ".
---

{{<section widget>}}
---
title: Cách chỉnh sửa siêu dữ liệu PUB bằng Java
item1: "Để chỉnh sửa siêu dữ liệu PUB, chúng tôi sẽ sử dụng [Aspose.PUB dành cho API Java](https://products.aspose.com/pub/java/), đây là một chuyển đổi giàu tính năng, mạnh mẽ và dễ sử dụng API cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất trực tiếp từ [Maven](https://repository.aspose.com/pub/) và cài đặt nó trong Maven của bạn dựa trên dự án bằng cách thêm các cấu hình sau vào pom.xml."
---

{{<section feature1>}}
---
title: Xem và chỉnh sửa siêu dữ liệu PUB trên Java
item1: "Quy trình đọc Siêu dữ liệu của nhà xuất bản bao gồm các bước tiếp theo:"
item2: Tải lên tệp PUB của bạn bằng phương pháp [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) của [*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Lớp.
item3: Phân tích cú pháp tệp qua [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) phương thức [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Giao diện.
item4: 'Chỉnh sửa siêu dữ liệu, ví dụ: Ngôn ngữ bằng [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) Phương thức Lớp [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo).'
---

{{<section feature2>}}
---
title: yêu cầu hệ thống
item1: Aspose.PUB cho Java được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.
item2: J2SE 8.0 (1.8) trở lên.
---

{{<section codeexample>}}
---
title: Mã Java để cập nhật siêu dữ liệu PUB
---