# Holool Laboratory Manager

Offline-first laboratory management software by [Holool Software](https://holoolsoftware.com). One Windows host serves concurrent staff browsers over the local network.

## Download

[Download the latest Windows installer](https://github.com/MohamedFadlala/lms-releases/releases/latest). Choose the **Setup.exe** file. Installing an update preserves the laboratory database and hardware-bound host license.

Installed releases check this repository for stable updates five seconds after launch and every four hours. Updates download in the background. Installation begins only after the host pauses new writes, drains active commands, and creates a fresh verified recovery backup. Choosing **Later** keeps the laboratory running and does not install the update on exit.

Normal laboratory operations and license verification work without internet access; update checks require internet access. Portable and development builds do not auto-update.

This public repository contains installers, blockmaps, and `latest.yml` update metadata only. Proprietary development source is maintained separately in a private repository. No open-source license is granted. Windows installers are currently unsigned.