# Mac Setup

Concept new mac setup

This item assumes that I have nothing installed (including homebrew) and that I will not have administrator access on the computer:


## Updating the bash terminal
```
sudo -s
echo /usr/local/bin/bash >> /etc/shell
chsh -s /usr/local/bin/bash
```