saycloud: text to soundcloud
============================

Saycloud is a little python script (and some ancillary helpers) that glues together OSX's 'say' text-to-speech synthesiser with Soundcloud.

Installation
------------

.. code-block:: bash
  pip install saycloud

or

.. code-block:: bash
  easy_install saycloud

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

