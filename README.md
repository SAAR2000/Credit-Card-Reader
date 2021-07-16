# Credit-Card-Reader
In this repository we aim to:
1. Detect the location of the credit card in the image.
2. Localize the four groupings of four digits, pertaining to the sixteen digits on the credit card.
3. Apply OCR to recognize the sixteen digits on the credit card.
4. Recognize the type of credit card (i.e., Visa, MasterCard, American Express, etc.).

Using OpenCV we will devise a Computer Vison algorithm that can:
1. Localize the four groupings of four digits on a credit card.
2. Extract each of these four groupings followed by segmenting each of the sixteen numbers individually.
3. Recognize each of the sixteen credit card digits by using template matching and the OCR-A font.
