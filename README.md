# Home Assistant Apps (EDGE)
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)
[![Github Sponsors][gh-sponsors-shield]][gh-sponsors]

## About

**Warning**: _This repository contains edge builds. They are based on the latest
development version and may not work as expected._

Home Assistant allows the creation of app repositories to facilitate the sharing
of custom apps. This is one such repository.

## Installation

[![Add app repository to Home Assistant.][supervisor-add-badge]][supervisor-add-link]

In the Home Assistant app store, you can add custom repositories. Use the button
above or the following URL to add this repository:

```txt
https://github.com/wbyoung/ha-apps-edge
```

## Apps provided by this repository

### [External Logs][addon-external_logs]

![Latest Version][external_logs-version-shield]
![Supports armhf Architecture][external_logs-armhf-shield]
![Supports armv7 Architecture][external_logs-armv7-shield]
![Supports aarch64 Architecture][external_logs-aarch64-shield]
![Supports amd64 Architecture][external_logs-amd64-shield]
![Supports i386 Architecture][external_logs-i386-shield]

Write logs to external storage

[:books: External Logs app documentation][addon-doc-external_logs]

## Support

Please open an issue on the appropriate GitHub repository for an app.

- [Open an issue for the app: External Logs][external_logs-issue]

[addon-external_logs]: https://github.com/wbyoung/ha-external-logs/tree/038ae73
[addon-doc-external_logs]: https://github.com/wbyoung/ha-external-logs/blob/038ae73/README.md
[external_logs-issue]: https://github.com/wbyoung/ha-external-logs/issues
[external_logs-version-shield]: https://img.shields.io/badge/version-038ae73-blue.svg
[external_logs-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[external_logs-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[external_logs-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[external_logs-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[external_logs-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[supervisor-add-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[supervisor-add-link]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fwbyoung%2Fha-apps
[license-shield]: https://img.shields.io/github/license/wbyoung/ha-apps-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[gh-sponsors-shield]: https://img.shields.io/badge/GitHub%20Sponsors-grey?&logo=GitHub-Sponsors&logoColor=EA4AAA
[gh-sponsors]: https://github.com/sponsors/wbyoung