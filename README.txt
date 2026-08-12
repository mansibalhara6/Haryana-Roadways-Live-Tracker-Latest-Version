HARYANA SMART TRANSIT — MANSI BALHARA

Run:
1. Put all files in one folder.
2. For best results use a local server:
   python -m http.server 8000
3. Open http://localhost:8000/

Features:
- Real interactive Leaflet/OpenStreetMap map
- Browser geolocation ("My Location")
- Real road-route drawing through OSRM when online
- 12 demo bus markers with ETA/speed/status
- Official Haryana Roadways timetable
- Official bus-stand enquiry directory
- Favorites/local storage
- Passenger journey planner
- Driver device GPS permission/watch
- Admin fleet view
- PWA install support

IMPORTANT:
Actual official Haryana Roadways live bus positions are NOT exposed by a public API that was verified for this build. Therefore bus markers are explicitly demo/simulated. Do not present them as government live GPS. A production deployment needs an authorized GPS/API feed or your own driver-device backend.


NEW  FEATURE — BUSES NEAR ME
- Uses browser/device geolocation.
- User can choose a 2/5/10/25/50 km radius.
- Calculates distance from the user to available bus positions.
- Sorts nearest buses first.
- Shows route, status, speed and ETA.
- Centers the real Leaflet map on the selected nearby bus.
- The current prototype's bus positions are demo/origin-city positions; they must be replaced by authorized live GPS coordinates for true live proximity.
