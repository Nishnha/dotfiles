Configuration for my Arch Linux machines.

Clone the repository including submodules and move all directories to your user home folder (preserving the directory structure).
`git clone --recurse-submodules git@github.com:Nishnha/arch-config.git &&
mv -u arch-config/{,.[!.]}* ~ &&
rm -rf arch-config`
