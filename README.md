<h1 align="center">
  <img src="i2pd-logo.png" alt="i2pd">
  <br />
  i2pd - Invisible Internet Protocol Daemon
</h1>

<p align="center"><b>This is the snap for i2pd</b>, <i>"Invisible Internet Protocol Daemon"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<p align="center">
<a href="https://build.snapcraft.io/user/PurpleI2P/i2pd-snap"><img src="https://build.snapcraft.io/badge/PurpleI2P/i2pd-snap.svg" alt="Snap Status"></a>
</p>

<p align="center">Published for :penguin: with :gift_heart: by Snapcrafters</p>

## Install

    sudo apt install snapd-xdg-open
    sudo snap install --edge i2pd

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/i2pd)

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Usage

Managing with systemd:

    systemctl status snap.i2pd.daemon.service
    systemctl stop snap.i2pd.daemon.service
    systemctl start snap.i2pd.daemon.service

View logs:

    journalctl -u snap.i2pd.daemon

Graceful router shutdown:

    sudo i2pd.graceful-shutdown

Reload config after changing `tunnels.conf` file:

    sudo i2pd.reload-tunnels-conf

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) 
are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml)
upstream so [i2pd](https://github.com/PurpleI2P/i2pd) can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account.
    - If you have already forked the Snapcrafter template to your account and want to create another snap, you'll need to use GitHub's [Import repository](https://github.com/new/import) feature because you can only fork a repository once.
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, transfer the snap name from you to snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [x] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [x] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

[l-n-s](https://github.com/l-n-s/)
[r4sas](https://github.com/r4sas/)
