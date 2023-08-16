System Insight
=====

A simple tool for quickly gathering information about the current state of the system.

Installation
------------

1. Download the repository as an archive from GitHub and extract it, or use the Git or GitHub CLIs to
   clone it.

2. Press Win+R and run the following command:

.. code:: bash

   rundll32 sysdm.cpl,EditEnvironmentVariables

3.  A window will open showing environment variables.

4.  Select "Path" and press "Edit".

5.  Click "New" and enter the full non-relative path to your
    installation.

6.  Press the Enter key.

7.  Press OK until you exit the window.

8.  Open your terminal.

9.  Change directories to the installation directory.

10. Run the following command:

.. code:: bash

   py setup.py sdist bdist_wheel

11. Run the following command:

.. code:: bash

   pip install dist/SOME_NAME_HERE.whl



