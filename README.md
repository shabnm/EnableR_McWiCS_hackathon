# ImplementAI Hackathon 2019
# EnableR : Application to enable the differently abled people

Steps for user: 

- User left click on "file:/// wants to: Use your microphone (alert dialog)", and select Allow

![Test Image 1](https://github.com/shabnm/EnableR_ImplementAI_hackathon/blob/master/Enable_microphone.PNG)

- Speak your query (use format for initial input : "From" to "To" on "Day")<br/>
  *for example-Toronto to Montreal on Monday* <br/>
  **Limited dataset:  {"T-M Express": ["Toronto","Montreal", "Monday", "Tuesday", "Sunday"],"O-T Express": ["Ontario", "Toronto", "Tuesday", "Wednesday", "Saturday"],"Toronto     superfast" : ["Toronto", "Montreal", "Tuesday"]};  ** <br/>
  *try with this input combinations only, as we have limited dataset* <br/>
  
![Test Image 1](https://github.com/shabnm/EnableR_ImplementAI_hackathon/blob/master/query.PNG)

- Results will be automatically filled, and clicking on Our recommendation button will read out the train list

Steps for coder: 

- I have used HTML5 speech recognition to initially record user inputs : https://codeburst.io/html5-speech-recognition-api-670846a50e92

- To, from and the date of travel from speech to text conversion

- Extracting data from the text, taken from above process, to search through data set to suggest most appropriate route to the user.

- Taking input from user and doing information retrieval from the data and returming the result
