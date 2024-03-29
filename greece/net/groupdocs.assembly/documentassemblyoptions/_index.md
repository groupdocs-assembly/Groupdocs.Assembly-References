---
title: DocumentAssemblyOptions
second_title: GroupDocs.Assembly για Αναφορά API .NET
description: Καθορίζει επιλογές που ελέγχουν τη συμπεριφορά τουDocumentAssembler./documentassembler κατά τη συναρμολόγηση ενός εγγράφου.
type: docs
weight: 210
url: /el/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Καθορίζει επιλογές που ελέγχουν τη συμπεριφορά του[`DocumentAssembler`](../documentassembler) κατά τη συναρμολόγηση ενός εγγράφου.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| None | `0` | Καθορίζει τις προεπιλεγμένες επιλογές. |
| AllowMissingMembers | `1` | Καθορίζει ότι τα μέλη αντικειμένων που λείπουν θα πρέπει να αντιμετωπίζονται ως μηδενικά κυριολεκτικά από το assembler. Αυτή η επιλογή επηρεάζει μόνο την πρόσβαση σε στιγμιότυπα (δηλαδή, μη στατικά) μέλη αντικειμένων και μεθόδους επέκτασης. Εάν αυτή η επιλογή δεν έχει οριστεί, ο assembler κάνει μια εξαίρεση όταν συναντά ένα μέλος αντικειμένου που λείπει. |
| UpdateFieldsAndFormulas | `2` | Καθορίζει ότι τα πεδία αποτελεσμάτων Τα έγγραφα επεξεργασίας κειμένου και οι τύποι των εγγράφων υπολογιστικού φύλλου αποτελεσμάτων θα πρέπει να ενημερωθούν από τη μονάδα συναρμολόγησης. |
| RemoveEmptyParagraphs | `4` | Καθορίζει ότι η assembler θα πρέπει να αφαιρέσει τις παραγράφους που γίνονται κενές αφού οι ετικέτες σύνταξης προτύπου αφαιρεθούν ή αντικατασταθούν με κενές τιμές. |
| InlineErrorMessages | `8` | Καθορίζει ότι η assembler θα πρέπει να ενσωματώνει μηνύματα σφάλματος σύνταξης προτύπου στα έγγραφα εξόδου. Εάν αυτή η επιλογή δεν έχει οριστεί, ο assembler δημιουργεί μια εξαίρεση όταν αντιμετωπίζει ένα συντακτικό σφάλμα. |
| UseSpreadsheetDataTypes | `10` | Σχετίζεται μόνο με έγγραφα υπολογιστικού φύλλου. Καθορίζει ότι τα αποτελέσματα των αξιολογημένων εκφράσεων θα πρέπει να αντιστοιχίζονται σε αντίστοιχους τύπους δεδομένων υπολογιστικού φύλλου, γεγονός που επηρεάζει επίσης την προεπιλεγμένη μορφοποίησή τους εντός των κελιών. Εάν αυτή η επιλογή δεν έχει οριστεί, τα αποτελέσματα της παράστασης γράφονται πάντα ως συμβολοσειρές από το assembler. Αυτή η επιλογή δεν έχει αποτέλεσμα όταν τα αποτελέσματα της έκφρασης μορφοποιούνται με χρήση σύνταξης προτύπου - τα αποτελέσματα της έκφρασης γράφονται πάντα ως συμβολοσειρές και στη συνέχεια. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Assembly](../../groupdocs.assembly)
* συνέλευση [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
