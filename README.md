<h1>HULK</h1>

<em>"PUNY HUMANS"</em>

<h2>Overview</h2>

JavaScript Application Architecture based on "mediator" pattern.

<h4>Backend</h4>

<ul>
  <li>NodeJS + Express
	<li>Templates w/Jade
	<li>LESS
</ul>

<h4>Client</h4>
<ul>
	<li>headJS
	<li>jQuery
	<li>HULK Boiler Plate
	<li>HULK JS Controllers
	<li>UI Widgets from Bootstrap
</uL>

<h3>JavaScript Code Based on</h3>
Concepts from Nicholas C. Zakas's, <a href="https://twitter.com/slicknet">@slicknet</a> presentation on "Scalable JavaScript Application Architecture".
<a href="http://youtu.be/mKouqShWI4o">Watch Presentation</a>

Syntax originally from Tutsplus.com 

<!-- API modules to consider making:
twitter
gmaps
dropbox -->
<h4>Flow</h4>
Base > Core > Sandbox > Module
<pre>//TODO ad a service layer that works between Sandbox and Modules.</pre>

TODO List
<pre>
//TODO Select JS templating service and create grunt build file.
//TODO Create a client data-attr service for hiding and show DOM elements. Refer to events.js for this.
//TODO create settings to flag dev, prod, etc
//TODO App core should handle all errors.
</pre>

<!-- API modules to consider making:
twitter
gmaps
dropbox -->


<h2>Documentation</h2>
<h3>Making Modules</h3>
Modules never speak to other directly modules, routing though sandbox required.
