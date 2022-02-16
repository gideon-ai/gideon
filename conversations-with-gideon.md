## Conversations with Gideon  
### This file contains the list of conversations that will help Gideon build AI products. Feel free to add more conversations and coding patterns.

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

Conversation 4: Textbook Chatbot  

Conversation 5: Video Search Engine  

Conversation 6: Text-to-Image Generator  

Conversation 7: Product Review Summarizer  

Conversation 8: Email Analyzer    

User: "I have a bunch of emails that I want to be analyzed. Can you help?"  
Gideon: Sure. Follow this [tutorial](https://youtube.com) and give me the link to the zip file containing the emails.  
User: Here you go - https://youtube.com  
Gideon: Great. I will mail you the report soon after the processing is complete.  

Conversation 9: Video Summarizer  

User: "Can you help me with the video summary of a webinar?"  
Gideon: Sure. Please provide the link  
User: Here you go - https://www.youtube.com/watch?v=i6XsRVcNThE  
Gideon: Great. I will mail you the summary once the video summary is ready.

Conversation 10: Audiobook Generator
