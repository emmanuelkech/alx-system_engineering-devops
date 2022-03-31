**su anotherUser** Switches the current user to a different user<br> 
**whoami** Prints the effective username of the current user<br>
**id -nG** Prints all the groups the current user is part of<br>
**sudo chown newOwner file** Changes the owner of the file to a different user<br>
**touch fileName** Creates an empty file called *fileName*<br>
**chmod u+x fileName** It adds execute permission to the owner of the file<br>
**chmod ug+x,o+r fileName** It adds execute permission to the owner and the group owner, and read permission to other users to the file *fileName*<br>
**chmod a+x fileName** Adds execution permission to the owner, the group owner and the other users to the file *fileName*<br>
**chmod 007 fileName** Sets no permission to owner, no permission to group, and all permissions to others to the file *fileName*<br>
**chmod 753 fileName** Sets the file to -rwxr-x-wx permission<br>
**chmod --reference=olleh hello** Sets the mode of the file *hello* the same as *olleh*<br>
**mkdir -m751 filename** Creates a directory called *filename* with permissions 751 in the working directory<br>
**chgrp newGroup someFile** Changes the group owner to *newGroup* for the file *someFile*<br>
**chown vincent:staff * ** Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory<br>
**sudo chown -h vincent:staff linkName** Changes the owner of symbolic link linkName and group name  to vincent and staff respectively<br>
**sudo chown --from=guillaume betty hello** Changes the owner of the file hello to betty only if it is owned by the user guillaume<br>
**telnet towel.blinkenlights.nl** This will play the StarWars IV episode in the terminal<br>
