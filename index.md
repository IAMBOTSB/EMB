<html>

<body>
   <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHu00000B48m6',
				'TestGit',
				'https://ca1729828676966.my.site.com/ESWTestGit1734703121882',
				{
					scrt2URL: 'https://ca1729828676966.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ca1729828676966.my.site.com/ESWTestGit1734703121882/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>

</html>
