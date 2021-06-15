# fetch_lfw_people_svm

Support Vector Machine is applied to train a model for Face Recognition dataset

This dataset is a collection of JPEG pictures of famous people collected over the internet, all details are available on the official website:

http://vis-www.cs.umass.edu/lfw/

The purpose in this project is to recognize the face of person in the picture and label it with its full name, based on a training process composed by thousand of labeled pictures.

For this project, all picture are black & white (sklearn.datasets.fetch_lfw_people -- parameter color = False)

Finally, for this project each class in dataset has at least 60 values.
