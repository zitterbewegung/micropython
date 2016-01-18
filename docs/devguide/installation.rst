.. _install-dev:

============
Installation
============

This section will help you set up the tools and programs needed for
developing programs and firmware to flash to the BBC micro:bit using MicroPython.

Dependencies
------------


Development Environment
-----------------------

You will need:

* git
* yotta

Depending on your operating system, the installation instructions vary. Use
the installation scenario that best suits your system.

Installation Scenarios
----------------------

* :ref:`Windows <microbit-windows>`
* :ref:`OS X <microbit-osx>`
* :ref:`Linux <microbit-linux>`
* :ref:`Debian and Ubuntu <microbit-debian-ubuntu>`
* :ref:`Red Hat Fedora/CentOS <microbit-redhat>`
* :ref:`Raspberry Pi <microbit-rpi>`


.. _microbit-windows:

Windows
~~~~~~~


.. _microbit-osx:

OS X
~~~~
You can install yotta from the app . See https://github.com/ARMmbed/yotta_osx_installer/releases/ and download the latest release.
Then when the yotta shell launches do '''yt up''' to get all of the depenencies.

.. _microbit-linux:

Linux
~~~~~

These steps will cover the basic flavors of Linux and working with the
micro:bit and MicroPython. See also the specific sections for Raspberry Pi,
Debian/Ubuntu, and Red Hat Fedora/Centos.


.. _microbit-debian-ubuntu:

Debian and Ubuntu
^^^^^^^^^^^^^^^^^

::

  sudo add-apt-repository -y ppa:terry.guo/gcc-arm-embedded
  sudo add-apt-repository -y ppa:pmiller-opensource/ppa
  sudo apt-get update
  sudo apt-get install cmake ninja-build gcc-arm-none-eabi srecord
  pip3 install yotta


.. _microbit-redhat:

Red Hat Fedora/CentOS
^^^^^^^^^^^^^^^^^^^^^


.. _microbit-rpi:

Raspberry Pi
^^^^^^^^^^^^



.. _next-steps:

Next steps
----------

Congratulations. You have installed your development environment and are ready to
begin :ref:`flashing firmware <flashfirmware>`  to the micro:bit.
