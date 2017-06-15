# Send An SMS

This is sample code from an upcoming blog post describing how to Send SMS Messages with Python and Flask.

# Installation

The project was written for Python 3, but should work with Python 2 just fine.

We recommend installing into a [virtualenv][virtualenv]. Once you have your virtualenv created and activated, run the following to install the project requirements:

```bash
pip install -r requirements.txt
```

# Configuration

Copy `.env-example` to `.env` and fill it in with your Nexmo credentials and the Nexmo number you want to send SMS from.

# Run It!

Run the service with:

```bash
FLASK_APP=smsweb/__init__.py flask run
```

Now if you open up your browser to: [http://localhost:5000/](http://localhost:5000/) you should see a form for sending SMS messages!

[virtualenv]: https://virtualenv.pypa.io/en/stable/userguide/