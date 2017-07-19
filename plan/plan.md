
# Map Event
	- data structure (B-Tree)
	- on Map Request Event
		- feed window into B-Tree
		- reparent window
	- Geometry of Windows

# IPC 
	- IPC for communication with Ruwm
	- seperate create/package/logic
	- communicate with eventual RuwmBar
	- UNIX Sockets

# Key Configuration
	- i3like configuration
	- Config file parser
	Future: 
		- put files in system dirs '/usr/share/????' && '/home/$USER/.config/ruwm/config'

# EWMH Compliance (ICCCM Compliance?)
	- Gotta read through the rest of that spec x.X

# Triage
	- Map them windows
	- Map Windows, default keybinding map, start on config file

## Learning
	- WTF is XKB and how do i use it
	- managing window properties
	- Fonts and X, htf do i use them
	- HiDPI fonts and X
	- X Touch Support

## Learned
	- WTF is an Atom
	- grab_key
	- Substructure Redirection

### Links:
https://specifications.freedesktop.org/wm-spec/wm-spec-1.3.html
https://www.x.org/wiki/guide/concepts/#index12h4
https://tronche.com/gui/x/icccm/

### Docs
http://rtbo.github.io/rust-xcb/xcb/
https://xcb.freedesktop.org/XcbApi/

### Libraries
https://github.com/rtbo/rust-xcb


