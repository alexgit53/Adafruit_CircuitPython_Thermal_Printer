
Introduction
============

.. image:: https://readthedocs.org/projects/adafruit_circuitpython_thermal_printer/badge/?version=latest
    :target: https://adafruit_circuitpython_thermal_printer.readthedocs.io/
    :alt: Documentation Status

.. image :: https://img.shields.io/discord/327254708534116352.svg
    :target: https://discord.gg/nBQh6qu
    :alt: Discord

.. image:: https://travis-ci.com/adafruit/Adafruit_CircuitPython_Thermal_Printer.svg?branch=master
    :target: https://travis-ci.com/adafruit/Adafruit_CircuitPython_Thermal_Printer
    :alt: Build Status

CircuitPython module for control of various small serial thermal printers.

Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://github.com/adafruit/Adafruit_CircuitPython_Bundle>`_.

**NOTE:** This library is not supported for smaller non-Express boards like
the Trinket M0, Gemma M0, etc.

Usage Example
=============

See examples/thermal_printer_simpletest.py for a demo of basic printer usage.

Contributing
============

Contributions are welcome! Please read our `Code of Conduct
<https://github.com/adafruit/Adafruit_CircuitPython_Thermal_Printer/blob/master/CODE_OF_CONDUCT.md>`_
before contributing to help this project stay welcoming.


Sphinx documentation
-----------------------

Sphinx is used to build the documentation based on rST files and comments in the code. First,
install dependencies (feel free to reuse the virtual environment from above):

.. code-block:: shell

    python3 -m venv .env
    source .env/bin/activate
    pip install Sphinx sphinx-rtd-theme

Now, once you have the virtual environment activated:

.. code-block:: shell

    cd docs
    sphinx-build -E -W -b html . _build/html

This will output the documentation to ``docs/_build/html``. Open the index.html in your browser to
view them. It will also (due to -W) error out on any warning like Travis will. This is a good way to
locally verify it will pass.
