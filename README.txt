These are Rho's configs, please read!



BASE CONFIG (z_main.cfg)

This is where I set important settings, like autoreload, FOV and mopuse sensitivity. 
I implement a zoom action here, that lowers your FOV and sens to make aiming easier without a scope,
it is specially useful for hunstman sniper and spy. 



GRAPHICAL SETTINGS

I don't run Chris's maxframes, my z_frames file is a customized version of highframes. 
It really is a middle ground, as I get fvery good FPS with these settings.
You can obviusly override the graphical settings in the autoexec.cfg file and call your preferred graphical config. 



NET SETTINGS

People like to mess with lerp and that stuff. 
I have compiled popular net settings, along with my own on the z_net config file. 
Chris's net settings are there, and this files contain aliases to switch on the fly. 
You'll notice my autoexec calls my net settings after defining the z_net aliases.



KEYBINDS

To edit keybinds to those that you use, edit the z_binds.cfg file. 
If you read through the configs, you'll notice I avoid binding keys directly at all costs, 
in order to keep keybinds in a single place.
IMPORTANT: The only config files that bind keys directly are z_viewmodels, pyro and spy. 
Please read the comments I have placed on z_binds for more info.

Keybinds most people find unusual is that I jump with mouse2 and alt fire is spacebar. 
Again, you can change these in z_binds. 



VIEWMODELS

These configs allow you to toggle viewmodels on and off for certain weapons and classes,
as well as hiding viewmodels/flame particles/muzzle flash when firing with the viewmodel_fov command.
See z_viewmodels for more info.
 
My scout.cfg and spy.cfg files are a good examples on how to implement hiding viewmodels when firing  
My demoman.cfg and soldier.cfg are good examples on how to implement selective viewmodel settings.
Each class can be customized in the class.cfg file.

I have also included special class specific actions, look at my medic/cfg file for a good example on how to implement thse. 
The key binds to call the special actions reside in z_binds.  
These special actiond default to funny voice commands when not defined in the class config file.
For medic, the "special" is the medic radar, "special2" is a fake uber call, "special3" is an uber mask.
Just read each class config file to see their special actions.