<h1 align="center">Plymouth Themes</h1>

<p align="center">
A big collection of plymouth themes, ported from <i>android bootanimation</i> from <a href="https:/forum.xda-developers.com/android/themes/alienware-t3721978">here.</a>
</p>

![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews)

### What is plymouth?

[Plymouth](http:/www.freedesktop.org/wiki/Software/Plymouth) is a project from Fedora and now listed among the [freedesktop.org's official resources](https:/www.freedesktop.org/wiki/Software/#graphicsdriverswindowsystemsandsupportinglibraries) providing a flicker-free graphical boot process. It relies on [kernel mode setting](https:/wiki.archlinux.org/index.php/Kernel_mode_setting) (KMS) to set the native resolution of the display as early as possible, then provides an eye-candy splash screen leading all the way up to the login manager.

### How to set it up?

follow [this](https:/wiki.archlinux.org/index.php/plymouth) *archwiki* article to setup plymouth in *archlinux* or any other distro.

### How to get these themes?

**Download :** you can download individual themes via link below -
<p align="center">
  <a href="https:/github.com/ervinpopescu/plymouth-themes/tree/main/all_themes"><img alt="undefined" src="https:/img.shields.io/badge/Download-Here-orange?style=for-the-badge&logo=github"></a>
</p>

**Clone :** or you can clone this repository if you want - 
```bash
git clone https:/github.com/ervinpopescu/plymouth-themes.git
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

Here is an [Album](https:/www.buymeacoffee.com/p/44845).


Colorful Loop|Connect
--|--
![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Colorful-Loop.gif)|![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Connect.gif)


Deus Ex|Hexagon Dots
--|--
![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Deus-Ex.gif)|![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-Dots.gif)


Lone|Pixels
--|--
![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Lone.gif)|![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Pixels.gif)


Red Loader|Splash
--|--
![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Red-Loader.gif)|![gif](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Splash.gif)


+ [Abstract Rings](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Abstract-Rings.gif)
+ [Abstract Rings Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Abstract-Rings-Alt.gif)
+ [Alienware](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Alienware.gif)
+ [Angular](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Angular-Alt.gif)
+ [Angular Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Angular.gif)
+ [Black HUD](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Black-HUD.gif)
+ [Blockchain](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Blockchain.gif)
+ [Circle](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Circle.gif)
+ [Circle Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Circle-Alt.gif)
+ [Circle Flow](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Circle-Flow.gif)
+ [Circle HUD](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Circle-HUD.gif)
+ [Circuit](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Circuit.gif)
+ [Colorful](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Colorful.gif)
+ [Colorful Loop](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Colorful-Loop.gif)
+ [Colorful Sliced](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Colorful-Sliced.gif)
+ [Connect](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Connect.gif)
+ [Cross HUD](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cross-HUD.gif)
+ [Cubes](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cubes.gif)
+ [Cuts](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cuts.gif)
+ [Cuts Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cuts-Alt.gif)
+ [Cyanide](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cyanide.gif)
+ [Cybernetic](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Cybernetic.gif)
+ [Dark Planet](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Dark-Planet.gif)
+ [Darth Vader](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Darth-Vader.gif)
+ [Deus Ex](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Deus-Ex.gif)
+ [DNA](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/DNA.gif)
+ [Double](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Double.gif)
+ [Dragon](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Dragon.gif)
+ [Flame](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Flame.gif)
+ [Glitch](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Glitch.gif)
+ [Glow](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Glow.gif)
+ [Green Blocks](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Green-Blocks.gif)
+ [Green Loader](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Green-Loader.gif)
+ [Hexagon](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon.gif)
+ [Hexagon 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-2.gif)
+ [Hexagon Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-Alt.gif)
+ [Hexagon Dots](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-Dots.gif)
+ [Hexagon Dots Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-Dots-Alt.gif)
+ [Hexagon HUD](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-HUD.gif)
+ [Hexagon RED](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexagon-RED.gif)
+ [Hexa Retro](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hexa-Retro.gif)
+ [Hud](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hud-2.gif)
+ [Hud 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hud-3.gif)
+ [Hud 3](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hud.gif)
+ [Hud Space](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Hud-Space.gif)
+ [IBM](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/IBM.gif)
+ [Infinite Seal](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Infinite-Seal.gif)
+ [Ironman](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Ironman.gif)
+ [Liquid](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Liquid.gif)
+ [Loader](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Loader-2.gif)
+ [Loader 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Loader-Alt.gif)
+ [Loader Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Loader.gif)
+ [Lone](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Lone.gif)
+ [Metal Ball](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Metal-Ball.gif)
+ [Motion](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Motion.gif)
+ [Optimus](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Optimus.gif)
+ [Owl](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Owl.gif)
+ [Pie](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Pie.gif)
+ [Pixels](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Pixels.gif)
+ [Polaroid](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Polaroid.gif)
+ [Red Loader](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Red-Loader.gif)
+ [Rings](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Rings-2.gif)
+ [Rings 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Rings.gif)
+ [Rog](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Rog-2.gif)
+ [Rog 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Rog.gif)
+ [Seal](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Seal-2.gif)
+ [Seal 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Seal-3.gif)
+ [Seal 3](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Seal.gif)
+ [Sliced](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Sliced.gif)
+ [Sphere](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Sphere.gif)
+ [Spin](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Spin.gif)
+ [Spinner Alt](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Spinner-Alt.gif)
+ [Splash](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Splash.gif)
+ [Square](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Square.gif)
+ [Square Hud](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Square-Hud.gif)
+ [Target](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Target-2.gif)
+ [Target 2](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Target.gif)
+ [Tech A](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Tech-A.gif)
+ [Tech B](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Tech-B.gif)
+ [Unrap](https:/raw.githubusercontent.com/ervinpopescu/plymouth-themes/main/previews/Unrap.gif)


### FYI
+ Created and tested on machine with 1366x768 resolution.
+ Yeah, that's how *quarantine* going on :grin:.
+ Stay Home - Stay Safe, Help Fighting CORONA.
