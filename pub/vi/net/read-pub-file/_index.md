---
translation: true
template: /_templates/reader-net.md
title: Đọc tệp PUB | .NET
description: Mở tệp Nhà xuất bản theo lập trình. Giải pháp API C# .NET để đọc thuộc tính PUB. Sử dụng nó để tích hợp vào dự án của bạn.
url: /net/read-pub-file/
metakeywords: mở tệp pub .net, xem các tệp của nhà xuất bản c#, đọc tệp của nhà xuất bản, trình xem của nhà xuất bản cho c#, trình đọc định dạng pub, trình mở tệp pub
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: Công cụ mở tệp PUB
h2: Đọc tệp PUB. Mở nhà xuất bản với API cho .NET
---

{{<section overview>}}
---
p1: Microsoft <sup> ® </sup> Định dạng tệp tài liệu dành cho nhà xuất bản được sử dụng để tạo các loại ấn phẩm khác nhau như bản tin, tài liệu quảng cáo, tờ rơi và bưu thiếp và được sử dụng trong Email và Trang web. Tệp Pub chứa văn bản, bảng cũng như dữ liệu đồ họa vector và bitmap.
p2: Mặc dù định dạng này khá phổ biến nhưng nó không phổ biến bằng các định dạng như PDF hoặc DOCX. Bản thân ứng dụng MS Publisher không miễn phí.
p3: Vì vậy, đôi khi bắt buộc phải mở các tệp PUB mà không cần chương trình này. Điều này là cần thiết khi bạn muốn hiển thị nội dung của tài liệu mà không cần chỉnh sửa hoặc thao tác theo bất kỳ cách nào khác, như khi bạn có một bản trình bày hoặc đánh giá. Với những mục đích như vậy, bạn có thể sử dụng ứng dụng PUB Viewer đa nền tảng.
p4: Tại đây, bạn sẽ nhận được Giải pháp API .NET cho phép bạn xem các thuộc tính của tài liệu MS Publisher như kích thước, chiều rộng, chiều cao, tên của các phông chữ được sử dụng, số lượng trường và màu sắc.
---

{{<section feature1>}}
---
title: Đọc tệp nhà xuất bản trên .NET
item1: "Để xem thuộc tính tệp .pub, bạn sẽ cần thực hiện các bước tiếp theo:"
item2: Tích hợp .NET PUB API, không chỉ hoạt động với các tài liệu một trang mà còn hỗ trợ các tệp .pub nhiều trang.
item3: Tải lên tệp PUB của bạn bằng [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Phương thức [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Lớp.
item4: Phân tích cú pháp tài liệu qua [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Phương thức [*IPubParser*](https://hamkhảo.aspose.com/pub/net/aspose.pub/ipubparser) Giao diện.
item5: In tài liệu [*thuộc tính*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Bắt đầu với .NET PUB API
item1: "Có hai cách để cài đặt sản phẩm:"
item2: Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.PUB '' hoặc thông qua Package Manager Console của Visual Studio với `` Install-Package Aspose.PUB ''.
item3: Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: .NET Mã để đọc thuộc tính tệp PUB
---

{{<section summary>}}
---
item1: Để xem mã đầy đủ, ví dụ ReadPubDocument.cs, hãy truy cập giải pháp Aspose.PUB.Examples.sln, trong các ví dụ mạng của Tài liệu Aspose.PUB, nơi bạn cũng có thể tìm thấy các ví dụ khác về cách sử dụng thư viện.
---