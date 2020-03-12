# Screen Debugger

This is a plugin which enables the user to show their variables in-game. You can see the variables changing on-screen instead of printing them into console...

## How to use

* Enable the plugin
* Make sure the singleton is the first one in the list
* In any script at "process" function type:
```
var life:int = 10
_process(delta):
    ScreenDebugger.dict["Life"] = life

```
