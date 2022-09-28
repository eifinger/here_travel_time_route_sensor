# here_travel_time_route_sensor

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)
[![License][license-shield]](LICENSE.md)

![Project Maintenance][maintenance-shield]
[![BuyMeCoffee][buymecoffeebadge]][buymecoffee]

[![Community Forum][forum-shield]][forum]

_Homeassistant Custom Component which adds a Route Sensor to [HERE Travel Time](https://www.home-assistant.io/integrations/here_travel_time/)._

## Important Information

**This component is only for ADVANCED users.**

**This will override the core integration.**

[!example][exampleimg]

## Why?

The route sensor got removed from the core integration with [this PR](https://github.com/home-assistant/core/pull/79211).

At the time of the PR there where anticipated dangers with allowing string over 255 characters into the Homeassistant state machine. Until a solution is found all states and attributes which might violate that limit are to be removed. Until a solution is found this repository is a workaround as asked by the community.

## Installation with HACS

The easiest way to add this to your Homeassistant installation is using [HACS](https://hacs.xyz).


## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

<a href="https://www.buymeacoffee.com/eifinger" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/black_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a><br>

***

[buymecoffee]: https://www.buymeacoffee.com/eifinger
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/custom-components/blueprint.svg?style=for-the-badge
[commits]: https://github.com/eifinger/here_travel_time_route_sensor/commits/master
[customupdater]: https://github.com/custom-components/custom_updater
[customupdaterbadge]: https://img.shields.io/badge/custom__updater-true-success.svg?style=for-the-badge
[exampleimg]: https://github.com/eifinger/here_travel_time_route_sensor/blob/master/route_sensor.png?raw=true
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/t/custom-component-here-travel-time/125908
[license-shield]: https://img.shields.io/github/license/eifinger/here_travel_time_route_sensor.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Kevin%20Stillhammer%20%40eifinger-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/eifinger/here_travel_time_route_sensor.svg?style=for-the-badge
[releases]: https://github.com/eifinger/here_travel_time_route_sensor/releases