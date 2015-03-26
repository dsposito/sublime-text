# Sublime Text Setup

My personal setup of [Sublime Text](http://www.sublimetext.com) packages and preferences.

## Packages

To install packages, first install [Package Control](https://sublime.wbond.net/installation).

Next, open the [Command Pallete](https://sublime.wbond.net/docs/usage) via cmd+shift+p (OS X) or ctrl+shift+p (Windows), type ```install``` and select ```Package Control: Install Package```

You can now search for and install the packages you want.  Here are my favorites:

* [Theme - Soda](https://github.com/buymeasoda/soda-theme)
* [Alignment](https://github.com/wbond/sublime_alignment)
* [DocBlockr](https://github.com/spadgos/sublime-jsdocs)
* [GitGutter](https://github.com/jisaacks/GitGutter)
* [PHP Syntax Checker](https://github.com/naomichi-y/php_syntax_checker)
* [Sublime-GitHub](https://github.com/bgreenlee/sublime-github)

## Package Preferences

Many packages allow you to customize their settings.  Your user Package Preferences can be found by selecting "Settings - User" under any installed package via: 
```Sublime Text -> Preferences -> Package Settings```

```javascript
{
	"alignment_space_chars"          : ["=", ":"],
	"jsdocs_spacer_between_sections" : true,
	"jsdocs_return_description"      : false,
	"jsdocs_per_section_indent"      : true,
	"jsdocs_lower_case_primitives"   : true,
	"jsdocs_extend_double_slash"     : false
}
```

## User Preferences

Open your user preferences via `cmd+,` (OS X) or `ctrl+,` (Windows).

```javascript
{
	"draw_white_space": "all",
	"ensure_newline_at_eof_on_save": true,
	"find_selected_text": true,
	"font_size": 14.0,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages": ["Vintage"],
	"rulers": [100],
	"show_full_path": true,
	"spell_check": true,
	"theme": "Soda Dark.sublime-theme",
	"trim_automatic_white_space": false
}
```

### User Key Bindings
```javascript
[
    // For Sublime-GitHub package.
    { "keys": ["super+shift+g"], "command": "copy_remote_url" }
]
```
