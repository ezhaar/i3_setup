Backing up my i3 configuration files to github.

Launcher:
=========

Use dmenu2.

.. code:: bash

    $ yaourt -S dmenu2

i3Status
========

Use i3bar. Using fonts from kde5. Copied to ``/usr/share/fonts/TTF/``.
Icons displayed using ``ttf-fonts-icons`` (installed using yaourt)

Terminal
========

Use rxvt-unicode with solarized theme. Configuration in Xdefaults

Restore
========

.. code:: bash
    
    $ git clone git://github.com/ezhaar/i3_setup.git
    $ ln -s ~/i3 ~/.i3
    $ ln -s ~/i3/i3status.conf ~/.config/i3status/config
    $ ln -s ~/i3/Xresources ~/.Xresources
    $ ln -S ~/i3/Xdefaults ~/.Xdefaults


