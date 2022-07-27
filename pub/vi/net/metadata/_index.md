---
translation: true
template: /_templates/metadata-net.md
title: Chỉnh sửa nhà xuất bản | Siêu dữ liệu PUB | .NET
description: Đọc Siêu dữ liệu nhà xuất bản bằng Giải pháp API PUB .NET. Native C# .NET API cung cấp cho bạn quyền truy cập vào các thuộc tính SummaryInfo và DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: 'chỉnh sửa siêu dữ liệu pub net, siêu dữ liệu tệp pub C #, trình chỉnh sửa siêu dữ liệu nhà xuất bản .net, đọc siêu dữ liệu tệp pub C #, đọc siêu dữ liệu pub .net'
family: pub
platformtag: net
feature: metadata
aliases: / net / siêu dữ liệu /
---

{{<section banner>}}
---
h1: Chỉnh sửa siêu dữ liệu PUB
h2: Đọc tệp MS Publisher. API biên tập PUB Metatada cho .NET
---

{{<section overview>}}
---
p1: Microsoft <sup> ® </sup> Định dạng tệp tài liệu dành cho nhà xuất bản được sử dụng để tạo các loại ấn phẩm khác nhau như bản tin, tài liệu quảng cáo, tờ rơi và bưu thiếp và được sử dụng trong Email và Trang web. Tệp Pub chứa văn bản cũng như dữ liệu đồ họa vector và bitmap.
p2: Siêu dữ liệu nhà xuất bản là các thuộc tính (thông tin) mô tả tài liệu PUB. Chúng là các thuộc tính tiêu chuẩn như nhà xuất bản, tiêu đề, tác giả cuối cùng, tổ chức, URL, ngôn ngữ và các thông tin tương tự khác. Ngoài ra còn có dữ liệu được tạo tự động sau khi làm việc với tệp như kích thước của tệp hoặc lần chỉnh sửa cuối cùng. Thông tin hữu ích này được lưu trữ cùng với tài liệu.
p3: Cùng với chức năng Đọc và Chuyển đổi, giải pháp PUB API này cho .NET cho phép bạn chỉnh sửa siêu dữ liệu chuẩn bằng các lớp DocSummaryInfo và SummaryInfo như được hiển thị trong mẫu mã sau. Bạn cũng có thể sử dụng API để tạo ứng dụng Trình chỉnh sửa siêu dữ liệu của riêng mình.
p4: 'Trước khi mã hóa Siêu dữ liệu, bạn cần tích hợp API siêu dữ liệu C # .NET PUB. Ví dụ sau đây sẽ chỉ cho bạn cách chỉnh sửa thuộc tính "Công ty".'
---

{{<section feature1>}}
---
title: Chỉnh sửa siêu dữ liệu của tệp PUB trên .NET
item1: "Quy trình đọc Siêu dữ liệu của nhà xuất bản bao gồm các bước tiếp theo:"
item2: Tải lên tệp PUB của bạn bằng [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Phương thức [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Lớp.
item3: Phân tích cú pháp tài liệu qua [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Phương thức [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Giao diện.
item4: 'Chỉnh sửa siêu dữ liệu, ví dụ: Công ty bằng [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Phương thức [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Lớp.'
---

{{<section feature2>}}
---
title: Bắt đầu với .NET PUB API
item1: Cài đặt từ dòng lệnh với tên `` nuget install Aspose.PUB '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.PUB ''.
item2: Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Mã .NET để chỉnh sửa siêu dữ liệu PUB
---