---
hide: navigation
---

# ajquery-xxx

[Download :material-download:](https://github.com/regorxxx/ajquery-xxx){ .md-button }

## Overview

[foo_httpcontrol](https://bitbucket.org/oblikoamorale/foo_httpcontrol/wiki/Home) template for [foobar2000](https://www.foobar2000.org) developed to be used in modern desktop or mobile browsers with responsive design; fully compatible with [Playlist-Tools-SMP](../../scripts/playlist-tools-smp) and [Playlist-Manager-SMP](../../scripts/playlist-manager-smp).

![ajquery-xxx](../images/aj.gif)

### Features
- Dynamic themes: Dark, light or dynamic colors based on album art palette similar to [Georgia-ReBORN](https://github.com/TT-ReBORN/Georgia-ReBORN).
- Full playback controls: smart play/pause, stop, prev/next, random.
- Extended controls: sort playlist, queue, etc.
- Library browser: by path.
- Query browser: by configured tags.
- Artwork support: front cover or disc animation.
- Console logging: able to read a txt file on server (for ex. the console log).
- Contextual menus: on selected items by right clicking.
- Run commands: able to run any contextual menu by name.
- Rating: displayed on playlist and full tagging support.
- Playlist Tools: Full integration with SMP script; all tools and menus, output and DSP selection.
- Playlist Manager: Full integration with SMP script; browse, load, lock, create, ... playlist files.

!!! note
	To use this plugin at its best, [foo_run_main](https://marc2k3.github.io/run-main/) is required. It's used to run dynamic contextual menus.

![image](../images/aj_1.png)

### Comparison to old ajquery
- Full and tested responsive design.
- Tile, artist, album tags are cut at display to soft-force one track per row.
- General tweaks to UI placement, space usage, fonts (larger) and many QOL changes.
- Contextual menus.
- Rating is now shown on the playlist list for every item (stars).
- Themes: dark/light and dynamic colors. (new themes may be easily added editing the html)
- Default 20 items per page.
- Artwork: non-playing and non-artwork found images are now animations.
- Extended controls reworked: rating and Custom contextual menu Buttons.
- Playlist Tools: Spider Monkey Menus, Output Devide & DSP selection.
- Playlist manager: Browse playlist files and load them on demand.
- Integration with Spider Monkey Panel.
- Dynamic icons, menus, tooltips and component checking via SMP.
- Toggleable log panel (usually used to display console log from foobar).
- Query browser filtering.
- Builtin documentation.
- Fixes to bugs on previous versions.
- Updated to modern web-standards.

![image](../images/aj_2.png)

!!! question
	Compatible with (SMP menus):  
    - [Playlist Tools](../../scripts/playlist-tools-smp): Offers different pre-defefined examples for 
	intelligent playlist creation.  
	- [Playlist Manager](../../scripts/playlist-manager-smp): Integrates Listenbrainz's feedback and recommendations.  
	Compatible with (buttons):  
	- [foo_quicksearch](https://www.foobar2000.org/components/view/foo_quicksearch): Buttons to search for title, artist and genre queries.  
	- [foo_youtube](https://fy.3dyd.com/home/): Buttons to search for acoustic versions, collaborations, tracks by artist, etc.  