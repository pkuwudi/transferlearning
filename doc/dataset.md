## Datasets for domain adaptation and transfer learning

Some widely used datasets are listed here. See [benchmark](#benchmark) of some algorithms.

|     Dataset    |        Area        | #Sample |       #Feature      | #Class |   Subdomain  | Reference |
|:--------------:|:------------------:|:-------:|:-------------------:|:------:|:------------:|:--------:|
| [Office+Caltech](#office+caltech) | Object recognition |   2533  | SURF:800 DeCAF:4096 |   10   |  C, A, W, D  |   [1]       |
|   [MNIST+USPS](#mnist+usps)   |  Digit recognition |   3800  |         256         |   10   |  USPS, MNIST |    [4]      |
|     [COIL20](#coil20)     | Object recognition |   1440  |         1024        |   20   | COIL1, COIL2 |    [4]      |
|       [PIE](#pie)      |  Face recognition  |  11554  |         1024        |   68   |   PIE1~PIE5  |     [6]     |
|     [VOC2007](#vlsc)    |       Object recognition      |   3376  |      DeCAF:4096     |    5   |       V      |    [8]      |
|     [LabelMe](#vlsc)    |       Object recognition      |   2656  |      DeCAF:4096     |    5   |       L      |    [2]      |
|      [SUN09](#vlsc)     |       Object recognition      |   3282  |      DeCAF:4096     |    5   |       S      |    [9]      |
|   [Caltech101](#vlsc)   |       Object recognition      |   1415  |      DeCAF:4096     |    5   |       C      |    [3]      |
|    [IMAGENET](#imagenet)    |       Object recognition      |   7341  |      DeCAF:4096     |    5   |       I      |     [7]     |
|    [AWA](#animals-with-attributes)    |       Animal recognition      |   30475  |      DeCAF:4096 SIFT/SURF:2000    |    50   |       I      |    [5]      |



### Office+Caltech

**Area:** Visual object recognition

Perhaps it is the *most popular* dataset for domain adaptation. Four domains are extracted: C(Caltech), A(Amazon), W(Webcam) and D(DSLR).

There are ususlly two kinds features: SURF and DeCAF6.

[Download Office+Caltech SURF dataset](https://www.jianguoyun.com/p/DWNPUA0QjKnsBRjygi4)

[Download Office_Caltech SURF dataset](https://www.jianguoyun.com/p/DRn57qkQjKnsBRj0gi4)



### MNIST+USPS

**Area** Handwritten digit recognition

It is also popular. It contains randomly selected samples from MNIST and USPS. Then the source and target domains are constructed using each other.

[Download MNIST+USPS SURF dataset](https://www.jianguoyun.com/p/DQNVR8IQjKnsBRj2gi4)

### COIL20

**Area** Object recognition

It contains 36 classes. There are two datasets extracted: COIL1 and COIL2.

[Download COIL20 SURF dataset](https://www.jianguoyun.com/p/DYkJdrEQjKnsBRj4gi4)

### PIE

**Area** Facial recognition

It is a relatively large dataset with many classes.

[Download PIE SURF dataset](https://www.jianguoyun.com/p/DfhzbUwQjKnsBRj5gi4)

### VLSC

**Area** Image classification

It contains four domains: V(VOC2007), L(LabelMe), S(SUN09) and C(Caltech). There are 5 classes: 'bird', 'car', 'chair', 'dog', 'person'.

[Download the VLSC DeCAF dataset](https://www.jianguoyun.com/p/DdaInQ0QjKnsBRj6gi4)

### IMAGENET

It is selected from imagenet challange.

[Download the IMAGENET DeCAF dataset](https://www.jianguoyun.com/p/DZCNd0oQjKnsBRj8gi4)

### Animals-with-Attributes

[Download the SURF/SIFT/DeCAF features](https://www.jianguoyun.com/p/DcRl38EQjKnsBRj_gi4)

### Benchmark

### References

[1] Gong B, Shi Y, Sha F, et al. Geodesic flow kernel for unsupervised domain adaptation[C]//Computer Vision and Pattern Recognition (CVPR), 2012 IEEE Conference on. IEEE, 2012: 2066-2073.
[2] Russell B C, Torralba A, Murphy K P, et al. LabelMe: a database and web-based tool for image annotation[J]. International journal of computer vision, 2008, 77(1): 157-173.
[3] Griffin G, Holub A, Perona P. Caltech-256 object category dataset[J]. 2007.
[4] Long M, Wang J, Ding G, et al. Transfer feature learning with joint distribution adaptation[C]//Proceedings of the IEEE International Conference on Computer Vision. 2013: 2200-2207.
[5] http://attributes.kyb.tuebingen.mpg.de/
[6] http://www.cs.cmu.edu/afs/cs/project/PIE/MultiPie/Multi-Pie/Home.html
[7] http://www.cs.dartmouth.edu/~chenfang/proj_page/FXR_iccv13/
[8] M. Everingham, L. Van-Gool, C. K. Williams, J. Winn, and A. Zisserman, “The pascal visual object classes (VOC) challenge,” Int. J. Comput. Vis., vol. 88, no. 2, pp. 303–338, 2010.
[9] M. J. Choi, J. J. Lim, A. Torralba, and A. S. Willsky, “Exploiting hierarchical context on a large database of object categories,” in Proc. IEEE Conf. Comput. Vis. Pattern Recogit., 2010, pp. 129–136