# osn2osm
Python script for transform OpenStreetMap notes dump file **\*.osn** to **\*.osm** file format.
This script improves https://github.com/tbicr/osn2osm as a expand to distinguish between open and closed statuses in OSM-Notes. 

## Setting
You can output open and closed OSM-Notes by switching the parse_notes() setting.

    notes = parse_notes(stdin)
    notes = parse_notes_without_closed(stdin)

## Usage
    wget -qO- http://planet.openstreetmap.org/notes/planet-notes-latest.osn.bz2 | bzcat | python osn2osm.py > output_with_close.osm

## About OSM-Notes
* Info - http://wiki.openstreetmap.org/wiki/Notes.
* Dumps - http://planet.openstreetmap.org/notes/.

## Visualize map examples
* Overview about Open/Closed OSM Notes (Neis Ones’ Result Maps) - http://resultmaps.neis-one.org/osm-notes
* Notes Review - https://ent8r.github.io/NotesReview/
* DE: Notes Map v2.5. - https://greymiche.lima-city.de/osm_notes/ 

## References
