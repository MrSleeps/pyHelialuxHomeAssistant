# pyHelialux

Python library to control (and get information from) Juwel's Helialux Smart Controller.

Modified to work with Home Assistant (tested with 2025.1), mostly just made the functions async.

Made to work with my [Juwel Helialux Home Assistant custom component](https://github.com/MrSleeps/Juwel-HeliaLux-Home-Assistant-Custom-Component).

## Suppored features
* Get current state of the controller
  * `currentProfile`
  * `currentWhite`
  * `currentBlue`
  * `currentGreen`
  * `currentRed`
  * `manualColorSimulationEanbled`
  * `manualDaytimeSimulationEnabled`
  * `deviceTime`
* Enable and disable manual color simulation
* Set the brightness of the channels manually
