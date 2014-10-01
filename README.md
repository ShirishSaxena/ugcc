### Welcome to UGCC Gaming Panel Installer { For Linux }.


Usage { CentOs/RedHat } :-
```
$ yum update -y
$ cd
$ wget http://shirish.me/UGCCPanel --no-check-certificate
$ chmod 777 UGCCPanel
$ ./UGCCPanel --install
```

Usage { Ubuntu/Debian} :-
```
$ apt-get update -y
$ cd
$ wget http://shirish.me/UGCCPanel --no-check-certificate
$ chmod 777 UGCCPanel
$ ./UGCCPanel --install
```

If you're using any OS other than Ubuntu/Debian/RedHat/CentOS then this script won't gonna work.

### Features

- Check for Distribution { Debian/RedHat }
- Support for Building Mono v2.10.9 , XSP v2.10.2, P7Zip v9.20.1 from Source { Available only for RedHat/CentOs }
- Use Screen and XSP2 to run the Panel as it uses less ram than binding it to apache2 { IMO }
- Can Start/Stop/Restart the Panel via this Script after installing Panel
        ./UGCCPanel start
- Generate Logs for Installation of { Mono | XSP | P7Zip }

More features are coming soon ...

### Left to do

  - Add Support to Ubuntu 10.04 or older
  - Support for Wine Installation for Debian/Ubuntu/RedHat/CentOS { For running Windows applications }
  - Much More.

### Support or Contact

Having trouble with UGCCPanel Installer ? 
Contact me @ me.shirish.me and I’ll help you sort it out.

### License and Other
This Installer is on GNU v2 license.
