# Pydle Changelog

## 1.5.0 (2026-11-01)
* Added a leaderboard with top 25 players based on character count for the daily puzzle. Custom games show top 50.
* Added custom games
* Added option to share creations with developer
* Added user profiles - avatar and username
* Show SVG of puzzle in Archive Dialog
* Added query search parameter to set game id
* Change Help to be FAQ
* Changed storage for games to use IndexedDB instead of Local Storage
* Switched to Lucide Icons (from Heroicons)

## 1.4.4 (2026-09-18)
* Removed changelog in How to play dialog
* Fixed issue #23 Puzzle doesn't open from Archive while in Create mode
## 1.4.3 (2026-09-18)
* Fixed Character counting bug #22
* Disable Run button while code is executing and show running indicator in console.
## 1.4.2 (2026-09-15)
* Show no-symbol icon while Python is loading / running
* Debounce counting characters and optimisations in guesses handling
## 1.4.1 (2026-09-06)
* Improved character count to not remove whitespace from strings.
## 1.4.0 (2026-09-02)
* Ability to load imported packages.
## 1.3.0 (2026-08-29)
* Added character counter
* Added word wrap and styled tabs.
* Added difficulty setting for game.
* Ability to click on cells in Create mode to draw a puzzle
* Fixed attempts start at 2 
* Fixed stats dialog showing stats in wrong category
* Save playground code.
## 1.2.9 (2026-08-07)
* Add keyboard shortcut for running code (F5)
* Fixed timezone bug when clicking next puzzle when DST changed
* Fixed timezone issue
## 1.2.8 (2026-08-02)
* Added Archive Dialog
* Ignore attempts that do not call pydle function
## 1.2.7 (2026-07-29)
* Added tooltips to cells to help aid colourblind users.
## 1.2.6 (2026-07-27)
* Added GitHub link.
* Able to continue running code after solving puzzle
## 1.2.5 (2026-07-26)
* Added documentation for the pydle function 
* Bug fix for recursion
* Added social media links at the bottom
## 1.2.4 (2026-07-25)
* Tab now indents code 
* Daily puzzle refreshes at 00:00 local time.
* Do not show character count when loading Python.
## 1.2.3 (2026-07-23)
* Show character count in console.
* Fixed bug where finishing a game didn't update character distribution
## 1.2.2 (2026-07-20)
* Refactor game logic to enforce character limits and update storage handling for guesses
* Migrated localstorage to only store latest guess
## 1.2.1 (2026-07-17)
* Fix pydle not available in functions.
* Fixed bug where code is not set to default code
## 1.1.0 (2026-07-10)
* Added copyright and key for console messages
* Improved busy icon for console
* Fixed line count bug
## 1.1.0 (2026-05-29)
* Updated how to play dialog with line length changes.
* Removed line length limit
* Changed parameters for pydle function to x, y from row, col
* Add url to copy to clipboard as well
## 1.0.1 (2026-02-27)
* Added Help Dialog with helpful links.
* Only show how to play dialog the first time someone visits the site.
* Added Stats Dialog
## 1.0.0 (2026-02-24
* Pydle released
