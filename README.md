# DUMPIT

Find RV dump stations near you — or along your route.

A single-page mobile-friendly web app. Station data comes live from
OpenStreetMap (tag `amenity=waste_disposal`) via the Overpass API.
Routing uses the public OSRM demo server. Fit reports and rig length
are stored on the phone only (localStorage) for now.

Camper features per station: a Navigate button opens turn-by-turn
directions in the phone's maps app; fee and potable-water info can be
reported by the camper and are shown with the report date; phone and
website from OpenStreetMap are shown as tap-to-call / link when present.
