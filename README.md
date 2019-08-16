<h1 align="center">
  <img src="i2pd-logo.png" alt="i2pd">
  <br />
  i2pd - Invisible Internet Protocol Daemon
</h1>

<p align="center"><b>This is the snap for i2pd</b>, <i>“Invisible Internet Protocol Daemon”</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<p align="center">
<a href="https://snapcraft.io/i2pd">
  <img alt="enpass" src="https://snapcraft.io/i2pd/badge.svg" />
</a>
<a href="https://snapcraft.io/i2pd">
  <img alt="enpass" src="https://snapcraft.io/i2pd/trending.svg?name=0" />
</a>
</p>

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Install

    sudo snap install i2pd

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/i2pd)

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

Snapcrafters ([join us](https://forum.snapcraft.io/t/snapcrafters-reboot/24625)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml) upstream so [Project] can authoritatively publish future releases.

  - [x] Click the green "Use this template" button above to create a new repository based on this template
  - [x] Give the newly created repository a sensible name, like `godzilla` if you're snapping the Godzilla software (*Note: Do not use `snap` in this name.*)
  - [x] Update the description of the repository to `Official snap for i2pd`
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Add the Snapcraft store account (snap-advocacy@canonical.com) as a collaborator to your snap in the [Dashboard](https://dashboard.snapcraft.io) and ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to accept this request
  - [ ] Fix all important issues found during testing
  - [ ] Make a post in the Snapcraft Forum ["store-requests" category](https://forum.snapcraft.io/c/store-requests/19) asking for a transfer of the snap name from you to Snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()
  - [x] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Ask upstream if they are interested in maintaining the Snap. If they are:
    - [ ] Fork the upstream project, add the snap build files and required assets/launchers to that repo and submit a pull request or patch - [link]()
    - [ ] Add upstream contact information to the `README.md`
    - If upstream accept the PR:
      - [ ] Request upstream create a Snap store account
      - [ ] Add upstream account as a collaborator on the snap
      - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![l-n-s](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/l-n-s/) |
| [![r4sas](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/r4sas/) |
| :---: |
| [l-n-s](https://github.com/l-n-s/) |
| [r4sas](https://github.com/r4sas/) |

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->