# Personalized-Virtual-Assistant
Machine learning based face recognition system for virtual assistant identifies a  user by using face recognition
 
 About the Project:
This project is a streamlit app based on personalized assistant IDA that can perform specific tasks like setting up alarms and reminders , playing music , initiating web searches and answer to general questions which  is combined with face recognition technology to maintain data privacy by providing access only to the registered and recognized users. Solving the issue of data privacy that is most common among the popularly available assistants in the market is its main functionality. 
OpenCV and Speech Recognition are the main packages used while for  Face Recognition Haar Cascade Algorithm is used. 
The user registers in the app and his data can be accessed only when the face is recognized by the assistant with the registered face.





Features :

Face Recognition anf Data Privacy

Deep Face Analysis ( Detecting Age, Race,Gender and Emotion)

Performing Mathematical Computations

Initiating Web Searches through Wikipedia and Google 

Setting personalized reminders 

Providing Weather and News Report 

Playing music through Youtube searches

Providing general answers to User's Queries.





In the Proposed System architecture camera captures the photo of the user and then it trains the models for the images stored in the database with respective to the features of the person. In the detection section it detects the face based on the haarxml file which has some pre-defined features of face. After detecting the face, it will start extracting the features of the face. By considering the features the images are classified accordingly. These classified images are compared with the trained models. If it matches the user can access the virtual assistance.
