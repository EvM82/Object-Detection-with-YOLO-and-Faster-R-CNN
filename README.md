# Object-Detection-with-YOLO-and-Faster-R-CNN
Χρησιμοποιείται το Pascal VOC dataset για πρόβλημα object detection. Υλοποιούνται 3 διαφορετικές προσεγγίσεις, με YOLO, με pretrained Faster RCNN στο οποίο θα προστεθεί ενα επιπλέον convolutional stem πριν το backbone και Faster RCNN στο οποίο θα γίνει δοκιμή με απλοποιημένο custom backbone.

Στόχος είναι να φανεί πώς αλλαγές σε διάφορα κομμάτια τςη αρχικής αρχιτεκτονικής στα Faster RCNN καθώς και η χρήση τεχνικών βελτίωσης όπως Batch Normalization, L2 regularization και ρύθμιση των anchors και thresholds θα επηρρεάσουν την απόδοση των μοντέλων, αλλά και πώς επηρράζεται το κομμάτι ευρεσης αντικειμένων και ταξινόμησής τους στην κάθε περίπτωση.

Τέλος, για κάθε προσέγγιση γίνεται εκπαίδευση στο clean Pascal VOC dataset και στα δεδομένα με προσθήκη noise και blur.
