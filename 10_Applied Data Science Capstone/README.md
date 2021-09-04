# Applied Data Science Capstone

## Description
This courses teaches how to apply Data Science and some Machine Learning concepts including identifying and clearly defining a problem that can be solved using location data, working with and making calls to APIs, Web Scraping and using location data to solve the problem defined. The individual has also demonstrated proficiency in documenting their work and preparing a full formal data science project report.

## Skills
Technical skills learned in this course are:
- Web Scraping (urllib, Requests, BeautifulSoup)
- Foursquare API (Developer Account)
- Geocoding (Geocoder)
- Data Cleaning & Preprocessing (Pandas, re, NumPy, Scikit-learn)
- Data Visualization (Matplotlib, Folium)

## Assignments & Certificate
This course spans over multiple weeks and it has at least one or more of the following assignments:
- Coding Exercises
- Quizzes (Multiple Choice)

The coding exercises & quizzes are auto-graded by the platform. If you pass a specific threshold (e.g. 80%), you pass the course and get the certificate. If you collect all 10 course certificates within this specialization, you get the specialization certificate.

## Personal Learnings
Some websites block python scripts that try to scrape them (read the /robots.txt from that site first and always obey to the legal rules!) but you can bypass those errors when you don't exceed rate limits (time.sleep(np.random.uniform(0,2)) and when you tell the server that you are a browser (Request-headers: headers = {'User-Agent': 'Mozilla/5.0 (Windows NT 6.1)'}). In the end the data that is scraped is mostly really messy and it is a good practice to check some of the sites by hand to determine if really the correct data was scraped. The most tricky thing is not that the scraping throws NULL or Error at you, it is that it gets you data but you don't know for sure if it is the correct one.

I also learned that just because you standardize or normalize the data doesn't mean that the resulting variables are not skewed. Outliers can still influence a StandardScaler() or MinMaxScaler() so you have to find those outliers and inspect them for plausibility before even consideing to delete them. Not all outliers are false data.

Most of the challenges that make up a good project appear when you are already deep in it and think you are nailing it. That makes it hard to estimate how much time you need for certain tasks; there is always the next error message waiting for you :-) And even if there are not Errors, there are still some things that seemed to be fine in ttheory but when you think about them from a programming point of view and disect the problem with code, you sometimes have to be quiet creative to find new solutions. In that case it is extremely important to document all your decisions - not only what you did, but also **WHY** you did it! Writing a project report besides the comments in your code definitely helps.

## Reference & more Infos
- For more Information visit [Coursera](https://www.coursera.org/learn/applied-data-science-capstone?specialization=ibm-data-science)
- Or visit the [IBM website](https://www.ibm.com/training/badge/9e2e8926-37b6-4db1-b95d-68e45e90ef48)

## 📫 Let's connect and learn from each other:

[<img src="https://github.com/kevin-goetz/kevin-goetz/blob/main/LinkedIn Logo.png" height="40em" align="center" alt="Connect with Me on LinkedIn" title="Connect with Me on LinkedIn"/>](https://linkedin.com/in/kgötz) [<img src="https://github.com/kevin-goetz/kevin-goetz/blob/main/Codewars Logo.svg" height="40em" align="center" alt="Connect with Me on Codewars" title="Connect with Me on Codewars"/>](https://www.codewars.com/users/kevin-goetz)

