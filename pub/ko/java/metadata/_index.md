---
translation: true
template: /_templates/metadata-java.md
title: 게시자 편집 | PUB 메타데이터 | 자바
description: 크로스 플랫폼 PUB Java API 솔루션을 사용하여 게시자 파일 메타데이터를 읽습니다. 사내 Java API를 사용하면 SummaryInfo 및 DocSummaryInfo 속성에 액세스할 수 있습니다.
url: /java/metadata/pub/
metakeywords: pub 메타데이터 편집 java, pub 파일 메타데이터 java, 게시자 메타데이터 편집기 java, pub 파일 메타데이터 읽기 읽기, pub 메타데이터 java 읽기
family: pub
platformtag: java
feature: metadata
aliases: /자바/메타데이터/
---

{{<section banner>}}
---
h1: PUB 메타데이터 편집
h2: MS 게시자 파일을 읽습니다. Java용 PUB Metatada 편집기 API
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 문서 파일 형식은 뉴스레터, 브로셔, 전단지 및 엽서와 같은 다양한 발행물 유형을 만드는 데 사용되며 전자 메일 및 웹 사이트에 사용됩니다. Pub 파일에는 텍스트와 비트맵 및 벡터 그래픽 데이터가 포함되어 있습니다.
p2: 퍼블리셔 메타데이터는 PUB 문서를 기술하는 속성(정보)이다. 게시자, 제목, 마지막 작성자, 조직, URL, 언어 및 기타 유사한 정보와 같은 표준 속성입니다. 파일의 크기나 마지막 편집 시간과 같이 파일 작업 후 자동으로 생성되는 데이터도 있습니다. 이 유용한 정보는 문서와 함께 저장됩니다.
p3: 변환 및 읽기 기능과 함께 이 Java용 PUB API 솔루션을 사용하면 다음 코드 샘플과 같이 DocSummaryInfo 및 SummaryInfo 클래스를 통해 표준 메타데이터를 편집할 수 있습니다. API를 사용하여 자신만의 메타데이터 편집기 응용 프로그램을 만들 수도 있습니다.
p4: Metadata를 코딩하기 전에 Java PUB Metadata API를 통합해야 합니다. 다음 예에서는 "Language" 속성을 편집하는 방법을 보여줍니다.
---

{{<section widget>}}
---
title: Java를 사용하여 PUB 메타데이터를 편집하는 방법
item1: "PUB 메타데이터를 편집하기 위해 기능이 풍부하고 강력하며 사용하기 쉬운 변환인 [Aspose.PUB for Java API](https://products.aspose.com/pub/java/)를 사용합니다. 자바 플랫폼용 API. [Maven](https://repository.aspose.com/pub/)에서 직접 최신 버전을 다운로드하여 Maven에 설치할 수 있습니다. pom.xml에 다음 구성을 추가하여 기반 프로젝트."
---

{{<section feature1>}}
---
title: Java에서 PUB 메타데이터 보기 및 편집
item1: "게시자 메타데이터 읽기 프로세스는 다음 단계로 구성됩니다."
item2: '[*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) 메서드를 사용하여 PUB 파일을 업로드합니다. ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) 클래스.'
item3: '[*IPdfConverter*](https://apireference)의 [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) 메소드를 통한 파싱 파일 .aspose.com/pub/java/com.aspose.pub/IPubParser) 인터페이스.'
item4: '[*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-)를 통해 메타데이터(예: 언어) 편집 [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) 클래스.'
---

{{<section feature2>}}
---
title: 시스템 요구 사항
item1: Java용 Aspose.PUB는 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.
item2: J2SE 8.0(1.8) 이상.
---

{{<section codeexample>}}
---
title: PUB 메타데이터를 업데이트하는 Java 코드
---