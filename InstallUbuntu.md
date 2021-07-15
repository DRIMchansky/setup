# My post-install process for Ubuntu

- firefox tweaks (sync, extensions etc.)
- [chrome](https://www.google.com/intl/en/chrome/)

- add russian keyboard (settings / region & language)
- fold apps in one click

```sh
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'
```

- `sudo apt install make`
- `sudo apt install gimp`
- `sudo apt-get install jq`
- `sudo apt-get install gnome-tweaks` + settings tweaks
- `sudo apt-get install vokoscreen`
- `sudo apt-get install ubuntu-restricted-extras`
- `sudo apt-get install sudo rar unrar p7zip-full`
- `sudo apt-get install jpegoptim optipng`

- `sudo apt-get install telegram-desktop`
- [zoom](https://zoom.us/download#client_4meeting)
- [skype](https://www.skype.com/ru/get-skype)
- [vlcplayer](https://www.videolan.org/vlc/index.ru.html)
- [transmission](https://linuxhint.com/transmission-bittorrent-client-linux/)

- [vscode](https://code.visualstudio.com/) + tweaks(config, extensions)
- [firacode](https://github.com/tonsky/FiraCode) (.local/share/fonts)
- nodejs, npm

```sh
sudo apt-get install curl
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install nodejs
```

```sh
sudo npm i -g n parcel-bundler webpack webpack-cli pm2 eslint svgo
```

- [git](https://git-scm.com/) + config + ssh

```sh
chmod =600 ~/.ssh/private_key // set strict access rights
ssh-add ~/.ssh/private_key // init ssh-key
```

- [mongodb](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)
- [mongodb-compass](https://www.mongodb.com/try/download/compass)
- postman (Ubuntu Software)

- [docker](https://docs.docker.com/engine/install/ubuntu/)
- [non-root docker](https://docs.docker.com/engine/install/linux-postinstall/)
