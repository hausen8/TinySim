# AL_SIM

Minimal simulation configuration for a LinuxCNC milling machine with 3 simulated axes, home switches and a spindle with adjustable acceleration/deceleration.

**Installation and configuration**
 - Simply copy all files into a new folder named AL_CNC in your linuxcnc/configs folder
 - Start LinuxCNC, select *My Configurations -> AL_SIM -> AL_SIM* from the tree and click the checkbox to create a desktop shortcut.
 - If you don't need the PyVCP side panel, delete or comment out *PYVCP = AL_SIM_panel.xml* in *AL_SIM.ini*. All pins for the panel can be found in *AL_SIM_postgui.hal* 
