Command Line Applications
=========================

.. todo:: Explain "Command Line Applications"

Clint
-----

`clint <https://pypi.python.org/pypi/clint/>`_ is a python module which is 
filled with very useful tools for developing commandline applications.
It supports features such as; CLI Colors and Indents, Simple and Powerful
Column Printer, Iterator based progress bar and Implicit argument handling.

docopt
------

`docopt <http://docopt.org/>`_ is a lightweight, highly Pythonic package that
allows creating command line interfaces easily and intuitively, by parsing
POSIX-style usage instructions.

Plac
------

`Plac <https://pypi.python.org/pypi/plac>`_ is a python module that allows developing command line applications. In fact 
plac is a simple wrapper over the python standard library `argparse <http://docs.python.org/2/library/argparse.html>`_, it hides most of its 
complexity by using a declarative interface: the argument parser is inferred 
rather than written down by imperatively. It is targetting especially unsophisticated
users, programmers, sys-admins, scientists and in general people writing throw-away
scripts for themselves, choosing the command-line interface because it is quick
and simple.

Cliff
------

`Cliff <https://cliff.readthedocs.org/en/latest>`_  is a framework for building command line programs. 
It uses setuptools entry points to provide subcommands, output formatters, and other extensions. The framework
is meant to be used to create multi-level commands such as subversion and git, where the main program handles 
some basic argument parsing and then invokes a sub-command to do the work.
