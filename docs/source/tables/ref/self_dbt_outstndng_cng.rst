
Πίνακας B7: Μεταβολή της Εναπομείνουσας Αξίας Χρεογράφων Εκδοθέντων από τον ΕΟ (SELF_DBT_OUTSTNDNG_CHNG)
========================================================================================================

Χρησιμοποιείται για την παροχή στοιχείων μεταβολής της εναπομένουσας αξίας
ιδίων εκδοθέντων χρεογράφων των ΕΟ. 

Ακολουθεί περιγραφή των μεταβλητών του πίνακα:

ΔΙΑΣΤΑΣΕΙΣ
----------

Αναγνωριστικός κωδικός χρεογράφου (ID)
    Ο αναγνωριστικός κωδικός :ref:`DBT <dbt>` του χρεογράφου που έχει εκδοθεί από τον ΕΟ.

Λόγος μεταβολής (RSN)
    Ο λόγος μεταβολής της εναπομένουσας αξίας.

    Η τιμή επιλέγεται από τη λίστα τιμών :doc:`../../types/codelists/dbt_outstndng_chn_typ`
    
Ημερομηνία μεταβολής (DT) 
    Ημερομηνία μεταβολής της εναπομένουσας αξίας.

    Το είδος της τιμής είναι :doc:`../../types/formats/datetime`.


ΜΕΤΑΒΛΗΤΕΣ
----------

Ποσό μεταβολής (AMNT)
    Ποσό μεταβολής της εναπομένουσας ονομαστικής αξίας.  
    
    Οι εξοφλήσεις συμπληρώνονται με αρνητικό πρόσημο.

    Το είδος της τιμής είναι :doc:`../../types/formats/float`.

Τιμή (PRC)
    Τιμή της συναλλαγής της αλλαγής στην εναπομένουσα αξία.  

    Ποσοστό επί τοις εκατό % της απόλυτης τιμής της μεταβλητής AMNT. 

    Το είδος της τιμής είναι :doc:`../../types/formats/nonnegativefloat`.
