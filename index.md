<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DSG00000H3xmX',
				'ESD',
				'https://omni-sdb6-asa.test1.my.pc-rnd.site.com/ESWESD1730706178015',
				{
					scrt2URL: 'https://omni-sdb6-asa.test1.my.pc-rnd.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://omni-sdb6-asa.test1.my.pc-rnd.site.com/ESWESD1730706178015/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
