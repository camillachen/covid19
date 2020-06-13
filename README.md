# Washington State County Coronavirus Data

## description

This project is focused on displaying the information relating to Coronavirus
in each county in Washington. My project goal is to show the current state of
the coronavirus situation. It shows how many people have the coronavirus,
how many people recovered from it, and how many people have died from it. It
also has a disclaimer telling the audience that only 5.6% of the people in
Washington state are tested. My goal is to provide a simple and easy to read
web map that is easy to navigate without all the clutter. It will provide
information and highlight the selected county for the user's convenience.

My Data source for the county polygons geojson is from
[standardco.de](https://www.standardco.de/mapping-resources-for-coronavirus-geojson-us-county-data-etc).
My data point for the coronavirus data is from directly from google, and google
claimed they got their source from WHO (World Health Organization). I entered
the information for the coronavirus manually onto the washington states County
geojson using [geojson.io](geojson.io).


Here are the applied libraries that I used. It is only leaflet.
<pre><code>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.4.0/dist/leaflet.css"/>
<script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/chroma-js/1.3.4/chroma.min.js"></script>
</pre></code>

Here is the basemap that I used:
<pre><code>
http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png
</pre></code>
