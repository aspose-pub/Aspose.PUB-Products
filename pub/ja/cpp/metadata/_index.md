---
translation: true
template: /_templates/metadata-cpp.md
title: 出版社を編集| PUBメタデータ| C ++
description: PUB C++APIソリューションを使用してパブリッシャーファイルのメタデータを読み取ります。オンプレミスのC++APIを使用すると、SummaryInfoプロパティとDocSummaryInfoプロパティにアクセスできます。
url: /cpp/metadata/pub/
metakeywords: パブメタデータの編集、パブファイルメタデータ、パブリッシャーメタデータエディター、パブファイルメタデータの読み取り、パブメタデータの読み取り
family: pub
platformtag: cpp
feature: metadata
aliases: / cpp / metadata /
---

{{<section banner>}}
---
h1: PUBメタデータの編集
h2: MSPublisherファイルを読み取ります。 C++用のPUBMetatadaエディターAPI
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup>Publisherドキュメントファイル形式は、ニュースレター、パンフレット、チラシ、はがきなどのさまざまな種類の出版物を作成するために使用され、電子メールやWebサイトで使用されます。 Pubファイルには、テキストだけでなく、ビットマップおよびベクターグラフィックデータも含まれています。
p2: パブリッシャーメタデータは、PUBドキュメントを説明するプロパティ（情報）です。これらは、発行者、タイトル、最終著者、組織、URL、言語、およびその他の同様の情報などの標準プロパティです。サイズや最終編集時間など、ファイルを操作した後に自動的に生成されるデータもあります。この有用な情報は、ドキュメントと一緒に保存されます。
p3: 次のコードサンプルに示すように、変換および読み取り機能に加えて、C++用のこのPUBAPIソリューションを使用すると、DocSummaryInfoクラスとSummaryInfoクラスを使用して標準メタデータを編集できます。 APIを使用して、独自のメタデータエディタアプリケーションを作成することもできます。
p4: メタデータをコーディングする前に、C++PUBメタデータAPIを統合する必要があります。次の例は、「Category」プロパティを編集する方法を示しています。
---

{{<section feature1>}}
---
title: C++でのPUBメタデータの表示と編集
item1: "パブリッシャーのメタデータ読み取りプロセスは、次のステップで構成されます。"
item2: '[*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) メソッド[*PubFactory*](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory) クラス。'
item3: '[*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) を介してファイルを解析する [*IPubParser*](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser) インターフェース。'
item4: '[*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec）メソッド[*DocSummaryInfo*](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) クラス。'
---

{{<section feature2>}}
---
title: CPP PUB APIの使用を開始する
item1: コマンドラインから```nuget install Aspose.PUB.cpp```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.PUB.cpp```を使用してインストールします。
item2: または、[downloads](https://releases.aspose.com/pub/cpp/)からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
---

{{<section codeexample>}}
---
title: PUBメタデータを変更するC++コード
---
