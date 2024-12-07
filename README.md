Ai Chemist
 
Project Flow

•	User interacts with the UI to enter the input. 

•	User input is collected from the UI and transmitted to the backend using the Google API key.

•	The input is then forwarded to the Gemini Pro pre-trained model via an API call.

•	The Gemini Pro pre-trained model processes the input and generates the output.

•	The results are returned to the frontend for formatting and display.



To accomplish this, we have to complete all the activities listed below:


Requirements Specification

o	Create a requirements.txt file to list the required libraries. 

o	Install the required libraries

o	Installed the streamlit to deploy the application.

o	Installed the generative ai to enable the LLM and text generation model.  

o	Installed the dotenv to load the environment variables which is in this case is Google API key 



Initialization of Google API Key

o	Generate Google API Key to integrate the Gemini API docs to our project

o	Initialize Google API Key by creating the .env or environment variable file. 



Interfacing with Pre-trained Model

o	Load the Gemini Pro pre-trained model 
 
o	Implement a function to get Gemini response. 

o	Implement a function to read the image. Write a prompt for Gemini model 

o	Initialisation of the submit (Tell me) button to take response from the API. .
 


•	Model Deployment

o	Integrate with Web Framework 

o	Host the Application on Streamlit by using “streamlit run app.py” command. 
 


•	Functioning of the Model

o	We use Images from the web to test the functioning of the model      
 	 
 	 

