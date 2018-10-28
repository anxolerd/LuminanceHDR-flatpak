============================
LuminanceHDR flatpak package
============================

This is an attempt to create a LuminanceHDR distriution via flatpak


Development
===========
Building the project and adding it to the local repo

.. code::

   flatpak-builder -vvvvv --force-clean --repo=local build-dir net.sourceforge.qtpfsgui.LuminanceHDR.yaml


Setting up local repo

.. code::

   flatpak --user remote-add --no-gpg-verify local local

Installing from local repo

.. code::

   flatpak --user install local net.sourceforge.qtpfsgui.LuminanceHDR

Run installed from local repo

.. code::

    flatpak run net.sourceforge.qtpfsgui.LuminanceHDR
