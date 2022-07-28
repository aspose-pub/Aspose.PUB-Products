---
translation: true
template: /_templates/metadata-java.md
title: Επεξεργασία εκδότη | Μεταδεδομένα PUB | Ιάβα
description: Διαβάστε τα Μεταδεδομένα του Publisher χρησιμοποιώντας τη Λύση API PUB Java. Το Native Java API σάς δίνει πρόσβαση στις ιδιότητες SummaryInfo και DocSummaryInfo
url: /java/metadata/pub/
metakeywords: επεξεργασία μεταδεδομένων pub java, αρχείο pub μεταδεδομένων java, εκδότης μεταδεδομένων επεξεργασίας java, ανάγνωση αρχείου pub μεταδεδομένων java, ανάγνωση μεταδεδομένων pub java
family: pub
platformtag: java
feature: metadata
aliases: /java/metadata/
---

{{<section banner>}}
---
h1: Επεξεργασία μεταδεδομένων PUB
h2: Διαβάστε το αρχείο MS Publisher. API επεξεργασίας PUB Metatada για Java
---

{{<section overview>}}
---
p1: Η μορφή αρχείου εγγράφου του Microsoft<sup>®</sup> Publisher χρησιμοποιείται για τη δημιουργία διαφόρων τύπων δημοσιεύσεων, όπως ενημερωτικά δελτία, φυλλάδια, φυλλάδια και καρτ ποστάλ και χρησιμοποιείται σε μηνύματα ηλεκτρονικού ταχυδρομείου και ιστότοπους. Τα αρχεία Pub περιέχουν κείμενο καθώς και δεδομένα bitmap και διανυσματικών γραφικών.
p2: Τα μεταδεδομένα του εκδότη είναι ιδιότητες (πληροφορίες) που περιγράφουν έγγραφα PUB. Είναι τυπικές ιδιότητες όπως εκδότης, τίτλος, τελευταίος συγγραφέας, οργανισμός, διεύθυνση URL, γλώσσα και άλλες παρόμοιες πληροφορίες. Υπάρχουν επίσης δεδομένα που δημιουργούνται αυτόματα μετά την εργασία με ένα αρχείο όπως το μέγεθός του ή τον τελευταίο χρόνο επεξεργασίας. Αυτές οι χρήσιμες πληροφορίες αποθηκεύονται μαζί με το έγγραφο.
p3: Μαζί με τη λειτουργία Conversion and Reading, αυτή η λύση PUB API για Java σάς επιτρέπει να επεξεργάζεστε τυπικά μεταδεδομένα μέσω των κλάσεων DocSummaryInfo και SummaryInfo, όπως φαίνεται στο ακόλουθο δείγμα κώδικα. Μπορείτε επίσης να χρησιμοποιήσετε το API για να δημιουργήσετε τη δική σας εφαρμογή επεξεργασίας μεταδεδομένων.
p4: Πριν κωδικοποιήσετε τα Μεταδεδομένα, πρέπει να ενσωματώσετε το Java PUB Metadata API. Το ακόλουθο παράδειγμα θα σας δείξει πώς να επεξεργαστείτε την ιδιότητα "Γλώσσα".
---

{{<section widget>}}
---
title: Πώς να επεξεργαστείτε τα μεταδεδομένα PUB χρησιμοποιώντας Java
item1: "Για να επεξεργαστούμε τα μεταδεδομένα PUB, θα χρησιμοποιήσουμε το [Aspose.PUB for Java API](https://products.aspose.com/pub/java/) που είναι μια μετατροπή πλούσια σε χαρακτηριστικά, ισχυρή και εύχρηστη API για την πλατφόρμα Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από το [Maven](https://repository.aspose.com/pub/) και να την εγκαταστήσετε στο Maven σας -βασισμένο έργο προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml."
---

{{<section feature1>}}
---
title: Προβολή και επεξεργασία μεταδεδομένων PUB σε Java
item1: "Η διαδικασία ανάγνωσης μεταδεδομένων εκδότη αποτελείται από τα ακόλουθα βήματα:"
item2: Ανεβάστε το αρχείο PUB χρησιμοποιώντας τη μέθοδο [*createParser*()](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory#createParser-java.lang.String-) της μεθόδου [*PubFactory* ](https://reference.aspose.com/pub/java/com.aspose.pub/PubFactory) Τάξη.
item3: Ανάλυση αρχείου μέσω της μεθόδου [*parse*()](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser#parse--) του [*IPdfConverter*](https://reference.aspose.com/pub/java/com.aspose.pub/IPubParser) Διεπαφή.
item4: Επεξεργασία μεταδεδομένων π.χ. γλώσσα μέσω της μεθόδου [*setLanguage*()](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo#setLanguage-java.lang.String-) του [*DocSummaryInfo*](https://reference.aspose.com/pub/java/com.aspose.pub/DocSummaryInfo) Τάξη.
---

{{<section feature2>}}
---
title: Απαιτήσεις συστήματος
item1: Το Aspose.PUB για Java υποστηρίζεται σε όλα τα κύρια λειτουργικά συστήματα. Απλώς βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.
item2: J2SE 8.0 (1.8) ή νεότερη έκδοση.
---

{{<section codeexample>}}
---
title: Κώδικας Java για ενημέρωση μεταδεδομένων PUB
---