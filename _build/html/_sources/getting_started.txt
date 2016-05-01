==================
Getting started
==================

---------------
Preliminaries
---------------

Very basic computer skills are handy, you need to know how to download and install a software into your computer.

You do not need to have any prior programming experience. You might need some basic algebra and statistics.
Some background in linear algebra and calculus might be useful as well however, I will try to give all the background
information when necessary. Let's get started!

---------------------------------
Installing the necessary software
---------------------------------

We are going to use Python and we are going to need some other packages with it. As the name states, packages include
previously written code (that is packed together) of which we are going to make use of. My reccomendation is for you to
install Anaconda distribution of Python. You can download it from `this webpage. <https://www.continuum.io/downloads>`_
You should download the Python 2.7 version available for your system. Follow the steps that are suggested on the webpage for
the installation.

After installation, there are a few ways to write and run our code. My suggestion is to use Jupyter Notebook.
if you are just starting with programming. If you have programmed in R (using R-studio) or MATLAB earlier, you might find
Spyder more comfortable. In my opinion, Spyder should be your choise when you start to write more lines of code.

----------------
Jupyter Notebook
----------------

`Jupyter Notebook <http://http://jupyter.org/>`_ , is a kind of a web application that runs on your computer locally. It opens a web page on your browser, so that you can write and run
your code in your browser and see the output. It also allows you to plot your data at the same page. Besides you can also write equations and documentations
in between. You can save all your data along with your code, therefore it is very useful.

In order to run it on Windows, click on "Jupter Notebook" under "Anaconda" section in start (or push ``Windows key + R``, write ``jupyter notebook`` and click on "Run").
In Mac OS X and in Linux you can run it from terminal by typing in ``jupyter notebook`` as well.

------
Spyder
------

`Spyder <https://pythonhosted.org/spyder/>`_ is an IDE (Integrated Development Environment), meaning that it is a software that contains sections to write and execute a code. It also includes a
section where you can browse through the variables that you created after running your program. When you want to visualize your data, you can do it either inside the console (which will give you
small images) or you can make it open a new window and show it in that.

After you install Anaconda, in Windows you should be able to find Spyder under "Anaconda" section in Start (or push ``Windows key + R``, write ``spyder`` and click on "Run").

-----------
First steps
-----------

I will continue assuming that you are running Jupyter Notebook. When you run Jupyter Notebook, it should automatically open your web browser (if it does not, just open your browser and type ``http://localhost:8888/``).
In the web browser you are going to see something like this:

.. figure:: _jupyter_main.png

   Jupyter Notebook main page, it shows your home folder when first opened.

Select the folder that you would like to work in and then on right top of the page click on "New", choose "Python 2".
This is going to create a new notebook file in the folder that you are in (named as ``Untitled.ipynb``). The notebook is going to open in a new tab in your browser.
On the right hand side of the Jupyter logo, you will see the name of your notebook, in the beginning it is named as "Untitled". You can click on it and change its name.
You can save all the progress that you made by clicking on the disk image or choosing "Save and Checkpoint" from "File".

You probably see the long rectangle box which writes ``In [ ]:`` on the left side. This is called a "cell". All Jupyter notebooks (also named as IPython notebooks) consists of *cells*. Cells are sections that
we can write code and evaluate independently. Go ahead and click inside the box and type the following:

.. nbinput:: python
    :execution-count: 1

    print "Hello Jupyter"

.. nboutput::
    :execution-count: 1

    Hello Jupyter

If you see the output above, then you have successfully written your first code!
