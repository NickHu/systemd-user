===============
Systemd-user
===============

---------------
Installation
---------------

.. code:: bash

  mkdir -p ~/.config/systemd/user
  git clone https://github.com/NickHu/systemd-user.git ~/.config/systemd/user
  ln -s ~/.config/systemd/user/xinit.target ~/.config/systemd/user/default.target
  mkdir -p ~/.config/systemd/default.target.wants
  mkdir -p ~/.config/systemd/xmonad.target.wants
