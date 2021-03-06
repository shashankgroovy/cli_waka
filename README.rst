CLI Waka
========

A command-line interface for `Wakatime.com`_.
It logs user's durations, heartbeats, stats, summary and more.

|pypi| |license|

Installation
------------

::

    $ pip install cliwaka

Or download from `source`_, ``cd`` to it and build using ``python setup.py install``

Requirements
------------

* `Requests`_ library
* `Wakatime.com`_ account and its api key

Usage
-----

`cliwaka` displays a help text when used with `-h` or `--help`.

::

    $ cliwaka -h
    usage: Cliwaka [-h] [-b] [-d] [-t] [-s] [--leaderboard] [-v] [-V]

    A command line tool for wakatime.com.

    optional arguments:
    -h, --help       show this help message and exit
    -b, --heartbeat  show user's latest heartbeat
    -d, --duration   show user's logged time for a given day
    -t, --stats      show user's current stats.
    -s, --summary    show user's logged time.
    --leaderboard    display the public leaderboard
    -v, --verbose    toggle verbose on (default is off)
    -V, --version    show program's version number and exit

    For more information see http://github.com/shashankgroovy/cliwaka

Upgrade
------------

::

    $ pip install -U cliwaka

License
-------

Cliwaka is released under the `GNU GPL License v3`_

.. _Requests: https://pypi.python.org/pypi/requests
.. _Wakatime.com: https://wakatime.com
.. _source: https://github.com/shashankgroovy/cliwaka/archive/master.zip
.. _GNU GPL License v3: http://www.gnu.org/licenses/quick-guide-gplv3.html

.. |pypi| image:: https://img.shields.io/pypi/v/cliwaka.svg
    :target: https://pypi.python.org/pypi/cliwaka
    :alt: Latest version released on PyPi
.. |license| image:: https://img.shields.io/badge/license-GPLv3-blue.svg
    :target: https://raw.githubusercontent.com/shashankgroovy/cliwaka/master/LICENSE.txt
    :alt: GPLv3 License
