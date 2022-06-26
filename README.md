# Ubuntu-wsl2-systemd-script
Script to enable systemd support on current Ubuntu WSL2 images from the Windows store. Script is unsupported and will no longer be maintained, but will be up here because it is used by quite some people. I am not responsible for broken installations, fights with your roommates and police ringing your door ;-).

## Usage
You need git to be installed for the commands below to work. Use
```
sudo apt install git
```
to do so.

## Run the script and commands
```
git clone https://github.com/kelwin13/WSL2_working_systemctl.git
cd ubuntu-wsl2-systemd-script/
bash ubuntu-wsl2-systemd-script.sh
```
## Enter your password and wait until the script has finished

Then restart the Ubuntu shell and try running systemctl
```
systemctl
```
If you don't get an error and see a list of units, the script worked.

Have fun using systemd on your Ubuntu WSL2 image. You may use and change and distribute this script in whatever way you'd like.
