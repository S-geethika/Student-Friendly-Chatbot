# INST-StudentFriendlyChatbot
In educational institutions, it is a difficult to task for a student to get all the details needed. With the growing technology, there are many student-friendly assistants for information retrieval. A Chatbot is one among them. 

AIM OF THE PROJECT: To develop a user interface that responds to the student queries instantly.

This chatbot uses the computer as an interface to take the queries from the user.
The given input is recognised by the lex as tokens. Rules for each token are defined and are processed as sql queries. The query results are displayed to the user.

Technologies used : C, MySql, Lex

Files Description
1. sample database
 a. cse_marks
 b. cse_grades
2. lex file : ask.l
3. c file : reply.c

RUNNING THE CODE
1. lex ask.l (generates lex.yy.c)
2. gcc -o run $(mysql_config --cflags) reply.c $(mysql_config --libs) lex.yy.c (compiles and links .c, lex files)
3. ./run






