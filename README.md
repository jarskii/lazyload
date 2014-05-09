Plugin for lazy loading images. 

See <a href="http://epic-zhara.ru/demo/lazyload">Demo</a>.

Working with all elements - if IMG add path in src attribute, for div's add background-image.

Connect Lazyload.js before closed body tag:

		<script type="text/javascript" src="lazystyle.js"></script>
		 
Add styles for blaze up:

		<style type="text/css">
			.lazy {
					opacity: 0;
		
					-webkit-transition: opacity .5s ease;
					-moz-transition: opacity .5s ease;
					-o-transition: opacity .5s ease;
					transition: opacity .5s ease;
		    }
		
				.lazy-show {
				    opacity: 1;
				}
		</style>

Fire: 
	<script type="text/javascript">	
		Lazyload.start()
	</script>
