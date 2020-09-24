<div align="center">

## Execute Control Panel Item


</div>

### Description

Allows the author to launch a Control Panel item (or .cpl file).
 
### More Info
 
The name of the .cpl file.

Windows Interface

Same effects of the Shell Command


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Will Smith](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/will-smith.md)
**Level**          |Advanced
**User Rating**    |4.2 (67 globes from 16 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/will-smith-execute-control-panel-item__1-5185/archive/master.zip)





### Source Code

```
'Where Odbccp32.cpl is the name of the control panel item.
Shell "rundll32.exe shell32.dll,Control_RunDLL Odbccp32.cpl", vbNormalFocus
```

