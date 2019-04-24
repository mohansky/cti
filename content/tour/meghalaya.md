+++
title = "Meghalaya"
subtitle= "Cycling in the Abode of Clouds 16 days"
tags = ["cycle"]
categories = ["Meghalaya"]
image = "/img/tours/meghalaya/cycling in meghalaya 1.jpg"
image1 = "/img/tours/meghalaya/living root bridge meghalaya 2.jpg"
image2 = "/img/tours/meghalaya/meghalaya landscape.jpg"
level =  "Medium" 
season =  "October to March"
days =  " 7/ 5"
cycling = "6 to 8 hrs"
accomodation = "Homestay 6/ Camping 0 "
cost = " $ 899 "
airportin = "Guwahati"
airportOut =  "Guwahati"
draft= "false"
+++


<div class="col-sm-8 desc">
<p>
Lying between the Brahmaputra valley in the north and flooded plains of Bangladesh in the South, is one of the wettest places on earth, Meghalaya. The place that records some of the highest average rainfall is the only state in India to have a matrilineal system. The Meghalaya Cycling tour takes us through the Khasi hills and Jaintia hills.Along the way are picturesque valleys, crystal clear streams and waterfalls, living root bridges and natural swimming pools.The route winding through hilly roads overlooking the plains of Bangladesh are generally in excellent condition. The spectacular views that await you at every turn,the pleasant weather,the lip-smacking Khasi cuisine,and the friendly people makes this a perfect holiday for outdoor lovers.
</div>

<div class = "col-sm-3 high">
<h4>Highlights</h4>
<li> Cycling in the wettest place on Earth
<li> Visit the Living root bridges
<li> Sacred groves and village markets
<li> Bathe in the natural swimming pools
<li> Stay at off the grid farms, family run home stays and village guest houses

<br><br>
<button type="button" class="btn btn-main" data-toggle="modal" data-target="#dayModal" style="width: 100%; padding: 0px 0px 0px -40px;">
Day to day</button> </div>

<!-- Modal -->
<div id="dayModal" class="modal fade" role="dialog">
<div class="modal-dialog">
<!-- Modal content-->
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal">&times;</button>
<h4 class="modal-title">Day to day</h4>
</div>
<div class="modal-body">
<div class="col-sm-3 table">
<table >
<thead>
<tr>
<th> 
<div class="itinicon">
<i class="ion-android-calendar"></i></div>
<div class="list-text"> 
Day   
</th>
<th>
<div class="itinicon">
<i class="ion-android-locate"></i></div>
<div class="list-text">  
Place   </th>
<th>
<div class="itinicon">
<i class="ion-android-bicycle"></i></div>
<div class="list-text">  
Activity /Highlight </th>
</tr></thead>
<tbody>
<tr><td> 1</td><td>Shillong </td><td>Transfer</td></tr>
<tr><td> 2</td><td>Jowai </td><td>Cycle 55km</td></tr>
<tr><td> 3</td><td>Dawki</td><td>Cycle 62km</td></tr>
<tr><td> 4</td><td>Mawlynnong </td><td>Cycle 30km</td></tr>
<tr><td> 5</td><td>Langkawat</td><td> Cycle 35km</td></tr>
<tr><td> 6</td><td>Cherrapunjee </td><td>Cycle 60km</td></tr>
<tr><td> 7</td><td>Cherrapunjee </td><td>Optional Hike/ cycle/ Vehicle</td></tr>
<tr><td> 8</td><td>Guwahati </td><td>Transfer/ Depart</td></tr>
</tbody>
</table></div>
</div>
<div class="modal-footer">
<button type="button" class="btn btn-main" data-dismiss="modal">Close</button>
</div>
</div>
</div>
</div>
</div>
</div>
</div>

<br><br>

 
<div id="mapid" style="width: 100%; height: 400px;"> </div>

<script>
	var mymap = L.map('mapid').setView([25.45350497782928,91.7574691772461 ], 9);
	L.tileLayer('https://tile.thunderforest.com/cycle/{z}/{x}/{y}.png?apikey=10771ad162c94f459d234529910e1de0', {
	attribution: '&copy; <a href="http://www.thunderforest.com/">Thunderforest</a>, &copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>',
	apikey: '<your apikey>', 
    maxZoom: 22,
		id: 'mapbox.streets'
	}).addTo(mymap);
	var cycleIcon = L.icon({
    iconUrl: '/img/cycle.svg',
    iconSize:     [20, 20], // size of the icon
    iconAnchor:   [1, 2], // point of the icon which will correspond to marker's location
    popupAnchor:  [5, 5] // point from which the popup should open relative to the iconAnchor
});
L.marker([25.45350497782928,91.7574691772461], {icon: cycleIcon}).addTo(mymap);
var geojson = {
	"type": "FeatureCollection",
	"features": [
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [91.7574691772461, 25.45350497782928]
			},
			"properties": {
				"name": "MAWPHLANG",
				"type": "Generic",
				"ele": "1847.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [91.72828674316406, 25.28195426595429]
			},
			"properties": {
				"name": "CHERRAPUNJI",
				"type": "Generic",
				"ele": "1386.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [91.67215347290039, 25.24997490761319]
			},
			"properties": {
				"name": "NONGRIAT",
				"type": "Generic",
				"ele": "370.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [92.02088356018066, 25.185721516388714]
			},
			"properties": {
				"name": "DAWKI",
				"type": "Generic",
				"ele": "42.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "MultiLineString",
				"coordinates": [[[91.879692, 25.5748175, 1483.0], [91.757555, 25.4546311, 1836.0], [91.728115, 25.2826576, 1390.0], [91.672368, 25.250927, 369.0], [91.7280292, 25.2819542, 1379.0], [92.0223426, 25.1860734, 52.0], [91.7475128, 26.1841132, 58.0]]],
				"bbox": [92.0223426, 26.1841132, 91.672368, 25.1860734]
			},
			"properties": {
				"name": "SHILLONG",
				"src": "https://www.gpsies.com/map.do?fileId=ozsqnfcxkswhlpha",
				"desc": "Generated by GPSies.com https://www.gpsies.com/"
			}
		}
	]
}
L.geoJSON(geojson, {
	style : function(feature) {
		return{
			color: '#000'
		}
	},
	pointToLayer: function (geoJsonPoint, latlong) {
		return L.marker(latlong, {
			icon: cycleIcon
		})
		},
	onEachFeature: function(feature, layer){
		if(feature.geometry.type==='Point'){
			layer.bindPopup(feature.properties.name);
		}
	}	
}).addTo(mymap);  
// Disable mousewheel zoom
	mymap.scrollWheelZoom.disable();
</script>

</div>


