# HiSlackGui
Hikari Slackware Gui is a small panel for Hikari desktop
But you can use it in every VM if you want. 

## Install
Download HiSlackGui.sh script and place it in your
```
$HOME/.config/hikari/
```
EDIT  or create this file if not exist (just an empty plain text file) named autostart.
```
$HOME/.config/hikari/autostart
and add script`s $PATH
```
EXAMPLE:
```
/home/rizitis/.config/hikari/HiSlackGui.sh
```

Thats it, every time you boot Slackware and start Hikari desktop, user will have the HiSlackGui panel in the screen.



![HiSlackGui](https://github.com/rizitis/HiSlackGui/raw/main/hikari-slackware.png)

### Deps
```
gtkdialog
zenity
```
All deps are in SBo repo.

#### Tip
![HiSlackGui](https://github.com/rizitis/HiSlackGui/raw/main/Hikari%20Slackware%20Gui.png)
If you have installed https://github.com/rizitis/Slackware-Commander
Then you can call it from HiSlackGui
In that case first you should command in terminal as user (not root)
```
xhost +
```
And then click button to launch Slackware-Commander


2) If you have Hybrid GPU NVIDIA you can run your apps from HiSlackGui
3) I use wf-recorder for recording desktop https://github.com/ammen99/wf-recorder
4) You can modify your it as you like... add most apps I use... 
