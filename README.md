# WebGIS_Direktvermarktung
 
<!DOCTYPE html>
<html>
<head>
 <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
   integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
   crossorigin=""/>
 <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
   integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
   crossorigin=""></script>
</head>
<body>
 <h1>TestGIS</h1>
 <p>Not a <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">Rickroll</a>.</p>
 <div id="DV" style="width: 600px; height: 400px; position: relative;"></div>
 
 <script>
var DV_WebGIS = L.map('DV').setView([48.48026129426459, 8.998832702636719]).setZoom(5);
L.tileLayer('https://{s}.tile.openstreetmap.de/tiles/osmde/{z}/{x}/{y}.png').addTo(DV_WebGIS);
var markBota = L.marker([48.48026129426459, 8.998832702636719]).addTo(DV_WebGIS);
markBota.bindPopup("<p>This is the Botanical Garden</p>");


</script>

</body>
</html>