# TinySim

Minimal simulation configuration for a LinuxCNC milling machine with 3 simulated axes, home switches and a spindle with adjustable acceleration/deceleration.

### Installation and configuration
 - Simply copy all files into a new folder named TinySim in your linuxcnc/configs folder
 - Start LinuxCNC, select *My Configurations -> TinySim -> TinySim* from the tree and click the checkbox to create a desktop shortcut.

### Removing the PyVCP side panel
- If you want to remove the panel, open *TinySim.ini* and comment out the following lines:

```
[DISPLAY]
# PYVCP = TinySim_panel.xml

[HAL]
# POSTGUI_HALFILE = TinySim_postgui.hal
```

- Open *TinySim.hal* and set *limit_speed.maxv* to a fixed value:

```
setp    limit_speed.maxv   5000
# net   spindle-acc-val    limit_speed.maxv   <=
```


