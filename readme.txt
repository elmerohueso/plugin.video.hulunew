::CREDIT::
All icons and fanart created by SamHill from XBMC forums

v4.0.0 - fixed SWFPlayer used for edgecast

v3.9.9 - added premiered, year, additional genres and studio to tvshow.nfo on add subscriptions to library - note you need to delete old tvshow.nfo as it won't overwrite

v3.9.8 - fixed an error in common.py related to logging an error

v3.9.7 - default ads on

V3.9.6 - tidy-up unused files

Version 3.9.5 is derived from Bluecop's original plugin and has no new functionality other than fixes for Frodo compatibility
Version 3.9.5 Changes made to support Frodo:

- fixed most if something: to if something is not None:
- fixed date format issues
- move the "cache" folder from pluginpath to user profile - using pluginpath on some linux systems will write fail
- added edgecast CDN recognition
- tried to fix fanart and art to carry through dir views properly - still some work to do
- fixed errors with search and subscriptions
- modified most prints to log - turn on debug flag to send data to xbmc.log
- added writing a tvshow.nfo for library export so that the XBMC library updates correctly
- various addon.xml changes

Version 3.9.6 - tidy up unused files

