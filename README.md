# bastille-emmett
Bastille template for Emmett Framework

Emmett Framework is an awesome framework for developing web applications [https://emmett.sh/] written in python

In this case the template creates a virtualenv and runs the app from there.

A script is also included to start and stop the emmett server

```
service emmett start
service emmett stop
service emmett restart
```
The service listens on port 8000


**Warning**
**This is for proof of concept**

I have to see how to copy a real application from the host to the jail

Fetch and apply this template with:

```
bastille bootstrap https://github.com/josejachuf/bastille-emmett
```

```
bastille template TARGET josejachuf/bastille-emmett
```
