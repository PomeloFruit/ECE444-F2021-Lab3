# ECE444-F2021-Lab3 
Alan Du<br>
This repo is a clone of https://github.com/nelaturuk/education_pathways.

<br>Activity 1<br>![activity1](https://user-images.githubusercontent.com/39738139/135664220-58261a3e-5647-4a43-b2ef-91eb1b04ba3e.PNG)
<br>Activity 2<br>![activity2](https://user-images.githubusercontent.com/39738139/135664249-d1c600e7-d3ae-45cd-ae34-f22b23f28940.PNG)
<br>Activity 3<br>![activity3](https://user-images.githubusercontent.com/39738139/135664285-6821d1af-3bab-4bbe-a825-84296e7091a5.PNG)
<br>Activity 4<br>![activity4](https://user-images.githubusercontent.com/39738139/135664304-f8b5ac4f-f1ba-4b9a-aa13-dad18ce77ee1.PNG)
<br>Activity 5<br>
Functional Requirement: Multiple Profiles<br>
I want to add the ability for the user to save multiple profiles to the Education Pathways tool. I think being able to save multiple profiles of different course selections would be very helpful in course selection.
<br><br>
Non-functional Requirement: Accuracy<br>
I want to improve the accuracy of the results shown by the search/filter system for the Education Pathways tool. When you search "machine learning" with no restrictions in the filter, you will see "Basics of Writing in English" and some Music courses, which have nothing to do with machine learning. I want to change the search system so that relevant courses will be listed.

# CARTE Education Pathways

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
