# Countdown Timer

A simple countdown timer app, modeled after a kitchen timer. I wanted something easy to remind myself to get up every hour and stretch. To jazz it up a little the timer can play a sound, flash a message, open the applet menu, or display a confirmation dialog on the screen. You can display several notifications at once, such as displaying the confirmation dialog while playing an alarm sound. 

All settings can be changed by right clicking on the icon and selecting configure. Changes are imediate and you dont need to restart cinnamon for them to take effect.

## Installing

0) Add sox play if you want sound capability: sudo apt-get install sox

1) Extract to ~/.local/share/cinnamon/applets

2) Enable the applet in cinnamon settings

## TODO:

## Changelog

* 1.0.0
  - Took over applet from @axos88.
  - Fixed settings to use cinnamon settings.
  - Made audio setting more user friendly. 
  - Made the timer persistant over a reboot.

> Forked from axos88@countdown-timer: https://cinnamon-spices.linuxmint.com/applets/view/280
> Forked from timer-notifications@markbokil.com: https://cinnamon-spices.linuxmint.com/applets/view/68
