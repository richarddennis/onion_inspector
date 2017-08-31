A simple tool - written in pure python - for inspecting Deep Web URLs (or onions). 
It takes specified onion links and returns their current status along with the site's title.

Compatible with Python 2.6 & 2.7.


-------------

Installation
-------------

You can download by cloning the `Git Repo and simply installing its requirements::


    apt-get install tor
    nano /etc/tor/torrc
        Edit the torrc with this ADD AUTHENTICATION ON PORT 9050 !!
        ControlPort 9051
        # hashed password below is obtained via `tor --hash-password my_password`
        HashedControlPassword 16:4B686E879FB96E1460637C8FCB6FEBAEF9C88CCDA997027AE52F2B22C8
        CookieAuthentication 1        
    git clone https://github.com/richarddennis/onion_inspector.git
    cd onion_inspector
    apt-get install python-pip
    pip install -U pip setuptools    
    pip install -r requirements.txt
  

Usage
------

Usage: **python onioff.py {onion} [options]**

To view all available options run:

::

    $ python onioff.py -h

Demo
-----

Here's a short demo:

.. image:: https://nikolaskama.me/content/images/2016/09/onioff_demo.png
   :target: https://asciinema.org/a/87557?autoplay=1


