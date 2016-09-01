Customized Solarized Dark Theme for ST3
=======================================

I love the Solarized Dark theme, I use it everywhere.  I use Sublime Text 3 as my default editor, and over the years I have been slowly tweaking the `color_scheme` to better suite my tastes.  The default light colored drawer didn't work for me, so I wrote a `theme` to match my `color_scheme`.  I hope you enjoy...

![screenshot](https://raw.githubusercontent.com/swill/Theme-SolarizedSwill/master/screenshot.png "SolarizedSwill")


## Install on Mac

**Clone to:**
```
/Users/USER/Library/Application Support/Sublime Text 3/Packages/Theme-SolarizedSwill
```

**Enabling by navigating to:**
```
Sublime Text > Preferences > Color Schemes > Theme-SolarizedSwill > SolarizedSwill
```


## Install on Windows

**Clone to:**
```
C:\Users\USER\AppData\Roaming\Sublime Text 3\Packages\Theme-SolarizedSwill
```

## General Details

You may notice that inside `Theme-SolarizedSwill` there is both `SolarizedSwill` and `SolarizedDark` as options.  The [`SolarizedDark`](http://tmtheme-editor.herokuapp.com/#!/editor/theme/Solarized%20(dark)) color scheme is the standard version which most of you are probably familiar with.  I included it in case you prefer that `color_scheme`.

Since this is the only Solarized Dark `theme` available to match the drawer and tabs with the `color_scheme`, I expect people will likely use it as a starting point for modifications.

With this in mind, I chose to override the `Default.sublime-theme` for the following reasons:

- By not creating a full theme, I can override only the pieces I care about, making the file easier to customize and understand.
- Simplifies the installation process because it is picked up automatically if it is present. 

The only downside of customizing the `Default.sublime-theme` file is that the change is global.  If you change to a different color scheme, the tabs and drawer will remain themed to match the `SolarizedSwill` color scheme.  You will have to rename that file to undo the change.