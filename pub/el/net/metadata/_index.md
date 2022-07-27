---
translation: true
template: /_templates/metadata-net.md
title: Επεξεργασία εκδότη | Μεταδεδομένα PUB | .NET
description: Διαβάστε τα Μεταδεδομένα των αρχείων Publisher χρησιμοποιώντας τη λύση PUB .NET API μεταξύ πλατφορμών. Το On-premise .NET API σάς δίνει πρόσβαση στις ιδιότητες SummaryInfo και DocSummaryInfo.
url: /net/metadata/pub/
metakeywords: επεξεργασία μεταδεδομένων pub, μεταδεδομένα αρχείου pub C#, επεξεργαστής μεταδεδομένων εκδότη .net, ανάγνωση μεταδεδομένων αρχείου pub C#, ανάγνωση μεταδεδομένων pub .net
family: pub
platformtag: net
feature: metadata
aliases: /net/metadata/
---

{{<section banner>}}
---
h1: Επεξεργασία μεταδεδομένων PUB
h2: Διαβάστε το αρχείο MS Publisher. API επεξεργασίας PUB Metatada για .NET
---

{{<section overview>}}
---
p1: Η μορφή αρχείου εγγράφου του Microsoft<sup>®</sup> Publisher χρησιμοποιείται για τη δημιουργία διαφόρων τύπων δημοσιεύσεων, όπως ενημερωτικά δελτία, φυλλάδια, φυλλάδια και καρτ ποστάλ και χρησιμοποιείται σε μηνύματα ηλεκτρονικού ταχυδρομείου και ιστότοπους. Τα αρχεία Pub περιέχουν κείμενο καθώς και δεδομένα bitmap και διανυσματικών γραφικών.
p2: Τα μεταδεδομένα του εκδότη είναι ιδιότητες (πληροφορίες) που περιγράφουν έγγραφα PUB. Είναι τυπικές ιδιότητες όπως εκδότης, τίτλος, τελευταίος συγγραφέας, οργανισμός, διεύθυνση URL, γλώσσα και άλλες παρόμοιες πληροφορίες. Υπάρχουν επίσης δεδομένα που δημιουργούνται αυτόματα μετά την εργασία με ένα αρχείο όπως το μέγεθός του ή τον τελευταίο χρόνο επεξεργασίας. Αυτές οι χρήσιμες πληροφορίες αποθηκεύονται μαζί με το έγγραφο.
p3: Μαζί με τη λειτουργία Conversion and Reading, αυτή η λύση PUB API για .NET σάς επιτρέπει να επεξεργάζεστε τυπικά μεταδεδομένα μέσω των κλάσεων DocSummaryInfo και SummaryInfo, όπως φαίνεται στο ακόλουθο δείγμα κώδικα. Μπορείτε επίσης να χρησιμοποιήσετε το API για να δημιουργήσετε τη δική σας εφαρμογή επεξεργασίας μεταδεδομένων.
p4: Πριν κωδικοποιήσετε τα Μεταδεδομένα, πρέπει να ενσωματώσετε το C# .NET PUB Metadata API. Το ακόλουθο παράδειγμα θα σας δείξει πώς να επεξεργαστείτε την ιδιότητα "Εταιρεία".
---

{{<section feature1>}}
---
title: Επεξεργασία μεταδεδομένων αρχείων PUB στο .NET
item1: "Η διαδικασία ανάγνωσης μεταδεδομένων εκδότη αποτελείται από τα ακόλουθα βήματα:"
item2: Ανεβάστε το αρχείο PUB χρησιμοποιώντας [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Μέθοδο του [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory) Τάξη.
item3: Αναλύστε το έγγραφο μέσω [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Μέθοδος [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser) Διεπαφή.
item4: Επεξεργασία μεταδεδομένων π.χ. Εταιρεία μέσω του [*SetCompany*()](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo/methods/setcompany) Μέθοδος [*DocSummaryInfo*](https://reference.aspose.com/pub/net/aspose.pub/docsummaryinfo) Τάξη.
---

{{<section feature2>}}
---
title: Ξεκινήστε με το .NET PUB API
item1: Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.PUB``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.PUB``.
item2: Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/pub/net).
---

{{<section codeexample>}}
---
title: Κωδικός .NET για επεξεργασία μεταδεδομένων PUB
---