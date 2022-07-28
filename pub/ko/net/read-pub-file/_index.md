---
translation: true
template: /_templates/reader-net.md
title: PUB 파일 읽기 | .NET
description: 프로그래밍 방식으로 Publisher 파일을 엽니다. PUB 속성을 읽기 위한 사내 .NET C# API 솔루션. 이를 사용하여 프로젝트에 통합하십시오.
url: /net/read-pub-file/
metakeywords: pub 파일 .net 열기, 게시자 파일 C# 보기, 게시자 파일 읽기, C#용 게시자 뷰어, pub 형식 리더, pub 파일 오프너
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: PUB 파일 오프너
h2: PUB 파일을 읽습니다. .NET용 API로 게시자 열기
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 문서 파일 형식은 뉴스레터, 브로셔, 전단지 및 엽서와 같은 다양한 발행물 유형을 만드는 데 사용되며 전자 메일 및 웹 사이트에 사용됩니다. Pub 파일에는 텍스트, 테이블, 비트맵 및 벡터 그래픽 데이터가 포함됩니다.
p2: 형식이 꽤 인기가 있지만 PDF 또는 DOCX와 같은 형식만큼 대중적이지는 않습니다. MS Publisher 응용 프로그램 자체는 무료가 아닙니다.
p3: 따라서 때때로 이 프로그램 없이 PUB 파일을 열어야 합니다. 프레젠테이션이나 리뷰가 있을 때와 같이 문서를 편집하거나 다른 방식으로 조작하지 않고 문서의 내용을 표시하려는 경우에 필요합니다. 이러한 목적으로 크로스 플랫폼 PUB 뷰어 응용 프로그램을 사용할 수 있습니다.
p4: 여기에서 크기, 너비, 높이, 사용된 글꼴 이름, 필드 수 및 색상과 같은 MS Publisher 문서의 속성을 볼 수 있는 .NET API 솔루션을 얻을 수 있습니다.
---

{{<section feature1>}}
---
title: .NET에서 게시자 파일 읽기
item1: ".pub 파일 속성을 보려면 다음 단계를 수행해야 합니다."
item2: 단일 페이지 문서뿐만 아니라 다중 페이지 .pub 파일도 지원하는 .NET PUB API를 통합합니다.
item3: '[*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory//methods/createparser/index) 메서드를 사용하여 PUB 파일을 업로드합니다. [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) 클래스.'
item4: '[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser//methods/parse) 메서드를 통해 문서를 구문 분석합니다. [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) 인터페이스.'
item5: 문서 [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties)를 인쇄합니다.
---

{{<section feature2>}}
---
title: .NET PUB API 시작하기
item1: "제품을 설치하는 방법에는 두 가지가 있습니다."
item2: 명령줄에서 ```nuget install Aspose.PUB```로 설치하거나 ```Install-Package Aspose.PUB```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.
item3: 또는 [다운로드](https://releases.aspose.com/pub/net/)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
---

{{<section codeexample>}}
---
title: PUB 파일 속성을 읽는 .NET 코드
---

{{<section summary>}}
---
item1: 전체 코드 ReadPubDocument.cs 예제를 보려면 Aspose.PUB 설명서의 net-examples에서 Aspose.PUB.Examples.sln 솔루션으로 이동하십시오. 여기에서 라이브러리 사용 방법에 대한 다른 예제도 찾을 수 있습니다.
---