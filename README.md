# Sublime Text 3 Setup - User Settings

Personal simple user settings to use on Sublime Text 3, feel free to change what you want.


## Afterglow Theme

I like the [Afterglow Theme](https://github.com/YabataDesign/afterglow-theme) with Monokai color scheme. All you'll need is restart Sublime Text after installation for the changes to take effect.


## Useful and awesome packages

All plugins are installed using Package Manager. `⌘`+`Shift`+`P` and type `install`. Then start typing the name of the extension you want to install.

### General 

- [ApplySyntax](https://github.com/facelessuser/ApplySyntax) - Provides a real-time Word Count and character count in the status-bar - Better syntax detection.
- [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter) - Bracket and tag highlighter.
- [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter) - Previews color values by underlaying the selected hex codes in different styles.
- [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements/tree/st3) - Provides enhancements to the operations on Sidebar of Files and Folders.
- [SublimeCodeIntel](https://sublime.wbond.net/packages/SublimeCodeIntel) - Full-featured code intelligence and smart autocomplete engine.
- [Trimmer](https://github.com/jonlabelle/Trimmer) - A tool for cleaning up whitespace.


### HTML, CSS & JS

- [Emmet](https://sublime.wbond.net/packages/Emmet) - For lightning fast coding.
- [HTML-CSS-JS Prettify](https://github.com/victorporof/Sublime-HTMLPrettify) - HTML, CSS, JavaScript and JSON code formatter via node.js.
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3#sublimelinter3) - Coming soon. Code linting & hinting for HTML/CSS/JS.
- [Sass](https://sublime.wbond.net/packages/Sass) - Adds syntax highlighting and tab/code completion for Sass and SCSS files. Also features Emmet shortcuts for many CSS properties.


### Git
- [GitGutter](https://github.com/jisaacks/GitGutter) - Tracks line changes in the gutter.
- [Modific](https://sublime.wbond.net/packages/Modific) - Highlight lines changed since the last commit.


## Settings - User

Accessible via: `SublimeText` &rarr; `Preferences` &rarr; `Settings – User`, or with `⌘`+`,'.'

```json
    {
        "ignored_packages":
        [
            "Vintage"
        ],
        "color_scheme": "Packages/Theme - Afterglow/Afterglow-monokai.tmTheme",
        "tab_size": 2,
        "tabs_small": true,
        "theme": "Afterglow-green.sublime-theme",
        "translate_tabs_to_spaces": true,
        "default_encoding": "UTF-8",
        "detect_indentation": true
    }
```


## Key Bindings - User

Accessible via: `SublimeText` &rarr; `Preferences` &rarr; `Key Bindings – User`. 

```

```


## Sublime from the Command Line

Sublime Text includes a command line tool which you just need to symlink up so that it's in your PATH file. In Sublime Text 3 simply copy this into a terminal session:

    ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl

Then you can open files in Sublime Text from the command line with:

    subl file.txt

Replacing `file.text` with the name of the file or folder you wish to open in Sublime Text.

All this is based on a Gist (https://gist.github.com/ijy/7399688).