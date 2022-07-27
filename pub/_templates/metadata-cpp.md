---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: pub
platformtag: cpp
feature: metadata
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}" >}}

{{% blocks/products/pf/feature-page-summary %}}

<p>{{i18n.overview.p1}}</p>
<p>{{i18n.overview.p2}}</p>
<p>{{i18n.overview.p3}}</p>
<p>{{i18n.overview.p4}}</p>

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature1.title}}" %}}
{{i18n.feature1.item1}}
1. {{i18n.feature1.item2}}
1. {{i18n.feature1.item3}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature2.title}}" %}}
1. {{i18n.feature2.item1}}
1. {{i18n.feature2.item2}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="{{i18n.codeexample.title}}" gistPath="" %}}

{{< gist "aspose-com-gists" "99e290ed0fa58bf6f54311d264b397ed" "update-pub-metadata.cpp" >}}

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.tabTitle">}}" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name1">}}" href="https://docs.aspose.com/pub/cpp/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name2">}}" href="https://github.com/aspose-pub/Aspose.PUB-for-C" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name3">}}" href="https://reference.aspose.com/cpp/pub" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="support.tabTitle">}}" tabId="support" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name1">}}" href="https://forum.aspose.com/c/pub" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name2">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name3">}}" href="https://blog.aspose.com/category/pub/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/pub/cpp/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="why.tabTitle">}}" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name1">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name2">}}" href="https://blog.aspose.com/category/pub/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/pub/cpp" pricingInformationLink="https://purchase.aspose.com/pricing/pub/cpp" >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}