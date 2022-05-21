# Leaflet.ColorIconAT
Leaflet plugin for create colored icons for AT

## Using the plugin
````xml
<script src="L.colorIcon.js"></script>
````

| Property        | Description              | Default Value | Possible  values                                     |
| --------------- | ------------------------ | ------------- | ---------------------------------------------------- |
| iconSize        | Name of the icon         | [25, 25]      | Size of the icon                                     |
| iconUrl         | Url of the icon          | ''            | Your image |
| color           | Color of the icon        | '#000000'     | Color to hex value (#ff0000) or rgb value (rgb(255, 0, 0)) |
| shadowUrl       | Url of the shadow        | ''            | Your shadow image |
| alertIconUrl    | Url of the gif animation | ''            | Your gif animation  |
| shadowSize      | Size of the shadow       | [25, 25]      | Size of the shadow  |
| shadowAnchor    | Anchor of the shadow     | [25, 25]      | Anchor of the shadow |

Example : 
````xml
let iconAvion = L.colorIcon({
      iconSize : [25, 25],
      popupAnchor : [-15, -20],
      iconUrl: "img/avion.svg",
	  shadowUrl:"img/marker-shadow.png",
	  alertIconUrl: "img/alert_2.gif",
	  iconSize : [25, 25],
	  shadowSize: [41, 41],
	  shadowAnchor: [-13,-29],
      color: "#4169E1",
    });
````
## Credits
Leaflet.ColorIconAT is a fork of - https://github.com/shevekk/Leaflet.ColorIcon

## License
Leaflet.ColorIcon is licensed under the MIT License - http://opensource.org/licenses/mit-license.html.