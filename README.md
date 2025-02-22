# Orchestra Rosichino web site
this repo contains the web site of the italian band "Orchestra Rosichino"

The web site is built with [Pelican](https://docs.getpelican.com/en/latest/), a static site generator written in python.


## Local development

In order to make changes to the site, we are going to create and activate a python
virtual environment in the same folder where you cloned or checked out
this repo:


```bash
mkdir venv
python3 -m venv venv
source venv/bin/activate
```

Then we install `pelican`, `markdown`` and `pelican-neighbors`

```bash
python -m pip install pelican pelican-neighbors markdown

```


Then (provided you have the utility `make` installed) you can run

```
make devserver

```

to run the pelican development server.

Then you can point your browser to  `http://localhost:8000` and you will see the development site.

You can change the code and the development server will auto re-compile the pages.
