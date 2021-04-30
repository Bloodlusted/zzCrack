# zzCrack v2
Ever forgot your password to a zipfile or you just want to crack the password for some reason, Then zzCrack is what you need

This is a advanced tool to crack passwords on zipfiles by wordlists or bruteforce.

You can also save the current state and return from it anytime

Name           | zzCrack
:------------- | :----------------------------------------------------------------------------------------------
Python Version | python3
Languages      | Python
Author         | [@robi0t](https://github.com/robi0t)
Project GitHub | <https://github.com/robi0t/zzCrack>
License        | [GNU General Public License v3.0](https://github.com/robi0t/zzCrack/blob/main/LICENSE)


## Usage:
Run main.py with either arguments(more advanced) or without arguments(easy)

Argument Help: ```python zipcrack-v2.py --help```

### Exampel Usage:
#### Without arguments:
```
  _______        _____                _
 |___  (_)      / ____|              | |
    / / _ _ __ | |     _ __ __ _  ___| | __
   / / | | '_ \| |    | '__/ _` |/ __| |/ /
  / /__| | |_) | |____| | | (_| | (__|   <
 /_____|_| .__/ \_____|_|  \__,_|\___|_|\_|
         | |
         |_|

https://github.com/robi0t


Enter a directory/name to a .zip file > test.zip
Which attack type would you like to run
0: Bruteforce    1: Wordlist > 0

[+] Which characters to use in the attack (combine to use multiple, separated by +)
 0: Only small letters
 1: Only big letters
 2: Only numbers
 3: Only signs
 4: Everything
> 0

[-+] Max length > 4

Do you want to output everything (slower) or not (faster)  y/n > y
```

#### With arguments:
```python main.py -z test.zip -w rockyou.txt --stream```

```python main.py -z test.zip -b -c 0 -m 4 --stream```

```python main.py --restore 0```

**--stream prints everything it tries, it makes the process slower**


### If you experience any error please post a issue
