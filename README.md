# Python interface for the Reflexxes Motion Libraries

The `setup.py` script will invoke CMake to build the module. The module can thus
be built and installed with e.g.

    pip install --user .

This library depends on (note: use conda to install pybind11!)
- python-dev
- pybind11
- libReflexxesTypeII (see [RMLTypeII](https://github.com/Lipeng-Robotics/RMLTypeII)) or libReflexxesTypeIV
