Lab 10 - Arduino Clock
======

Getting started:
----------------
Our group initially had a hard time running the initial LCD code due to a unicode copy-paster error causing the arduino parser to fail.

This was eventually tracked down a difference between two types of semicolons ';'.

Progress:
---------
We did not have a problem reading in from serial or, after a bit of work, parsing the \n to add a new line.

Finally our group reached the step of parsing \t to set the time.

I, Benjamin Espey, expanded slightly into actually running a timer up to the set time before stopping. However, this code is completely untested (written just after lab.)
