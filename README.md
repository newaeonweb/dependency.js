<h1>Dependecy.js</h1>

Version: 2013.03.01

=======================================================================

Small lib to load JavaScript files async and sync, very lightweight and easy to use. Also works for CSS files.


-----------------------------------------------------------------------

<h1>Depend</h1>

<ul>
	<li>jQuery 1.9 (But works fine with all versions)</li>
</ul>


------------------------------------------------------------------------
<h1>How to use :</h1>

<script src="jQuery-latest"></script>
<script src="dependency.min.js"></script>

$(window).load(function(){
	$('head').dependency({
	    loadDependency: [
	        {urlPath:"http://localhost:28289/js/date.js", scriptType:"text/javascript", async: true},
	        {urlPath:"http://localhost:28289/js/daterangepicker.js", scriptType:"text/javascript"},
	        {urlPath:"http://localhost:28289/css/style.css", scriptType:"text/css",}
	    ]
	});
});
-----------------------------------------------------------------------

<h1>More infos:</h1>

Developer: feiochc@gmail.com
Twitter: <a href="https://twitter.com/@newaeonweb">@newaeonweb</a>
Google Plus: <a href="https://plus.google.com/102311871192373469721/posts">Fernando Monteiro</a>