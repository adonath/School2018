# School2018
2nd ASTERICS-OBELICS International School


[![School indico](https://indico.in2p3.fr/event/16864/logo-841635696.png)](https://indico.in2p3.fr/event/16864/)

This repository contains all the material needed for the [2st
ASTERICS-OBELICS International
School](https://indico.in2p3.fr/event/16864/) on "Advanced software
programming for astrophysics and astroparticle physics".

# Table on content

- [Important links](#links)
- [Get a copy of this repository with `git`](#repo)
- [Recommendation for Python install](#python)
    - [Linux](#linux)
    - [Mac](#mac)
    - [Windows](#windows)
    - [Library requirements](#python-req)
- [Jupyter](#jupyter)    
- [IDE: PyCharm](#pycharm)
- [Tutors](#tutors)
- [Help](#help)

# Important links <a name="links"></a>

- [Local copies](https://lapp-owncloud.in2p3.fr/index.php/s/HtYGL5G7TAe0nok) of needed software, like Anaconda and PyCharm


# Get a copy of this repository with `git` <a name="repo"></a>

Clone this repository on your personal computer.

      git clone https://github.com/Asterics2020-Obelics/School2018.git

You will need it before the school to install the different tools, and
during the school while attending the hands-on. For Windows, see [below](#windows).

# Recommendation for Python install <a name="python"></a>

You must install Python 3.6 and a few Python libraries. The
recommended way to do so is to use
[Anaconda](https://www.continuum.io/downloads). The procedures described bellow will help you install what is needed for the school.

## Linux <a name="linux"></a>

1. Install required distribution packages :
    - Ubuntu: `sudo apt-get install -y git bzip2 wget`
    - Fedora 25: `sudo dnf install -y git wget bzip2`
    - CERN Scientific Linux 6: `sudo yum install -y git tar bzip2 wget`
    - CERN CentOS 7: `sudo yum install -y git bzip2 wget`

1. [Download](https://repo.continuum.io/archive/Anaconda3-4.3.1-Linux-x86_64.sh) ([local copy](https://lapp-owncloud.in2p3.fr/index.php/s/HtYGL5G7TAe0nok))
the Linux `Anaconda` installer for Python 3.6.

1. Run the following command line:

		bash Anaconda3-4.3.1-Linux-x86_64.sh

1. Answer `no` to the following question if you do not want to mess up
  your previous installs of python.
	
		Do you wish the installer to prepend the Anaconda3 install location
		to PATH in your /home/chotard/.bashrc ? [yes|no]
		[no] >>> no

1. If you haven't cloned this repository, download one of the
`anaconda_setup` script (`sh` or `csh` depending on your shell):

		wget https://raw.githubusercontent.com/Asterics2020-Obelics/School2017/master/anaconda_setup.sh
		or
		wget https://raw.githubusercontent.com/Asterics2020-Obelics/School2017/master/anaconda_setup.csh

1. If you have installed `anaconda` in a different directory than the default one suggested by the `anaconda` installer (your home directory), edit the first line of the `anaconda_setup` script with your selected path.

		ANACONDA=YOURSELECTEDPATH
		or
		setenv ANACONDA YOURSELECTEDPATH

1. Run the `anaconda_setup` script to set up the correct PATH and
PYTHONPATH enabling the use of your `Anaconda` install.

		source anaconda_setup.sh
		or
		source anaconda_setup.csh

    You can either run this command each time you need to use `Anaconda`,
    or add its content to your `.bashrc` (or equivalent) to set it up at
    the opening of a new terminal.

1. See next section for extra Python libraries requirements (if any).

## Mac <a name="mac"></a>

1. [Download](https://repo.continuum.io/archive/Anaconda3-4.3.1-MacOSX-x86_64.sh) ([local copy](https://lapp-owncloud.in2p3.fr/index.php/s/HtYGL5G7TAe0nok))
the Mac `Anaconda` installer for Python 3.6.

1. Run the following command line:

		bash Anaconda3-4.3.1-MacOSX-x86_64.sh

1. Answer `no` to the following question if you do not want to mess up
  your previous installs of python.
	
		Do you wish the installer to prepend the Anaconda3 install location
		to PATH in your /home/chotard/.bashrc ? [yes|no]
		[no] >>> no

1. If you haven't cloned this repository, first get the `anaconda_setup.sh` script:

		wget https://raw.githubusercontent.com/Asterics2020-Obelics/School2017/master/anaconda_setup.sh

1. If you have installed `anaconda` in a different directory than the default one suggested by the `anaconda` installer (your home directory), edit the first line of the `anaconda_setup` script with your selected path.

		ANACONDA=YOURSELECTEDPATH

1. Run the `anaconda_setup.sh` script to set up the correct PATH and
PYTHONPATH enabling the use of your `Anaconda` install.

		source anaconda_setup.sh

    You can either run this command each time you need to use `Anaconda`,
    or add its content to your `.bashrc` (or equivalent) to set it up at
    the opening of a new terminal.

1. See next section for extra Python libraries requirements (if any).

## Windows <a name="windows"></a>

Instruction for Windows can be found
[here](https://www.continuum.io/downloads#windows) for the installation of Anaconda ([local copy](https://lapp-owncloud.in2p3.fr/index.php/s/HtYGL5G7TAe0nok)). Once installed, you can run `Anaconda navigator`. To run Jupyter, on the main page of the Anaconda navigator, click on `Launch` on the Jupyter notebook box. This will open your favorite browser. From there, you can either load a notebook (e.g. from the Git folder) or create a new notebook by clicking `new -> Python 3`. 

You can also install a Git tool for Windows: [Git for Windows](https://git-for-windows.github.io/). Launch `Git GUI` or `Git bash` to get started. 

## Library requirements <a name="python-req"></a>

All the required libraries come with the `Anaconda` install described
above. If you have followed the previous steps to install Python, you
can skip this section.

If you choose an other way to install Python 3.6 than the one
recommended above, you must install manually the Python libraries
listed in the [requirements.txt](requirements.txt) file. To do so, we
recommend using `pip`.

	  pip install -r requirements.txt

# Jupyter <a name="jupyter"></a>

To launch a Jupyter notebook, simply run the following command:

`jupyter notebook`

On Windows, see in the [above](#windows).

# IDE: PyCharm <a name="pycharm"></a>

We strongly recommend to use pycharm, especially for the "Debugging & profiling" course. Free Community Edition: [Download PyCharm](https://www.jetbrains.com/pycharm/download) ([local copy](https://lapp-owncloud.in2p3.fr/index.php/s/HtYGL5G7TAe0nok)) or opt for a free copy of the Professional Edition under [Student License](https://www.jetbrains.com/student/).


# Tutors <a name="tutors"></a>

TBC
 
# Help

Please create a [new
issue](https://github.com/Asterics2020-Obelics/School2018/issues) (you
will need a github account) for each question you may have before or
during the school about software install and/or about one of the
classes. Of course, you should first check the existing list of issues
to see if your question has already been asked and answered before
creating a new one.
