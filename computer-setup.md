

# macOS setup

## Editors
### [Sublime Text](https://www.sublimetext.com/)

#### Preferences
Sublime Text --» Settings --» Settings
```json
{
    "bold_folder_labels": true,
    "color_scheme": "Packages/Agila Theme/Agila Oceanic Next.tmTheme",
    "draw_indent_guides": true,
    "draw_white_space": "all",
    "ensure_newline_at_eof_on_save": true,
    "folder_exclude_patterns":
    [
        ".git",
        ".vscode",
        "__pycache__"
    ],
    "font_face": "Fira Code",
    "font_size": 12,
    "ignored_packages":
    [
        "Vintage",
    ],
    "indent_guide_options":
    [
        "draw_normal",
        "draw_active"
    ],
    "line_padding_bottom": 0,
    "line_padding_top": 0,
    "overlay_scroll_bars": "disabled",
    "rulers":
    [
        88
    ],
    "show_rel_path": true,
    "theme": "Adaptive.sublime-theme",
    "theme_find_panel_size_xs": true,
    "theme_scrollbar_rounded": true,
    "theme_scrollbar_semi_overlayed": true,
    "theme_sidebar_font_sm": true,
    "theme_sidebar_heading_bold": true,
    "theme_sidebar_indent_top_level_disabled": true,
    "theme_sidebar_size_xxs": true,
    "theme_tab_font_sm": true,
    "theme_tab_selected_label_bold": true,
    "theme_tab_selected_underlined": true,
    "theme_tab_size_sm": true,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": false,
}
```
#### Packages
* [A File Icon](https://github.com/SublimeText/AFileIcon)
* [BracketHighlighter](https://facelessuser.github.io/BracketHighlighter/)
* [GitGutter](https://github.com/jisaacks/GitGutter)
* [Indent XML](https://github.com/alek-sys/sublimetext_indentxml)
* [Package Control](https://packagecontrol.io/)
* [Pretty JSON](https://github.com/dzhibas/SublimePrettyJson)
* [SqlBeautifier](https://github.com/zsong/SqlBeautifier) -- Ok, but not great.
* [sublack](https://github.com/jgirardet/sublack)
* [SublimeLinter](https://www.sublimelinter.com/en/stable/)
* [SublimeLinter-flake8](https://github.com/SublimeLinter/SublimeLinter-flake8)
* [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces)

#### Syntax
* [Dockerfile Syntax Highlighting](https://github.com/asbjornenge/Docker.tmbundle)
* [Dotfiles Syntax Highlighting](https://github.com/mattbanks/dotfiles-syntax-highlighting-st2)
* [ini](https://github.com/jwortmann/ini-syntax)
* [requirements.txt](https://github.com/wuub/requirementstxt)

### Theme
* Settings --» Select Theme
* Choose "Adaptive (Theme Default)"

#### Color Themes
* Settings --» Select Color Theme
* Choose "Agila Oceanic Next (Agile Theme)"

* [Agila](https://github.com/arvi/Agila-Theme)
* [Oceanic](https://github.com/memco/Oceanic-tmTheme)
* [Okami](https://github.com/Rayraegah/okami)

### [Nova](https://nova.app/)

## Git
* [Tower](https://www.git-tower.com/mac) -- Long-time licensed user.
* [Fork](https://git-fork.com/) -- My new daily driver.
* [Sublime Merge](https://www.sublimemerge.com/) -- Used mostly right right-click context menu support in Sublime Text.

## Database
* [TablePlus](https://tableplus.com/) -- My favorite
* [Postico](https://eggerapps.at/postico2/) -- Solid features

## Browser
* Safari
* [Firefox](https://www.mozilla.org/en-US/firefox/new/?redirect_source=getfirefox-com)
  * Extension: [1Password](https://1password.com/)
  * Extension: [AdBlocker Ultimate](https://adblockultimate.net/)
  * Extension: [Fake Filler](https://fakefiller.com/)

## Security
* [1Password](https://1password.com/) -- For everything

## Notetaking
### [UpNote](https://getupnote.com/)
Replacement for Evernote after 15 years of a paying membership.

* Settings --> General
  * Show number of notes in each notebook ☑️
  * Sort items in sidebar: Custom
  * Display note timestamp: Created time
  * Show nested notebooks in notes list ☑️
  * Auto lock: NEVER
* Settings --> Editor
  * Font: System
  * Font size: 14
  * Wrap code ☑️
  * Format Markdown automatically ☑️
  * Type `/` to show menu ☑️
  * Default image size: Medium
  * New notes start with: H1
  * Line length: 40%
  * Line spacing: 20%
  * Paragraph spacing: 0%
* Settings --> Backup
  * Frequency: Daily
  * Maximum number of backups: 100
  * Maximum number of version history: 50
  * Backup attachments ☑️
  * Export backup file to Markdown ☑️

## Transfers
### [Transmit](https://panic.com/transmit/)
The gold standard.

## Diagrams
* [yEd](https://www.yworks.com/products/yed)

## Terminal
* [iTerm](https://iterm2.com/) -- Been using this forever, like most of us?
  * [Putting it all together](https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49)
    * Shell: [Oh My Zsh](https://ohmyz.sh/)
    * Theme: [Snazzy](https://github.com/sindresorhus/iterm2-snazzy)
    * Zsh Plugin Manager: [zplug](https://github.com/zplug/zplug): `brew install zplug`
  * Preferences
    * General --» Window
      * ☑️ Native full screen windows
      * ☑️ Separate window title per tab
    * Appearance --» General
      * Theme: Minimal
      * Tab bar location: Top
      * Status bar location: Bottom
    * Appearance --> Windows
      * ☑️ Show line under title bar when tab bar is not visible
    * Appearance --> Tabs
      * ☑️ Show tab bar even when there is only one tab
      * ☑️ Tabs have close buttons
      * ☑️ Show activity indicator
      * ☑️ Show new-output indicator
      * ☑️ Show tab bar in fullscreen
    * Appearance --> Panes
      * ☑️ Separate background images per pane
      * Side margins: 5
      * Top and bottom margins: 2
    * Appearance --> Dimming
      * Dimming amount: 15

* [Warp](https://www.warp.dev/) -- New player on the scene, quite a few fun tricks.

## Utilities
* [Homebrew](https://brew.sh/) -- MacOs package manager
* [DaisyDisk](https://daisydiskapp.com/)
* [iStatMenus](https://bjango.com/mac/istatmenus/)
  * CPU & GPU
  * Network
  * Battery/Power
  * Time
* [SpeedTest](https://www.speedtest.net/apps)
* [Vivid](https://www.getvivid.app/) -- Good for unlocking the full brightness of the MacBook Pro display, especially when working outdoors
* [Dropbox](https://www.dropbox.com)
* [Magnet](https://magnet.crowdcafe.com) -- For easy window positioning



