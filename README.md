## [demo app](https://mddown.github.io/json/) using github and [rawgit](http://rawgit.com/) to host json data

```javascript
$.getJSON("https://cdn.rawgit.com/mddown/json/master/data.geojson", function(data) {
			var jsonData = L.geoJson(data, {
		}).addTo(map);
		});
```

###[VIEW DEMO](https://mddown.github.io/json/)
