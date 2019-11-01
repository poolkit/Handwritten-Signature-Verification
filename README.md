# Handwritten Signature Verification
Signature verification is an important biometric technique that aims to detect whether a given signature is genuine or forged. It is essential in preventing falsification of documents in numerous financial, legal, and other commercial settings. This is a comparative analysis of different already known deep learning architectures to check which of those performs the best on the classification. It was solely for offline handwritten signatures.

### Datasets Used:
The datasets are not available publicly . But you can mail the publisher and they would provide the download links.
1. [CEDAR](http://www.cedar.buffalo.edu/NIJ/data/signatures.rar)
   - 55 users : 24 forgeries/user + 24 genuine/user = 2640 signatures
2. [MCYT-75](http://atvs.ii.uam.es/atvs/mcyt100s.html)
   - 75 users : 15 genuine signatures/user + 15 forgeries/user = 2250 signature images
3. [GPDS Synthetic Signature-55](http://www.gpds.ulpgc.es/)
   - 4000 user : 24 genuine signatures + 30 forgeries signature for each individaul.

### Architectures Used:
1. VGG16
2. VGG19
3. InceptionV3
4. ResNet50
5. DenseNet201
6. Random Forest Classifier (Machine Learning Approach)

### Accuracy
Obsereved a highest accuracy of ~80% on both the datasets with VGG16 architecture. Generally in signature verification, it can be considered as a quite good accuracy considering the randomness of the signatures.


