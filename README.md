# sublime-text-3-settings
### Settings and package details for Python and Django development with Sublime Text 3

The following settings provide a number of benefits-
- PEP8 autoformatting
- Word wrapping to PEP8 standard of max line length of 79 characters
- autosave
- tab size to 4 to assist with PEP8 standards

### Packages Installed
The following packages are minimum required for Django development.
```
Djaneiro
GitGutter
Anaconda
```

### Settings

Preferences > Settings
```
{
	"detect_indentation": false,
	"font_size": 15,
	"hot_exit": false,
	"ignored_packages":
	[
		"Vintage"
	],
	"remember_open_files": false,
	"tab_size": 4,
	"translate_tabs_to_spaces": true,
	"word_wrap": true,
	"save_on_focus_lost": true
}
```

Preferences > Settings - Syntax Specific
```
{
 "pep8_max_line_length": 79,
}
```
