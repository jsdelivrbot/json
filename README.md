## demo app using github and [rawgit](http://rawgit.com/) to host json data

```javascript
$.getJSON("https://cdn.rawgit.com/mddown/json/master/data.geojson", function(data) {
			var jsonData = L.geoJson(data, {
		}).addTo(map);
		});
```

###[DEMO](https://mddown.github.io/json/)
