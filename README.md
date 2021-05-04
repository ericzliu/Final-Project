# Final-Project
This final project involves the combined usage Textblob and Flask to create a basic sentiment analysis web app. 

## Summary of Project
I focused my Midterm Package Research on Textblob, I still wanted to utilize that aspect. However, I knew that I needed something else to make things more interesting; the purpose of creating this project was so that I could become more familiar with using Flask in conjunction with Textblob. This semester, I have learned not only Python but have also learned the basics and fundamentals for HTML, CSS, and Javascript. As a result, I thought it would be a good idea to utilize these developed skills and create a project around them.
### When analyzing the inputted user text, the app does a basic analysis of two things: polarity and subjectivity.
- **polarity:** defines how positive, negative, or neutral a piece of text is
- **subjectivity:** defines how clear the text is
Polarity is measured as being >0 (positive), =0 (neutral), or <0 (negative).

Similarly, subjectivity is measured on the same scale, with a greater number indicating that the text is more clear and a smaller/negative number indicating the text is more unclear.
## Information Sources utilized
Because this project involved many areas of unfamiliarity, I found myself doing a lot of research and reading/watching countless tutorials in order to find and understand what I wanted to do. Here is a list of some important sites/pages I have come across (and have been able to write down/remember) that have aided me throughout this learning process. For many of these websites, I utilized several resources; I could not have done this project without the help they provided:
- https://www.youtube.com/watch?v=NKJV0ekmo4U&list=WL&index=72&ab_channel=TheCodex
- https://getbootstrap.com/
- https://flask.palletsprojects.com/en/1.1.x/templating/
- https://www.tutorialrepublic.com/faq/how-to-reset-a-form-using-jquery.php
- https://attacomsian.com/blog/javascript-hide-show-dom-elements
- https://jinja.palletsprojects.com/en/2.11.x/
- https://www.codegrepper.com/code-examples/javascript/add+classlist+javascript
- and many more.

## Libararies/imports used:
### [requirements.txt](https://github.com/ericzliu/Final-Project/blob/main/requirements.txt)

## How to successfully run the program
[Creating a Virtual Environment for Flask](https://code.visualstudio.com/docs/python/tutorial-flask)
is necessary for us to do, because we will be installing our packages that way.

## How to successfully install Textblob and Flask
Once you have properly set up your virtual environment, here's how to install the necessary packages:
#### Installing Textblob:
Run the following commands into your terminal:
- python -m pip install textblob
- python -m textblob.download_corpora
#### Installing Flask (and its necessary components):
- python -m pip install flask
- python -m pip install flask_bootstrap

## Overview of Project Code
**Required Libraries and Imports**
![libaries_and_imports](https://user-images.githubusercontent.com/81776233/116954024-c78ff080-ac5c-11eb-8159-aa0deb4edb1a.png)

## Python Code

**This is the default application settup/syntax for Flask applications. It is suggested to create a Flask instance by passing __name__ for this argument.
Bootstrap is an open-source framework code that is specifically used for front end development. We need it because it is used to support the HTML and "CSS" code we have.**
![carbon](https://user-images.githubusercontent.com/81776233/116954250-716f7d00-ac5d-11eb-87f8-9899b4b89e4c.png)

**Index Function**
![index](https://user-images.githubusercontent.com/81776233/116954293-98c64a00-ac5d-11eb-8e4c-234ac9ba756b.png)

**Analyse Function, utilizing Textblob**
![carbon (2)](https://user-images.githubusercontent.com/81776233/116955279-155a2800-ac60-11eb-90e8-7e20455facad.png)

![carbon (1)](https://user-images.githubusercontent.com/81776233/116955024-6a496e80-ac5f-11eb-995f-981487750dc0.png)

**app.run method**
![carbon (3)](https://user-images.githubusercontent.com/81776233/116955337-45093000-ac60-11eb-80e6-fa4d530663b9.png)

## HTML Code (Important Parts)
![carbon (4)](https://user-images.githubusercontent.com/81776233/116955585-fb6d1500-ac60-11eb-8d46-f39541fe0112.png)

![carbon (5)](https://user-images.githubusercontent.com/81776233/116955650-22c3e200-ac61-11eb-8905-4eef33c0fd00.png)

![carbon (6)](https://user-images.githubusercontent.com/81776233/116955760-759d9980-ac61-11eb-8648-82560e99687c.png)

![carbon (7)](https://user-images.githubusercontent.com/81776233/116955821-9bc33980-ac61-11eb-9aa9-9cdeb20fd4a7.png)

## More Ideas
At the end of my Midterm Project, I mentioned that I wanted to create a sentiment analysis project with a Raspberry Pi 4. I still plan on doing this, however, my plan was to use wiring, resistors, cables, LEDs, etc., all of which were things that I did not have at the time. So because of this, I invested time into learning about Flask, and still kept the sentiment analysis part of it into my project.
If I were to think of another near-future project I'd be interested in making, I think a blog app could be a very cool idea. Other ideas that come into mind would be a weather app or a portfolio website. There are many great ideas out there that I'd be willing to try, after completing such a project.
