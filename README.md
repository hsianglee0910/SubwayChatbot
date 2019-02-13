# Subway Chatbot
The chatbot can answer questions about Beijing Subway, plan a trip as well.

## Functions
    1)Understand the intent of the input and provide suitable response
    2)Greet and introduce the function of this chatbot
    3)According to the user's questions, reply the running route and timetable
    4)Provide the line information, if one specific station has been asked
    5)Find out whether the question user asked is solved
    6)Plan a shortest transfer route for user
    7)Call relevant API, provide a route only taking buses

## Technical points
    1)Build the training data based on Rasa NLU, to understand the intent of natural language
    2)Using key word to distinguish the user's intent
    3)Recognize named entity by regular expression
    4)Establsh the database and the query mechanism
    5)Provide a random reply to the same question
    6)Define the states and policy rules in order to answer contextual questions
    7)Find out the shortest path through breadth-first search
    8)Call Baidu Map API, realizing real-time query
    9)Deploy the chatbot on wechatt, a commonly-used Chinese social networking app
## Demo
