# MISS_TSN-Command
TSN RP Community Command Systems for building the TSN Sandbox
 
TSN Command Systems is a script that generates the TSN Sandbox.

The TSN Sandbox is a mission script to be used in Artemis that enables fully Game Master-moderated missions.
 
## Requirements
The current version of TSN Command Systems and the TSN Sandbox require Artemis 2.8.1 with the TSN Mod installed. For the TSN Mod, see [here](https://github.com/tsnrp/mod).

## Installation
Clone or download this repository into the `dat\missions` folder of your Artems installation. **Important**: The name of the folder within `dat\missions` has to exactly correspond to the file name of the mission XML file (minus the file extension)─in this case, `MISS_TSN-Command`. The final folder structure should look as follows:
```
[Artemis install directory]
├── dat
│   ├── missions
│   │   ├── MISS_TSN-Command
│   │   │   ├── [contents of this repository]
```

## Usage
### Command Systems
To generate the XML files of the TSN sandbox (i.e. the files used by Artemis), first run the `MISS_TSN-Command.exe` executable included in this repository. Select the systems and modules to be included in your sandbox. Finally, click `Build` to generate the XML files according to your settings.

[Video overview of the TSN Command Systems](https://www.youtube.com/watch?v=sDXynMsksXY)

### TSN Sandbox
To use the generated sandbox, first launch Artemis and start a server. Select a Custom Script, and then select the `TSN-Command` script.
Note that to use the sandbox, it is required for one client to use the Game Master console.

[Slightly outdated, but still helpful video explaining how to use the TSN Sandbox](https://www.youtube.com/watch?v=pFmg2e8LOYs)
