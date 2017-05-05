google ahk manual
Version 1.1.24.05
https://autohotkey.com/docs/AutoHotkey.htm

[TOC]

#Quick Reference
#Basic Usage and Syntax
##Hotkeys
```
`::
msgbox 1Click
return
```
```
`::msgbox 1
```

```
` & 1::msgbox 1
```

Other Features:
```
` & 1::AltTab  ; Hold down right-control then press right-shift repeatedly to move forward.
` & 2::ShiftAltTab  ; Without even having to release right-control, press Enter to reverse direction.
```

##Hotstrings & auto-replace
```
::\1::11
```
```
::\1::
msgbox 1
return
```
##Remapping keys and buttons
```
1::2
```
##Key List (Keyboard, Mouse, Joystick)
https://autohotkey.com/docs/KeyList.htm
##Scripts
```
msgbox 1
```
##Variables and Expressions
```
v1 := 123
v2 := "abc"
v3 := 1+1
msgbox, %v1%%v2%%v3%
```
#Mouse and Keyboard
##Hotkeys and Hotstrings
### #If
```
#If WinActive("ahk_exe explorer.exe")
`::msgbox 1
#If
#If WinActive("ahk_exe notepad.exe")
`::msgbox 2
#If
```
note:To turn off context sensitivity, specify #If or any #IfWin directive but omit all the parameters.
##MouseClick
windows7sp1点击开始
```
`::MouseClick, left, 33, 920
```
##MouseGetPos
```
MouseGetPos, xpos, ypos
Msgbox, The cursor is at X%xpos% Y%ypos%. 
```

##MouseMove
```
MouseMove, 200, 100
```
##Send, SendRaw, SendInput, SendPlay, SendEvent
```
`::send {bs 5}
```