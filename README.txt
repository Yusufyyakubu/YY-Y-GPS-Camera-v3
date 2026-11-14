YY&Y GPS Camera v3 — map and GeoJSON update

DEPLOY
Upload the CONTENTS of this folder to the repository root, replacing previous files.
Settings > Pages > Deploy from a branch > main > /(root) > Save.
Open the HTTPS Pages site and allow camera and location. Reload online once for updates.
Keep the same Pages address to retain access to existing browser-local records.
Do not clear site data unless you have exported records/photos first.

FEATURES
Camera, stamped JPEGs, IndexedDB records and CSV retained.
Map tab: OpenStreetMap, or Google Maps with your own Maps Embed API key.
Current GPS or one selected saved record can be shown. Refresh recentres the map.
Map panels are embedded provider maps, not a combined multi-marker GIS layer.
Maps need internet; no offline tile downloading is implemented.
GeoJSON: Records > GeoJSON; WGS84 Point coordinates are longitude, latitude.
Photo filenames are properties; photos are NOT embedded. Download JPEGs separately.
Create your own tags with + Add tag; remove tags without deleting existing records.
New captures also receive UUID identifiers, collision-resistant filenames and UTC timestamps.
Existing records are retained without rewriting their original metadata.

GOOGLE SETUP
Enable Maps Embed API in Google Cloud. Create a browser API key.
Restrict it to Maps Embed API and your exact GitHub Pages website/referrer pattern.
In Map > Google Maps setup paste and save the key. Browser keys are visible to users;
restrictions are essential. Google Cloud account/setup requirements apply.
Without a key, the Google external-map link is still available.
No API key has been supplied or bundled.

PRIVACY AND STORAGE
Maps send selected coordinates to the chosen provider only when the Map view is used.
Records/photos remain local to this browser. Export backups regularly.
Tags and map key are stored locally. No cloud sync or accounts added.
Camera/offline capture remain dependent on browser permissions and device support.

VERIFICATION
Source updated and structural checks performed; no physical-device, field GPS,
live Google API or full browser-runtime testing has been performed for this release.
Test online/offline capture, tag persistence and exports before operational use.

Documentation:
https://developers.google.com/maps/documentation/embed/embedding-map
https://wiki.openstreetmap.org/wiki/Export
