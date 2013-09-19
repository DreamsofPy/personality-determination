![Image](http://dreamsofpy.github.io/assets/img/slider/slider1.jpg)

Personality Determination
=========================

This app will help folks determine their personality type. Basic features will allow users to create profiles and create surveys. Advanced features can include social networking component to help users form friendships with complementary and similar personality types.

**User goals:** Complete survey and see results. See what your friends' personality types are.

Tasks:

1. Develop the questionnaire - what the questions and answers should be
	* How many questions? Overall and per page
	* What are the questions, how many answers per question
2. Results - Write up description of personalities
3. Set up database connection
3. Develop forms for entering question/answers, templates to show surveys.
	* Can people make their own "quiz" like blogthings?
	* Is it one standard survey?
4. Design page layout for surveys and results
5. Upload to staging server, test surveys and collect feedback
6. Future ideas
	* See who else has your personality type
	* See who matches your personality type and location
	* Communication between different people
	* See what jobs or activities are recommended for your personality type


##This code base uses these python libraries:

Basic Requirements
-----------------
* [Flask](http://flask.pocoo.org/docs/) Web Framework
* Flask-SQlalchemy
* Flask-WTF
* MySQL-python==1.2.4
* Bootstrap
* [Database]() TBD

## Setup

###Project Structure

    ├── Procfile
    ├── Procfile.dev
    ├── app.py
    ├── config.py
    ├── error.log
    ├── forms.py
    ├── models.py
    ├── requirements.txt
    ├── static
    │   ├── css
    │   │   ├── boostrap-responsive.css
    │   │   └── bootstrap.css
    │   ├── img
    │   │   ├── glyphicons-halflings-white.png
    │   │   └── glyphicons-halflings.png
    │   └── js
    │       ├── libs
    │       │   ├── bootstrap.min.js
    │       │   ├── jquery.min.js
    │       │   └── modernizr-2.0.6.min.js
    │       ├── plugins.js
    │       └── script.js
    └── templates
        ├── 404.html
        ├── 500.html
        ├── index.html
        ├── login.html
        ├── register.html
        └── template.html

Quick Start
----------

1. Clone the repo

        $ git clone git@github.com:DreamsofPy/Personality_Determination.git
        $ cd flask-boilerplate

2. Initialize and activate a virtualenv:

        $ virtualenv --no-site-packages env
        $ source env/bin/activate

4. Install the dependencies:

        $ pip install -r requirements.txt

5. Run the development server:

        $ python app.py

6. Navigate to [http://localhost:5000](http://localhost:5000)

Learn More
---------

2. [Flask Documentation](http://flask.pocoo.org/docs/)
3. [Flask Extensions](http://flask.pocoo.org/extensions/)
4. [Flask-Boilerplate reference](https://github.com/mjhea0/flask-boilerplate)
