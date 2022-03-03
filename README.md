Gymbot is a script that books the UCD gym for you so you don't have to remember to book it when the desired time becomes available three hours before booking.
### Usage:
`./gymbot --student-number 18521034 --time 10:45` will book the performance gym at 7:45am
It must be left running until that time - this script is intended to run on an always-on computer/server. I managed to get it to run on my phone through some termux + arch-chroot trickery but it didn't work consistently due to how android sleeps background processes.

More info can be seen with `./gymbot --help`
### Requirements
* Modules in `requirements.txt`
* geckodriver

For Arch-based users run:
```
sudo pacman -S geckodriver && pip install -r requirements.txt
```
