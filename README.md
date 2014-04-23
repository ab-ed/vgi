<h1>VGI</h1>
=====

A project by <a href="http://edmontonpipelines.org/">Edmonton Pipelines</a>and the <a href="http://kcvs.ca/rivervalleyatlas/">King's University College River Valley Atlas project.</a>

<p>Edmonton's river valley has a long history of occupation and use. From aboriginal settlements that date back 8000 years, to more recent colonisation and the build up of Edmonton and Edmonton's parks systems. Humans have interacted with the river valley by a variety means during this long span of time. Furthermore, people living today, in Edmonton and other places, have memories and stories that capture this history of use. These stories may be specific to one location and time, or may span multiple locations through time. There is a lot that is unknown.</p>

<p>To that end, Edmonton Pipelines and the King's University College are partering to build a mapping interface that can record these stories through a participatory and collaborative mapping platform. The University College London's Extreme Citizen Science Research Group has a good introduction to an <a href="https://docs.google.com/document/d/1vWdzei4JgD0oQwe9HYE2XvalWjRZT5pZUEE5vLisKV4/edit#heading=h.c1an28gqz5ae">Open Infrastructure for Participatory and Collaborative Mapping.</a></p>
<p>Our project will be comprised of the following components:
<ol>
<li>Is open and available on GitHub;</li>
<li>Supports user contributions of point, line, and polygon;</li>
<li>Allows the user to label and describe their geometry;</li>
<li>Saves the geometry and metadata in a database;</li>
<li>Supports the moderation of contributions.</li>
</ol></p>

<p>Our current stact concept includes:
<ol>
<li><a href="http://cartodb.com/">CartoDB</a>: As the DB where contributions will be written and stored for moderation via SQL.I also like the <a href="https://github.com/CartoDB/cartodb-publishing-templates">CartoDB SidePanel Template.</a></li>
<li><a href="https://www.mapbox.com/"> MapBox</a>: To provide a custom (cartocss) base-map.</li>
<li><a href="http://leafletjs.com/">LeafLet</a>: As the user interface and to provide the <a href="https://github.com/Leaflet/Leaflet.draw">LeafLetDraw Plugin</a> as well as the pan, zoom and layer control.</li>
<li>HTML/CSS: Basic web functionality, look and feel.</li>
<li>Javascript: To power the map, LeafLet plugins and custom windows associated with the VGI contributions.</li>
<li>SQL: CartoDB describes <a href="http://blog.cartodb.com/post/53510434258/read-and-write-to-cartodb-with-the-leaflet-draw-plugin"> here</a> how they use SQL to link the LeafLetDraw plugin to a table.
</ol>
</p>

<p>
	Other project components include:

	
	<ul>
	<li>The geostack that I envision is stack_concept.png</li>
	<li>The splash page will inlcude a disclaimer that indicates a user is about to contribute potentially provate data to a (see wireframe_splash.png).</li>
	<li>The main page posses the zoom, drawing and layer control tools (see wireframe_main.png).</li>
	<li>When the user selects a drawing tool, they must also provide a title and description of that tool prior to saving whatever spatial element that they contribute (see wireframe_add_polygon.png).</li>

</p>





<p>
	More to come.
	
	![ScreenShot] (https://raw.github.com//mattdance/vgi_project/master/stack_concept.png)
</p>
