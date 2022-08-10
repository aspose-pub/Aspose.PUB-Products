---
translation: true
template: /_templates/conversion.md
title: PUB 변환기 API 솔루션 | C++
url: /cpp/conversion/
description: C++ 라이브러리를 통해 프로그래밍 방식으로 Microsoft Publisher 파일을 변환합니다. 나만의 PUB 변환기 C++ 프로젝트를 구축하는 간단한 API 솔루션입니다.
metakeywords: pub cpp 변환기, pub 파일 cpp 변환
family: pub
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PUB 파일 변환
h2: 크로스 플랫폼 C++ 애플리케이션을 구축하기 위한 게시자 변환기 기능.
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup> Publisher 문서 파일 형식은 뉴스레터, 브로셔, 전단지 및 엽서와 같은 다양한 발행물 유형을 만드는 데 사용되며 전자 메일 및 웹 사이트에 사용됩니다. Pub 파일에는 텍스트와 비트맵 및 벡터 그래픽 데이터가 포함되어 있습니다.
p2: 형식이 꽤 인기가 있지만 PDF 또는 DOCX와 같은 형식만큼 대중적이지는 않습니다. MS Publisher 응용 프로그램 자체는 무료가 아닙니다. 따라서 확장자가 .pub인 파일을 널리 보급되고 사용하기 쉬운 다른 형식으로 변환해야 하는 경우가 많습니다. 다음은 C++의 변환 기능입니다. 이 라이브러리에는 자신의 프로젝트를 만드는 데 사용할 수 있는 필요한 변환 기능이 포함되어 있습니다.
---

{{<section feature1>}}
---
title: Publisher .pub 파일 변환
item1: PUB에서 PDF로 변환을 통한 기능을 살펴보겠습니다.
item2: "게시자 전환 프로세스는 다음 단계로 구성됩니다."
item3: C++ PUB를 단일 페이지 문서뿐만 아니라 다중 페이지 .pub 파일도 지원하는 PDF 변환기 API에 통합합니다.
item4: '[*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) 클래스를 사용하여 PUB 파일을 로드합니다.'
item5: '[*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) 메서드를 통해 Parser 및 Parse 생성 /apireference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) 인터페이스.'
item6: '[*ConvertToPdf*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pdf_converter) 메서드를 사용하여 변환을 실행합니다.'
---

{{<section codeexample>}}
---
title: 게시자 PUB를 PDF로 변환하는 C++ 코드
---

{{<section summary>}}
---
p1: 파일을 PDF 형식으로 변환한 후 PUB를 다른 형식으로 변환할 수 있으며 이 변환된 파일을 필요한 형식으로 변환할 수 있습니다.
p2: "Publisher Converter 플랫폼 간 응용 프로그램을 사용해 볼 수도 있습니다. 그것은 매우 간단한 인터페이스를 가지고 있으며 프로세스는 몇 초 밖에 걸리지 않습니다. 이 솔루션을 통해 다음을 수행할 수 있습니다."
p3: 여러 게시자 파일을 변환합니다.
p4: PUB를 PDF, HTML, EPUB, DOCX, SVG 및 기타 여러 이미지 형식으로 변환합니다.
p5: 변환된 문서를 장치에 저장합니다.
---