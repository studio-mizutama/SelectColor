# SelectColor
The purpose of this project is porting [SelectColor](https://github.com/bryful/F-s-PluginsProjects/tree/master/SelectColor), a After Effects plug-in to [OpenFX](https://github.com/ofxa/openfx) plug-in.

[SelectColor](https://github.com/bryful/F-s-PluginsProjects/tree/master/SelectColor) is a After Effects plug-in created by [bryful](https://github.com/bryful). It is very useful for anime creation.


## How to build and install the plug-in

for example, macOS

```sh
$ cd ~
$ git clone git@github.com:ofxa/openfx.git
$ git clone git@github.com:studio-mizutama/SelectColor.git
$ cp -r SelectColor ~/openfx/Examples/
$ cd ~/openfx/Examples/SelectColor
$ make
$ cp Darwin-64-debug/SelectColor.ofx.bundle /Library/OFX/Plugins/
```