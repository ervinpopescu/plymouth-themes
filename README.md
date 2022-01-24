<h1 align="center">Plymouth Themes</h1>

<p align="center">
A big collection of plymouth themes, ported from <i>android bootanimation</i> from <a href="https://forum.xda-developers.com/android/themes/alienware-t3721978">here.</a>
</p>

![](./previews/Lone.gif)

### What is plymouth?

[Plymouth](http:/www.freedesktop.org/wiki/Software/Plymouth) is a project from Fedora and now listed among the [freedesktop.org's official resources](https:/www.freedesktop.org/wiki/Software/#graphicsdriverswindowsystemsandsupportinglibraries) providing a flicker-free graphical boot process. It relies on [kernel mode setting](https:/wiki.archlinux.org/index.php/Kernel_mode_setting) (KMS) to set the native resolution of the display as early as possible, then provides an eye-candy splash screen leading all the way up to the login manager.

### How to set it up?

follow [this](https:/wiki.archlinux.org/index.php/plymouth) *archwiki* article to setup plymouth in *archlinux* or any other distro.

### How to get these themes?

**Download :** you can download individual themes via link below -
<p align="center">
  <a href="./all_themes"><img alt="undefined" src="https://img.shields.io/badge/Download-Here-orange?style=for-the-badge&logo=github"></a>
</p>

**Clone :** or you can clone this repository if you want - 
```bash
git clone https://github.com/ervinpopescu/plymouth-themes.git
```

**AUR :** If you have `archlinux`, you can install these [themes](https:/aur.archlinux.org/packages/?O=0&K=adi1090x) individually with an `AUR helper like yay`
```bash
yay -S plymouth-theme-NAME-git
```
> Remember to replace the underscore(\_) with an hyphen(-) in theme's NAME.


### How to use these themes?

+ follow the step below (I'm using **archlinux** here)- 
```bash
# packages needed - plymouth, plymouth-x11, plymouth-plugin-script(fedora)

# after downloading or cloning themes, copy the selected theme in plymouth theme dir
sudo cp -r angular /usr/share/plymouth/themes/

# check if theme exist in dir
sudo plymouth-set-default-theme -l

# now set the theme (angular, in this case) and rebuilt the initrd
sudo plymouth-set-default-theme -R angular

# optionally you can test theme by running the script given in repo (plymouth-x11 required)
sudo ./showplymouth.sh 20
```
+ For **debian**(Ubuntu, Kubuntu) based distros-
```bash
# make sure you have the packages for plymouth
sudo apt install plymouth

# after downloading or cloning themes, copy the selected theme in plymouth theme dir
sudo cp -r your_theme /usr/share/plymouth/themes/

# install the new theme (angular, in this case)
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/your_theme/your_theme.plymouth 100

# select the theme to apply
sudo update-alternatives --config default.plymouth
#(select the number to install your_theme)

# update initramfs
sudo update-initramfs -u
``` 
### Previews
Abstract Rings|Abstract Rings Alt|Alienware|Angular
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Abstract-Rings.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Abstract-Rings-Alt.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Alienware.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Angular-Alt.gif)

Angular Alt|Black HUD|Blockchain|Circle
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Angular.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Black-HUD.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Blockchain.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Circle.gif)

Circle Alt|Circle Flow|Circle HUD|Circuit
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Circle-Alt.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Circle-Flow.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Circle-HUD.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Circuit.gif)

Colorful|Colorful Loop|Colorful Sliced|Connect
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Colorful.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Colorful-Loop.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Colorful-Sliced.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Connect.gif)

Cross HUD|Cubes|Cuts|Cuts Alt
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cross-HUD.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cubes.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cuts.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cuts-Alt.gif)

Cyanide|Cybernetic|Dark Planet|Darth Vader
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cyanide.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Cybernetic.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Dark-Planet.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Darth-Vader.gif)

Deus Ex|DNA|Double|Dragon
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Deus-Ex.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//DNA.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Double.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Dragon.gif)

Flame|Glitch|Glow|Green Blocks
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Flame.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Glitch.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Glow.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Green-Blocks.gif)

Green Loader|Hexagon|Hexagon 2|Hexagon Alt
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Green-Loader.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-2.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-Alt.gif)

Hexagon Dots|Hexagon Dots Alt|Hexagon HUD|Hexagon RED
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-Dots.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-Dots-Alt.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-HUD.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexagon-RED.gif)

Hexa Retro|Hud|Hud 2|Hud 3
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hexa-Retro.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hud-2.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hud-3.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hud.gif)

Hud Space|IBM|Infinite Seal|Ironman
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Hud-Space.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//IBM.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Infinite-Seal.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Ironman.gif)

Liquid|Loader|Loader 2|Loader Alt
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Liquid.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Loader-2.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Loader-Alt.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Loader.gif)

Lone|Metal Ball|Motion|Optimus
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Lone.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Metal-Ball.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Motion.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Optimus.gif)

Owl|Pie|Pixels|Polaroid
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Owl.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Pie.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Pixels.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Polaroid.gif)

Red Loader|Rings|Rings 2|Rog
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Red-Loader.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Rings-2.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Rings.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Rog-2.gif)

Rog 2|Seal|Seal 2|Seal 3
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Rog.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Seal-2.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Seal-3.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Seal.gif)

Sliced|Sphere|Spin|Spinner Alt
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Sliced.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Sphere.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Spin.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Spinner-Alt.gif)

Splash|Square|Square Hud|Target
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Splash.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Square.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Square-Hud.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Target-2.gif)

Target 2|Tech A|Tech B|Unrap
--|--|--|--
![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Target.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Tech-A.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Tech-B.gif)|![gif](https://raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews//Unrap.gif)


### FYI
+ Created and tested on machine with 1366x768 resolution.
+ Yeah, that's how *quarantine* going on :grin:.
+ Stay Home - Stay Safe, Help Fighting CORONA.
