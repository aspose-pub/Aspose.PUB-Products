---
translation: true
template: /_templates/metadata-cpp.md
title: 게시자 편집 | PUB 메타데이터 | C++
description: PUB C++ API 솔루션을 사용하여 게시자 파일 메타데이터를 읽습니다. 온프레미스 C++ API를 사용하면 SummaryInfo 및 DocSummaryInfo 속성에 액세스할 수 있습니다.
url: /cpp/metadata/pub/
metakeywords: pub 메타데이터 편집, pub 파일 메타데이터, 게시자 메타데이터 편집기, pub 파일 메타데이터 읽기, pub 메타데이터 읽기
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/메타데이터/
---

{{<section banner>}}
---
h1: PUB 메타데이터 편집
h2: MS 게시자 파일을 읽습니다. C++용 PUB Metatada 편집기 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 문서 파일 형식은 뉴스레터, 브로셔, 전단지 및 엽서와 같은 다양한 발행물 유형을 만드는 데 사용되며 전자 메일 및 웹 사이트에 사용됩니다. Pub 파일에는 텍스트와 비트맵 및 벡터 그래픽 데이터가 포함되어 있습니다.
p2: 퍼블리셔 메타데이터는 PUB 문서를 기술하는 속성(정보)이다. 게시자, 제목, 마지막 작성자, 조직, URL, 언어 및 기타 유사한 정보와 같은 표준 속성입니다. 파일의 크기나 마지막 편집 시간과 같이 파일 작업 후 자동으로 생성되는 데이터도 있습니다. 이 유용한 정보는 문서와 함께 저장됩니다.
p3: 변환 및 읽기 기능과 함께 이 C++용 PUB API 솔루션을 사용하면 다음 코드 샘플과 같이 DocSummaryInfo 및 SummaryInfo 클래스를 통해 표준 메타데이터를 편집할 수 있습니다. API를 사용하여 자신만의 메타데이터 편집기 응용 프로그램을 만들 수도 있습니다.
p4: Metadata를 코딩하기 전에 C++ PUB Metadata API를 통합해야 합니다. 다음 예는 "Category" 속성을 편집하는 방법을 보여줍니다.
---

{{<section feature1>}}
---
title: C++에서 PUB 메타데이터 보기 및 편집
item1: "게시자 메타데이터 읽기 프로세스는 다음 단계로 구성됩니다."
item2: '[*CreateParser*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) 메서드를 사용하여 PUB 파일을 업로드합니다. [*PubFactory*](https://apireference) .aspose.com/pub/cpp/class/aspose.pub.pub_factory) 클래스.'
item3: '[*Parse*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915)를 통한 파일 구문 분석 [*IPubParser*](https://apireference.aspose) 메서드 .com/pub/cpp/class/aspose.pub.i_pub_parser) 인터페이스.'
item4: '[*SetCategory*()](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec) 메서드를 통해 메타데이터(예: 카테고리) 편집 [*DocSummaryInfo*](https://apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) 클래스.'
---

{{<section feature2>}}
---
title: CPP PUB API 시작하기
item1: 명령줄에서 ```nuget install Aspose.PUB.cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.PUB.cpp```로 설치합니다.
item2: 또는 [downloads](https://downloads.aspose.com/pub/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
---

{{<section codeexample>}}
---
title: PUB 메타데이터를 수정하는 C++ 코드
---
