Changelog
---------

2026-10-14
----------
wha-linux.sh (renamed from wha-linux-0.2.10.4.sh):

- support WiiM Home 0.2.10.5 (0.2.10.4 still supported)
- add --allow-untested to try installers not yet listed as tested
- Fedora prerequisites in README and error messages
- .desktop file now uses the wiim launcher instead of a fixed build path
- KDE theme and system window frame only on KDE; elsewhere the app keeps its own title bar and hides the menu bar to avoid douple decorations. 

README:

- Fedora package list
- how to handle new installer versions
- install step for the launcher (the app creates its desktop entry itself)
- desktop integration on KDE and GNOME
- note that only the desktop app's music services are available (no YouTube Music, Spotify, ...)

2024-10-07
----------
wha-linux-0.2.10.4.sh : 

- allow to disable debug messages
- quit python when gui is closed
- version with Plasma decoration to match kde desktop
- .desktop file and launcher

The original script from Malfman is wha-linux-0.2.10.4.sh.orig.
