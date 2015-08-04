# machine-setup-tasks
This document will  preserve the steps for setting up a new windows box for development

1. Download and install chocolatey from http://chocolatey.org
2. Execute
```
cinst -yfr google-chrome-x64 robomongo sublimetext3 putty winscp git conemu mingw keepass dropbox openvpn adobe-creative-cloud tunnelier tortoisesvn 7zip ccleaner teamviewer rdm nginx skype wireshark sumatrapdf spotify paint.net nssm nsis nodejs mongodb.core.2.6
 ```
3.set up services
* Install mongodb windows service
* Install nginx windows service
* Install graphicsmagick
* Install wkhtmltopdf
* Install Microsoft Office
4. Set path variables
* Add mongodb to path
* Add linux utilities to path 
```
set PATH=%PATH%;C:\mongodb\2.6.1\bin;C:\Program Files (x86)\Git\bin
```
