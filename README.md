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

## Functions in Ae plug-in
- About
- GlobalSetup
- GlobalSetdown
- ParamsSetup
- SequenceSetup
- SequenceSetdown
- SequenceResetup
- Render
- PreRender             PF_Cmd_SMART_PRE_RENDER
- SmartRender           PF_Cmd_SMART_RENDER
- (RespondtoAEGP)       PF_Cmd_COMPLETELY_GENERAL
- (HandleChangedParam)  PF_Cmd_USER_CHANGED_PARAM
- (QueryDynamicFlags)   PF_Cmd_QUERY_DYNAMIC_FLAGS
- (FilterImage*)
- (GetParams)
- (Exec)
- EntryPointFunc                                        pluginMain