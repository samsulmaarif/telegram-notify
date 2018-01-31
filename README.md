# telegram-notify

These scripts are used to send Telegram messages from a Debian server.

Based on the tutorial at http://bernaerts.dyndns.org/linux/75-debian/351-debian-send-telegram-notification created by [@NicolasBernaerts](https://github.com/NicolasBernaerts)

## How to install

Install curl first

```sh
$ sudo apt install curl
```

Clone this repositoy

```sh
$ git clone https://github.com/samsulmaarif/telegram-notify.git
```

Edit `send-message` file, change the value line 25 `FILE_CONF` with the path of file `telegam-notify.conf`.

Create the symbolic link:

```sh
$ sudo ln -s /path/to/send-message /usr/bin/telegram-notify
```

Now the command `telegram-notify` can be called from anywhere in the command line.
