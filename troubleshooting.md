---
title: Troubleshooting
layout: default
nav_order: 6
---

# Frequently Asked Questions

{: .no_toc }

If you encounter any issues or the clock is not functioning as expected, this page serves as a troubleshooting resource. It contains frequently asked questions that can help address common concerns and provide solutions to potential problems.
{: .fs-6 .fw-300 }

### How to reset the clock?
Located on the back of the clock, there is a push button that provides functionality for restarting or resetting the device. To restart the clock, simply press and hold the button for 2 seconds. If you wish to perform a factory reset, press and hold the button for 10 seconds. It's important to note that a factory reset will erase all settings and restore the clock to its original state. 

As an alternative to using the physical push button on the back of the clock, you can also use the buttons `Restart Word Clock` or `Factory Reset Word Clock` on the clock's webpage.

![Webpage Restart & Reset](https://skyextechnologies.github.io/word-clock-one/images/web-server-entities-overview-restart-reset-marked-only.png)

### Time is incorrect
The clock automatically sets the time based on the time settings of your router, including the time, time zone, and any adjustments for winter or summer time. However, if you find that the time is incorrect for any reason, you can manually adjust it using the sliders in the webpage labeled "06. Hour Offset" and "07. Minutes Offset". These sliders allow you to add the correct number of hours and minutes to align the clock with the accurate time. 

![Webpage Time Offset](https://skyextechnologies.github.io/word-clock-one/images/web-server-entities-overview-offset-marked-only.png)

### Clock is turned off in a dark room
Please note that if you have set a very low value for `04. Minimum Brightness` or selected this value in a brightly lit room, the clock may appear turned off or extremely dim (in a dark room). In such situations, it is advisable to adjust the brightness setting by increasing the value for `04. Minimum Brightness`. 

### Webpage does not load
In certain situations, it might not be possible to access the webpage via `word-clock-one-xxxxxx.local` due to router settings. If you encounter this issue, you can try accessing the webpage by entering the IP address directly. To find the IP address, you can check your router's configuration or employ network scanning tools like [Fing](https://www.fing.com/) to discover the assigned IP address for your clock. If you are still unable to access the webpage or encounter any difficulties, you can attempt restarting the clock by holding the button located on the back of the device for 2 seconds.

{: .important-title }
Please note that you can find the unique ID (`xxxxxx`) written on the backside of the clock.