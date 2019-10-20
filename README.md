![katoolin](https://github.com/mkrupczak3/Katoolin-Robust/blob/master/Katoolin-Robust-Screenshot_2019-06-29%2017-03-50.png)
# Katoolin Robust
Automatically install all, or some, of Kali Linux tools.


# Alternatives
## A better, alternative fork can be found [here](https://github.com/s-h-3-l-l/katoolin3) with more up to date package lists and a more modular code structure.

# New in this fork (from [Katoolin](https://github.com/LionSec/katoolin))
Installs of multiple packages are performed sequentially rather than in bulk, so the install process will not fail if one or more packages fail to install.

## Forker's note:
If you are interested in maintaining this fork as a hard fork alternative to Lionsec's Katoolin (non responsive to PR's and issues) please create an issue and assign me as a assigne and I'll consider transfering ownership. PR's are also welcome.


# Features
- Add Kali Linux repositories
- Remove Kali Linux repositories
- Install Kali Linux tools

# Requirements
- Python 2.7
- Ubuntu 18.04+ (Only tested on Ubuntu)

# Installation
```shell
sudo su

git clone https://github.com/mkrupczak3/Katoolin-Robust.git && cp Katoolin-Robust/katoolin.py /usr/bin/katoolin

chmod +x /usr/bin/katoolin

sudo katoolin
```

# Video
https://www.youtube.com/watch?v=8VxCWVoZEEE

# Usage
- Typing the number of a tool will begin the install of it.
- Typing 0 will install all Kali Linux tools.
- back : Go back to previous menu
- gohome : Go to the main menu

# Notes
- By installing Armitage, you will all be installing metasploit, as it is a dependency.

# Warning
Before updating your system, please remove all Kali Linux repositories to avoid any problems.



## I have some questions!
_forker's note: Lionsec does not appear to be responding to most forms of contact_

~~Please visit https://github.com/LionSec/katoolin/issues

# Donations
- Paypal : https://www.paypal.me/lionsec
- skrill : informatica98es@gmail.com


~~# Contact
- Website : https://neodrix.com
~~- Youtube : https://youtube.com/inf98es
- Facebook : https://facebook.com/in98
~~- Twitter: @LionSec1
- Email : informatica98es@gmail.com
