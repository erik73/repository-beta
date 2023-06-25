# BETA - Home Assistant Add-ons by erik73

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## WARNING! THIS IS A BETA REPOSITORY

This Home Assistant Add-ons repository contains beta builds of add-ons.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/erik73/hassio-addons>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/erik73/repository-beta
```

## Add-ons provided by this repository

### &#10003; [Mailfilter][addon-mailfilter]

![Latest Version][mailfilter-version-shield]
![Supports armhf Architecture][mailfilter-armhf-shield]
![Supports armv7 Architecture][mailfilter-armv7-shield]
![Supports aarch64 Architecture][mailfilter-aarch64-shield]
![Supports amd64 Architecture][mailfilter-amd64-shield]
![Supports i386 Architecture][mailfilter-i386-shield]

Rspamd mailfilter for Home Assistant

[:books: Mailfilter add-on documentation][addon-doc-mailfilter]

### &#10003; [Mailserver][addon-mailserver]

![Latest Version][mailserver-version-shield]
![Supports armhf Architecture][mailserver-armhf-shield]
![Supports armv7 Architecture][mailserver-armv7-shield]
![Supports aarch64 Architecture][mailserver-aarch64-shield]
![Supports amd64 Architecture][mailserver-amd64-shield]
![Supports i386 Architecture][mailserver-i386-shield]

Postfix and Dovecot mail server for Home Assistant, with Postfix Admin web interface

[:books: Mailserver add-on documentation][addon-doc-mailserver]

### &#10003; [SteVe][addon-steve]

![Latest Version][steve-version-shield]
![Supports armhf Architecture][steve-armhf-shield]
![Supports armv7 Architecture][steve-armv7-shield]
![Supports aarch64 Architecture][steve-aarch64-shield]
![Supports amd64 Architecture][steve-amd64-shield]
![Supports i386 Architecture][steve-i386-shield]

OCPP server for EV charging stations

[:books: SteVe add-on documentation][addon-doc-steve]

### &#10003; [TellStick with Telldus Live][addon-tellsticklive]

![Latest Version][tellsticklive-version-shield]
![Supports armhf Architecture][tellsticklive-armhf-shield]
![Supports armv7 Architecture][tellsticklive-armv7-shield]
![Supports aarch64 Architecture][tellsticklive-aarch64-shield]
![Supports amd64 Architecture][tellsticklive-amd64-shield]
![Supports i386 Architecture][tellsticklive-i386-shield]

TellStick and TellStick Duo service with Telldus Live

[:books: TellStick with Telldus Live add-on documentation][addon-doc-tellsticklive]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

The beta add-ons will also have an additional beta marker, unless, the
stable release is newer, in that case, the stable release is published
in this channel.

## Support

Got questions?

You could open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Mailfilter][mailfilter-issue]
- [Open an issue for the add-on: Mailserver][mailserver-issue]
- [Open an issue for the add-on: SteVe][steve-issue]
- [Open an issue for the add-on: TellStick with Telldus Live][tellsticklive-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2018-2023 Erik Hilton

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-mailfilter]: https://github.com/erik73/addon-mailfilter/tree/v3.0.2
[addon-doc-mailfilter]: https://github.com/erik73/addon-mailfilter/blob/v3.0.2/README.md
[mailfilter-issue]: https://github.com/erik73/addon-mailfilter/issues
[mailfilter-version-shield]: https://img.shields.io/badge/version-v3.0.2-blue.svg
[mailfilter-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mailfilter-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[mailfilter-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[mailfilter-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[mailfilter-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-mailserver]: https://github.com/erik73/addon-mail/tree/v1.2.19
[addon-doc-mailserver]: https://github.com/erik73/addon-mail/blob/v1.2.19/README.md
[mailserver-issue]: https://github.com/erik73/addon-mail/issues
[mailserver-version-shield]: https://img.shields.io/badge/version-v1.2.19-blue.svg
[mailserver-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mailserver-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[mailserver-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[mailserver-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[mailserver-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-steve]: https://github.com/erik73/addon-steve/tree/v2.0.10
[addon-doc-steve]: https://github.com/erik73/addon-steve/blob/v2.0.10/README.md
[steve-issue]: https://github.com/erik73/addon-steve/issues
[steve-version-shield]: https://img.shields.io/badge/version-v2.0.10-blue.svg
[steve-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[steve-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[steve-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[steve-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[steve-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-tellsticklive]: https://github.com/erik73/addon-tellsticklive/tree/v1.1.8
[addon-doc-tellsticklive]: https://github.com/erik73/addon-tellsticklive/blob/v1.1.8/README.md
[tellsticklive-issue]: https://github.com/erik73/addon-tellsticklive/issues
[tellsticklive-version-shield]: https://img.shields.io/badge/version-v1.1.8-blue.svg
[tellsticklive-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tellsticklive-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tellsticklive-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[tellsticklive-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tellsticklive-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/erik73/repository-beta/issues
[license-shield]: https://img.shields.io/github/license/erik73/repository-beta.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-development-yellowgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html