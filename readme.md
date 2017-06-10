# Video Info 
An Electron app that shows basic information about a video file on your local hard drive.

## FFMPEG
Install FFMEG on Mac using Homebrew:
```bash
brew install ffmpeg
```
Install fluent-ffmpeg from npm:
```bash
npm install --save fluent-ffmpeg
```
## IPC - inter process communication
The communication protocol for sending events between the mainProcess and RenderProcess.
 
![Communication Between Processes](communication-ipc.png)


![Between MainWindow and Electron](ipc-process-videoinfo.png)