## Explatory_Data_Analysis_and_ML_Projects


#### 1- Kaggle movie dataset is analyzed with Pandas and Matplot Libraries.
Raw tmdb_5000_movies.csv dataset is cleaned, organized, and nested json files are flattened with Pandas. The tables are created with matplotlib.pyplot. There are clean instructions to follow each step for the beginners. Last update: June 15, 2020


#### 2- Framingham dataset is analyzed with Pandas, Seaborn, and Matplot Libraries. KNN, Logistic Regression Classifier, and a One Layer Neural Network are applied to the dataset.
Raw framingham.csv dataset is downloaded from Kaggle. The dataset is cleaned, the feature scoring analysis and pruning is done. 3 different ML algorithms are applied for logistic regression analysis. There are clean instructions to follow each step for the beginners. Last update: September 24, 2020


#### 3- MNIST dataset is analyzed with Pandas, Seaborn, and Matplot Libraries. Pytorch and TF-Keras libraries are used to build models with FCL and CNNs.
The dataset can be downloaded from: https://www.kaggle.com/oddrationale/mnist-in-csv for EDA. 
The dataset used for creating the models are downloaded through torchvision.datasets and keras.datasets in the ipynb attached
(See the downloads from: tf.keras.datasets.mnist and torchvision.datasets.MNIST)


#### 4- Breast Cancer dataset is analyzed with Pandas, Seaborn, and Matplot Libraries. Decision Tree & XGBoost models are trained to make a prediction with 95% and 97% accuracy respectively.
The dataset can be obtained at: http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. Data has information about 569 patients. There are 32 attributes.


#### 5- Ambient Temperature dataset (in Anomaly Detection Dataset Folder) is analyzed with Pandas, Seaborn, and Matplot Libraries. Kmeans++ is used to cluster the data and basic adtk tool is used to see the anomalities.
The dataset can be obtained at: https://www.kaggle.com/boltzmannbrain/nab
This is a timeseries dataset showing hourly temperature values for one year


#### 6- Yahoo APPL Stock dataset (Time Series Stock Dataset Folder) is analyzed with Pandas, Seaborn, and Matplot Libraries. FBProphet, ARIMA, and LSTM models (with Keras TF) are used to make predictions.
The dataset can be obtained at: https://finance.yahoo.com/chart/AAPL/
This is a timeseries dataset showing daily stock value changes of APPLE. 


#### 7- Audio Dataset: Several laughters in .wav format analyzed with Librosa and Matplotlib Libraries. Convolutional NN are used to make predictions.
The dataset can be found in the 'laugh' and 'laugh_test' folders.
There are 22 laughter files in total. Some sound sincere and some sound fake. The gray scale mel spectogram images of the laughter audio files are trained and tested. 


#### 8- Self-supervised learning with a truck parking its trailer backwards, creating its own training data with emulator and doing the steering with controller
A truck is created in a frame of 400x300 area for about 100,000 scenerios (at different coordinates) and a random steering angle (wheel input) is added and output is observed. When truck learns how to step backwards from any steering angle (wheel input), a controller is added to the system which is actually a smart steering wheel to take the truck back to the origin. This system is only trained on a CPU for about 1 epoch and it needs improvements, some corrections, and way more training. This notebook is the enhanced version of the copy given at NYU Deep Learning Class. The trained weights of the system are already presented in the folder (ready to upload) so that students do not need to train them from scratch if they do not need to. 


#### 9- Transformer Encoder: Sentiment Analysis made on the torch.datasets.IMDB dataset.
TORCHTEXT.DATASETS.IMDB dataset is made of 25000 comments on several movies. A simple Transformer Encoder is coded from scratch with PyTorch and then used for performing a sentiment analysis on these comments. The encoder model is trying to detect whether these comments are positive or negative. 


#### 10- Variational Auto Encoder with Yale Face Dataset
Created a Variational Auto Encoder (VAE) and fed the Yale Face Database to the model to extract the average facial features of the dataset. This dataset can be found here: https://www.kaggle.com/kerneler/starter-yale-face-database-c5f3978b-5
Note: Since the trained model parameters are about 3.2 GB, it is not available here. Download the dataset from the link above to your working folder and then UNMARK all the cells in the notebook and run it to train your model. If you use a simple CPU, it might take up to 12 hours. It is recommended to use a GPU. 


#### 11- DGL Library Simplified with Examples
Deep Graph Library is a great tool to do node classification, edge classification, and graph classification. It has its own tutorial datasets. This notebook has detailed analysis of CoraDataSet and MiniGCDatasets with dgl.nn module. https://www.dgl.ai/  





