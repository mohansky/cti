+++
title = "Cycling in Arunachal Pradesh"
subtitle= "The Dawnlit Mountains"
tags = ["cycle"]
categories = ["Arunachal"]
image = "/img/tours/arunachal/arunachal cycling 1.jpg"
image1 = "/img/tours/arunachal/mishmi hills camp.jpg"
image2 = "/img/tours/arunachal/arunachal cycling 2.jpg"
level =  "Difficult" 
season =  "October to March"
days =  "13 / 10"
cycling = "6 to 8 hrs"
accomodation = "Hotel 5/ Camping 7 "
cost = " $ 2400 "
airportin = "Dibrugarh"
airportOut =  "Dibrugarh"
draft= "false"
+++


<div class="col-sm-8 desc">
<p>
The Eastern Arunachal ride takes us from the Brahmaputra valley of upper Assam to the Acheso Valley of Arunachal Pradesh, which is where the road ends (If there were a road we will end up in China). In between the start and the end, one will traverse across varied landscape, terrain, road conditions and the all important tribes of this region. From the Oil and Tea growing regions of Assam, the tropical forests of Namdapha and Kamlang to the cane and grasslands of the Acheso valley, everyday is a revelation. Interestingly during the entire ride you will cross territories of the Chakma, Singpho, Khamti, Miju Mishmi, Digaru Mishmi and finally the Idu Mishmi tribes.
</div>

<div class = "col-sm-3 high">
<h4>Highlights</h4>
<li> Cycling through the far flung villages of Northeast India
<li> Nature walk Namdapha National Park 
<li> Off the grid home stays 
<li> Discover the Animist and Theravada Buddhist tribes
<li> Tea Plantations, River Valleys, Remote Villages

 

<br><br>
<button type="button" class="btn btn-main" data-toggle="modal" data-target="#dayModal" style="width: 100%; padding: 0px 0px 0px -40px;">
Day to day</button></div>

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
<tr><td>Day 1</td><td>Inthong Village</td><td>Eco Lodge (B)</td><td>Airport Pick up (Dibrugarh) and transfer by road to Inthong Village (4hrs)</td>
<tr><td>Day 2</td><td>Miao</td><td>Lodge (B,L,D)</td><td>Cycle 75 Km</td>
<tr><td>Day 3</td><td>Deban</td><td>Camping (B,L,D)</td><td>Cycle 35 Km</td>
<tr><td>Day 4</td><td>Wakro </td><td>Camping (B,L,D)</td><td>Cycle 50 Km</td>
<tr><td>Day 5</td><td>Tezu </td><td>Camping (B,L,D)</td><td>Cycle 65 km</td>
<tr><td>Day 6</td><td>Roing </td><td>Camping (B,L,D)</td><td>Cycle 67 km</td>
<tr><td>Day 7</td><td>47 Kilo</td><td>Camping (B,L,D)</td><td>Cycle 45 km</td>
<tr><td>Day 8</td><td>Ithun</td><td>Camping (B,L,D)</td><td>Cycle 60 km</td>
<tr><td>Day 9</td><td>Aloya</td><td>Camping (B,L,D)</td><td>Cycle 60 km</td>
<tr><td>Day 10</td><td>Agui</td><td>Camping (B,L,D)</td><td>Cycle 65 km</td>
<tr><td>Day 11</td><td>Acheso</td><td>Camping (B,L,D)</td><td>Cycle 40 km</td>
<tr><td>Day 12</td><td>Roing</td><td>Eco Lodge (B,L,D)</td><td>Transfer</td>
<tr><td>Day 13</td><td>Depart</td><td></td><td></td>

</tr>
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

<div id="mapid" style="width: 100%; height: 400px;"></div>
<script>
	var mymap = L.map('mapid').setView([28.1090315221500, 95.9498764038086], 8);
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
				"coordinates": [95.01852035522461, 27.481928309895576]
			},
			"properties": {
				"name": "Dibrugarh Airport",
				"type": "Generic",
				"ele": "115.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.40939331054688, 27.27080437821597]
			},
			"properties": {
				"name": "TIPAM FAKEY VILLAGE",
				"type": "Generic",
				"ele": "128.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.82344055175781, 27.429680289871587]
			},
			"properties": {
				"name": "INTHONG VILLAGE",
				"type": "Generic",
				"ele": "151.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [96.20658874511719, 27.484517217871932]
			},
			"properties": {
				"name": "MIAO",
				"type": "Generic",
				"ele": "279.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [96.345291, 27.633657]
			},
			"properties": {
				"name": "DEBAN",
				"type": "Generic",
				"ele": "1225.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [96.35215759277344, 27.778341612236325]
			},
			"properties": {
				"name": "WAKRO",
				"type": "Generic",
				"ele": "450.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [96.16384506225586, 27.923895597121078]
			},
			"properties": {
				"name": "WP 7",
				"type": "Generic",
				"ele": "220.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [96.16341590881348, 27.924390909369155]
			},
			"properties": {
				"name": "TEZU",
				"type": "Generic",
				"ele": "221.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.84232330322266, 28.134669178920163]
			},
			"properties": {
				"name": "ROING",
				"type": "Generic",
				"ele": "369.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.91167449951172, 28.232414812316087]
			},
			"properties": {
				"name": "47 KILO",
				"type": "Generic",
				"ele": "2419.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.82653045654297, 28.436996771113794]
			},
			"properties": {
				"name": "ITHUN",
				"type": "Generic",
				"ele": "1151.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.8498764038086, 28.462353152215343]
			},
			"properties": {
				"name": "173 KM",
				"type": "Generic",
				"ele": "908.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.85090637207031, 28.598388697125415]
			},
			"properties": {
				"name": "AMBOLI",
				"type": "Generic",
				"ele": "949.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [95.97355842590332, 28.934441831427485]
			},
			"properties": {
				"name": "ACHESO",
				"type": "Generic",
				"ele": "1729.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "MultiLineString",
				"coordinates": [[[95.0167608, 27.485375, 112.0], [95.4093289, 27.2723784, 123.0], [95.8218955, 27.432199, 165.0], [96.2083053, 27.4877247, 269.0], [96.3456344, 27.6350353, 1235.0], [96.3502693, 27.7808523, 443.0], [96.163845, 27.9247345, 222.0], [95.8416366, 28.1357382, 372.0], [95.911889, 28.2330398, 2453.0], [95.8267021, 28.4379826, 1282.0], [95.850048, 28.4624333, 920.0], [95.8498764, 28.5991517, 832.0], [95.9739875, 28.9347023, 1735.0], [95.849018, 28.4473409, 774.0], [95.8421516, 28.1317219, 359.0], [95.0187778, 27.4825779, 112.0]]],
				"bbox": [96.3502693, 28.9347023, 95.0167608, 27.2723784]
			},
			"properties": {
				"name": "Arunachal - website",
				"src": "https://www.gpsies.com/map.do?fileId=sndmxvmhsokbsvgo",
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
