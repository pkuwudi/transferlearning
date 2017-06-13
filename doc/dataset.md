## Datasets for domain adaptation and transfer learning

Some widely used datasets are listed here. See [benchmark](#benchmark) of some algorithms.

|     Dataset    |        Area        | #Sample |       #Feature      | #Class |   Subdomain  | Download |
|:--------------:|:------------------:|:-------:|:-------------------:|:------:|:------------:|:--------:|
| Office+Caltech | Object recognition |   2533  | SURF:800 DeCAF:4096 |   10   |  C, A, W, D  |          |
|   MNIST+USPS   |  Digit recognition |   3800  |         256         |   10   |  USPS, MNIST |          |
|     COIL20     | Object recognition |   1440  |         1024        |   20   | COIL1, COIL2 |          |
|       PIE      |  Face recognition  |  11554  |         1024        |   68   |   PIE1~PIE5  |          |
|     VOC2007    |       Object recognition      |   3376  |      DeCAF:4096     |    5   |       V      |          |
|     LabelMe    |       Object recognition      |   2656  |      DeCAF:4096     |    5   |       L      |          |
|      SUN09     |       Object recognition      |   3282  |      DeCAF:4096     |    5   |       S      |          |
|   Caltech101   |       Object recognition      |   1415  |      DeCAF:4096     |    5   |       C      |          |
|    IMAGENET    |       Object recognition      |   7341  |      DeCAF:4096     |    5   |       I      |          |

### Office+Caltech

**Area:** Visual object recognition

Perhaps it is the *most popular* dataset for domain adaptation. Four domains are extracted: C(Caltech), A(Amazon), W(Webcam) and D(DSLR).

There are ususlly two kinds features: SURF and DeCAF6.

Download Office+Caltech SURF dataset

Download Office_Caltech SURF dataset



### MNIST+USPS

**Area** Handwritten digit recognition

It is also popular. It contains randomly selected samples from MNIST and USPS. Then the source and target domains are constructed using each other.

Download MNIST+USPS SURF dataset

### COIL20

**Area** Object recognition

It contains 36 classes. There are two datasets extracted: COIL1 and COIL2.

Download COIL20 SURF dataset

### PIE

**Area** Facial recognition

It is a relatively large dataset with many classes.

Download PIE SURF dataset

### VLSC

**Area** Image classification

It contains four domains: V(VOC2007), L(LabelMe), S(SUN09) and C(Caltech). There are 5 classes: 'bird', 'car', 'chair', 'dog', 'person'.

Download the VLSC DeCAF dataset

### IMAGENET

It is selected from imagenet challange.

Download the IMAGENET DeCAF dataset

### Benchmark

