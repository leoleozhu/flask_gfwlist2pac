Flask-Gfwlist2Pac
===============

Current version: 0.0.2

Flask-Gfwlist2Pac is a flask extension to make gfwlist2pac work on flask applications.

### Usage

    from flask import Flask
    from flask.ext.gfwlist2pac import Pac

    app = Flask(__name__)
    pac = Pac(app, url='/')

    if __name__ == '__main__':
        app.run()

### About
The pac generation work is done by clowwindy at [https://github.com/clowwindy/gfwlist2pac](https://github.com/clowwindy/gfwlist2pac)

### Examples
See examples [here](https://github.com/leoleozhu/flask_gfwlist2pac/tree/master/examples)

### Online example
A working heroku app: [https://gfwlist2pac.herokuapp.com/](https://gfwlist2pac.herokuapp.com/)
