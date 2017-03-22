# bash-stash

Personal bash and vim customizations for cygwin and linux.

To install:
```
cd ~; \
git clone https://github.com/waltwood/bash-stash; \
echo -e "\n#bash customizations\n. ~/bash-stash/main" >> ~/.bashrc
```
Extra steps may be necessary in Cygwin (if core.autocrlf is enabled globally):
```
cd ~/bash-stash; \
git config --local core.autocrlf false; \
dos2unix .gitignore *
```
