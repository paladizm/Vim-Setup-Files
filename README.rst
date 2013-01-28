Vim Setup Files
===============

These are my personal setup files for my vim setup. Currently they are pretty bare bones and work for what I do. There are some plugins that I am using that make Python development with Vim a little easier like jedi-vim, and supertab. 

Prerequisites
=============

Vim Installation with python module installed (This is pretty standard on linux) 

To check just run, 

.. code-block:: vim

    $ vim --version

    look for the +python in the stdout

Also install jade (Makes the python autocomplete work)

.. code-block:: vim

    $ pip install jade

That should be all that you need as of right now. If you have any issues check out this `blog <http://redkrieg.com/2012/12/11/writing-python-like-a-jedi/>`_.

Plugins (installed with pathogen)
=================================

* `jade-vim <https://github.com/davidhalter/jedi-vim>`_

* `supertab <https://github.com/ervandew/supertab>`_

* `sensible <https://github.com/tpope/vim-sensible>`_
