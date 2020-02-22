## Fashion_Class_Classification
### Description

**The aim is to predict type of clothes on the image**

Fashion dataset consists of 70,000 images divided into 60,000 training and 10,000 testing samples. Dataset sample consists of 28x28 grayscale image, associated with a label.

There are 10 classes (labels) available:  
- 0 => T-shirt/top
- 1 => Trouser
- 2 => Pullover
- 3 => Dress
- 4 => Coat
- 5 => Sandal
- 6 => Shirt
- 7 => Sneaker
- 8 => Bag
- 9 => Ankle boot

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.

### Workflow
1. Data import
- Load libraries
- Load dataset
2. Data visualizing
- Display dataframe
- Display random images
3. Model training
- Prepare train, validation and test datasets
- Create neural network model
- Compile model
- Train model
4. Model evaluating
- Test data
- Print heatmap
- Print classification report

### Conclusions
1. By using (32,3,3) kernel with dropout, we were able to achieve:
- Accuracy: 89.55%
- Test accuracy: 90.10%

### Acknowledgements
This implementation was inspired by Kirill Eremenko, Hadelin de Ponteves, Dr. Ryan Ahmed, Ph.D., MBA, SuperDataScience Team, Rony Sulca [Machine Learning Practical Udemy course](https://www.udemy.com/course/machine-learning-practical/?utm_source=adwords&utm_medium=udemyads&utm_campaign=DataScience_v.PROF_la.EN_cc.ROW_ti.5336&utm_content=deal4584&utm_term=_._ag_85469003954_._ad_395279056268_._kw__._de_c_._dm__._pl__._ti_dsa-774930036449_._li_1011367_._pd__._&matchtype=b&gclid=CjwKCAiAvonyBRB7EiwAadauqdGsq1pYwJXPHmZpdR12WWHTeI31ZGNAR7wJqhrnln_dI452sQCbCBoCnvwQAvD_BwE)
