# newrez

Newrez is a nautilus script that not only makes it easy to change screen resolution on the fly, it lets you specify a resolution higher than your display's physical dimensions! This means that a netbook with a screen that's 1024x600 can display a scaled 1280x800 or higher (limited only by your eyesight :-)

Newrez does NOT "over-drive" the actual hardware. Instead, it defines a higher-resolution display on the netbook's VGA port, and scales it to the LCD.

You are not restricted to "standard" resolutions. Values like 1100x730 or 1350x900 or even 1400x700 will work just fine (and a few-pixel adjustment automatically applied if needed). Setting to 'default' will return everything back to normal.

Newrez can also be run directly from the command line, as in "newrez 1280x800" or "newrez default". This makes it a simple matter to switch to create scripts or icons that set your most common resolutions, or to include resolution changes into other scripts or launchers.
___________________________________________________________________________________

Native resolution (1366x768)

 <img src="https://github.com/enzodn/newrez/blob/main/screenshots/1366x768.png"/>
  
FullHD (1920x1080)

<img src="https://github.com/enzodn/newrez/blob/main/screenshots/1920x1080.png"/>

___________________________________________________________________________________


### Requirements:
```
xrandr (version 1.3 or higher)
zenity
bc
cvt 
```

#### Credits
The original author is
