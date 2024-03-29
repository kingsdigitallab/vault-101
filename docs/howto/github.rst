Github starter page
===================

Some of the research data and project web site content is hosted in a
`Github`_ file repository managed by KDL (we'll send you the link). The
repository is a dedicated cloud space for your file which can be
collaboratively edited by KDL and the research team. All changes are
versioned, all files are public.

Github is the cloud repository provider. And Git is the versioning
system it is based on.

How do I access the repository?
-------------------------------

If you only need to browse the files, you can do so without an account,
directly on the github.com website.

First you need to `create github account`_ if you haven't one yet. Then
let KDL know what your account name/id is so we can give you access to
the repository.

How can I interact with the files on github?
--------------------------------------------

Listed below are four options, ranging from the most straightforward to
the most advanced. If you are new to github, try option 1 first and move
to option 2 it is too limiting. If you have experience with coding
environments, option 4 might be preferred.

.. _1-githubcom-website:

1. Github.com website
~~~~~~~~~~~~~~~~~~~~~

The github.com site lets you search, browse and edit html, markdown or
json files and save your changes immediatelly. You don't need to
download anything and the changes occur directly on the cloud.

The editorial documentation contains an `illustrative walkthrough of the
editorial workflow on Github`_.

.. _2-desktop-git-clients:

2. Desktop Git clients
~~~~~~~~~~~~~~~~~~~~~~

In this option and the following ones you copy the cloud repository
locally (i.e. on your machine), modify the files with the editors of
your choice, and share the modified files back to the cloud.

The git editorial workflow works like this:

1. **clone**: a one-off initial download of a github repository to your
   machine
2. **pull**: any subsequent download (to receive changes made by others)
3. edit: the files using your favourite desktop editors
4. **commit**: to save change files to your local copy of the repository
5. **push**: to upload your local repository back to the cloud
6. iterate from step 2

Steps 1, 2, 4 and 5 can be done with one of those free desktop Git
applications:

-  https://desktop.github.com/
-  https://www.sourcetreeapp.com/

.. _3-command-line--terminal:

3. Command line / Terminal
~~~~~~~~~~~~~~~~~~~~~~~~~~

If you are confident with the terminal, the `git application`_ is an
efficient command line tool to do steps 1, 2, 4 and 5.

.. _4-integrated-development-environemnt-ide:

4. Integrated development environemnt (IDE)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

An IDE is a desktop application dedicated to code development. It
integrates git operations and file editing under the same environment.
It is very convenient but require some initial set up and is typically
filled with distracting features you'll rarely use.

Recommended free IDEs:

-  `Visual Studio Code`_
-  `PyCharm Community Edition`_

.. _Github: github.com
.. _create github account: https://github.com/signup
.. _illustrative walkthrough of the editorial workflow on Github: content-editing.md#how-to-edit-a-markdown-file
.. _git application: https://github.com/git-guides/install-git
.. _Visual Studio Code: https://code.visualstudio.com/
.. _PyCharm Community Edition: https://www.jetbrains.com/pycharm/
