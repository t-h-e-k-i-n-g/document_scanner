# document_scanner
Document Scanner allows you to scan documents with your phone camera, convert them into PDF using this program. It convert photos into documents.
This document scanner is built using openCV and Python.
It works in three steps:
1) First of all it detect edges in the given image
2) Then it find the contours of the paper which is our object from the image.
3) Lastly, it apply perspective transform to give the birds eye view of the scanned paper.
