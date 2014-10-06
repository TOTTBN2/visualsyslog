Visual Syslog Server
===
Visual Syslog Server (daemon) for Windows with a graphical user interface.

Visual Syslog Server is a free open source program to receive and view syslog messages. Useful when setting up routers and systems based on Unix/Linux.

Visual Syslog Server has a live messages view: switches to a new received message. Helpful color highlighting. Useful message filtering.

![Visual Syslog Server Screen](https://github.com/MaxBelkov/visualsyslog/blob/master/screens/screen1.png?raw=true)

Features
===
* Receive messages from various devices via UDP or TCP protocol (compliant to RFC 3164)
* Support Windows XP/Vista/7/8/8.1, Windows Server 2003/2008/2012
* Syslog messages are displayed in real-time
* Filter displayed syslog messages based on priority or message contents
* Сolor highlighting based on priority
* Import historical syslog files after the start of the program
* View and analyze syslog messages from the file
* Run as a Windows application
* Minimize to system tray
* Store all syslog messages in a single file
* Free open source software, licensed under the GPL V2

Download
===
Visual Syslog Server download installer for Windows  
[Download last developper snapshot from here](https://github.com/MaxBelkov/visualsyslog/blob/master/Output/visualsyslog_setup.exe?raw=true)  
[Download latest stable release from here](https://github.com/MaxBelkov/visualsyslog/releases/latest)

Installation
===
After installation Visual Syslog Server works immediately: adjustment is not required.
Waiting for messages on the UDP port 514 (default setting).
Visual Syslog Server is an Windows application (installing a system service is not required).

Building from sources
===
To build Visual Syslog Server from sources use CodeGear RAD Studio C++Builder 2007.  
Main project file _visualsyslog.cbproj_

To build the installer, use Inno Setup Compiler 5.5.1(a)  
Installer project file _visualsyslog.iss_

Is not supported yet
===
* RFC 5424
* Log file rotation
* Files larger than 2 GB
* Customizable color highlighting

If you need these or other functions let me know.  
Your questions and suggestions please send to ![ ](https://github.com/MaxBelkov/visualsyslog/blob/master/screens/m.png?raw=true)