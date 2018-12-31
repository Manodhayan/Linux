# Install ZSH 

## Prerequisites
```
sudo apt-get install git
sudo apt-get install curl
sudo apt-get install zsh
```

## Clone zsh repository
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Enter your passowrd when prompted!
Congratulations! Your theme has been changed. To make it effective reboot the system

```
sudo reboot
```
You can change any theme you want by editing the .zshrc file

```
cd #Go to home directory
sudo nano .zshrc
```
In that find ZSH_THEME. Assign the theme name you like. I personaly prefer 'agnoster'