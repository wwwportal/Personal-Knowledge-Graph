# Personal Knowledge Graph
## Project Overview:

1.  Use Brightspace API and user credentials to get course contents
    1.1. Identify relevant API endpoints
        1.1.1. List of courses user is enrolled in
        1.1.2. Content structure of a specific course
        1.1.3. Details about a specific topic and its contents
    1.2. Address security concerns
        1.2.1. Use secure authentication methods like OAuth 2.0
2.  Identify topics and subtopics based on course contents
    2.1. spaCy for text pre-processing
    2.2. Gensim API for topic modeling tools
3.  Create topic and subtopic nodes
4.  Generate tests relevant to each topic node
    4.1. Quiz
        4.1.1. True or false
        4.1.2. Multiple choice
        4.1.3. Fill in the blanks
        4.1.4. Short answer
    4.2. Coding challenges
5.  Set forgetting curve timer
    5.1. Exponential increase
6.  Prompt user to take test again once timer approaches zero
    6.1. Notification System
