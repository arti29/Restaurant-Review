### Restaurant Review App

## Table of Contents

* [Overview](#overview)
* [Specification](#specification)
* [How to run the project](#howtoruntheproject)
* [Contributing](#contributing)

## Overview:

For the **Restaurant Reviews** projects, I incrementally converted a static webpage to a mobile-ready web application. I took a static design that lacks accessibility and converted the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for users.

### Specification

I was provided with the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. My job was to update the code to resolve these issues while still maintaining the included functionality.


### How to run the project

1. Download or clone the repository to your computer.
2. In project folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
3. With your server running, visit the site: `http://localhost:8000`, this will load the application.


## Contributing

* Starter code by Udacity.
* Leafletjs, an open-source JavaScript library for mobile-friendly interactive maps.
* Mapbox, an open source mapping platform for custom designed maps.
* Youtube presentations and some other online references.
* Font: https://fonts.googleapis.com/css?family=Coda
* Font Awesome: https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css
