.. _intro-tutorial:

====================
First Elegit Project
====================

Loading a Repository
-----------------------
In order to use Elegit you will first need to:

* `Install Git <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>`_
* Have an existing git repository, either locally or remotely
* Create an account with GitHub, Bitbucket, or another similar service

Next, open Elegit and click the plus button in the top left corner:

.. image:: _static/screenshots/new_repo.png
     :scale: 50%

If you already have a local copy of the git repository you want to work with, select **Load existing repository** and open the folder containing the repository. Otherwise, click **Clone repository** (or navigate **Repository > Clone**).

.. image:: _static/screenshots/clone_window.png
    :scale: 50%

Fill out the information for your project and click **Clone**. If the repository has loaded successfully, you should see a :ref:`tree structure <tree-view>` in the middle of the screen representing the project status and history. To learn more about how Elegit represents the state of your repository, see :ref:`repo-status`.

.. |modified| image:: _static/screenshots/tag_modified.png
    :scale: 50%
.. |staged| image:: _static/screenshots/tag_staged.png
    :scale: 50%

Adding Changes
--------------
As you work on your project, you will notice that Elegit will display the files you have changed in the file view on the left. Initially, they will be tagged as |modified|. When you wish to add a file, simply click the check next to it and press the "Add" button. You should now see the tag changed to |staged|. By staging a file you are saying you are finalizing the modifications to that file and are ready to commit it.

Committing and Pushing Changes
------------------------------
One of the most crucial parts of Git are **commits**. While working on a project, you will want to save your progress, whether fixing a bug or adding a new feature. At this point you should make sure you have added all the files  you want to save. The commit box shows which files you have staged. Click the **Commit** button in the upper left, add a useful message, and then hit the window's **Commit** button. A successful commit will show up in the tree view. Finally, to backup your commits online in your remote repository, click **Push**.
