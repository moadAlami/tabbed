# tabbed - generic tabbed interface

tabbed is a simple tabbed X window container.

## Requirements
In order to build tabbed you need the Xlib header files.

## Installation
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

    make clean install

## Running tabbed
See the man page for details.

## Patches
This build uses the following patches:

  * [alpha](https://tools.suckless.org/tabbed/patches/alpha/) - This patch create 32bit window in tabbed. This allows to handle windows with transparency.
  * [autohide](https://tools.suckless.org/tabbed/patches/autohide/) - This patch hides the tab bar if only one tab is open.
  * [client number](https://tools.suckless.org/tabbed/patches/clientnumber/) - With this patch, tabbed prints the position number of the client before the window title.
