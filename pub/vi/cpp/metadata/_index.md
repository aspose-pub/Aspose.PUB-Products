---
translation: true
template: /_templates/metadata-cpp.md
title: Chỉnh sửa nhà xuất bản | Siêu dữ liệu PUB | C ++
description: Đọc Siêu dữ liệu nhà xuất bản bằng Giải pháp API PUB C++. Native C++ API cung cấp cho bạn quyền truy cập vào các thuộc tính SummaryInfo và DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: chỉnh sửa siêu dữ liệu pub, siêu dữ liệu tệp pub, trình chỉnh sửa siêu dữ liệu nhà xuất bản, đọc siêu dữ liệu tệp pub, đọc siêu dữ liệu pub
family: pub
platformtag: cpp
feature: metadata
aliases: / cpp / siêu dữ liệu /
---

{{<section banner>}}
---
h1: Chỉnh sửa siêu dữ liệu PUB
h2: Đọc tệp MS Publisher. API biên tập PUB Metatada cho C ++
---

{{<section overview>}}
---
p1: Microsoft <sup> ® </sup> Định dạng tệp tài liệu dành cho nhà xuất bản được sử dụng để tạo các loại ấn phẩm khác nhau như bản tin, tài liệu quảng cáo, tờ rơi và bưu thiếp và được sử dụng trong Email và Trang web. Tệp Pub chứa văn bản cũng như dữ liệu đồ họa vector và bitmap.
p2: Siêu dữ liệu nhà xuất bản là các thuộc tính (thông tin) mô tả tài liệu PUB. Chúng là các thuộc tính tiêu chuẩn như nhà xuất bản, tiêu đề, tác giả cuối cùng, tổ chức, URL, ngôn ngữ và các thông tin tương tự khác. Ngoài ra còn có dữ liệu được tạo tự động sau khi làm việc với tệp như kích thước của tệp hoặc lần chỉnh sửa cuối cùng. Thông tin hữu ích này được lưu trữ cùng với tài liệu.
p3: Cùng với chức năng Chuyển đổi và Đọc, giải pháp PUB API cho C ++ này cho phép bạn chỉnh sửa siêu dữ liệu chuẩn bằng các lớp DocSummaryInfo và SummaryInfo như được hiển thị trong mẫu mã sau. Bạn cũng có thể sử dụng API để tạo ứng dụng Trình chỉnh sửa siêu dữ liệu của riêng mình.
p4: Trước khi mã hóa Siêu dữ liệu, bạn cần tích hợp API siêu dữ liệu PUB C ++. Ví dụ sau đây sẽ chỉ cho bạn cách chỉnh sửa thuộc tính "Category".
---

{{<section feature1>}}
---
title: Xem & Chỉnh sửa Siêu dữ liệu PUB trên C ++
item1: "Quy trình đọc Siêu dữ liệu của nhà xuất bản bao gồm các bước tiếp theo:"
item2: Tải lên tệp PUB của bạn bằng [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Phương thức [*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) Lớp.
item3: Phân tích cú pháp tệp qua [*Phân tích cú pháp*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Phương thức [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) Giao diện.
item4: 'Chỉnh sửa siêu dữ liệu, ví dụ: Danh mục bằng [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) Phương thức của [*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Lớp.'
---

{{<section feature2>}}
---
title: Bắt đầu với API CPP PUB
item1: Cài đặt từ dòng lệnh với tên `` nuget install Aspose.PUB.cpp '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.PUB.cpp ''.
item2: Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/pub/cpp/).
---

{{<section codeexample>}}
---
title: Mã C ++ để sửa đổi siêu dữ liệu PUB
---
