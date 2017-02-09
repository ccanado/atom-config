ATOM Configuration & save/restore installed packages
=======================

To export packages (only packages name):
```
apm list --installed --bare > apm-list.txt
```
To import packages:
```
apm install --packages-file apm-list.txt
```
