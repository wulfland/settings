# settings

Settings for different tools to share with the community. Let me know what you think.

# iTerm Shortcuts for Windows Terminal

[Here](terminal/settings.json) are my settings for the [Windows Terminal](https://github.com/microsoft/terminal). I use the same settings file for Preview and Stable.

My goal is to have the shortcuts as close as posible to iTerm2 since I work on Windows and Mac.

The Windows Terminal does not support the Windows key for shortcuts. That's why I had to replace the Command key with alt+

If you want to store you settings in GitHub like I do, you can do the following:

1. Open your settings with <kbd>CTRL</kbd>+<kbd>,</kbd>
2. Copy the file to a new or existing git repository
3. Copy the path to the file (in VSCode <kbd>Shift</kbd>+<kbd>ALT</kbd>+<kbd>C</kbd>)
4. Open a command prompt as adiministrator
5. Now create a hard symlink with the following command:

``` powershell
mklink settings.json /H <path_to_your_repository>\settings.json
```

Thats it. Now you can use your settings normally and if you change them your repos changes.
