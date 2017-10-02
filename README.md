### Dependencies
The easiest way to install all the packages needed to run this code is Anaconda. Anaconda comes with Conda, a package and environment manager built specifically for data science. Install the Python 3.6 version of Anaconda appropriate for your operating system.


#### Windows

For Windows, you'll need to install Python 3.6, scipy  0.19.0, and numpy 1.12.1.

After installing Anaconda, open your command prompt. In there, enter these commands line by line:

<li><code> conda create --name=larp python=3.6 </code></li>
<li><code> activate larp </code></li>
<li><code> conda install -c menpo opencv </code></li>
<li><code> conda install scipy numpy </code></li>
The first line creates a new environment that will hold the packages needed for the Assignment code. The next line (activate larp) enters the environment, you should see the environment name in the prompt at the beginning of the line. The next two install opencv, Scipy, and numpy.

#### OS X and Linux
For OS X and Linux, you'll need to install Python 3.6, scipy 0.19.0, and numpy 1.12.1

In your terminal, enter this commands line by line:

<li><code> conda create -n larp python=3.6 </code></li>
<li><code> activate larp </code></li>
<li><code> conda install -c menpo opencv </code></li>
<li><code> conda install scipy numpy </code></li>
The first line creates a new environment that will hold the packages needed for the Assignment code. The next line (source activate larp) enters the environment, , you should see the environment name in the prompt at the beginning of the line. The next two install opencv, Scipy, and numpy.
