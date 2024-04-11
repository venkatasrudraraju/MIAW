<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHu000002h6nh',
				'SDO_Messaging_for_Web',
				'https://vrudraraju-231129-714-demo.my.site.com/ESWSDOMessagingforWeb1701328418202',
				{
					scrt2URL: 'https://vrudraraju-231129-714-demo.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://vrudraraju-231129-714-demo.my.site.com/ESWSDOMessagingforWeb1701328418202/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>

