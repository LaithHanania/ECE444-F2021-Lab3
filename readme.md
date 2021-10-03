Name: Laith Hanania <br />
This repo is a clone of https://github.com/nelaturuk/education_pathways <br />


# Activity 1
<img width="553" alt="Activity 1" src="https://user-images.githubusercontent.com/50575615/135761633-e7364a84-fd66-4f3b-9dc0-0e2672537a9d.png">


# Activity 2
![Activity 2](https://user-images.githubusercontent.com/50575615/135761634-d99575ce-a316-47da-a731-ace5de6455f3.png)


# Activity 3
<img width="766" alt="Activity 3" src="https://user-images.githubusercontent.com/50575615/135761639-23f2445e-a089-47a6-bb67-144007a0697b.png">


# Activity 4
Education pathways on localhost:5000 : <br />
![Activity 4 - 1](https://user-images.githubusercontent.com/50575615/135761648-68732a05-a415-4780-8355-a9ea2cb6af48.png)

Docker running: <br />
<img width="1211" alt="Activity 4 - 2" src="https://user-images.githubusercontent.com/50575615/135761659-d76f37da-ce34-4b48-9d71-6df4422e8f3c.png">


# Activity 5
functional: The application should have the ability to allow the user to slect courses and add them in a cart <br />
Non-functional: The application should be accurate, querying similar terms should lead to consistently similar and expected results (i.e searching for engineer / engineering should lead to the same or similar set of results) <br />


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
