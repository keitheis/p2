p2: Rerun command when given filed changed
==========================================

.. image:: http://img.shields.io/pypi/v/p2.svg?style=flat
   :target: https://pypi.python.org/pypi/p2

.. code-block:: sh

  % p2 'make' *.plim static/*.scss
  Player Two is watching about 6 files [ base.plim content.plim index.plim oldcontent.plim oldindex.plim static/index.scss].
  CONTINUE?
  make
  python -mscss < static/index.scss > static/index.css
  plimc -H -o index.html index.plim
  FIGHT!
  content.plim changed
  CONTINUE?
  make
  python -mscss < static/index.scss > static/index.css
  plimc -H -o index.html index.plim
  FIGHT!

Installation
------------

.. code-block::

  pip install p2
