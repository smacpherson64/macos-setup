# Mac Setup

Concept new mac setup

This item assumes that I have nothing installed (including homebrew) and that I will not have administrator access on the computer:


## To Update Bash
I will need to request bash be added to the allowed shells and to change the shell to bash

```
sudo -s
echo /usr/local/bin/bash >> /etc/shell
chsh -s /usr/local/bin/bash
```
