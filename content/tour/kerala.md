+++
title = "Kerala"
subtitle= "Cycling to Gods own country"
tags = ["cycle"]
categories = ["Kerala"]
image = "/img/tours/kerala/cycling in kerala 2.jpg"
image1 = "/img/tours/kerala/tee plantations kerala.jpg"
image2 = "/img/tours/kerala/chinese fishing nets kochi.jpg"
level =  "Tough" 
season =  "October to March"
days =  "14 / 10"
cycling = "6 to 8 hrs"
accomodation = "Hotel 10/ Houseboat 1 "
cost = " $ 2499 "
airportin = "Bangalore"
airportOut =  "Kochi"
draft= "false"
+++


<div class="col-sm-8 desc">
<p>
This cycling holiday starts with a transfer to Mysore.The historic settlement of Mysore is one of South India's most enchanting cities.Explore its glittering royal heritage and magnificent monuments and buildings. We continue our ride through one of the greenest coastal belts of the Indian peninsula and the parallel running Western Ghats mountain range.En- route we will ride through the back water region of Kuttanad,known as the rice bowl of Kerala.The Kuttanad region resembles a gigantic rural representation of Venice with waterways playing a central role in transportation.It's close proximity to the rich spice growing hills became one of the central reasons for the early explorations of a sea route to India,a voyage first completed by the Portuguese explorer Vasco da Gama in the year 1498. This cycle tour takes us south along the coast to the cliff side vacation town of Varkala.
</div>
<div class = "col-sm-3 high">
<h4>Highlights</h4>
<li> Mysore Palace Visit
<li> Overnight Houseboat cruise
<li> Experience the hill country and the tea plantations in Munnar
<li>Experience traditional art forms and dance programs in Kerala
<li> Nature Walks & spice plantation visits
 
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
<h4 class="modal-title">Day</h4>
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
Place </th>
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
<tr><td> 1</td><td>Bangalore </td><td>Hotel Escape </td><td>Arrival</td>
<tr><td> 2</td><td>Mysore</td><td>Regaalis </td><td>Mysore Palace, Local market visits</td>
<tr><td> 3</td><td>Mudumalai</td><td>Jungle Hut </td><td>Cycling, Wildlife Jeep Safari (Optional)</td>
<tr><td> 4</td><td>Ooty</td><td>Taj Savoy </td><td></td>
<tr><td> 5</td><td>Pollachi</td><td>Coco Lagoon </td><td>Toy Train Ride</td>
<tr><td> 6</td><td>Munnar</td><td>Kaivalyam Retreat </td><td></td>
<tr><td> 7</td><td>Munnar</td><td>Kaivalyam Retreat </td><td>Tea Museum Visit</td>
<tr><td> 8</td><td>Periyar</td><td>Wildernest </td><td>Spice plantation visit</td>
<tr><td> 9</td><td>Periyar</td><td>Wildernest </td><td>Free </td>
<tr><td> 10</td><td>Kuttikanam</td><td>Misty Mountain </td><td></td>
<tr><td> 11</td><td>Alleppey</td><td>Houseboat </td><td></td>
<tr><td> 12</td><td>Ezhupunna</td><td>Villa De Parrai </td><td></td>
<tr><td> 13</td><td>Fort Kochi</td><td>Fort House </td><td>City Sightseeing</td>
<tr><td> 14</td><td>Depart</td><td></td><td></td>
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
	var mymap = L.map('mapid').setView([8.49039061631656, 77.24418640136719], 6);
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
L.marker([12.325328074276468, 76.64886474609375], {icon: cycleIcon}).addTo(mymap);
var geojson = {
	"type": "FeatureCollection",
	"features": [
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.65274, 13.200549]
			},
			"properties": {
				"name": "Airport - Bengaluru",
				"type": "Generic",
				"ele": "930.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.61041259765624, 12.314594747056262]
			},
			"properties": {
				"name": "TOUR START - MYSORE",
				"type": "Generic",
				"ele": "770.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.24418640136719, 11.762860714331467]
			},
			"properties": {
				"name": "GEREMALAM",
				"type": "Generic",
				"ele": "1009.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.01141357421875, 10.655209552534227]
			},
			"properties": {
				"name": "POLLACHI",
				"type": "Generic",
				"ele": "287.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.06085205078125, 10.078389257351695]
			},
			"properties": {
				"name": "MUNNAR",
				"type": "Generic",
				"ele": "1453.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.16041564941406, 9.728683999359466]
			},
			"properties": {
				"name": "VANDANMEDU",
				"type": "Generic",
				"ele": "1086.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [77.165222, 9.600073]
			},
			"properties": {
				"name": "PERIYAR",
				"type": "Generic",
				"ele": "881.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.902924, 9.687398]
			},
			"properties": {
				"name": "VAGAMON",
				"type": "Generic",
				"ele": "942.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.302795, 9.623768]
			},
			"properties": {
				"name": "MARARI",
				"type": "Generic",
				"ele": "14.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.3494873046875, 9.499180522706906]
			},
			"properties": {
				"name": "ALLEPPY",
				"type": "Generic",
				"ele": "6.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.4044189453125, 9.272911497538322]
			},
			"properties": {
				"name": "THIRUKUNNAPUZHA",
				"type": "Generic",
				"ele": "10.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.70928955078125, 8.729005290108992]
			},
			"properties": {
				"name": "TOUR END - VARKALA",
				"type": "Generic",
				"ele": "40.0"
			}
		},
				{
			"type": "Feature",
			"geometry": {
				"type": "Point",
				"coordinates": [76.92146301269531, 8.49039061631656]
			},
			"properties": {
				"name": "Airport Out - Trivandrum",
				"type": "Generic",
				"ele": "14.0"
			}
		},
		{
			"type": "Feature",
			"geometry": {
				"type": "MultiLineString",
				"coordinates": [[[77.6799488, 13.1978774, 901.0], [76.6532421, 12.3085177, 747.0], [77.229638, 11.7646266, 1093.0], [77.0133018, 10.6596853, 291.0], [77.059822, 10.0839771, 1493.0], [77.1594285, 9.7301446, 1088.0], [77.1649646, 9.60638032, 883.0], [76.9025802, 9.68960877, 912.0], [76.2996196, 9.62753644, 11.0], [76.3507533, 9.50008062, 6.0], [76.4011573, 9.27672867, 9.0], [76.7099761, 8.73479533, 36.0], [76.9191455, 8.48158582, 4.0]]],
				"bbox": [77.6799488, 13.1978774, 76.2996196, 8.48158582]
			},
			"properties": {
				"name": "Karnataka to Kerala - website",
				"src": "https://www.gpsies.com/map.do?fileId=ezsyehciorlrkkxj",
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

</div></div>

