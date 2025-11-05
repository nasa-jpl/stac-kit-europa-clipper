# Europa-Clipper packet definitions

For instruments ECM, MISE and SUDA, some of the CCSDS packets definitions are coded here, as needed by the Science Data System.

Those packet definitions are used by the [SPaC-kit CCSDS library](https://github.com/CCSDSPy/SPAC-kit) to decode CCSDS packets, generate documentation and simulated datasets.

## Prerequisites

This package has been tested with Python 3.9.

## Users


TO BE DONE (deploy from pypi, link to SPaC-kit for usage...)


## Developers

Clone the repository:

    git clone  https://github.com/joshgarde/europa-cliper-ccsds-plugin.git 

Create a virtual environment and activate it:

    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`

You might need to upgrade pip first:

    pip install --upgrade pip

Install the package in editable mode:

    pip install -e .

Make your changes in the package definition files located in the `ccsds.packets.europa_clipper` directory.

Update the test reference data as needed in `ccsds.packets.europa_clipper.test`.

Run the tests to ensure everything is working:

    pytest

