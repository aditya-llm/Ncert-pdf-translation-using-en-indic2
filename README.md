# Ncert-pdf-translation-using-en-indic2

This is the Colab notebook link (as the file upload caused an error):
📘 First_try.ipynb =>  https://colab.research.google.com/drive/1HToqicJtVOgAJAR-riCz5r9lsrMR1shc#scrollTo=jRpaje3XDHe2

Observations and Issues

Image Extraction Problem:
The NCERT PDFs contain layered images, which makes it difficult to extract them properly. As a result, the Hindi PDFs do not retain the correct layout when processed.

OCR Attempt:
I also tried using OCR for image and text extraction. Although it successfully extracted text, it introduced significant noise and inaccuracies compared to PyMuPDF, so I chose to continue using PyMuPDF for cleaner output.
