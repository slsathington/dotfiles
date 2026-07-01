# Linux Cheatsheet

## Git

```bash
git status
git add .
git commit -m "message"
git push
git pull
git diff
git log --oneline
git branch
git checkout branch-name
git switch branch-name
git restore filename
```

## GitHub CLI

```bash
gh auth login
gh auth status
gh repo clone owner/repo
gh repo create
gh repo view
```

## Pacman

```bash
sudo pacman -Syu          # Update system
sudo pacman -S package    # Install package
sudo pacman -Rns package  # Remove package
pacman -Qs package        # Search installed packages
pacman -Ss package        # Search repositories
pacman -Qi package        # Package information
```

## Paru

```bash
paru                     # Update everything
paru -S package          # Install AUR package
paru -Ss package         # Search AUR
paru -Rns package        # Remove package
```

## Fish

```bash
fish_config
source ~/.config/fish/config.fish
```

## Fastfetch

```bash
fastfetch
```

## Kitty

```bash
kitty
kitty --config ~/.config/kitty/kitty.conf
```

## Rofi

```bash
rofi -show drun
rofi -show run
```

## File Management

```bash
ls
ls -la
pwd
cd
mkdir
cp
mv
rm
find
```

## Networking

```bash
ping google.com
ip addr
ip route
nmcli device status
```

## Processes

```bash
ps aux
htop
btop
kill PID
killall program
```

## Disk Usage

```bash
df -h
du -sh *
```

## System

```bash
uname -a
hostnamectl
systemctl status
systemctl --user status
```
