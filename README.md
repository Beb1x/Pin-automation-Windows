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

## XML format
```xml
<setting name="PIN">
    <value>1234</value>
</setting>
