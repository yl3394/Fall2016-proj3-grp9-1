# Project: Labradoodle or Fried Chicken? 
![image](https://s-media-cache-ak0.pinimg.com/236x/6b/01/3c/6b013cd759c69d17ffd1b67b3c1fbbbf.jpg)
### [Full Project Description](doc/project3_desc.html)

Term: Fall 2016

+ Team iTrainer
+ Team members
	+ Yanjin Li
	+ Youzhu Liu
	+ Yanxi Chen
	+ Ran Li
	+ Hyungjoon Choi
+ Project summary: In this project, we created a classification engine for images of poodles versus images of fried chickens. We extract many geature extraction methods: MSER, SIFT, HoG, Harris Corner and CNN deep learning methods. In terms of classifiers, we considered KNN, Logistic and SVM. We cross compare the combinations of feature extraction methods and classifiers in order to find the best model. We also use GBM as our baseline model plus sift feature set to compare with the CNN(norm2 layer) feature set and our advanced model. The final advanced model we choose is CNN(norm2 layer)+SVM. For code details, please check on lib directory: test.R and train.R. Please refer to lib/feature extractions/002_feature extraction_CNN for the CNN(norm2 layer)code.
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) Yanjin took charge of Caffe CNN feature extraction/presentation. Youzhu took charge of MSER/HoG/SIFT/Harris feature extraction. Yanxi took charge of Logistic classifier. Ran took charge of KNN/SVM and PCA classifier. Hyungjoon took charge of GBM.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

![image](figs/cover_images/Screen Shot 2016-11-03 at 10.24.46 AM.png)
![image](figs/cover_images/Screen Shot 2016-11-03 at 10.24.54 AM.png)
![image](figs/cover_images/Screen Shot 2016-11-03 at 10.24.57 AM.png)
![image](figs/cover_images/Screen Shot 2016-11-03 at 10.25.06 AM.png)
![image](figs/cover_images/Screen Shot 2016-11-03 at 10.25.13 AM.png)




```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
