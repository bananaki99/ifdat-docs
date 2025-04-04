Κρίσιμα Λάθη
============

Περιγράφονται τα κρίσιμα λάθη των οποίων η ύπαρξη διακόπτει την αποθήκευση του συνόλου των στοιχείων του αρχείου στη βάση δεδομένων.

Μη αποδεκτά Excel αρχεία (CRRPT_EXCEL)
    Αρχεία **.xlsx** με μη αποδεκτή δομή. 

Μη αποδεκτά json αρχεία (CRRPT_JSON)
    Αρχεία **.json** με μη αποδεκτή δομή. 

Λάθος δέσμη (NT_IFDAT)
    Αρχεία δέσμης δεδομένων άλλων από το IFDat.

Ασυνέπεια στον αναγγέλοντα (RP_INCNSSTNCY)
    Για τα αρχεία που προκύπτει ασυνέπεια στον αναγγέλοντα όπως προκύπτει από την ονομασία του αρχείου και από το HEADER του αρχείου δίδονται τα ακόλουθα:
    * Ονομασία αρχείου (FLNM)
    * Ονομασία αναγγέλοντα από το όνομα του αρχείου (RP_FRM_FLNM)
    * Ονομασία αναγγέλοντα από το header (RP_FRM_HDR)

Λάθη Σχήματος (SCHEMA_ERRRS)
    Σε περίπτωση που τα εισερχόμενα αρχεία δεν ακολουθουν το json schema δίδονται τα λάθη.  Σε περίπτωση που το εισερχόμενο αρχείο είναι μορφής EXCEL πρώτα τα μετατρέπονται σε JSON και μετά ελέγχονται.  Στο :doc:`./critical/schema_error` περιγράφονται οι πληροφορίες που δίνονται για κάθε λάθος στο σχήμα.

.. toctree::
   :maxdepth: 1 

   critical/schema_error
