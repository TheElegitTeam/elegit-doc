.. Elegit documentation master file, created by
   sphinx-quickstart on Mon Jan  9 01:29:04 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Elegit!
==================================

.. toctree::
   :hidden:
   :maxdepth: 2

   getting_started
   intro_tutorial
   load_repo
   add_files
   commit
   push
   fetch
   branch
   merging
   tree_view
   notes
   contribute_docs

What is Elegit?
---------------
The version control system `Git <https://git-scm.com/>`_ has become popular for developers who track and share code. Elegit is a Git client for people who actually want to learn Git.

Context for this Project
------------------------
The version control system `Git <https://git-scm.com/>`_ has become very popular for developers to track and share the code that they write. Accordingly, Git has been making its way into classrooms in computer science programs around the world. One of the main challenges that students face in using Git is its complexity. Git is quite powerful, but contains a lot of complicated functionality that students don't need to use right away. Moreover, understanding at a deeper level how Git works can be quite useful, and current Git clients don't necessarily help users achieve this understanding. Finally, instructors use Git in the classroom, and typically need to accomplish a variety of tedious and complex details to organize projects and submissions.

Purpose
-------
The goal of this project is to design and build a new Git client for use by students that helps them use Git successfully with a minimum of challenges, likely by use of a subset of Git commands, but also specifically with the goal of helping them learn at a deeper level how Git works. The Java IDE BlueJ serves as one inspirational example that serves this purpose in a different context (Kölling et al). Furthermore, the proposed new client would support the major Git workflows that are currently used in classrooms. Educators and developers have undertaken a few attempts thus far to make Git easier to use in the classroom. Some of these efforts seem to be based on providing students with a minimal subset of Git commands, and a minimal structure around these commands, to help get the students going without running into too much trouble (Lawrance et al, Horstmann). A large number of `existing software clients <https://git-scm.com/downloads/guis>`_ are designed to help make Git easier to use via GUIs. Scarce attention has been given, however, towards making a tool to help students better learn Git’s organizational structure. A major problem that many Git users face is running into problems and challenges in using Git while lacking a deep enough understanding of what’s going on to resolve the issues. (A recent XKCD comic, shown here, makes the point much better than I could.)

.. image:: _static/git.png
