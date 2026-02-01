# 25DollarPhone
Tips and Tricks on using a cheap modern Android smartphone as a server.


Tweaks for better reliability on a modern (Android 12+) smartphone:

* In Developer Options --> Enable (turn on the toggle) "Disable Child process restrictions"
* If the device has it, enable the maximum amount of RAM boost.
* Check the OOM score using `cat /proc/<PROCCESS_ID_NUM>/oom_score` and if it's over 850, dial the max amount of RAM downward for the service/process/program.
* For Minecraft servers specifically, turn the view and sim distance way down (recommend 3-6 for 8+ people) in the `server.properties`.
* Follow instructions on https://github.com/atamshkai/Phantom-Process-Killer for disabling the phantom process killer.
* Remove all bloatware and and disable as many pre-installed apps as is possible.
* 



TODO: I am testing using Tasker to automatically restart the Termux app and within that there will be a startup script when Termux launches to restart all the services.
