## Read Me
### Information Recommender System for Students

This is an information recommender system designed for CDM students. Basically, the system is based on a content-based search engine with website data as data pool and students' profile as queries. 

If there are any questions, please feel free to contact with me at nicolelee005@gmail.com.

=========================================================================================================================
This project file includes three main files:

a. Project word file - Information Recommendation System for Students_LINNA LI.docx
    This file has the detailed interpretation for the entire project. 

b. Project IPython code - CSC575_Project_LINNA LI.ipynb
    This file includs all the Python code used to build the recommendation system.
    Here are the modules needed to run the system:
	#import urllib2
	#from urllib2 import HTTPError
	#from bs4 import BeautifulSoup
	#import re
	#import numpy as np
	#import math
	#import json

c. JSON files
    This is created for back-up. In the file, there are six JSON file and one IPython file. This recommendation system will first obtain the most recent information from website. Thus, it is possible that the web crawler doesn't work well in other computers. Or sometimes, the news from The Washington Post is hard to get (sometimes you have to run the function several times). For these situations, you might want to use these JSON files. But the recommended information won't be the most recent.

    To use these files, please open the IPython file "Load_JSONfiles.ipynb", copy all the code into the project IPython file, and keep them at the most top. Then, to continue the project, you can skip the website crawler part and go to "Prepared functions" directly. 

=========================================================================================================================

How to run the system:

1. If you don't use the JSON files, you have to run the IPython code from the very beginning. In the web crawler part, I check the results of crawler by calculating the length of them, such as len(l_web1). If the length is 0, you have to run the function again. If you would like to use the data in JSON, please review the description above. 

2. After you get all the information data repository, you will start the "Prepared functions" and "Ranking Results" function. This won't take long.

3. Next part is "Student profile database". This is the virtual database, and will be updated with the following steps.

4. In "Student inputs", I list the profiles of three students. PLEASE DO NOT RUN the parts with "#Sample inputs X". This is only for your information, and provide the reference for your inputs. Please run the "User Interface" below, where you are able to input the student's information.

5. For separate the results of the three students, please remember the student's name. And in "Run", please run the function with the name of this student. 

6. Similarily, in the "Results" part, please only run the functions with the student's name. 


Thank you!
