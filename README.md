# Athena AI
Master repo for the rebuild of my personal home ai. It's kindof like Tony Stark's (Iron Man) Jarvis but this one is real :D   
##I'm taking some time to remake my bot from the ground up to incorperate better use of flask's server capabilities and the ai to function across far more platforms like:   
- Android Wear
- Android OS
- iOS (a bit of a stretch goal)
- MACOS
- Windows
- Linux (crazy right?)

## Progress update:
*Check out our [projects](https://github.com/Jspsun/Athena/projects/1) to see what we are working on 
- We've build the rough modules needed to accept a JSON request for commands
- Started work on a watch face to interface with the server
- Working on porting a bunch of the functionality and IOT modules from previous builds
- [ ] I'm aiming on setting up a wiki as I go so stay tuned for that
---

## Links to previous builds:
- [Version 2.0] (https://github.com/Jspsun/AthenaHomeAi)
- [Version 1.0] (https://github.com/Jspsun/AthenaVoiceAssistant)

## Submodules
Eventually there are going to be a whole ton of submodules in this repo so here's a short lookup of what each of them is

### [Athena Server] (https://github.com/Jspsun/AthenaServer)  
- Server that accepts JSON requests from clients
- Processes incoming posted data, sends back which actions need to be handled

### [Athena Smart Watch Face] (https://github.com/Jspsun/AthenaSmartWatchFace)
- Acts as regular watch face but also lets you use your voice to interface with the Athena Server
- Listens on requests from the Athena Server to carry out actions on the smart watch

*Big thanks to [Justin Li](https://github.com/Jli0423) for his help on the project*
