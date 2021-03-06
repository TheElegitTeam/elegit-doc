.. _repo-status:

====================
Repository Status
====================

The main view in Elegit shows the status of your :ref:`working-tree`, :ref:`local-repository`, and :ref:`remote-repository`.

.. image:: _static/screenshots/main_view.png
     :scale: 28%

.. _working-tree:

Working Tree
------------
The **Working Tree** is the directory of files that you are currently changing on the branch you are on. For more information about branches and branching, see :ref:`branch`. The **Working Tree** pane in Elegit is your main way of seeing what files you have created, changed, or deleted. Clicking the **All Files** tab allows you to browse the file structure of your repository. Files in the working tree are tagged to represent their status.

.. |missing| image:: _static/screenshots/tag_missing.png
    :scale: 50%
.. |untracked| image:: _static/screenshots/tag_untracked.png
    :scale: 50%
.. |ignored| image:: _static/screenshots/tag_ignored.png
    :scale: 50%
.. |modified| image:: _static/screenshots/tag_modified.png
    :scale: 50%
.. |staged| image:: _static/screenshots/tag_staged.png
    :scale: 50%
.. |staged_modified| image:: _static/screenshots/tag_staged_modified.png
    :scale: 50%
.. |unchanged| image:: _static/screenshots/tag_unchanged.png
    :scale: 50%

* |missing| This file was deleted or otherwise removed from the repository.
* |untracked| This file has not been added to git.
* |modified| This file was modified after your most recent commit.
* |staged| This file has a version stored in your git index and is ready to commit.
* |staged_modified| This file has a version stored in your git index and other changes in the working directory.
* |ignored| This file is being ignored because it is in your .gitignore. Remove it from your .gitignore if you want to add it to git.
* |unchanged| This file has not been changed since your most recent commit.
* conflicting
* conflicting modified

Only staged files will be commited.

.. _local-repository:

Local Repository
----------------
The Local Repository column shows the broader view of your project. It represents your history of commits and branches in a :ref:`tree structure <tree-view>` that imitates how Git keeps track of your changes. The status message lets you know how the local repository compares to the remote repository. For example, if you have made 3 commits on branch ``master`` since the last time you pushed, it should say **master ahead of origin/master by 3 commits**.

Clicking on a commit will reveal more information about it in the pane to the right.


.. _remote-repository:

Remote Repository
-----------------
Elegit shows the state of the Remote Repository in the box in the upper right corner of the main screen. The buttons **Fetch**, **Push**, and **Push Tags** cross the border between the local repository and the remote repository to indicate how the two interact.

* **Fetch** downloads files from the remote repository into the local repository. Note that this does not change any files in your working tree. If you want to update your working tree with these files, you need to :ref:`merge <merge>`.
* **Push** updates the remote repository with local changes.
* **Push Tags** updates the remote repository with :ref:`tags` that have been added to local commits.
