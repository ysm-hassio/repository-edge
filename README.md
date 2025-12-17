# EDGE - Ysm Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/ysm-hassio/repository>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/ysm-hassio/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Grafana][addon-grafana]

![Latest Version][grafana-version-shield]
![Supports armhf Architecture][grafana-armhf-shield]
![Supports armv7 Architecture][grafana-armv7-shield]
![Supports aarch64 Architecture][grafana-aarch64-shield]
![Supports amd64 Architecture][grafana-amd64-shield]
![Supports i386 Architecture][grafana-i386-shield]

The open platform for beautiful analytics and monitoring

[:books: Grafana add-on documentation][addon-doc-grafana]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You could open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Grafana][grafana-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an open-source project. We are always open to people who want to
use the code or contribute to it.

Thank you for being involved! :heart_eyes:

## License

MIT License

Copyright (c) 2018-2024 Franck Nijhof

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

[addon-grafana]: https://github.com/ysm-hassio/addon-grafana/tree/a9f7fb7
[addon-doc-grafana]: https://github.com/ysm-hassio/addon-grafana/blob/a9f7fb7/README.md
[grafana-issue]: https://github.com/ysm-hassio/addon-grafana/issues
[grafana-version-shield]: https://img.shields.io/badge/version-a9f7fb7-blue.svg
[grafana-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grafana-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grafana-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[grafana-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[grafana-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[issue]: https://github.com/ysm-hassio/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/ysm-hassio/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html