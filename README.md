# TextUtils
_A web tool to analyse and process text using Django backend._<br/>
This is my first website built with Django. This website is all about changing the input text, such as removing punctuation, capitalization, newlines, and extra spaces.
All of these operations are carried out on the backend using Python.


## Features:

- Capitalization
- Remove newlines
- Remove extra spaces
- Remove punctuations


## Future Features:

- Sentense case
- Adding pumctuations
- Capitalizing each word
- Text effects like **Bold**, _Italic_, ~Strikethrough~, etc.


## Requirements:

- Django - `pip install Django`
- HTML and basics of python


## How to run?

1. Clone or download this repo to your system.
2. Open terminal or cmd and `cd` into `/Textutils/`.
3. Type `python manage.py runserver` in terminal or cmd and hit enter.
4. Go to `http://127.0.0.1:8000/` from your browser to view the webpage.
    - It will look similar to [this](#home-page)


## How to use?

1. Enter the text you want to change in the textbox on `http://127.0.0.1:8000/` (see [How to run?](#how-to-run)).
2. Select what you want to do with your text, i.e, [Features](#features).
3. Click the `Analyze Text` button and view your analyzed text.
    - It will look similar to [this](#analyzed-text)


## How it looks like?

### Home page

![Home](https://github.com/HarshShroff/TextUtils/blob/main/imgs/Home.png)

### Analyzed text

![Analysis](https://github.com/HarshShroff/TextUtils/blob/main/imgs/AnalyzedText.png)
