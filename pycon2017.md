PyCon 2017 Tutorial Proposal
============================
**Title:** Introduction to Xonsh

Description
-----------
<!--
# Both your title and this description are made public and displayed in the
# conference program to help attendees decide whether they are interested in
# this presentation. Limit this description to a few concise paragraphs.
-->

Xonsh is general purpose shell that combines Python v3.4+ and the best features 
of Bash, zsh, and fish. Relying only the standard library, the xonsh language is 
a strict superset of Python which compiles to a Python AST. The shell provides 
exciting features such as a rich history, tab completion from Bash and man pages, 
syntax highlighting, auto-suggestion, foreign shell aliases, macros, and more!

This tutorial will walk the user through the basics of the xonsh language,
customization of the shell, and advanced features such as writing
xonsh extensions (xontribs) and events. This tutorial
will focus on using xonsh day-to-day, rather than xonsh's implementation.


Audience
--------
<!--
# 1–2 paragraphs that should answer three questions: (1) Who is this tutorial
# for? (2) What background knowledge or experience do you expect students to
# have? (3) What do you expect students to learn, or to be able to do after
# attending your tutorial?
-->

Anyone who has looked at Bash and thought, "there must be another way." or
"I wish there was a way for Python to truly be my main shell." Students at
a minimum should have a basic understanding of the Python language. Ideally,
the student would have some additional knowledge of a shell language, such
as Bash, fish, cmd.exe, or powershell. After this tutorial students should be
able to use xonsh as their main, default, everyday shell on all platforms.


Outline
-------
<!--
# Make an outline that lists the topics and activities you will guide your
# students through over the 3 hours of your tutorial. Provide timings for
# each activity — indicate when and for how long you will lecture, and when
# and for how long students will be tackling hands-on exercises. This is a
# very important criteria! Generally speaking, the more detailed the outline,
# the more confidence the committee will have that you can deliver the material
# in the allotted time.
-->

* Welcome (1 min)
* Install Now! (1 min)
* Instructor Intro (1 min)
* Python Mode (15 min)
  - Basic syntax
  - Environment variables
  - Environment lookup
* Python Mode Exercise (8 min)
* Subprocess Mode (20 min)
  - Basic syntax
  - When in doubt, string literals
  - Captured subprocesses
  - Unaptured subprocesses
  - Python Evaluation
  - Globbing
  - Piping
  - Redirection
  - And, Or, Not
* Subprocess Mode Exercise (8 min)
* Macros (15 min)
  - Function Macros
  - Subprocess Macros
  - Context Manager Macros
* Macro Exercise (8 min)
* Break (10 min)
* Customizing Xonsh (15 min)
  - Xonsh Scripts
  - Run Control Files
  - Static Configuration Files
  - Prompt Customization
  - Writing Aliases
  - Typefying Environment Variables
* Customizing Xonsh Exercise (8 min)
* History (10 min)
  - Rich history
  - The history object
  - History alias and its subcommands
* History Exercise (8 min)
* Xontibs - Xonsh Extensions (15 min)
  - Survey of existing xontribs
  - Loading xontribs
  - Writing xontribs
  - Registering xontribs
* Xontrib Exercise (8 min)
* Xonsh Events (15 min)
  - Overview
  - Writing handlers
  - Core events
  - Custom events
* Events Exercise (8 min)
* Wrap-up (1 min)

Note that there are 5 minutes of wiggle room.

Additional notes
----------------
<!--
# (a) If you have offered this tutorial before, please provide links to the
# material and video, if possible. Otherwise, please provide links to one
# (or two!) previous presentations by each speaker. (b) Please summarize your
# teaching or public speaking experience and your experience with the subject
# of the tutorial. (c) Let us know if you have specific needs or special
# requests — for example, requests that involve accessibility, audio, or
# restrictions on when your talk can be scheduled.
-->

I have given other xonsh talks, most notably at
[last year's PyCon](https://www.youtube.com/watch?v=uaje5I22kgE). Other talks have
been given at APUG (the Austin Python User’s Group) and the HubPy (Spartanburg,
SC Python Meetup). Additionally I know of other people having given xonsh talks
both publically and privately; Aaron Meurer (SymPy developer) gave a talk at
Continuum and Lucas Inojosa in Brazil for a user group meeting, and
[Matthias Bussonnier at PyBay 2016](https://www.youtube.com/watch?v=lopI4HkA9rE).

I myself have given talks at many conferences, such as PyCon, SciPy, PyData, PyCon CA, and
many nuclear engineering conferences (ANS, Physor, Global, etc.). I am also the co-author
of O’Reilly’s “Effective Computation in Physics.”

Furthermore, in my role as an assistant professor at the University of South Carolina,
I have taught two introductory level nuclear engineering courses to upper division
undergraduates and first year graduate students.
