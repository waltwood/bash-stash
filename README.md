# bash-stash

Personal bash and vim customizations for cygwin and linux.

To install:
```
cd ~; \
git clone https://github.com/waltwood/bash-stash; \
echo -e "\n# customizations from https://github.com/waltwood/bash-stash\n. ~/bash-stash/main" >> ~/.bashrc
```
Extra steps may be useful in Cygwin (if core.autocrlf is enabled globally):
```
cd ~/bash-stash; \
git config --local core.autocrlf false; \
dos2unix .gitignore *; \
git reset --hard
```
