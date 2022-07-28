---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: pub
platformtag: net
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
1. {{i18n.feature1.item4}}
1. {{i18n.feature1.item5}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="{{i18n.feature2.title}}" %}}
{{i18n.feature2.item1}}
1. {{i18n.feature2.item2}}
1. {{i18n.feature2.item3}}
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="{{i18n.codeexample.title}}" gistPath="" %}}

{{< highlight csharp >}}
    // Load PUB file
    var parser = PubFactory.CreateParser("sample.pub");
    // Parse file 
    var doc = parser.Parse();
    // Print document properties
    Console.WriteLine($"Page width: {GetInchesString(doc.Width)}");            
    Console.WriteLine($"Page height: {GetInchesString(doc.Height)}");
    Console.WriteLine($"Field count: {doc.FieldCount}");
    string fontNames = GetCollectionString(doc.FontNames);
    if (!string.IsNullOrEmpty(fontNames))
    {
        Console.WriteLine($"Fonts used in document: {fontNames}");
    }
    string colors = GetCollectionString(doc.Colors);
    if (!string.IsNullOrEmpty(colors))
    {
        Console.WriteLine($"Colors used in document: {colors}");
    }
{{< /highlight >}} 

{{i18n.summary.item1}}
 
{{< highlight csharp >}}
    // Description of invoked methods:
    
        private string GetInchesString(uint size)
        {
            double value = (double)size / EMUsesInOneInch;
            return Convert.ToString(value) + " inches";
        }

        private string GetCollectionString(ICollection array)
        {
            if (array.Count == 0)
            {
                return null;
            }

            StringBuilder sb = new StringBuilder();
            int num = -1;
            IEnumerator enumerator = array.GetEnumerator();

            while (enumerator.MoveNext())
            {
                num++;
                sb.Append(GetObjectStirng(enumerator.Current));
                if (num < (array.Count - 1))
                {
                    sb.Append(", ");
                }
            }

            return sb.ToString();
        }

        private string GetObjectStirng(object value)
        {
            if (value is Color)
            {
                Color colorVal = (Color)value;
                return $"RGB({colorVal.R}, {colorVal.G}, {colorVal.B})"; 
            }

            return value.ToString();
        }
{{< /highlight >}} 

{{% /blocks/products/pf/agp/code-autogen %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.tabTitle">}}" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name1">}}" href="https://docs.aspose.com/pub/net/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name2">}}" href="https://github.com/aspose-pub/Aspose.PUB-for-.NET/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="learningresources.name3">}}" href="https://reference.aspose.com/pub/net//" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="support.tabTitle">}}" tabId="support" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name1">}}" href="https://forum.aspose.com/c/pub/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name2">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="support.name3">}}" href="https://blog.aspose.com/category/pub/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/pub/net/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="{{<import path="/{{lang}}/partials/_content.md" section="why.tabTitle">}}" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name1">}}" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="{{<import path="/{{lang}}/partials/_content.md" section="why.name2">}}" href="https://blog.aspose.com/category/pub/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://releases.aspose.com/pub/net/" pricingInformationLink="https://purchase.aspose.com/pricing/pub/net/" >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}