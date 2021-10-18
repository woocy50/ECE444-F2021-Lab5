# CARTE Education Pathways

Chang Yeon Woo

This repo is a clone of https://github.com/nelaturuk/education_pathways.

# Activity 1

![image](https://user-images.githubusercontent.com/19890962/137704600-f65f8a1c-5565-4ac8-9485-cbc0b1b22520.png)

# Activity 2-5
## Home page
![image](https://user-images.githubusercontent.com/19890962/137705037-8a694ef2-55ae-4e74-b060-c595fba642b7.png)

## Results page
![image](https://user-images.githubusercontent.com/19890962/137704942-5fa20076-4890-4f9b-9ed5-f018225ca615.png)

# Activity 6
The new UI looks more pleasing, now with appropriate margins and borders. However, it still looks very basic -- much like early 2000s websites. In our project, we should use more asthetic approaches such as cards to format the texts/buttons/etc. even nicer.

-----------------------

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
