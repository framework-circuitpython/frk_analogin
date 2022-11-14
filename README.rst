============
frk_analogin
============

This is an ADC driver for framework for CircuitPython. It is a light wrapper over the analogio CircuitPython core module.

Usage
-----

In your project conf.py file, include an AnalogIn driver.

.. code-block:: python

    # conf.py
    conf = {
        'ADC':
            {'driver': 'AnalogIn',
             'pin':
                 {'my_adc': 'A0'}
        }
    }