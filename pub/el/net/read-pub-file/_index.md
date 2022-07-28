---
translation: true
template: /_templates/reader-net.md
title: Ανάγνωση αρχείων PUB | .NET
description: Ανοίξτε τα αρχεία του Publisher μέσω προγραμματισμού. Λύση C# .NET API για ανάγνωση ιδιοτήτων PUB. Χρησιμοποιήστε το για να ενσωματωθείτε στο έργο σας.
url: /net/read-pub-file/
metakeywords: άνοιγμα αρχείου pub .net, προβολή αρχείων εκδότη c#, ανάγνωση αρχείων εκδότη, πρόγραμμα προβολής εκδότη για c#, πρόγραμμα ανάγνωσης μορφής pub, πρόγραμμα ανοίγματος αρχείων pub
family: pub
platformtag: net
---

{{<section banner>}}
---
h1: Άνοιγμα αρχείων PUB
h2: Διαβάστε αρχεία PUB. Ανοίξτε τον Publisher με API για .NET
---

{{<section overview>}}
---
p1: Η μορφή αρχείου εγγράφου του Microsoft<sup>®</sup> Publisher χρησιμοποιείται για τη δημιουργία διαφόρων τύπων δημοσιεύσεων, όπως ενημερωτικά δελτία, φυλλάδια, φυλλάδια και καρτ ποστάλ και χρησιμοποιείται σε μηνύματα ηλεκτρονικού ταχυδρομείου και ιστότοπους. Τα αρχεία Pub περιέχουν κείμενο, πίνακες καθώς και δεδομένα bitmap και διανυσματικών γραφικών.
p2: Παρόλο που η μορφή είναι αρκετά δημοφιλής, δεν είναι τόσο δημοφιλής όσο μορφές όπως το PDF ή το DOCX. Η εφαρμογή MS Publisher δεν είναι η ίδια δωρεάν.
p3: Έτσι, μερικές φορές απαιτείται να ανοίξετε αρχεία PUB χωρίς αυτό το πρόγραμμα. Αυτό απαιτείται όταν θέλετε να εμφανίσετε το περιεχόμενο του εγγράφου, χωρίς να το επεξεργαστείτε ή να το χειριστείτε με άλλο τρόπο, όπως όταν έχετε μια παρουσίαση ή κριτική. Για τέτοιους σκοπούς, μπορείτε να χρησιμοποιήσετε μια εφαρμογή PUB Viewer μεταξύ πλατφορμών.
p4: Εδώ θα λάβετε τη Λύση .NET API που σας επιτρέπει να προβάλετε τις ιδιότητες του εγγράφου MS Publisher, όπως το μέγεθος, το πλάτος, το ύψος, τα ονόματα των γραμματοσειρών που χρησιμοποιούνται, τον αριθμό των πεδίων και τα χρώματα.
---

{{<section feature1>}}
---
title: Διαβάστε τα αρχεία του Publisher στο .NET
item1: "Για να προβάλετε τις ιδιότητες των αρχείων .pub θα χρειαστεί να ακολουθήσετε τα ακόλουθα βήματα:"
item2: Ενσωματώστε το .NET PUB API, το οποίο λειτουργεί όχι μόνο με έγγραφα μιας σελίδας, αλλά υποστηρίζει επίσης πολυσέλιδα αρχεία .pub.
item3: Ανεβάστε το αρχείο PUB χρησιμοποιώντας [*CreateParser*()](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/methods/createparser/index) Μέθοδο του [*PubFactory*](https://reference.aspose.com/pub/net/aspose.pub/pubfactory/) Τάξη.
item4: Αναλύστε το έγγραφο μέσω [*Parse*()](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/methods/parse) Μέθοδος [*IPubParser*](https://reference.aspose.com/pub/net/aspose.pub/ipubparser/) Διεπαφή.
item5: Εκτυπώστε το έγγραφο [*properties*](https://reference.aspose.com/pub/net/aspose.pub/document/#properties).
---

{{<section feature2>}}
---
title: Ξεκινήστε με το .NET PUB API
item1: "Υπάρχουν δύο τρόποι για να εγκαταστήσετε το προϊόν:"
item2: Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.PUB``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.PUB``.
item3: Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/pub/net/).
---

{{<section codeexample>}}
---
title: Κωδικός .NET για ανάγνωση ιδιοτήτων αρχείων PUB
---

{{<section summary>}}
---
item1: Για να δείτε το παράδειγμα του πλήρους κώδικα ReadPubDocument.cs, μεταβείτε στη λύση Aspose.PUB.Examples.sln, στα net-παραδείγματα της Τεκμηρίωσης Aspose.PUB όπου μπορείτε επίσης να βρείτε άλλα παραδείγματα σχετικά με τον τρόπο χρήσης της βιβλιοθήκης.
---