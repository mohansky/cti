+++
title = "Cycling in Meghalaya"
subtitle= "The Abode of Clouds"
tags = ["cycle"]
categories = ["Meghalaya"]
image = "/img/tours/meghalaya/cycling in meghalaya 1.jpg"
image1 = "/img/tours/meghalaya/living root bridge meghalaya 2.jpg"
image2 = "/img/tours/meghalaya/meghalaya landscape.jpg"
level =  "Moderate" 
season =  "October to March"
days =  " 10/ 7"
cycling = "6 to 8 hrs"
accomodation = "Hotel 11/ Camping 1 "
cost = " $ 899 "
airportin = "Guwahati"
airportOut =  "Guwahati"
draft= "false"
+++


<div class="col-sm-8 desc">
<p>
We start at Guwahati and head towards Meghalaya. Other than being one of the wettest places on earth during the monsoons Meghalaya is also the only state in India to have a matrilineal system. The state is divided into three hill ranges, namely the Khasi, Jaintia and Garo hills. The principal languages in Meghalaya are Khasi, Pnar and Garo with English as the official language of the State. On this Bicycle trip we will be riding through the west Khasi and neigbouring Jaintia hills overlooking the plains of Bangladesh. Deep forested valleys, gushing rivers, innumerable waterfalls, natural root bridges, archery competitions, village markets will be your companions through this ride. We have introduced a day of hiking so as to experience the livng root bridge trail.
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
<i class="ion-android-home"></i></div>
<div class="list-text"> 
Accomdation  </th>
<th>
<div class="itinicon">
<i class="ion-android-bicycle"></i></div>
<div class="list-text">  
Activity /Highlight </th>
</tr></thead>
<tbody>
<tr><td>Day 1</td><td>Mawphanlur</td><td>Camping/ Cottage (B)</td><td>Airport Pick up (Guwahati) and transfer by road to Mawphanlur (4hrs)</td>
<tr><td>Day 2</td><td>Mwaphlang</td><td>Farm stay (B,L,D)</td><td>Cycle 60 Km</td>
<tr><td>Day 3</td><td>Shillong</td><td>Hotel (B,L,D)</td><td>Cycle 37 km</td>
<tr><td>Day 4</td><td>Jowai</td><td>Hotel (B,L,D)</td><td>Cycle 75 Km</td>
<tr><td>Day 5</td><td>Krangshuri Falls</td><td>Camping (B,L,D)</td><td>Cycle 75 Km</td>
<tr><td>Day 6</td><td>Mawlynnong</td><td>Camping (B,L,D)</td><td>Cycle 58 km</td>
<tr><td>Day 7</td><td>Langkawet</td><td>Camping (B,L,D)</td><td>Cycle 25 km</td>
<tr><td>Day 8</td><td>Cherrapunjee</td><td>Hotel (B,L,D)</td><td>Cycle 58 km</td>
<tr><td>Day 9</td><td>Cherrapunjee</td><td>Hotel (B,L,D)</td><td>Cycle 100 km</td>
<tr><td>Day 10</td><td>Depart</td><td></td><td></td>

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
	var mymap = L.map('mapid').setView([25.8350497782928,91.7574691772461 ], 8);
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


