## Conversations with Gideon  
### This file contains the list of conversations that will help Gideon build AI products. Feel free to add more conversations and coding patterns here.

`Conversation 1: Customer Segmentation`   

User: "How can I perform Customer Segmentation?"  
Gideon: Here is a coding pattern that can help you [build a K-Means Clustering model](ml-code-patterns/model%20training/customer_segmentation_plotly) 

`Conversation 2: Resume Scorecard`   

User: "How to build a resume scorecard?"  
Gideon: Here are the steps to build a resume scorecard:  

Step 1: Extract the text from a pdf using PyPDF package - [pyPDF code pattern](ml-code-patterns/NLP/text_from_pdf)   
Step 2: Clean the textual data by removing stop words - [Stopword Removal](ml-code-patterns/NLP/stopword_removal)  
Step 3: Setup a NLP Pipeline for keyword extraction - [Keyword Extraction](ml-code-patterns/NLP/NER_Spacy)    
Step 4: Define weights to the extracted keywords and calculate the score of the [resume](ml-code-patterns/NLP/keywords_resume)      

`Converstation 3: Audiobook Generator`

User: "I want to build an app that lets me convert pdfs to audiobooks. Can you help?"
Gideon: Sure thing! Here are the steps to build an Audiobook Generator using Google Cloud APIs:

Step 1: Enable the Cloud Vision and TexttoSpeech APIs in the Google Cloud Console  
Step 2: Create a service account with 'Owner' privileges and store the credentials in a 'credentials.json' file  
Step 3: Create a bootstrap application using the html templates outlined [here](https://www.creative-tim.com/product/argon-design-system)  
Step 4: Integrate the bootstrap application with the Flask code using the steps outlined [here](https://www.digitalocean.com/community/tutorials/how-to-create-your-first-web-application-using-flask-and-python-3)  
Step 5: Here is the code to upload your pdfs to Google Cloud Storage [bucket](ml-code-patterns/flask/google_cloud_storage)
Step 6: Here is the code to detect text from [pdfs](ml-code-patterns/model%20training/detect_text_pdf_cloud_vision)
Step 7: Here is the code to convert the recognized text [above](ml-code-patterns/model%20training/audiobook_generator)

`Conversation 4: Text Search Engine`  

User: "I want to build a NLP-powered search engine for an internal Knowledge Management portal. Can you help?"  
Gideon: Here you go. [Build a search engine using Transformers](ml-code-patterns/model%20training/qa_system_transformers)  

 `Conversation 5: Text Recommendation Engine`  
 
 User: "I have a bunch of articles. I want to build a Recommendation engine akin to Netflix for these articles. Any ideas?"  
 Gideon: Here are the steps you can follow for building a text recommendation engine:  
 
 Step 1: Scrape the text from the articles. Here is a [code recommendation](ml-code-patterns/NLP/scrape_text_from_external_articles)  
 Step 2: Clean the text using this [code recommendation](ml-code-patterns/NLP/Text_Preprocessing)  
 Step 3: Generate the embeddings for the cleaned text using [Word2Vec](ml-code-patterns/NLP/Word2Vec-Gensim)  
 Step 4: Start finding the most similar articles to a given article using the [cosine similarity code recommendation engine](ml-code-patterns/NLP/Cosine_Similarity_Recommendations)

`Conversation 6: Product Review Summarizer`  

User: "I have a bunch of product reviews. I wish to summarize the reviews using NLP."  
Gideon: Very good. Would you prefer Extractive Summarization or Abstractive Summarization?  
User: Abstractive Summarization please    
Gideon: Here you go. [Abstractive Summarization using BERT](ml-code-patterns/NLP/Abstractive_Summary_BERT) 

`Conversation 7: Anomaly Detector `  

User: "I want to detect anomalies in my dataset. What are the possible approaches?"  
Gideon: Here are 4 different approaches you can explore:  

1.If your data is following a normal distribution, go for [Anomaly Detection using Z-score](ml-code-patterns/Anomaly%20Detection/anomaly_z-score)  
2.If your data can be linearly separated, go for [Anomaly Detection using SVM](ml-code-patterns/Anomaly%20Detection/anomaly_one_class_svm)  
3.If you have no idea about your underlying data distribution, go for [Anomaly Detection using Clustering](ml-code-patterns/Anomaly%20Detection/anomaly_kmeans)  

`Conversation 8: Dataset Recommender`    

User: "I am looking for reference datasets for a problem I am working on. Is there a way I can get that info?"  
Gideon: What is the problem you are trying to solve?    
User: "It is a problem in the Finance domain"  
Gideon: Here is a code repository that can help you build your own [Dataset Recommender](https://github.com/gideon-ai/Dataset-Recommendation-Engine)    

`Conversation 9: AI Product Deployer`

User: "I have a Deep Learning model that I wish to integrate with a bootstrap application and deploy in the cloud. What are the steps?"  
Gideon: Here is the process:  

Step 1: Choose a Bootstrap template from the options available [here](https://www.creative-tim.com/product/argon-design-system)
Step 2: Build a Flask application using the code pattern available [here](ml-code-patterns/flask/build_flask_application)  
Step 3: Create a project in Google Cloud  
Step 4: Create a service account with 'Owner' privileges and store the credentials in a 'credentials.json' file     
Step 5: Create a VM in the Google Cloud Console    
Step 6: Deploy the Flask application in Google Cloud by following the steps in this [coding pattern](ml-code-patterns/flask/flask_google_cloud) 

`Conversation 10: CCTV Analyzer`  

User: "I want to identify objects in a CCTV Video repository. Where should I start?"  
Gideon: YOLO library is a good place to start. Here is a [code pattern](ml-code-patterns/model%20training/obj_detection_video_stream_yolo) that can detect objects in a video stream.  
