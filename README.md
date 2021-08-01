# g6ujb-multi-smartsdr

Some scripts that allow you to run multiple copies of FlexRadio's SmartSDR.

The current limitation with SmartSDR is that it only has a single configuration file called SSDR.settings and although you can
launch multiple copies of SmartSDR it only has the single instance of the file available to retain settings, so each
instance reads and writes to this file.

These scripts tried to overcome this problem by moving copies of the SSDR.settings file into place before launching the instance
of SmartSDR.

Ray G6UJB
