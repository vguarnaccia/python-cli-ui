====================================
Sample Terminal User Interface (TUI)
====================================
.. image:: https://travis-ci.org/vguarnaccia/easy_tui.svg?branch=master
    :target: https://travis-ci.org/vguarnaccia/easy_tui

This is a small package inspired by the work of Dimitri Merejkowsky. 
You can read about his project on dev.to (which is how I found it) or on 
`his blog <https://dmerej.info/blog/post/introducing-python-cli-ui/>`_.

Installation
============

::

    pip install git+https://github.com/vguarnaccia/easy_tui.git

Update::

    pip install --upgrade git+https://github.com/vguarnaccia/easy_tui.git

Examples
========

To see the latest interactive example::

    python -m tui

.. image:: https://asciinema.org/a/xJ6TffmNGkNigxkEB6jPxcKRM.png?size=medium
    :target: https://asciinema.org/a/xJ6TffmNGkNigxkEB6jPxcKRM?size=medium

Testing
=======

Run doctests with::

    python -m tui.core
