# machine-setup-tasks
This document will  preserve the steps for setting up a new windows box for development

1. Download and install chocolatey from http://chocolatey.org
2. Execute
```
cinst -yfr google-chrome-x64 robomongo sublimetext3 putty winscp git conemu mingw keepass dropbox openvpn adobe-creative-cloud tunnelier tortoisesvn 7zip ccleaner teamviewer rdm nginx skype wireshark sumatrapdf spotify paint.net nssm nsis nodejs choco install procmon mongodb.core.2.6 ruby divvy
 ```
option 2
```
cinst -yfr google-chrome-x64 sublimetext3 putty winscp git conemu mingw keepass dropbox openvpn tunnelier 7zip ccleaner teamviewer nginx wireshark sumatrapdf spotify paint.net nssm nsis nodejs procmon ruby divvy
```

3. set up services
 * Install mongodb windows service
 * Install nginx windows service
 * Install graphicsmagick
 * Install wkhtmltopdf
 * Install Microsoft Office

option 2
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
 
 option 2
 ```
 set PATH=%PATH%;C:\Program Files (x86)\Git\bin
 ```

5. Install npm modules
```
npm install -g grunt grunt-cli yo bower typescript tsd
```
6. Install ruby gems
```
gem install sass
```

7. Install Sublime text packages
```
{
	"bootstrapped": true,
	"in_process_packages":
	[
	],
	"installed_packages":
	[
		"BracketHighlighter",
		"HTML-CSS-JS Prettify",
		"Jade",
		"Package Control",
		"SCSS",
		"SideBarEnhancements",
		"SublimeLinter-gjslint",
		"SublimeLinter-jshint",
		"SublimeLinter-json",
		"TypeScript"
	]
}
```
