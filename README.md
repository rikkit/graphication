Graphication
============

In a quest to make new and better code for LastGraph, I decided to make it more
generic and accessible for anyone to use, and so here we have Graphication.

It uses Cairo for rendering, and is designed to be (somewhat) modular and
expandable. Early releases only do wavegraphs, but hopefully this will improve
as time goes on.


Requirements
============
 
 - Python 2.3 or newer
 - pyCairo


Installation
============

(as root):
python setup.py install

If you want instant gratification, then run one of the examples:

 As a script:
  python examples/random_wavegraph.py
 
 As a module:
  python -m "graphication.examples.random_wavegraph"
  
Licence
============

GPLv3. See ```./LICENSE``` for full text.
