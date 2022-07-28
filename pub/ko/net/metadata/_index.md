---
translation: true
template: /_templates/metadata-net.md
title: 게시자 편집 | PUB 메타데이터 | .NET
description: 플랫폼 간 PUB .NET API 솔루션을 사용하여 게시자 파일 메타데이터를 읽습니다. 온프레미스 .NET API를 사용하면 SummaryInfo 및 DocSummaryInfo 속성에 액세스할 수 있습니다.
url: /net/metadata/pub/
metakeywords: pub 메타데이터 net 편집, pub 파일 메타데이터 C#, 게시자 메타데이터 편집기 .net, pub 파일 메타데이터 읽기 C#, pub 메타데이터 .net 읽기
family: pub
platformtag: net
feature: metadata
aliases: /net/메타데이터/
---

{{<section banner>}}
---
h1: PUB 메타데이터 편집
h2: MS 게시자 파일을 읽습니다. .NET용 PUB Metatada 편집기 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 문서 파일 형식은 뉴스레터, 브로셔, 전단지 및 엽서와 같은 다양한 발행물 유형을 만드는 데 사용되며 전자 메일 및 웹 사이트에 사용됩니다. Pub 파일에는 텍스트와 비트맵 및 벡터 그래픽 데이터가 포함되어 있습니다.
p2: 게시자 메타데이터는 PUB 문서를 설명하는 속성(정보)입니다. 게시자, 제목, 마지막 작성자, 조직, URL, 언어 및 기타 유사한 정보와 같은 표준 속성입니다. 파일의 크기나 마지막 편집 시간과 같이 파일 작업 후 자동으로 생성되는 데이터도 있습니다. 이 유용한 정보는 문서와 함께 저장됩니다.
p3: 변환 및 읽기 기능과 함께 이 .NET용 PUB API 솔루션을 사용하면 다음 코드 샘플과 같이 DocSummaryInfo 및 SummaryInfo 클래스를 통해 표준 메타데이터를 편집할 수 있습니다. API를 사용하여 자신만의 메타데이터 편집기 응용 프로그램을 만들 수도 있습니다.
p4: 메타데이터를 코딩하기 전에 C# .NET PUB Metadata API를 통합해야 합니다. 다음 예에서는 "회사" 속성을 편집하는 방법을 보여줍니다.
---

{{<section feature1>}}
---
title: .NET에서 PUB 파일의 메타데이터 편집
item1: "게시자 메타데이터 읽기 프로세스는 다음 단계로 구성됩니다."
item2: '[*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) 메서드를 사용하여 PUB 파일을 업로드합니다. [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) 클래스.'
item3: '[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) 메서드를 통해 문서를 구문 분석합니다. [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 인터페이스.'
item4: '[*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany)를 통해 메타데이터(예: 회사) 편집 [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) 클래스.'
---

{{<section feature2>}}
---
title: .NET PUB API 시작하기
item1: 명령줄에서 ```nuget install Aspose.PUB```로 설치하거나 ```Install-Package Aspose.PUB```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.
item2: 또는 [다운로드](https://releases.aspose.com/pub/net/)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
---

{{<section codeexample>}}
---
title: PUB 메타데이터를 편집하는 .NET 코드
---