---
translation: true
template: /_templates/metadata-java.md
title: 出版社を編集| PUBメタデータ| Java
description: クロスプラットフォームのPUBJavaAPIソリューションを使用して、パブリッシャーファイルのメタデータを読み取ります。オンプレミスのJavaAPIを使用すると、SummaryInfoプロパティとDocSummaryInfoプロパティにアクセスできます。
url: /java/metadata/pub/
metakeywords: pubメタデータjava、pubファイルメタデータjava、パブリッシャーメタデータエディターjava、pubファイルメタデータjavaの読み取り、pubメタデータjavaの読み取りを編集します。
family: pub
platformtag: java
feature: metadata
aliases: / java / metadata /
---

{{<section banner>}}
---
h1: PUBメタデータの編集
h2: MSPublisherファイルを読み取ります。 Java用のPUBMetatadaエディターAPI
---

{{<section overview>}}
---
p1: Microsoft<sup>®</sup>Publisherドキュメントファイル形式は、ニュースレター、パンフレット、チラシ、はがきなどのさまざまな種類の出版物を作成するために使用され、電子メールやWebサイトで使用されます。 Pubファイルには、テキストだけでなく、ビットマップおよびベクターグラフィックデータも含まれています。
p2: パブリッシャーメタデータは、PUBドキュメントを説明するプロパティ（情報）です。これらは、発行者、タイトル、最終著者、組織、URL、言語、およびその他の同様の情報などの標準プロパティです。サイズや最終編集時間など、ファイルを操作した後に自動的に生成されるデータもあります。この有用な情報は、ドキュメントと一緒に保存されます。
p3: 次のコードサンプルに示すように、変換および読み取り機能に加えて、このJava用PUB APIソリューションでは、DocSummaryInfoクラスとSummaryInfoクラスを使用して標準メタデータを編集できます。 APIを使用して、独自のメタデータエディタアプリケーションを作成することもできます。
p4: メタデータをコーディングする前に、JavaPUBメタデータAPIを統合する必要があります。次の例は、「Language」プロパティを編集する方法を示しています。
---

{{<section widget>}}
---
title: Javaを使用してPUBメタデータを編集する方法
item1: "PUBメタデータを編集するには、機能が豊富で強力で使いやすい変換である [Aspose.PUB for Java API](https://products.aspose.com/pub/java/)を使用します。 Javaプラットフォーム用のAPI。最新バージョンは [Maven](https://repository.aspose.com/pub/) から直接ダウンロードして、Mavenにインストールできます。次の構成をpom.xmlに追加することによるベースのプロジェクト。"
---

{{<section feature1>}}
---
title: JavaでのPUBメタデータの表示と編集
item1: "パブリッシャーのメタデータ読み取りプロセスは、次のステップで構成されます。"
item2: '[*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) メソッド[*PubFactory*](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory)クラス。'
item3: '経由でファイルを解析する[*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--)のメソッド[*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser)インターフェース。'
item4: '[*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-）メソッド[*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo）クラス。'
---

{{<section feature2>}}
---
title: システム要求
item1: Aspose.PUB for Javaは、すべての主要なオペレーティングシステムでサポートされています。次の前提条件があることを確認してください。
item2: J2SE 8.0（1.8）以降。
---

{{<section codeexample>}}
---
title: PUBメタデータを更新するJavaコード
---