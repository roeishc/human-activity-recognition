# Human Activity Recognition
## B.Sc, Computer Engineering final project
### General Information

Human Activity Recognition refers to the classification of time-series data samples, usually taken from sensors, to physical activities. In this project, I classify samples from a smartphone's gyroscope and accelerometer to the following activities: walking, walking upstairs, walking downstairs, standing, sitting, or laying. The classification is done by creating different models and architectures using the Keras interface in Python.
<br>
<br>
The [public domain dataset](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones) used in this project was published with [an article](https://www.esann.org/sites/default/files/proceedings/legacy/es2013-84.pdf) that used an SVM model and 500+ human-engineered features for classification. In addition to the human-engineered features, a relatively-raw samples dataset was published as well. I used these raw samples in this project.
<br>
<br>
The project's goals were:
- deepen my knowledge and understanding of Machine Learning as a whole, and deep dive into Neural Networks and Deep Learning.
- learn and experiment with Convolutional Neural Networks and with Long Short-Term Memory neural networks.
<br>
This is a supervised multivariate time-series classification problem implemented with Google Colaboratory.
<br>
<br>
I recommend checking the <a href="./Human%20Activity%20Recognition%20Project%20Book.pdf">project's book</a> (PDF) - I tried understanding and explaining the behavior exhibited by the different models and architectures, and had a lot of fun on the way!


### Technicalities
- If you want to run the code yourself, all you need to do after cloning the repo is correcting the path to the UCI HAR Dataset directory in the notebooks. I used Google Colaboratory, so I added the option to either fetch the dataset from Google Drive or from a local directory on your machine.

A big thank-you to [Jason Brownlee](https://machinelearningmastery.com), whose books and blogs provided great resources and guidance for me during this project.
