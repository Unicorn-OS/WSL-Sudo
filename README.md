# WSL-Sudo
run Sudo commands in WSL with python

sch: https://www.google.com/search?q=wsl+exec+sudo

# Solution:
- https://github.com/Microsoft/WSL/issues/1476

## Using piped sudo
sch: https://www.google.com/search?q=wsl+exec+with+pipe

works: true!
- https://craigloewen-msft.github.io/WSLTipsAndTricks/tip/use-pipe-in-one-line-command.html

example:
```
wsl.exe -- echo 'u' `| sudo -S ls /var
```

other
- https://github.com/Chronial/wsl-sudo
