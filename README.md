<h1 align="center">
 <img src="https://github.com/erikdubois/arcolinux-nemesis/blob/master/Personal/settings/arcolinuxw.png">
  <br />
   Power - rising example for Plasma
</h1>

![Maintenance](https://img.shields.io/maintenance/yes/2024?style=for-the-badge)
![Last-Commit](https://img.shields.io/github/last-commit/erikdubois/arcolinux-nemesis?style=for-the-badge)

<a href="https://discord.gg/stBhS4taje" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/discord/1068192254365282405?logo=discord&label=discord" alt="discord"/></a>
<a href="https://t.me/arcolinux_d_b" target="_blank" rel="noopener noreferrer"><img alt="Telegram" src="https://img.shields.io/badge/telegram-chat-blue?logo=telegram"></a>

<img alt="GitHub followers" src="https://img.shields.io/github/followers/erikdubois?style=flat">&nbsp;&nbsp;<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/erikdubois/arcolinux-nemesis">&nbsp;&nbsp;<img alt="GitHub forks" src="https://img.shields.io/github/forks/erikdubois/arcolinux-nemesis">

<img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCJdmdUp5BrsWsYVQUylCMLg">&nbsp;&nbsp;<img alt="YouTube Channel Views" src="https://img.shields.io/youtube/channel/views/UCJdmdUp5BrsWsYVQUylCMLg">

<img alt="AUR Last Modified" src="https://img.shields.io/aur/last-modified/archlinux-tweak-tool-git?label=AUR%20-%20ArchLinux-Tweak-Tool%20or%20ATT">


# Nixos-configurations

3 desktops (1 with nvidia card) and 1 laptop will be set with these configs

Plasma as default desktop.

Use the plasma iso from Nixos - install it with calamares.

Open up your Documents folder and open a terminal there and type:

nix-env -i git 

This will install git. It might take a while to install it. Be patient.

Then you get this github project via this command in the same terminal:

git clone https://github.com/erikdubois/nixos-configurations

My pcs got a name because of this project.

Keep the name or change it anywhere and everywhere.

My username and keyboard setup (Belgium - Azerty) are also in my configs. So change them.

Some are with nvidia - others are just intel.

The dotfiles folder contain all the desktops we can install. Code is coming from ArcoLinux - then we adapt it to work on NixOS.

We use the same dotfiles on all pcs.


# Desktops

 - awesome

 - bspwm

 - chadwm - not working

 - dusk - not working

 - dwm

 - hyprland

 - i3wm

 - openbox

 - plasma

 - qtile

 - others ... see images


I have created separate desktops file in the folder Desktops.

If we remove the "#" in the configuration.nix file it will be installed.

This is a personal project.

We call it sidetracking.

You always learn something from switching distros.

More info in our videos

https://www.youtube.com/playlist?list=PLlloYVGq5pS7HDKMIzvngkPsZvaxTsYKq

# Tips

TIP 1: your scripts always start with this shebang

#!/usr/bin/env bash

TIP 2: your desktops name is not bspwm for example but none+bspwm - that matters in variety, polybars and wherever you make references to the ENV variables

TIP 3: Use syntax editing for the nix language in sublime-text or visual studio code - you will make less mistakes



# Examples

All the possible desktops on NixOS : https://mynixos.com/options/services.xserver.desktopManager 


![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/9bd7360b-cd5b-40e6-b70a-9df9e0e0221f)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/ea56ddbd-b15a-4cb9-b71e-b8a8ee9929a6)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/75d587cb-2547-425a-8ba4-012bcfc238a1)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/d3bb2eb7-39dd-4d4e-97a6-233ae02505d7)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/bba78edc-7fdf-49d9-9692-5464e10ba075)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/3a21ac3c-2b2f-45be-80e9-ee169bc78074)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/e1d837ec-9d45-4836-a7a7-f924cfefadb2)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/43da73a4-a261-4a74-823a-f63b187fa9f4)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/d22bcd6d-6c1a-4af1-a0e8-46fb2ae1457e)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/6e49cb93-24da-4ea1-935d-2cf20c615128)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/c5ec03a5-a6fe-4310-bef6-06a4b8836f1d)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/f9161bae-09bd-41fb-bdae-335dd53d6fb7)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/4edbcabd-2daa-4ac9-94b3-903fb48ec799)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/a76e2257-b450-484e-920f-c3e31477902f)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/1b154332-a279-4fea-8a5f-9a8e65243979)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/474cabf6-1703-4871-bff3-a4d800fd8a07)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/8b61a601-57ae-402a-aa21-0ff28c573673)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/a3b611f2-efb1-4396-9312-1acd64796ad7)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/ee155703-c466-460d-ba06-1e685971190a)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/8e90af0e-4c61-4904-9dd6-d4e503ae88ae)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/b7ee6cd2-7955-4d17-bdc3-7fcd36073d0d)

![image](https://github.com/erikdubois/nixos-configurations/assets/10594806/6a65179a-4032-4789-879f-f4133f9fc6b9)







