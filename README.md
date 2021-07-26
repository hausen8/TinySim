# AL_SIM

Minimal simulation configuration for a LinuxCNC milling machine with 3 simulated axes, home switches and a spindle with adjustable acceleration/deceleration.

**Installation and configuration**
 - Simply copy all files into a new folder named AL_CNC in your linuxcnc/configs folder
 - Start LinuxCNC, select *My Configurations -> AL_SIM -> AL_SIM* from the tree and click the checkbox to create a desktop shortcut.
 - If you want to remove the PyVCP side panel, please note that you have to set *spindle-acc-val* in *AL_SIM.hal* to a fixed value (i.e. 5000)
