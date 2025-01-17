# trackmac 💻

A fork of the simple time tracker for Mac OS X by Nat Friedman (nat@nat.org).

```
conda env create -f environment.yml
conda activate trackmac
python trackmack.py
```

Run this script in a terminal. It displays activity statistics 
from the last 24 hours, like this:
```
 1h 8m57s  70%  Google Chrome
   14m17s  14%  Mail
    8m11s   8%  iChat
    3m16s   3%  Colloquy
    1m28s   1%  1Password
      43s   0%  Terminal
      12s   0%  TextMate
       4s   0%  Finder
       4s   0%  SecurityAgent

 1h37m12s Sitting at the computer
 3h37m16s Doing something else
 5h14m28s Total
```
It detects idle time based on the screensaver, so lower your 
screensaver delay or use a hot corner to improve accuracy.

It doesn't save the data, so if you kill the script it loses the
history.