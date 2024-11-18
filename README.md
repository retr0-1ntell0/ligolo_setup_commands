## Ligolo setup commands
I love ligolo and love using it. This small bash script helps me with running the initial setup for adding a new tuntap device on my OS.
It is easy to use and had to share it for me not to lose it again because I am lazy running these commands everytime I want to use ligolo.
It is straight forward and really easy to use

### Requirement
The only requirement so far is to have root access or password to be able to make it work. If you are having issues running the commands you are proably missing `iproute` packages.

On Debian/Ubuntu-based distributions:
```
sudo apt update
sudo apt install iproute2
```
On Red Hat/CentOS/Fedora-based distributions:
```
sudo yum install iproute
```
or (on newer versions of Fedora):
```
sudo dnf install iproute
```
On Arch Linux:
```
sudo pacman -S iproute2
```
or 
```
yay -S iproute2
```
## Usage
Very easy to use, so that you don't have to type these everytime. You can add one or delete one. Your choice.
Once installed, give it executable permissions:
```bash
chmod +x ligolo-setup.sh
```
Once this step is done we are ready to roll, now just execute it and make a choice:
```bash
./ligolo-setup.sh
```
Here are some screenshots:

![image](https://github.com/user-attachments/assets/41696e52-f23e-45cc-9f99-dab4508d62ff)


Hope it helps someone who is also tired or too much in a rush of typing those two commands. 
Planning on adding functionalities as I go because `ligolo-ng` is such a powerfull tool and makes a lot of things easier

Keep hacking and enjoy 😄
