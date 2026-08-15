# My Hyprland config
> ⚠️ This README is still a work in progress.

This is my personal Hyprland configuration.

I wanted a simple, minimal and comfortable setup without too many visual effects or unnecessary customization. When I was looking for existing Hyprland configurations, I found that many of them were heavily customized or focused on a very specific aesthetic.

``$mainMod`` is used instead of ``SUPER`` throughout the configuration. It is a variable that allows the main modifier key to be changed easily.

## Disclaimer
This configuration can be not plug-and-play, due the setting specific for my use, for example for the ``binds``, or for the ``exec``. 


## Hyprland.conf
The ``hyprland.conf`` is the main Hyprland configuration file, with basic things, and command for the source of the others files of config. 

### Wallpaper
For the wallpaper i used ``swaybg``, because it was the only one that worked properly on my system.

### Monitors
Basically, in this section there is my config of the monitors position. 

### Workspace
Here there is the different workspaces assigned to each monitor.

### Exec commands
In this section there is the commands when hyprland starts.
There is ``kitty``, the ``waybar``, the wallpaper(``swaybg``), and ``hypridle``.

### General commands
The sections ``general commands`` there are commands that i used to configure ``animations``, ``blur``, etc.


## Binds
To set up the binds i made the file ``binds.conf`` with all binds divided by sectors. 

The following subtitles are details about what i used for different things about the binds. 

### Screenshots - Screen recording 
To do screenshots i use ``slurp`` with a bind assigned to it, with assigned also the location of the screenshot taken.
The same for screenshot only a part of the screen.
And the same also for do a recording of the screen.

### Workspaces
The workspaces are configured that there are nine, and you select which one use using ``$mainMod + (number of the workspace)``

### Windows Binds
#### Windows move focus
With: ``$mainMod + arrow``.

#### Windows movement
With: ``$mainMod + SHIFT + arrow``.

### Windows movement between workspace
With: ``$mainMod + SHIFT + (number of the workspace)``.
