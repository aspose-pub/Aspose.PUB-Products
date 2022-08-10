---
translation: true
template: /_templates/metadata-net.md
title: 出版社を編集| PUBメタデータ| .NET
description: クロスプラットフォームのPUB.NETAPIソリューションを使用して、パブリッシャーファイルのメタデータを読み取ります。オンプレミスの.NETAPIを使用すると、SummaryInfoプロパティとDocSummaryInfoプロパティにアクセスできます。
url: /net/metadata/pub/
metakeywords: パブメタデータネットの編集、パブファイルメタデータC＃、パブリッシャーメタデータエディター.net、パブファイルメタデータC＃の読み取り、パブメタデータ.netの読み取り
family: pub
platformtag: net
feature: metadata
aliases: / net / metadata /
---

{{<section banner>}}
---
h1: PUBメタデータの編集
h2: MSPublisherファイルを読み取ります。 .NET用のPUBMetatadaエディターAPI
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup>Publisherドキュメントファイル形式は、ニュースレター、パンフレット、チラシ、はがきなどのさまざまな種類の出版物を作成するために使用され、電子メールやWebサイトで使用されます。 Pubファイルには、テキストだけでなく、ビットマップおよびベクターグラフィックデータも含まれています。
p2: パブリッシャーメタデータは、PUBドキュメントを説明するプロパティ（情報）です。これらは、発行者、タイトル、最終著者、組織、URL、言語、およびその他の同様の情報などの標準プロパティです。サイズや最終編集時間など、ファイルを操作した後に自動的に生成されるデータもあります。この有用な情報は、ドキュメントと一緒に保存されます。
p3: 変換および読み取り機能に加えて、この.NET用PUB APIソリューションでは、次のコードサンプルに示すように、DocSummaryInfoクラスとSummaryInfoクラスを使用して標準メタデータを編集できます。 APIを使用して、独自のメタデータエディタアプリケーションを作成することもできます。
p4: メタデータをコーディングする前に、C＃.NETPUBメタデータAPIを統合する必要があります。次の例は、「Company」プロパティを編集する方法を示しています。
---

{{<section feature1>}}
---
title: .NET上のPUBファイルのメタデータを編集する
item1: "パブリッシャーのメタデータ読み取りプロセスは、次のステップで構成されます。"
item2: '[*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/createparser/) メソッド[*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/)クラス。'
item3: '[*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/parse/) [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) インターフェース。'
item4: '[*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/setcompany/) [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/) クラス。'
---

{{<section feature2>}}
---
title: .NETPUBAPIの使用を開始する
item1: コマンドラインから```nuget install Aspose.PUB```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから```Install-PackageAspose.PUB```を使用してインストールします。
item2: または、[ダウンロード](https://releases.aspose.com/pub/net/) からオフラインMSIインストーラーまたはDLLをZIPファイルで取得します。
---

{{<section codeexample>}}
---
title: PUBメタデータを編集するための.NETコード
---