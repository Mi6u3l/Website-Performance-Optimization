<h1>Website Performance Optimization portfolio project</h1>

<p>Optimize the critical rendering path of an exisiting online portfolio for Pagespeed Insights score above 90 by applying the techniques in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).</p>

<p>Open index.html from the webrowser to start the application.</p>


<h2>Following techniques are used to optimize the website:</h2>
<ul>
	<li>Add async tag to js source to avoid render blocking</li>
	<li>Use <a href="https://github.com/typekit/webfontloader">Web Font Loader</a> to load fonts</li>
	<li>Inline CSS to <a href="https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery">optimize CSS delivery</a></li>
	<li>Two major issues are fixed in the views/js/main.js to achieve 60 frames per second</li>
	<li>Optimize views/js/main.js calls to the DOM by replacing querySelector/querySelectorAll with getElementById/getElementsByClassName</li>
	<li>CSS files are minified as no changes are made to the original files</li>
	<li>Load CSS files dynamically using JavaScript</li>
</ul>