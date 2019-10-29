### GeoJSON
https://geojson.org/
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [125.6, 10.1]
  },
  "properties": {
    "name": "Dinagat Islands"
  }
}

### Cycling data in Berlin
https://lab.technologiestiftung-berlin.de/projects/datadive-cycling/en/
Assessing open bike sharing data in Berlin
https://lab.technologiestiftung-berlin.de/projects/bike-sharing/en/


### STRAVA
Access-Token:
ACCESS_TOKEN

curl -H "Authorization: Bearer ACCESS_TOKEN" "https://www.strava.com/api/v3/athlete/activities” 

### Meta-Projekt BikeSharing
https://github.com/ubahnverleih/WoBike 

### Nextbike
Für Berlin: https://api.nextbike.net/maps/nextbike-live.json?city=362
Aber nur Live-Standortdaten

### Flinkster
Consumer-Key: CONSUMER_KEY
Consumer-Secret: CONSUMER_SECRET
Zugangstoken: ACCESS_TOKEN

curl -H "Authorization: Bearer ACCESS_TOKEN” https://api.deutschebahn.com/flinkster-api-ng/v1/bookingproposals?lat=48.15&lon=11.5&radius=5000&limit=100&providernetwork=2

### Uber
https://www.npmjs.com/package/movement-data-toolkit

$ mdt speeds-to-geojson berlin 2019-03-01 2019-06-30 > uber_2019-03-06.geojson

https://movement.uber.com/explore/berlin/speeds/query?lat.=52.519171&lng.=13.3884101&z.=13&lang=en-US&dt[tpb]=ALL_DAY&dt[wd;]=1,2,3,4,5,6,7&dt[dr][sd]=2019-06-01&dt[dr][ed]=2019-06-30&ff=


### Bing Maps
API-Key: API_KEY
http://dev.virtualearth.net/REST/v1/Traffic/Incidents/37,-105,45,-94?key=API_KEY

bbox parameter set
0    47.27577590942383
1    5.865616798400879
2    55.06619644165039
3    15.039889335632324
name    "Germany"

#### Api-Call für Live-Störungen - Date format hat drei Nachkommastellen
https://dev.virtualearth.net/REST/v1/Traffic/Incidents/52.308479,12.974854,52.716331,13.908691?key=API_KEY

