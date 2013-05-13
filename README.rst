saycloud: text to soundcloud
============================

Saycloud is a little python script (and some ancillary helpers) that glues together OSX's 'say' text-to-speech synthesiser with Soundcloud.

`You end up with something like this <https://soundcloud.com/cellols/test-foo-bar-baz#play>`_.

Installation
------------

.. code-block:: bash

  $ pip install saycloud

or

.. code-block:: bash

  $ easy_install saycloud

Usage
-----

.. code-block:: bash

  usage: saycloud [-h] [-t TITLE] -s SAY [-v VOICE]

  Saycloud - text to Soundcloud.

  optional arguments:
    -h, --help            show this help message and exit
    -t TITLE, --title TITLE
                          Track title (on Soundcloud)
    -s SAY, --say SAY     Words to say.
    -v VOICE, --voice VOICE
                          Voice to use (get a list with "say -v ?").

Example
-------

An entertaining little example to get you going:

.. code-block:: bash

  $ saycloud -t "Test Foo Bar Baz" -v "Cellos" -s "Foo foo foo foo foo foo bar foo foo bar bar bar baz foo foo foo foo foo foo foo bar foo bar foo bar baz"


Which will run something like this the first time around:

.. code-block:: bash

  Incorrect username/password
  username: cellols
  Password:
  Do you want to store your Soundcloud username and password at
  ~/.saycloud so you don't have to enter them in future? (y/n) y
  https://soundcloud.com/cellols/test-foo-bar-baz

