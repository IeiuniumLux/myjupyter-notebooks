# myjupyter-notebooks

These notebooks review Python data containers and some of the powerful data objects of NumPy and Pandas. The goals is to highlight just how much it can be achieved with a few lines of Python code. Some of the notebooks examples, make 3D images and movies with photographs taken by NASA's Rover on Mars and they’ll map the Rover's progress through Martial topography.

## Quick Start

If you want to play with these notebooks without having to install anything, then open this repository in [Binder](https://mybinder.org/v2/gh/IeiuniumLux/myjupyter-notebooks.git/master):
<a href="https://mybinder.org/v2/gh/IeiuniumLux/myjupyter-notebooks.git/master"><img src="https://matthiasbussonnier.com/posts/img/binder_logo_128x128.png" width="90" /></a>

**NOTE**: Binder creates a new environment from scratch every time this repo is updated or when you launch it for the first time; and in those cases it takes quite some time to start the service.  Be also aware that Binder provides a temporary environment, therefore, anything you do will be deleted after a while.

If you rather install this project on your own machine with a working Python 3.5+ environment and git is installed, then an easy way to install this project and its dependencies is using pip. Open a terminal and run the following commands (do not type the `$` signs, they just indicate that this is a terminal command):

    $ git clone https://mybinder.org/v2/gh/IeiuniumLux/myjupyter-notebooks.git
    $ cd myjupyter-notebooks
    $ python3 -m pip install --user --upgrade pip setuptools
    $ python3 -m pip install --user --upgrade -r requirements.txt
    $ jupyter notebook
