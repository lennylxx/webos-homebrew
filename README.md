# webOS Homebrew Repository

A shared Homebrew Channel repository for webOS apps.

## Add the repository

In [Homebrew Channel](https://github.com/webosbrew/webos-homebrew-channel)
on your TV, open **Settings > Add repository** and enter:

```text
https://raw.githubusercontent.com/lennylxx/webos-homebrew/main/repository.json
```

Confirm **Add repository**, then return to the app list to install an app.
Homebrew Channel can also detect updates from later GitHub releases.

Alternatively, from a computer with the webOS CLI and your TV configured:

```bash
ares-launch --device tv org.webosbrew.hbchannel -p '{"launchMode":"addRepository","url":"https://raw.githubusercontent.com/lennylxx/webos-homebrew/main/repository.json"}'
```

Replace `tv` with your configured device name. Confirm **Add repository**
on the TV to finish.
