#Parametric openscad needle cutter mount

Default settings should give a usable cutter mount that's about 20mm taller than [http://www.thingiverse.com/thing:1211039](djk4linux's orignal design) based on his suggestion that a taller mount would probably work better due to putting less lateral force on the needle.  So far this seems to be true.

Right now this only includes the [http://www.thingiverse.com/thing:1234989](hicwic) QC mount and it's not really done parametrically yet.  When I find time I want to add the new default MPCNC mount as an option and adjust both so they can resize correctly as the height is adjusted.

8/28/2016 - Finally found time to print one of my own and confirmed that at least with the default settings it works quite well.  Original [http://www.thingiverse.com/thing:1234989](hicwic mount) is now included and should work for most reasonable sizes - but the mount isn't parametric yet so it just kind of jumps between two sizes.  Also haven't added the new default MPCNC mounts but I'm getting ready to upgrade my MPCNC so will probably add those soon.
8/17/2016 - Uploaded revised .scad file with hicwic style QC mount and a few minor fixes.
8/17/2016 - Uploaded another revised .scad file fixing some issues with the QC mount.  QC mount isn't smart enough to resize yet, but now sits level with the base and will add an extension for taller mounts.