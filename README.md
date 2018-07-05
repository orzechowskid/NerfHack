# NerfHack

## What is it?

[NetHack](http://nethack.org/common/index.html) is really hard!  This patch makes it a little easier!

More specifically, it changes a few lines of code relating to fountains, altars, item probablities, and some other things, to make some positive effects slightly more common and some negative effects slightly less common.

## How do I get it?

1. `git clone https://github.com/orzechowskid/NerfHack`
2. `git clone https://github.com/NetHack/NetHack`
3. `cd NetHack && patch -p1 < ../NerfHack/NerfHack.patch`

That should give you a modified version of the latest NetHack release.

4. `sudo apt install build-essential` (or your platform's equivalent)

then just follow the NetHack build instructions (and, optionally, the installation instructions too).

## What if it doesn't work?

- it's possible you're trying to patch a version of NetHack that's too old.  Make sure your NetHack source repo is up-to-date.
- it's possible you're trying to patch a version of NetHack that's too new.  Open an issue, or even better a pull request!, and I'll get around to fixing it.  Don't open an issue against the main NetHack source repo; the Dev Team (rightly) refuses to provide support for code that's not theirs.

## License

NetHack General Public License (original source code)
