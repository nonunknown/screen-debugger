# Screen Debugger

This is a plugin which enables the user to show their variables in-game. You can see the variables changing on-screen instead of printing them into console...

## Plugin in action
[![Plugin in action](http://img.youtube.com/vi/F_sUpE7E0Tc/0.jpg)](http://www.youtube.com/watch?v=F_sUpE7E0Tc)

## How to use

* Enable the plugin
* Make sure the singleton is the first one in the list
* In any script at "process" function type:
```
var life:int = 10
_process(delta):
    #ScreenDebugger Singleton Class / dict > The dictionary which holds all variables
    #Make sure to use unique name for the dict["UniqueNameHere"] identification of the var
    ScreenDebugger.dict["Life"] = life

```
