A outline of filesystem hieracrchy of modern versions of macOS, due to `File System Programming Guide` not including a description of the current macOS
filesystem hieracy, i've decided to make one outline here:

	`/` :Root directory of the system
  
	
	`Applications/`: macOS applications aviable globaly on the system.
	
	`Library/`:
	
	`System/`: System files-
	
-`Applications/`:Standard macOS apps

-`Developer/`

-`DriverKit/`

-`Library/`

-`Volumes/`

`-iOSSupport/`

	
	`Users/`:
	
	`Volumes/`: Simular to `Media`, lists all mounted filesystems, can lead to recursion.
	
	`bin/`:
	
	`cores/`:
	
	`dev/`:
	
	`etc@`:
	
	`home@`: 
	
	`opt/`: A directory meant for tridtional unix apps too complex for '/bin' and package managers.
	
	`private/`:
	
	`sbin/`:
	
	`tmp@`:

	`usr/`:
	
	`var@`:
`
There are some items not meant to be seen in regular use by the user:

	`.VolumeIcon.icns@`:

	`.file`:
		
	`.vol/`:
	
