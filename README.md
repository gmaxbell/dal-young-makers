# dal-young-makers
Dallas Young Makers Source Repo

This repo hosts source code and project materials used in classes taught by the Dallas Young Makers Group.  All code is published under GPL.

Included is a utility to automate the flashing RCX bricks [flash-rcx-class](../master/tools/flash-rcx-class).  This will flash the brick with the approproate firmware and load the programs used in the specified class.

After you have the files, you can flash your RCX brick(s) with the following command from the tools folder:

`$ ./flash-rsx-class /path/to/classes/build-a-rover`
(edit path as necessary)

If you already have the firmware installed, you can add -s to just load the programs. The script should download firmware, find IR tower(s), and load all 5 programs automatically. 

