This is phython program for implementation of an audio personal chatbot,it consist of an intracting UI using simple web socket server.
The essential requierments are being listed in the requirement.txt file, install them using pip install.
The data file contains coversations or data sets which are trained for the working of the project.
The python file chatbot_train.py actually trains the data in data file.Once it is trained , the result will be stored as db.sqlite.
The chatbot.py uses this db.sqlite to generate responses for user queries.
The file server.py send back the files to our User Interface Index.html file.
The advantages of this bot is that it comes with personal data storage and an audio outputs.
