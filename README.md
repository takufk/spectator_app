=====================================

#  __THE SPECTATOR APP.__

=====================================

## Overview  
The Spectator App. is developed for extension to a soccer monitor that is used in RoboCup soccer simulation 2D league. 
The aim of the extension is to make the experience of watching games more entertaining. 

## Demonstration
The demonstration and the tutorial are shown in the [YouTube](https://youtu.be/XFsRj6JVx_E).

## Requirement
- OS
  - Ubuntu 
- tool
  - [rcssserver](https://github.com/rcsoccersim/rcssserver)  
  - [soccerwindow2-screenshot](https://github.com/rinmunagi/soccerwindow2-screenshot)  
- library
  - Python 2.7.15  
  - Tensorflow 1.12.0  
  - PyQt4
  - opencv2

## Install
```
git clone http://github.com/rinmunagi/spectator_app
```
Install the [soccerwindow2-screenshot](https://github.com/rinmunagi/soccerwindow2-screenshot) in the 'spectator_app' directory.   
If librcsc isn't installed in the system directory, please change the path of it in the script 'execute'.
```  
LIBPATH=usr/local/lib -> /path/to/the/lib
```  
## Usage
```
./execute  
```
The three windows (the two soccerwindows and the SituationScore window) are launched.  
Start the rcssserver, and connect **the both soccerwindows** to the server.  
Run the team scripts and 'KickOff'.  

## License
[MIT](https://github.com/rinmunagi/spectator_app/blob/master/LICENSE)


## Author
- Yudai Suzuki (Osaka Prefecture University)  
- Takuya Fukushima (Osaka Prefecture University)  
- Lea Thibout (Osaka Prefecture University)  
- Tomoharu Nakashima (Osaka Prefecture University)  
- Hidehisa Akiyama (Fukuoka University)  

