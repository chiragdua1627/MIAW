<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dbf000001dtYj',
				'Web_Chat',
				'https://merolatile--dev.sandbox.my.site.com/ESWWebChat1743413972658',
				{
					scrt2URL: 'https://merolatile--dev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://merolatile--dev.sandbox.my.site.com/ESWWebChat1743413972658/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
