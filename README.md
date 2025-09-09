[![jp](https://img.shields.io/badge/lang-jp-blue.svg)](https://github.com/svglan/arch-dots/blob/main/i18n/README.jp.md)
[![ro](https://img.shields.io/badge/lang-ro-green.svg)](https://github.com/svglan/arch-dots/blob/main/i18n/README.ro.md)
[![ru](https://img.shields.io/badge/lang-ru-red.svg)](https://github.com/svglan/arch-dots/blob/main/i18n/README.ru.md)
[![ua](https://img.shields.io/badge/lang-ua-white.svg)](https://github.com/svglan/arch-dots/blob/main/i18n/README.ua.md)
[![de](https://img.shields.io/badge/lang-de-magenta.svg)](https://github.com/svglan/arch-dots/blob/main/i18n/README.de.md)

<h3 align="center">
<img align="center" width="80%" src=https://github.com/user-attachments/assets/bc18bd4d-944b-4d5f-a119-7578fa38f9b4 />
</h3>


<div align="center">
<br>
  <a href="#-copying--installation--update-instructions-"><kbd> <br> Installation <br> </kbd></a>&ensp;&ensp;
  <a href="https://github.com/svglan/arch-dots/wiki"><kbd> <br> Wiki <br> </kbd></a>&ensp;&ensp;
  <a href="https://github.com/svglan/arch-dots/discussions"><kbd> <br> Discussions <br> </kbd></a>&ensp;&ensp;
  <a href="https://github.com/svglan/arch-dots/wiki/Keybinds"><kbd> <br> Keybinds <br> </kbd></a>&ensp;&ensp;
</div><br>

<div align="center">


<div align="center">

https://github.com/user-attachments/assets/49bc12b2-abaf-45de-a21c-67aacd9bb872

</div>


---
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=22&pause=1000&color=F7077E&vCenter=true&width=435&height=30&lines=INSTALLATION)](https://git.io/typing-svg)
### 🚩 🏁 Auto Distro-Hyprland install scripts cloning and starting 🇵🇭
> [!CAUTION] 
> If you are using FISH SHELL, DO NOT use this function. Clone the Distro-Hyprland and ran install.sh instead

- NOTE: you need package `curl` for this to work

```bash
sh <(curl -L https://raw.githubusercontent.com/JaKooLit/Hyprland-Dots/main/Distro-Hyprland.sh)
```

- you can now use above command to automatically clone the Distro-Hyprland install scripts below
- it will clone the install scripts and start the `install.sh` 😎


### 👁️‍🗨️ My Hyprland install Scripts 👁️‍🗨️
- Automated Hyprland Scripts for Distro of choice which will pull this dotfiles if opted to install these configurations

- [Arch-Linux](https://github.com/svglan/arch)

---

### 🪧 Attention 🪧
- This repo does NOT contain or will NOT install any packages. These are only pre-configured-hyprland configs or dotfiles
- refer to install scripts what packages needed to install... but atleast, Hyprland packages is needed 😏😏😏 duh!!
- This repo will be pulled by the Distro-Hyprland install scripts above if you opt to download pre-configured dots


### 📦 Whats new?
- To easily track changes, I will be updating the [CHANGELOGS](https://github.com/svglan/arch-dots/wiki/Changelogs)  Screenshots will be included if worth mentioning the changes!

> [!NOTE]
> Kindly note that by defeault, Kools Dots are adjusted / configured for 2k (1440p) display without scaling. 

### 💥 Copying / Installation / Update instructions 💥
- [`MORE INFO HERE`](https://github.com/svglan/arch-dots/wiki/Install_&_Update) 
> [!Note] 
> The auto copy script "copy.sh" will create backups of intended directories to be copied. However, still a good idea to manually backup just incase script failed to backup!
- clone this repo by using git. Change directory, make executable and run the script

> to download from Master branch
```bash
git clone --depth=1 https://github.com/svglan/arch-dots.git
cd Hyprland-Dots
```

> to download from Development branch (development and testing)
```bash
git clone --depth=1 https://github.com/svglan/arch-dots.git -b development
cd Hyprland-Dots
```

- automatic copy/install of pre-configured dots (recommended for updating)
```bash
chmod +x copy.sh
./copy.sh
```

- to copy/install from releases (stable) (note this is 1 version older than in main)
```bash
chmod +x release.sh
./release.sh
```

- UPGRADE.sh function
> [!IMPORTANT]
> You need rsync for it to work
> you should have already up and running KooL's Hyprland before using this function
```bash
chmod +x upgrade.sh
./upgrade.sh
```

## ❗❗❗ DEBIAN AND UBUNTU HEADS UP!
- I am getting ridiculously amount of messages for updating your KooL Hyprland dotfiles. I have made a BIG note on [`WIKI`](https://github.com/svglan/arch-dots/wiki/Install_&_Update)


#### ⚠️⚠️⚠️ ATTENTION - BACKUPS CREATED by SCRIPT
> [!CAUTION]
> copy.sh, release.sh and even upgrade.sh creates a backup!
> Kindly investigate manually contents on your $HOME/.config
> Delete manually all the backups which you dont need

#### 🛎️ a small note on wallpapers
- by default, only few wallpapers will be copied (1 each dark and light plus 3 more). You will be offered to download more wallpapers. You can preview/check the additional wallpapers from [`THIS`](https://github.com/JaKooLit/Wallpaper-Bank/tree/main/wallpapers) Link


#### ⚠️⚠️⚠️ A MUST! after copying  / Installing these dots
+ Press SUPER W and set a wallpaper. This is also to initiate wallust for waybar, kitty (tty) and rofi themes. However, If you use the copy.sh or the release.sh, there will be a preset initial Wallpaper and you dont have to do this

+ Nvidia Owners. Make sure to edit your `~/.config/hypr/UserConfigs/ENVariables.conf` (highly recommended).
- NVIDIA users / owners, after installation, check [`THIS`](https://github.com/svglan/arch-dots/wiki/Notes_to_remember#--for-nvidia-gpu-users)

+ If you have already set your own keybinds, monitors, etc.... Just copy over from backup created before log-out or reboot. (recommended)


#### 📖 Known issues and possible solutions
- check out this page [FAQ](https://github.com/svglan/arch-dots/wiki/FAQ) and [UNSOLVED ISSUES](https://github.com/svglan/arch-dots/wiki/Known_Issues)


#### 🙋 QUESTIONS ?!?! ⁉️
- FAQ! Yes you can use these dotfiles to other distro! Just ensure to install proper packages first! If it makes you feel better, I use same config on my Gentoo:)
- QUICK HINT! Click the HINT! Waybar module (note only available in Waybar default and Simple-L [TOP] layout). Can be launched by Keybind `SUPER H`
- More question? click here browse through this [WIKI](https://github.com/svglan/arch-dots/wiki/)
- If you want the old configs, it is collected on my "Archive" repo. See [HERE](https://github.com/svglan/arch-dots-releases-Archive)

#### ⌨ Keybinds
- Keybinds [`CLICK`](https://github.com/svglan/arch-dots/wiki/Keybinds)

#### 🙏 Special request
- If you have improvements on the dotfiles or configuration, feel free to submit a PR for improvement. I always welcome improvements as I am also just learning just like you guys!


#### ✍️ Contributing
- Want to contribute? Click [`HERE`](https://github.com/svglan/arch-dots/blob/main/CONTRIBUTING.md) for a guide how to contribute


#### 🤷‍♂️ TO DO!
- [ ] Tweak dots - 🚧 in constant progress 




                        
## 🫰	Thank you for the stars 🩷
[![Stargazers over time](https://starchart.cc/JaKooLit/Hyprland-Dots.svg?variant=adaptive)](https://starchart.cc/JaKooLit/Hyprland-Dots)
