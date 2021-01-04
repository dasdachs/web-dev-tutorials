# Smartninja tutorials


Some additional material for my [SmartNinja](https://www.smartninja.org/) courses.


## How to read these tutorials

### Disclaimer 
Hopefully it goes without saying, but just to be safe: the code in the tutorial is not production ready and might be missing some important performance or security features. 

These tutorial represent complementary material for my web development courses I teach at SmartNinja. If you are not enrolled in these course, you might still find them useful, but I highly recommend to take them up.

You can find the tutorial in the respective directory. Some include code samples or whole projects, while others don't. 

### Code snippets

Python snippets use the [type hints](https://docs.python.org/3/library/typing.html). This is optional and you do not need to use this in your code, although you will find that it improves readability and IDE support.

Code snippet include comments in their respective language they are written. The file system snippets use bash comments (`#`).

The first comment is usually the name of the file in the tutorial. If you decide to use a different naming/layout ignore it.

Three dots (`...` ) indicate missing code that should be easy to fill in based on the **Prerequisites** paragraph in the tutorial. 

E.g. if you encounter a snippet for like this

```python
# file: main.py
from flask import Flask

...

@app.routes("/")
def index():
    return b"Hello world!"

```

The snippet assumes you are comfortable instantiating the flask app.

```python
# file: main.py
from flask import Flask


app = Flask(__name__)   # omitted part


@app.routes("/")
def index():
    return b"Hello world!"

```

If you don't know how to write the missing code, make sure to go through the tutorial's *Prerequisites*, look at the official course material and previous recordings, google etc. If nothing helps, feel free to contact me via the our Slack channel.

### Api testing

Where apis are used the tutorials uses the python cli package [httpie](https://httpie.io/docs) to make HTTP requests. 

You can of course use [postman](https://www.postman.com/) or `curl` or any other application you feel comfortable with.

## Table of content


## Misc

Feel free to contact me via mail or twitter.

PRs are always welcome, although I might reject some because the content is meant to be primarily used along the courses I teach.
