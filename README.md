# bash-stash

Personal bash and vim customizations for cygwin and linux.

### Basic Install
```
cd ~; \
git clone https://github.com/waltwood/bash-stash; \
echo -e "\n# customizations from https://github.com/waltwood/bash-stash\n. ~/bash-stash/main" >> ~/.bashrc
```
### Cygwin Additions
Fix line endings (e.g., git core.autocrlf is enabled globally):
```
cd ~/bash-stash; \
git config --local core.autocrlf false; \
dos2unix .gitignore *; \
git reset --hard
```
Add the ssh agent handler to bash profile:
```
echo -e "\n# bash-stash ssh agent handler function\nssh-agent-init" >> ~/.bash_profile
```
