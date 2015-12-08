gmusic-playlist.js
===============

javascript based playlist scripts for gmusic

## prerequisites

- greasemonkey addon for your browser
 - chrome: https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en
 - firefox: https://addons.mozilla.org/en-us/firefox/addon/greasemonkey/
 - ie: ?

## importing

the script will allow songs to be imported from csv formated files. a single
file will be used for all playlists, a column in the csv file will indicate
which playlist a song belongs in. the first row of the csv file will be
reserved for headers indicating what each column in the file is.

## exporting

the script will export songs to csv formated files. a single file will be
exported for all playlists. each song will have the playlist that it belonged
to exported. the first row of the csv file will be reserved for headers
indicating what each column in the file is.

## status

development currently in progress. estimated initial release by Dec 18 2015.
TODO
- develop CSV parsing logic
- develop CSV writing logic
- develop File writing/export logic
- tie together import logic
- tie together export logic
COMPLETE
- determine correct web service calls
- encapsulate web service calls
- insert ui controls

## see also

the original python based version - https://github.com/soulfx/gmusic-playlist
