Πίνακας B10: Μεταβλητά Στοιχεία Αναφοράς Μετοχών/Μεριδίων εκδοθέντων από τον ΕΟ (SELF_SHR_DYNMC)
================================================================================================

Χρησιμοποιείται για την παροχή στοιχείων αναφοράς ιδίων μετοχών/μεριδίων των ΕΟ
και περιλαμβάνει μετρήσεις που οι τιμές τους δύναται να μεταβληθούν κατά τη
διάρκεια του κύκλου ζωής της μετοχής/μεριδίου.

Ακολουθεί περιγραφή των μεταβλητών του πίνακα:

ΔΙΑΣΤΑΣΕΙΣ
----------
Αναγνωριστικός κωδικός μετοχής/μεριδίου (ID)
    Ο αναγνωριστικός κωδικός :ref:`SHR <shr>` της ιδίας μετοχής/μεριδίου.

Ισχύει από (VLD_FRM)
    Ημερομηνία από την οποία ισχύουν οι τιμές των παρεχόμενων μεταβλητών.

    Περαιτέρω διευκρινιστικές πληροφορίες δίδονται στην ενότητα :doc:`../../generic`.

    Το είδος της τιμής είναι :doc:`../../types/formats/datetime`.

Ισχύει έως (VLD_T)
    Ημερομηνία από την οποία ισχύουν οι τιμές των παρεχόμενων μεταβλητών.

    Περαιτέρω διευκρινιστικές πληροφορίες δίδονται στην ενότητα :doc:`../../generic`.

    Το είδος της τιμής είναι :doc:`../../types/formats/datetime`.


ΜΕΤΑΒΛΗΤΕΣ
~~~~~~~~~~

Ονομασία με λατινικούς χαρακτήρες (NM_LTN)
    Ονομασία της μετοχής/μεριδίου με λατινικούς χαρακτήρες.

    Το είδος της τιμής είναι :doc:`../../types/formats/ext_latin`.

Σύντομη ονομασία (NM_SHRT)
    Σύντομη ονομασία ή το FISN της μετοχής/μεριδίου.

    Συμπληρώνεται μόνο αν υπάρχει τέτοια ονομασία.

    Το είδος της τιμής είναι :doc:`../../types/formats/string64`.

Εκδόθηκε από (ISSD_BY)
    O Αναγνωριστικός κωδικός :ref:`ORG <org>` του ΕΟ που έχει εκδώσει το συμμετοχικό τίτλο.

Ονομαστική τιμή (NMNL_PRC)
    Ονομαστική τιμή της μετοχής ή αρχική τιμή έκδοσης του μεριδίου.

    Το είδος της τιμής είναι :doc:`../../types/formats/nonnegativefloat`.

Κωδικός χρηματοοικονομικού μέσου (CFI)
    Κατηγοριοποίηση CFI του μετοχής/μεριδίου 

    Για περισσότερες πληροφορίες δείτε το πρότυπο ISO-10962

    Το είδος της τιμής είναι :doc:`../../types/formats/ascii6`.

Συχνότητα εξόφλησης (RDMPTN_FRQNCY)
    Η συχνότητα εξόφλησης προσδιορίζει το χρονοδιάγραμμα βάσει του οποίου οι επενδυτές στον ΕΟ μπορούν να εξοφλούν τις μετοχές/μερίδια.

    Η τιμή επιλέγεται από τη λίστα τιμών :doc:`../../types/codelists/other_rdmptn_frqncy`.

Ελάχιστο ποσό συμμετοχής (MNMM_AMNT)
    Ελάχιστο ποσό συμμετοχής.

    Τιμή συμπληρώνεται μόνο στην περίπτωση ύπαρξης ελάχιστου ποσού συμμετοχής. 

    Το είδος της τιμής είναι :doc:`../../types/formats/nonnegativefloat`.

Είδος μετοχής/μεριδίου (TYP)
    Είδος της μετοχής/μεριδίου
    
    Η τιμή επιλέγεται από τη λίστα τιμών :doc:`../../types/codelists/shr_typ`.
