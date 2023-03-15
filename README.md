# TinySim

Minimal simulation configuration for a LinuxCNC milling machine with 3 simulated axes, home switches and a spindle with adjustable acceleration/deceleration.

**Installation and configuration**
 - Simply copy all files into a new folder named TinySim in your linuxcnc/configs folder
 - Start LinuxCNC, select *My Configurations -> TinySim -> TinySim* from the tree and click the checkbox to create a desktop shortcut.
 - If you want to remove the PyVCP side panel, please note that you have to set *spindle-acc-val* in *TinySim.hal* to a fixed value (i.e. 5000)
