Flask template for YunoHost
===========================

## Disclaimers
**Warning:** This YunoHost app is still in development. Use it at your own risk!

## Overview
This is a fork of Flask template for YunoHost.
This fork doesn't include database dependencies because it would break the installer.

It will setup a basic Hello World app in `/var/www/<appname>`.

You can then use it to : 

- start developing an app
- or install an existing app by replacing the appropriate files
- or package your flask app using this app template

Technologies
------------

- Python 3
- Gunicorn

Todo
----

- [ ] Really set app label
- [ ] Handle public/private option
- [ ] Add database features
- [ ] Document how to launch a dev server
- [ ] ???
