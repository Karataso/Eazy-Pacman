#!/bin/bash
#This is the istaller of EazyPacman but for both Devian Based distros and Arch Linux (And derivates)
#This is still on development, be patient, am learning the bare basics 

# ANSI color codes
RED='\033[0;31m'
GREEN='\033[0;32m'
YELLOW='\033[1;33m'
NC='\033[0m' # No Color

if [ -f /etc/debian_version ]; then
    clear
    sudo apt upgrade -y && sudo apt upgrade -y
    sudo apt install -y python3
    cp EzPacmanDebian /usr/local/bin/EzPacman
    clear
    echo -e "${GREEN}Success: EazyPkg was installed succesfilly${NC}"
    echo -e "${GREEN}Thank you so much for giving EzPkg a try <3 ${NC}"
    echo -e "${RED}EzPkg v1.2B ${NC}"
    
elif [ -f /etc/arch-release ]; then
    clear
    sudo pacman -Sy python-termcolor --noconfirm
    clear
    cp EzPacmanArch /usr/local/bin/EzPacman
    clear
    echo -e "${GREEN}Success: EazyPkg was installed succesfilly${NC}"
    echo -e "${GREEN}Thank you so much for giving EzPkg a try <3 ${NC}"
    echo -e "${RED}EzPkg v1.2B ${NC}"
    
else
    echo -e "${RED}Error: Unknown Distro :( ${NC}"
    echo -e "${RED}This Script is made for Arch Linux and Devian Baded distros ${NC}"
    echo -e "${GREEN}Thank you so much for giving EzPkg a try <3 ${NC}"
    echo -e "${GREEN}Am absolutely sory for the inconbeniences${NC}"
fi
