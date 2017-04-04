# landmark-reg

Interactive tool for landmark-based spatial alignment of volumetric images

# Developement set-up

Prerequisites:
* Python version 3.4 or later;
* Nodejs and the NPM package manager.

First, set up a virtual environment for the back-end under `venv/`, and install
the dependencies there:

    python3 -m venv venv
    . venv/bin/activate
    python -m pip install -r requirements.txt


Once this is done, you can use `npm start` to install the dependencies, build
the front-end, and start the backend in debug mode.

    . venv/bin/activate
    npm start

The app should be accessible on http://localhost:5000/ .

If you make changes to the front-end you may want to use `npm run test:watch`
to automatically run tests on every change, and `npm run build:watch` to
automatically re-build the JavaScript bundle that is served to the browser
(`frontend/bundle`).


# Tests

## Unit-tests for the frontend

    npm run test

## Unit-tests for the backend

TODO

## End-to-end tests

TODO
