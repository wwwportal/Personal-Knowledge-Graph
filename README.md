# Personal Knowledge Graph
## Project Overview:

1.  Use Brightspace API and user credentials to get course contents
    1. Identify relevant API endpoints
        1. List of courses user is enrolled in
        2. Content structure of a specific course
        3. Details about a specific topic and its contents
    2. Address security concerns
        1. Use secure authentication methods like OAuth 2.0
2.  Identify topics and subtopics based on course contents
    1. spaCy for text pre-processing
    2. Gensim API for topic modeling tools
3.  Create topic and subtopic nodes
4.  Generate tests relevant to each topic node
    1. Quiz
        1. True or false
        2. Multiple choice
        3. Fill in the blanks
        4. Short answer
    2. Coding challenges
5.  Set forgetting curve timer
    1. Exponential increase
6.  Prompt user to take test again once timer approaches zero
    1. Notification System
