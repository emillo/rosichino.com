# Orchestra Rosichino web site
this repo contains the web site of the italian band "Orchestra Rosichino"

The web site is built with [Pelican](https://docs.getpelican.com/en/latest/), a static site generator written in python.

Specifically, the version used is the one shipped with debian 12 ``bookworm``: 4.8.0+dfsg-1

 
## Local development

In order to make changes to the site, you must first install pelican and make:

```
sudo apt install pelican make
```

then you can run 
```
make devserver
```
