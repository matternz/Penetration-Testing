# Essential Linux Commands
#### Commands that I think is important to know, explanation of them taken from explainshell.com
#### Other resources used:
- https://www.hackingloops.com/command-cheat-sheet-for-linux/

### Basic Shell Commands

**clear**
***clears console***
```
clear - clear the terminal screen
```

**mount**
***displays mounted media and file systems***
```
mount - mount a filesystem
```

**uptime**
***displays how long system has being active***
```
uptime - tell how long the system has been running
```

**su root**
******
```
su - change user ID or become superuser
```

**ls -lah**
***ls all files in long format including hidden in a human readable format***
```
ls - list directory contents

-l list directory contents using a long listing format 

-a do not ignore entries starting with .with -l, 

-h print sizes in human readable format (e.g., 1K 234M 2G)
```

**pwd**
```
pwd - prints name of current/working directory
```

**cd**
***moves directory e.g. cd desktop, cd ..***
```
cd - change the current working directory
```

**pwd**
***prints current location in file system***
```
pwd - print name of current/working directory
```

**whoami**
***displays the current activate user***
```
whoami - print effective userid
```

**date**
***prints out the time and date of the system***
```
date - print or set the system date and time
```

**ps aux**
***Displays list of running processes***
```
ps - reports a snapshot of the current processes

-a Select all processes except both session leaders and processes not associated with a terminal.

-u  Select by effective user ID (EUID) or name. 
    This selects the processes whose effective user name or ID is in userlist. 
    The effective user ID describes the user whose file access permissions are used by the process.
    Identical to U and --user.

x - Lift the BSD-style "must have a tty" restriction, which is imposed upon the set of all
    processes when some BSD-style (without "-") options are used or when the ps personality
    setting is BSD-like. The set of processes selected in this manner is in addition to the
    set of processes selected by other means. An alternate description is that this option
    causes ps to list all processes owned by you (same EUID as ps), or to list all processes
    when used together with the a option.
```

**kill**
***Kills a processe based on number given e.g. kill 4***
```
kill - send a signal to a process
```

## Network Interface and IP Commands

**ifconfig**
***display interface information, mac addresses, IPv4, IPv6, interface status, transmitted and received date etc.***
```
ifconfig - configure a network interface
```

**route**
***displays current routing table, including default route***
```
route - show / manipulate the IP routing table
```
