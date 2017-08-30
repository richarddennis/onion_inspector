A simple tool - written in pure python - for inspecting Deep Web URLs (or onions). 
It takes specified onion links and returns their current status along with the site's title.

Compatible with Python 2.6 & 2.7.

.. image:: https://travis-ci.org/k4m4/onioff.svg?branch=master
    :target: https://travis-ci.org/k4m4/onioff
.. image:: https://img.shields.io/badge/say-thanks-ff69b4.svg
    :target: https://saythanks.io/to/k4m4
.. image:: https://img.shields.io/badge/made%20with-%3C3-red.svg
    :target: https://github.com/k4m4
.. image:: https://img.shields.io/badge/license-MIT-blue.svg
    :target: https://github.com/k4m4/dymerge/blob/master/LICENSE

-------------

Installation
-------------

You can download by cloning the `Git Repo and simply installing its requirements::

    $ git clone "URL TO GITHUB APP HERE"
    
    $ cd onioff
    
    $ pip install -r requirements.txt

Usage
------

Usage: **python onioff.py {onion} [options]**

To view all available options run:

::

    $ python onioff.py -h

**NOTE**: In order for ONIOFF to work, Tor must be correctly configured and running.

Demo
-----

Here's a short demo:

.. image:: https://nikolaskama.me/content/images/2016/09/onioff_demo.png
   :target: https://asciinema.org/a/87557?autoplay=1

(For more demos click `here <https://asciinema.org/~k4m4>`_)
