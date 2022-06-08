## Έξυπνος κάδος διαχώρισης πλαστικού και μετάλλου με ασύρματο σύστημα ειδοποίησης πληρότητας σε πραγματικό χρόνο
### Το πρόβλημα
Τα πλαστικά βρίσκονται παντού γύρω μας. Στην Ελλάδα παράγονται κάθε χρόνο 940.000 τόνοι πλαστικού, δηλαδή 40 περίπου φορές όσο το βάρος του Παρθενώνα! Το 84% των πλαστικών απορριμμάτων καταλήγει στις χωματερές. Η ρύπανση επηρεάζει σοβαρά τα χερσαία οικοσυστήματα, τις θάλασσές μας και την ίδια μας την υγεία. Ότι καταλήγει στο περιβάλλον επιστρέφει στον ίδιο μας τον οργανισμό μέσω της τροφικής αλυσίδας. Για να αποκτήσουν τα παιδιά μας οικολογική συνείδηση, χρειάζονται μικρές, καθημερινές “πράξεις σεβασμού” προς στο περιβάλλον. Μπορούν να υιοθετήσουν τη συνήθεια της ανακύκλωσης των πλαστικών μπουκαλιών που χρησιμοποιούν στο χώρο του σχολείου βοηθώντας στην  διατήρηση της καθαριότητας  της αυλής του σχολείου τους.
### Σκοπός Project
Οι μαθητές με την χρήση της τεχνολογίας να αποκτήσουν οικολογική συνείδηση δημιουργώντας έναν έξυπνο κάδο. Ο έξυπνος κάδος διαχωρίζει το πλαστικό από το μέταλλο. Θα τοποθετηθεί στην αυλή του σχολείου όπου οι μαθητές τοποθετώντας ένα αντικείμενο θα αναγνωρίζει αν είναι πλαστικό ή μέταλλο και θα το διαχωρίζει. 

### Σχεδιασμός  Project
Για την δημιουργία του Project  θα χρησιμοποιηθεί η   πλακέτα Micro:bit.  Ο κάδος θα είναι κατασκευασμένος  από χαρτόνι.  Όταν τοποθετεί ένας μαθητής  ένα αντικείμενο  το αυτόματο σύστημα διαχωρισμού θα το τοποθετεί στον αντίστοιχο κάδο ανάλογα αν είναι πλαστικό ή μέταλλο.  Για την υλοποίηση του project δεν θα χρησιμοποιηθούν έτοιμοι αισθητήρες του εμπορίου για την αναγνώριση των υλικών(πλαστικό/μέταλλοο).  Με την χρήση απλών υλικών(αλουμινόχαρτο ,καλώδια) οι μαθητές θα φτιάξουν τους δικούς τους αισθητήρες.  Το project με αυτό τον τρόπο θα γίνει πιο απλό και κατανοητό στους μαθητές και θα μειωθεί το κόστος κατασκευής του. 
Προτείνεται στο συγκεκριμένο project η πλακέτα Micro:bit για το χαμηλό κόστος, την ευκολία προγραμματισμού από μαθητές δημοτικού και της ενσωματωμένες δυνατότητες όπου διαθέτει (Radio σήματα, Led οθόνη, αναγνώριση κλειστού κυκλώματος) . Κατά προτίμηση θα χρησιμοποιηθούν ανακυκλώσιμα υλικά για να εξυπηρετηθεί ο σκοπός του project.

### Υλοποίηση Project
 ![Screenshot](images/station.jpg)
 
### Έξυπνος κάδος
Ο έξυπνος κάδος διαχωρίζει τα πλαστικά από τα μέταλλα. Όταν τοποθετείτε ένα αντικείμενο στον κάδο το έξυπνο σύστημα διαχώρισης ελέγχει αν το αντικείμενο είναι πλαστικό ή μέταλλο και το τοποθετεί στον αντίστοιχο κάδο.
![Screenshot](images/kados2022.jpg)
* **Σύστημα διαχώρισης πλαστικού από μέταλλο.**

Το έξυπνο σύστημα διαχώρισης αντικειμένων ελέγχει αν δημιουργείτε κλειστό κύκλωμα όταν τοποθετείτε ένα αντικείμενο. Υπάρχει ένα αλουμινόχαρτο στην κάτω πλευρά και στα πλάγια του συστήματος διαχώρισης. Όταν τοποθετείτε ένα μέταλλο ανιχνεύει κλειστό κύκλωμα και το αντικείμενο τοποθετείτε στην πλευρά των μετάλλων διαφορετικά τοποθετείτε στην πλευρά των πλαστικών. Ένα servo μοτέρ περιστρέφει  αριστερά η δεξιά το σύστημα διαχώρισης ανάλογα με το αν ανιχνεύει μέταλλο ή όχι.

### Κώδικας
Tο περιβάλλον MakeCode είναι απλό και προσιτό σε μαθητές δημοτικού (μπορείτε να το βρείτε στη διεύθυνση https://makecode.microbit.org/# ).  Αυτό θα χρησιμοποιήσουμε στη συνέχεια. 
Διάγραμμα ροής του έξυπνου κάδου
![Screenshot](images/ flow chart.jpg)
Ο κώδικας για την υλοποίηση του έξυπνου κάδου

![Screenshot](images/code2.jpg)


### Υλικά
1.	BBC micro:bit Board 18,90€
2.	Μπαταριοθήκη 3xΑΑ με JST PH  0,80€
4.	Servo Micro 2.2kg.cm Plastic Gears 3,60€
5.	Traffic Light for BBC micro:bit 5€
6.	Αισθητήρας Υπερήχων 5€
7.	Jumper Wires 15cm 4€
Σύνολο: 37 €

### Παρουσίαση Youtube
[![IMAGE ALT TEXT](https://img.youtube.com/vi/FV2nJcAjP18/1.jpg)](https://youtu.be/FV2nJcAjP18 "My video")

### Φωτογραφικό Υλικό
![Screenshot](images/1.jpg)

![Screenshot](images/2.jpg)

![Screenshot](images/3.jpg)

![Screenshot](images/4.jpg)

![Screenshot](images/sillogos.jpg)


