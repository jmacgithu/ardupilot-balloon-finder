Fabio's ardupilot-balloon-finder
========================

Here is an improved version of [rmackey9](https://github.com/rmackay9/ardupilot-balloon-finder)'s original ardupilot balloon finder.

I have modified the scripts/balloon_strategy.py file to work with the most recent version of [ardupilot](https://github.com/diydrones/ardupilot) / [Copter v3.3](https://github.com/diydrones/ardupilot/tree/Copter-3.3) (as of 2015/06/05) and to make it easier to run it from mavproxy.

I have also added a balloon/mavinit.scr to load the droneapi module and execute the balloon_strategy.py automatically when mavproxy is launched.

##Instructions

In linux, from the script folder, run linux_run_strategy.sh, and when the simulator loads up and finds the home location, insert the commands found in mavproxy_sequence.txt.

##More info

For more information, check rmackey9's repository or the original installation page [here](http://dev.ardupilot.com/wiki/odroid-via-mavlink/#Red_Balloon_Finder).