# iHRIS 4.3 Documentation

iHRIS 4.3 is IntraHealth International's open-source software for managing health workforce information. It runs on a Linux server with Apache, MySQL and PHP, and is used through a web browser.

!!! note "Looking for iHRIS 5?"
    This site covers iHRIS 4.3 only. iHRIS 5 is a different system; its documentation is at [ihris.github.io/ihris-documentation](https://ihris.github.io/ihris-documentation/).

## The products

iHRIS 4.3 comes as three products. All three are built on the same framework, I2CE, and can run side by side on one server.

| Product | Used for | Code and downloads |
| --- | --- | --- |
| **iHRIS Manage** | Health worker records, positions and deployment, for ministries and employers | [launchpad.net/ihris-manage](https://launchpad.net/ihris-manage) |
| **iHRIS Qualify** | Training, examination, registration and licensing, for professional councils | [launchpad.net/ihris-qualify](https://launchpad.net/ihris-qualify) |
| **iHRIS Train** | Training providers, courses, participants and exams | [launchpad.net/ihris-train](https://launchpad.net/ihris-train) |

Every product also needs three shared parts: [I2CE](https://launchpad.net/i2ce) (the framework), [iHRIS Common](https://launchpad.net/ihris-common) and [TextLayout](https://launchpad.net/textlayout) (PDF output).

## Current release: 4.3.4

iHRIS 4.3.4 (October 2026) is a maintenance release that runs on PHP 8. Earlier 4.3 releases fail on PHP 8, which is the default on current Ubuntu releases.

- Runs on **PHP 7.2 to 8.5**. Use PHP 8.3 or later: older versions no longer get security fixes.
- Tested with MySQL 8.0, Apache 2.4 and memcached on Ubuntu 24.04.
- Existing 4.3 sites can be upgraded in place.

## Guides

- [Installing iHRIS 4.3.4 on Ubuntu](install_ubuntu.md): a new server, from PHP and MySQL to a running site, plus upgrading an existing site and running in production.

## Getting help

- **Bugs:** report them on the Launchpad project of the product concerned, under **Bugs**.
- **Source code:** each project's Bazaar branches are on Launchpad; `4.3.4-release` holds the release and `4.3-dev` the latest code.
- **This documentation:** to suggest a change, use the edit button at the top of any page, or open an issue on [GitHub](https://github.com/iHRIS/ihris-4-documentation).
