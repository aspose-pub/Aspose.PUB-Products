---
translation: true
template: /_templates/metadata-cpp.md
title: Επεξεργασία εκδότη | Μεταδεδομένα PUB | C++
description: Διαβάστε τα Μεταδεδομένα του Publisher χρησιμοποιώντας τη Λύση API PUB C++. Το Native C++ API σάς δίνει πρόσβαση στις ιδιότητες SummaryInfo και DocSummaryInfo.
url: /cpp/metadata/pub/
metakeywords: επεξεργασία μεταδεδομένων pub, μεταδεδομένα αρχείου pub, επεξεργασία μεταδεδομένων εκδότη, ανάγνωση μεταδεδομένων αρχείου pub, ανάγνωση μεταδεδομένων pub
family: pub
platformtag: cpp
feature: metadata
aliases: /cpp/μεταδεδομένα/
---

{{<section banner>}}
---
h1: Επεξεργασία μεταδεδομένων PUB
h2: Διαβάστε το αρχείο MS Publisher. API επεξεργασίας PUB Metatada για C++
---

{{<section overview>}}
---
p1: Η μορφή αρχείου εγγράφου του Microsoft<sup>®</sup> Publisher χρησιμοποιείται για τη δημιουργία διαφόρων τύπων δημοσιεύσεων, όπως ενημερωτικά δελτία, φυλλάδια, φυλλάδια και καρτ ποστάλ και χρησιμοποιείται σε μηνύματα ηλεκτρονικού ταχυδρομείου και ιστότοπους. Τα αρχεία Pub περιέχουν κείμενο καθώς και δεδομένα bitmap και διανυσματικών γραφικών.
p2: Τα μεταδεδομένα του εκδότη είναι ιδιότητες (πληροφορίες) που περιγράφουν έγγραφα PUB. Είναι τυπικές ιδιότητες όπως εκδότης, τίτλος, τελευταίος συγγραφέας, οργανισμός, διεύθυνση URL, γλώσσα και άλλες παρόμοιες πληροφορίες. Υπάρχουν επίσης δεδομένα που δημιουργούνται αυτόματα μετά την εργασία με ένα αρχείο όπως το μέγεθός του ή τον τελευταίο χρόνο επεξεργασίας. Αυτές οι χρήσιμες πληροφορίες αποθηκεύονται μαζί με το έγγραφο.
p3: Μαζί με τη λειτουργία Conversion and Reading, αυτή η λύση PUB API για C++ σάς επιτρέπει να επεξεργάζεστε τυπικά μεταδεδομένα μέσω των κλάσεων DocSummaryInfo και SummaryInfo, όπως φαίνεται στο ακόλουθο δείγμα κώδικα. Μπορείτε επίσης να χρησιμοποιήσετε το API για να δημιουργήσετε τη δική σας εφαρμογή επεξεργασίας μεταδεδομένων.
p4: Πριν κωδικοποιήσετε τα Μεταδεδομένα, πρέπει να ενσωματώσετε το C++ PUB Metadata API. Το ακόλουθο παράδειγμα θα σας δείξει πώς να επεξεργαστείτε την ιδιότητα "Κατηγορία".
---

{{<section feature1>}}
---
title: Προβολή και επεξεργασία μεταδεδομένων PUB σε C++
item1: "Η διαδικασία ανάγνωσης μεταδεδομένων εκδότη αποτελείται από τα ακόλουθα βήματα:"
item2: Ανεβάστε το αρχείο PUB χρησιμοποιώντας [*CreateParser*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.pub_factory#a88c04c4c35d45ee8febc7e1554d03c4b) Μέθοδος [*]apireference(s) .aspose.com/pub/cpp/class/aspose.pub.pub_factory) Τάξη.
item3: Ανάλυση αρχείου μέσω [*Parse*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.i_pub_parser#ae9fc7043f382a5b4a7b694f0fe477915) Μέθοδος [*IPubParse. .com/pub/cpp/class/aspose.pub.i_pub_parser) Διεπαφή.
item4: Επεξεργασία μεταδεδομένων π.χ. Κατηγορία μέσω του [*SetCategory*()](https://reference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info#a2e023fe8e8ecd0bf03bb6c9d561f8fec9d561f8fec9d561f8fec./apireference.aspose.com/pub/cpp/class/aspose.pub.doc_summary_info) Τάξη.
---

{{<section feature2>}}
---
title: Ξεκινήστε με το CPP PUB API
item1: Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.PUB.cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.PUB.cpp``.
item2: Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/pub/cpp).
---

{{<section codeexample>}}
---
title: Κωδικός C++ για τροποποίηση μεταδεδομένων PUB
---
