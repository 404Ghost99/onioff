ONIOFF
=======

`ONIOFF <https://nikolaskama.me/onioffproject/>`_ - **Onion URL Inspector**

A simple tool - written in pure python - for inspecting Deep Web URLs (or onions). 
It takes specified onion links and returns their current status along with the site's title.

Compatible with Python 2.6 & 2.7.

Author: `Nikolaos Kamarinakis <mailto:nikolaskam@gmail.com>`_ (`nikolaskama.me <https://nikolaskama.me/>`_)

.. image:: https://nikolaskama.me//content/images/2016/09/onioff_med-1.png

Installation
-------------

You can download ONIOFF by cloning the `Git Repo <https://github.com/k4m4/onioff>`_ and simply installing its requirements::

    $ git clone https://github.com/k4m4/onioff.git
    
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

License
--------

Copyright 2016 by `Nikolaos Kamarinakis <mailto:nikolaskam@gmail.com>`_. All rights reserved.

ONIOFF is under the terms of the `MIT License <https://www.tldrlegal.com/l/mit>`_, following all clarifications stated in the `license file <https://raw.githubusercontent.com/k4m4/onioff/master/LICENSE>`_.


For more information head over to the `official project page <https://nikolaskama.me/onioffproject/>`_.
You can also go ahead and email me anytime at nikolaskam{at}gmail{dot}com.
