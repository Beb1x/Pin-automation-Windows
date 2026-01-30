# Pin-automation-Windows
well, it writes to windows security a pin you set up


Small Windows utility that:
- waits for a window by title
- reads a PIN from an XML config
- types it automatically

Built out of pure frustration because of outdated pharma softwares in Romania

## Use it / Modify it to yours Heart content
but if you use it like 1:1, just add a link to this rep , if you can, or not, idk how this thing goes

## Requirements
- Windows
- Python 3.x
- pywin32

## KEEP IN MIND
1) im not a fully dev nor a CS student , im just a sys admin / l2 suport
2) I do not care about "Noo dont automate pin" or "why dont you useee thissss" , trust me i try d more than i can write, it just Did not fit MY USE CASE
3) If you Blocked your token is not my fault , just try it out on notepad first :D
4) this code is written by me, with my logic, and some help with log creation from chat gpt ( I still dont know how to use that libary sorry bros )

## XML format
```xml
<setting name="PIN">
    <value>1234</value>
</setting>
