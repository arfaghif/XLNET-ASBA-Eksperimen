# TRANSFER LEARNING PRETRAINED XLNET MODEL FORINDONESIAN ASPECT-BASED SENTIMENT CLASSIFICATION (FINAL PROJECT)

Aspect-based sentiment analysis (ABSA) is widely used in product and service company. One of the tasks in ASBA modeling is the classification of sentiments for a given aspect. Building an automation model requires a lot of data resources, lack of available labeled data and consumes a lot of time and costs. After the transformer-based model was proposed, it prompted a large number of studies using transformer-based transfer learning models to complete many tasks in natural language processing.


This research builds a model for aspect-based sentiment classification using the XLNet Malay model with a finetuning and post-training method approach that accepts input in the form of sentence-pairs. XLNet is a model introduced to overcome the weakness of the BERT model which is an autoencoding model. Conducts Post-training to increase task and/or domain awareness to produce better finetuned models with unlabeled corpus data. This Indonesian language aspect- based sentiment classification research was conducted for three different domains, namely hotels, cars, and restaurants.


The experimental results show that there is an increase in model performance when post-training is carried out on the pre-trained model to complete the task of sentiment classification based on aspects of Indonesian language. The model created was able to outperform previous studies using the mBERT model with f1 scores of 0.9778 and 0.9411. The results showed that conducting post- training using review corpus data from different domains can improve model performance and will be more effective if the domain is close to the domain to be trained. The performance of the model for the restaurant domain increased from f1 score 0.8375 to 0.9254 after conducting post- training with the combined hotel and restaurant corpus data.


Keywords: aspect-based sentiment analysis, XLNet, post-training, finetuning, sentence-pair
