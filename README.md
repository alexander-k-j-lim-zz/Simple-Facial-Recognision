# Simple-Facial-Recognision
A simple facial recognision using Principal Component Analysis (PCA) as eigen faces and Random Forest to classify

The black and white, 50 by 37 pixels, images of 7 people Ariel Sharon, Colin Powell, Donald Rumsfeld, George W Bush, Gerhard Schroeder, Hugo Chavez and Tony Blair are included in the data sets from fetch_lfw_people data set. There are in total 1288 sample data, 1850 features (50 * 37), and 7 classes.

With 966 samples as training sample, it is used to find their eigen faces via PCA. Then 322 samples are classified via random forest classifier.
