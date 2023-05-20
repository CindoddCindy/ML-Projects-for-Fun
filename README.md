# Exploring Machine Learning and Deep Learning

These projects I created with the aim of learning and exploring new areas of interest.

- ## [EUR/USD Forex Market Prediction: Conv1D Model with MultiHeadAttention for Exchange Rate Forecasting](https://github.com/spoluan/Forex_market_prediction_EUR_USD)
  Forex is a global marketplace where currencies are bought and sold, with a daily trading volume reaching trillions of dollars, making it the largest and most liquid financial market. Forex trading involves speculating on fluctuations in exchange rates between different currency pairs, such as EUR/USD and GBP/JPY. EUR/USD is one of the most actively traded currency pairs, representing the exchange rate between the Euro and the US Dollar. The exchange rate between these currencies is influenced by economic indicators, political events, central bank policies, and market sentiment. Traders and investors analyze historical price data and use technical and fundamental analysis techniques to predict future movements in the EUR/USD exchange rate. In this project, a Conv1D model with a MultiHeadAttention layer is used for predicting the future price of this time series data.

- ## [Federated Learning for MNIST Digits](https://github.com/spoluan/federated_learning_mnistdigit)
  Federated learning is a decentralized machine learning approach that enables training models without requiring data to be centralized in one location. Instead, the learning process takes place on the edge devices or local servers where the data is generated. This collaborative method offers privacy, as the data remains on the devices, and allows for efficient training on a large scale. With federated learning, models are trained across distributed devices, and only the model updates are shared, ensuring privacy and preserving data locality.

- ## [Exploring Reinforcement Learning: Implementing Various Approaches on OpenAI Gym Tasks](https://github.com/spoluan/reinforcement_learning)
  Reinforcement learning is a type of machine learning that focuses on training agents to make decisions in an environment in order to maximize a reward signal. In other words, reinforcement learning involves training an agent to learn by trial and error, through interaction with its environment. In this repository, I implement several approaches to reinforcement learning on different tasks using the OpenAI Gym simulation environment.

- ## [Exploiting NVIDIA TX2 Resources for Human Identification with Smart Insoles and OpenPose](https://github.com/spoluan/social-robots)
  This Identity Recognition program, built to process OpenPose coordinate data, smart insole information, and RGB camera input, provides a sophisticated solution for real-time human identification without compromising privacy. Operating on the potent NVIDIA Jetson TX2 platform, this system ensures privacy by focusing on behavioral and physical patterns instead of personal identifiable information. With on-device training capabilities, this program is not only portable and adaptable but also highly efficient in diverse environments. In this guide, we'll navigate the process of running this state-of-the-art identity recognition application, maintaining a strong commitment to user privacy while demonstrating the exceptional capabilities of the TX2 platform.


- ## [Head Detection Using SCUT-HEAD Dataset: Implementing Object Detection with Detecto Library](https://github.com/spoluan/SCUT_HEAD_object_detection)
  In this project, I will be implementing object detection using the SCUT-HEAD-Dataset. The dataset includes two releases, A and B, and contains a total of 4,405 images labeled with 111,251 heads. The dataset is divided into two parts, Part A and Part B, with each part containing training and testing images. I will be using the detecto library, which is based on the Faster R-CNN ResNet-50 FPN model and built on top of the PyTorch framework. Our goal is to build a model that can accurately detect heads in images and provide the coordinates of the bounding boxes around them.

- ## [IMDB Sentiment Analysis: Binary Sentiment Classification on a Large Movie Review Dataset](https://github.com/spoluan/IMDB_sentiment_analysis)
  For this project, I will be implementing sentiment analysis on the large movie review dataset. This dataset is specifically designed for binary sentiment classification, and consists of 50,000 movie reviews, with 25,000 reviews allocated for training and the other 25,000 for testing. The dataset provides a vast collection of data for conducting sentiment analysis.

- ## [Smart Basket: Automated Waste Sorting Using Sound Classification](https://github.com/spoluan/rpi-smart-wastebasket)
  The Smart Basket project is a unique approach to waste management. By utilizing the distinct sound that each piece of trash creates when it falls into the basket, the project aims to classify the type of trash being discarded. To achieve this, multiple microphones are placed underneath the basket to record the sound, triggered by ultrasonic sensors at the mouth of the basket. The collected data is then processed using a combination of Conv1D and LSTM neural networks to train the trash classification model. The project was developed for a competition and has been implemented on a Raspberry Pi with an accuracy rate of over 90%. The Smart Basket project offers a promising solution for automated waste sorting, reducing the need for manual sorting and increasing recycling rates.
 
- ## [Deep Learning-Based Spoken Digit Recognition](https://github.com/spoluan/sound-classification)
  The ability to recognize and classify spoken digits is a fundamental task in speech processing and pattern recognition. In this project, I leverage a dataset consisting of 30,000 audio samples of spoken digits (0-9) from 60 different speakers by harnessing the power of deep learning techniques  to develop a robust and accurate system for automated spoken digit recognition.

- ## [Medical Abstracts Classification: Developing a Deep Learning Model for Categorizing Medical Research Articles](https://github.com/spoluan/PubMed200kRCT_medical_abstracts_classification)
  The Medical Abstracts dataset is a collection of text data consisting of medical abstracts from various research articles. The dataset is categorized into five classes, namely BACKGROUND, CONCLUSIONS, METHODS, OBJECTIVE, and RESULTS, which correspond to different sections of the research articles. This dataset provides a valuable resource for developing natural language processing (NLP) models for text classification and information extraction in the medical domain. In this project, I aim to implement a machine learning model that can accurately classify the medical abstracts into their respective classes.

- ## [Image Captioning with Flickr30k Dataset: Transformer Model with MultiHeadAttention for Describing Image](https://github.com/spoluan/flickr30k_image_captioning)
  The Flickr30k dataset is widely used in image captioning research and serves as a benchmark for evaluating the performance of different models. With approximately 31,000 images, each having five different captions, the dataset offers a diverse range of descriptions that are crowdsourced. For a better understanding of the image-caption relationship in this dataset, I will employ a Transformer model that utilizes a MultiHeadAttention layer.

- ## [US Insurance Regression: Predicting Health Insurance Charges Using Deep Learning Algorithms](https://github.com/spoluan/USInsurance_regression)
  The aim of this project is to predict the next charge of health insurance for individuals in the United States using a dataset containing various factors, including age, BMI, smoking status, region, and number of children. The dataset provides valuable insights into the cost of health insurance and allows us to analyze the factors that influence the charges. The prediction of the next charge of health insurance can assist individuals and insurance companies in planning and budgeting for future expenses. In this project, I will use machine learning algorithms to build a model that can accurately predict the next charge of health insurance for individuals based on their demographic and health-related information.

- ## [TMDB Movie Recommendation System: Hybrid Approach with Content-Based and Collaborative Filtering Techniques](https://github.com/spoluan/TMDB_5000_Movie_recommendation_system)
  This project focuses on developing a movie recommendation system using a hybrid approach that combines both content-based and collaborative filtering techniques. The dataset used for this project will include movie titles, genres, and other related features. Content-based filtering will be utilized to analyze the user's movie preferences and recommend similar movies based on their genre, keywords, and taglines. Collaborative filtering will consider the user's movie ratings and suggest highly-rated movies by users with similar preferences. To enhance the accuracy of the system, I will also incorporate a weighted average method. The ultimate goal of this project is to provide an efficient and personalized movie recommendation system that enhances the overall movie watching experience of the user.

- ## [Cat and Dog Classification: Deep Learning-Based Image Classification for Distinguishing Cats and Dogs](https://github.com/spoluan/Cat_dogs_classification)
  In this project, I will be implementing a binary image classification system to differentiate between cats and dogs. The dataset used for this project will consist of a large number of images of cats and dogs, which will be used to train and validate the deep learning model. The goal of this project is to develop an accurate classification system that can effectively distinguish between cats and dogs in real-world images. This project can have many potential applications, such as automatic pet monitoring systems, animal behavior studies, and more. By accurately classifying images of cats and dogs, this project can contribute to advancements in computer vision technology and improve the accuracy and efficiency of various related applications.


- ## [Flower Classification: Deep Learning-Based System for Identifying Flower Species from Images](https://github.com/spoluan/FlowerClassification)
  In this project, I will be implementing a flower classification system. The system will use deep learning techniques to identify different species of flowers based on their images. The dataset used for this project will consist of images of various flowers, including daisies, roses, sunflowers, and tulips. The goal of this project is to build a model that accurately classifies images of flowers, which can be useful in fields such as agriculture, botany, and horticulture.  
 
- ## [Fashion MNIST Classification: Deep Learning-Based Clothing Item Classification Using the Fashion MNIST Dataset](https://github.com/spoluan/Fashion_mnist_classification)
  Fashion MNIST classification is a project that involves the classification of different types of clothing items using machine learning algorithms. The Fashion MNIST dataset consists of 70,000 grayscale images of clothing items that are 28x28 pixels in size. The dataset is divided into 60,000 training images and 10,000 test images, with each image belonging to one of 10 different categories such as T-shirt/top, trouser, pullover, dress, coat, sandal, shirt, sneaker, bag, and ankle boot. The goal of this project is to build a machine learning model that can accurately classify the different clothing items based on the provided images. This project is suitable for beginners in machine learning and provides a great opportunity to apply different classification algorithms and evaluate their performance.

- ## [Digits MNIST Classification: Handwritten Digit Recognition Using the MNIST Dataset](https://github.com/spoluan/MNIST_digits_recognition)
  The MNIST dataset is a widely-used benchmark dataset for image classification tasks. It consists of a large set of 28x28 pixel grayscale images of handwritten digits, each labeled with the corresponding digit from 0 to 9. The Digits MNIST dataset, in particular, is a subset of the original MNIST dataset that contains 10,000 images for testing and 60,000 images for training. The goal of this classification task is to correctly classify each handwritten digit image into its corresponding digit class. This is a fundamental problem in computer vision and machine learning, and the Digits MNIST dataset has been widely used to evaluate the performance of various image classification models and algorithms.

- ## [Food 101 Classification: Deep Learning-Based Food Categorization Using the Food 101 Dataset](https://github.com/spoluan/Food-101_classification)
  Food 101 is a large and diverse dataset that includes images of 101 different food categories, ranging from apple pie and avocado toast to sushi and pizza. The dataset includes a total of 101,000 images, with 1,000 images per category. Each image is labeled with its corresponding food category, making it an ideal dataset for training a deep learning model for food classification. The goal of this project is to develop a model that can accurately classify images of food into their corresponding categories. The project will involve preprocessing the images, training a deep learning model using techniques such as convolutional neural networks (CNNs). The potential applications of this project include developing a food recognition app or assisting in the automation of food quality control in the food industry.

- ## [Next Word Prediction in Medium Titles: Language Modeling Using LSTM for Improved Search Query Suggestions](https://github.com/spoluan/MEDIUM_pred_next_words)
  In this project, I will be implementing a language modeling task of predicting the next words in Medium post titles. The Medium dataset, which can be downloaded from Kaggle, will be used for this purpose. The objective is to develop a deep learning model that can accurately predict the next words given the context of the post title. The focus will be on predicting the title only, assuming that users will type it in the search bar, and the model will suggest the most probable sentences that the user may type. This project aims to improve the user experience by suggesting relevant and accurate search queries.

- ## [Transforming VGG16 into U-Net for Deep Learning-Based Segmentation of Oxford-IIIT Pet Dataset](https://github.com/spoluan/semantic-segmentation-Oxford-IIIT-Pet)
  In this project, I'll delve into deep learning-based segmentation, specifically focusing on the Oxford-IIIT Pet dataset. This dataset boasts a vast collection of meticulously annotated images featuring adorable cats and dogs. To tackle this task, I'll take the VGG16 model and give it a makeover to align with the U-Net architecture.