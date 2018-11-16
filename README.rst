============================
LuminanceHDR flatpak package
============================

.. warning::

   !!!DEPRECATED!!!
   Moved to the official repo https://github.com/flathub/net.sourceforge.qtpfsgui.LuminanceHDR

This is an attempt to create a LuminanceHDR distriution via flatpak


Development
===========
Building the project and adding it to the local repo

.. code::
   bash

   flatpak-builder -vvvvv --force-clean --repo=local build-dir net.sourceforge.qtpfsgui.LuminanceHDR.yaml


Setting up local repo

.. code::
   bash

   flatpak --user remote-add --no-gpg-verify local local

Installing from local repo

.. code::
   bash

   flatpak --user install local net.sourceforge.qtpfsgui.LuminanceHDR

Run installed from local repo

.. code::
   bash

    flatpak run net.sourceforge.qtpfsgui.LuminanceHDR
