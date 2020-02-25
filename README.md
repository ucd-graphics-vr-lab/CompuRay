## CompuRay with HoloLens

### Description
CompuRay augments the experience involved during troubleshooting or upgrading of a traditional desktop computer. This project makes use of Microsoft HoloLens, the AR device recognizes various components of the computer and the results are spatial mapped to the real-world through HoloLens. HoloLens was trained to recognize the following components of a computer cabinet: CPU, Drive Bay, SMPS, GPU, RAM and PCI Slots. 

### Interaction
The interface provided for a user to interact with HoloLens is through voice commands, except during the phase of analysis. The advantage of voice commands over traditional HoloLens recognizable gestures includes handsfree control along with a more natural UI and almost a zero-learning curve in order to operate the device.
A demo of this project can be viewed here: [CompuRay Demo](https://youtu.be/kPMvuo2RQSU)

### Documentation
You can refer to our official blog [CompuRay with HoloLens](https://compuray.home.blog) for a detailed documentation. This repo mainly provides you with code, which might be helpful for you to build something upon.

### Requirements 
HoloLens (1st Gen), Visual Studio 2017, Unity 2017.x, HoloToolKit 2017 (note: not MRTK).

### Usage
Repo consists a Unity project directory.
Clone this directory and point Unity to this directory as a project. Unity should import all the assets and figure out project import work. You need to make a few changes in Unity as follows: 
- Build Settings > Switch to "Universal Windows Platform" and Target Device = HoloLens 
- Player Settings > Other Settings > Scripting Backend = .NET
- XR Settings > Virtual Reality Supported > Windows Mixed Reality
- Project Settings > Quality > Very Low

You should be now be set to make changes, build and deploy this app to the HoloLens. 
