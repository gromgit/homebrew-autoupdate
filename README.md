# Homebrew-autoupdate

An easy, convenient way to automatically update Homebrew.
This script will run once every 24 hours, doing both brew update & brew upgrade.

[![](http://imgs.xkcd.com/comics/update.png)](https://xkcd.com/1328/)

## How do I tap this repository?

Just `brew tap domt4/autoupdate`.

## Usage

To run the script, you’d just do `brew autopdate`. The following options are available:

```
Usage:
--start = Start autoupdating every 24 hours.
--stop = Stop autoupdating, but retain plist & logs.
--delete = Cancel the autoupdate, delete the plist and logs.
```

## License
Code is under the [BSD 2 Clause (NetBSD) license](https://github.com/DomT4/homebrew-autoupdate/blob/master/LICENSE).
