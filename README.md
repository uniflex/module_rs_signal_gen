# Wishful R&S signal generator module

The R&S signal generator can be controlled from this module.

## Installation

Make sure that the folder bin/ is in global PATH variable:

    export PATH=~/repos/wishful/modules/rs_signal_gen/bin:$PATH
    
or execute the Makefile in src/ when using a Python virtualenv

    cd src ; make
    
## Test the module

    cd test
    wishful-agent --config config_local.yaml
