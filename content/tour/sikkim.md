+++
title = "Cycling in Sikkim"
subtitle= "The Monastic Trail"
tags = ["cycle"]
categories = ["Sikkim"]
image = "/img/tours/sikkim/cyling in sikkim 1.jpg"
image1 = "/img/tours/sikkim/cyling in sikkim 2.jpg"
image2 = "/img/tours/sikkim/toy train sikkim.jpg"
level =  "Tough" 
season =  "October to March"
days =  "12 / 10"
cycling = "6 to 8 hrs"
accomodation = "Hotel 11/ Camping 0 "
cost = " $ 1199 "
airportin = "Bagdogra"
airportOut =  "Bagdogra"
draft= "false"
+++


<div class="col-sm-8 desc">
<p>
The Himalayan state of Sikkim is landlocked by the Tibetan landmass on the North, Nepal in the West, Bhutan in the East and the Indian mainland in the south. This bicycle ride, starting from Gangtok and ending at Darjeeling takes us through typical Sikkemese countryside with phenomenal panoramic views of the Eastern Himalayas including Mt. Kanchenjunga. While cycling in Sikkim you will stay amidst tea estates, sub-alpine villages and quaint little towns whilst interacting with the Lepcha, Nepali and the Bhutia people who call this state their home.
</div>

<div class = "col-sm-3 high">
<h4>Highlights</h4>
<li> Discover distant sub alpine villages
<li> Unsurpassing views of the Mt. Kanchenjunga
<li> Cycle to some of the important monasteries in Sikkim
<li> Stay in resorts and home stays set a midst the stepped countryside


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

<tr><td>Day 1</td><td>Gangtok</td><td>Hotel (D)</td><td>Transfer 124km</td>
<tr><td>Day 2</td><td>Rumtek </td><td>Hotel (B, L, D)</td><td> Cycle 30 Km</td>
<tr><td>Day 3</td><td>Temi </td><td>Hotel (B, L, D)</td><td> Cycle 55 Km</td>
<tr><td>Day 4</td><td>Yuksom </td><td>Hotel (B, L, D)</td><td> Cycle 75 Km</td>
<tr><td>Day 5</td><td>Pelling </td><td>Hotel (B, L, D)</td><td> Cycle 60 Km</td>
<tr><td>Day 6</td><td>Rinchenpong</td><td> Homestay (B, L, D)</td><td> Cycle 40 Km</td>
<tr><td>Day 7</td><td>Okhrey</td><td> Homestay (B, L, D)</td><td> Cycle 52 Km</td>
<tr><td>Day 8</td><td>Okhrey (Hillay – Barsay visit)</td><td> Homestay (B, L, D)</td><td> Cycle 20 Km</td>
<tr><td>Day 9</td><td>Darjeeling</td><td>Hotel (B, L, D)</td><td> Cycle 40 Km</td>
<tr><td>Day 10</td><td>Darjeeling (Local)</td><td> Hotel (B)</td><td> Cycle 45 Km</td>
<tr><td>Day 11</td><td>Siliguri</td><td> Homestay (B)</td><td> Cycle 70 Km</td>
<tr><td>Day 12</td><td>Depart</td><td></td><td></td>

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


<br><br>

<div id="mapid" style="width: 100%; height: 400px;"></div>
<script>
	var mymap = L.map('mapid').setView([27.015617915, 88.2134910583496], 9);
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
				"coordinates": [88.6134910583496, 27.330986181693344]
			},
			"properties": {
				"name": "GANGTOK",
				"type": "Generic",
				"ele": "1641.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.56109142303467, 27.28638684872434]
			},
			"properties": {
				"name": "RUMTEK",
				"type": "Generic",
				"ele": "1620.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.42796802520752, 27.238396382546334]
			},
			"properties": {
				"name": "TEMI",
				"type": "Generic",
				"ele": "1337.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.216288, 27.369072]
			},
			"properties": {
				"name": "YUKSOM",
				"type": "Generic",
				"ele": "1774.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.2351279258728, 27.300602024188137]
			},
			"properties": {
				"name": "PELLING",
				"type": "Generic",
				"ele": "1936.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.26900959014893, 27.242211962678944]
			},
			"properties": {
				"name": "RINCHENPONG",
				"type": "Generic",
				"ele": "1584.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.10301303863525, 27.1411313064203]
			},
			"properties": {
				"name": "OKHREY",
				"type": "Generic",
				"ele": "2057.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.2621431350708, 27.03713052159677]
			},
			"properties": {
				"name": "DARJEELING",
				"type": "Generic",
				"ele": "2075.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [88.43000650405884, 26.71561791508631]
			},
			"properties": {
				"name": "SILIGURI",
				"type": "Generic",
				"ele": "128.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "MultiLineString",
				"coordinates": [[[88.3208084, 26.6825979, 126.0], [88.6170959, 27.3309432, 1692.0], [88.5615634, 27.2857968, 1617.0], [88.42785, 27.2389916, 1335.0], [88.2169532, 27.3691042, 1770.0], [88.2354497, 27.3009553, 1931.0], [88.2698678, 27.2421356, 1602.0], [88.101747, 27.1411975, 2052.0], [88.2633018, 27.0368856, 2108.0], [88.4308433, 26.7162552, 127.0], [88.3237266, 26.6834366, 127.0]]],
				"bbox": [88.6170959, 27.3691042, 88.101747, 26.6825979]
			},
			"properties": {
				"name": "Sikkim - website",
				"src": "https://www.gpsies.com/map.do?fileId=lyzhohcdrcsmvcqj",
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
