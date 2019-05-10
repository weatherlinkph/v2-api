---
title: API Reference Swagger
permalink: /api-reference-swagger
classes: wide
sidebar:
  nav: "navMain"
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/swagger-ui/3.22.1/swagger-ui.css">

<script src="https://cdnjs.cloudflare.com/ajax/libs/swagger-ui/3.22.1/swagger-ui-bundle.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/swagger-ui/3.22.1/swagger-ui-standalone-preset.js"></script>


<div id="api-ref"></div>
<script>
var ui = SwaggerUIBundle({
	dom_id: '#api-ref',
	url: "https://weatherlink.github.io/v2-api/_pages/v2-api-swagger.json",
	presets: [
		SwaggerUIBundle.presets.apis,
		SwaggerUIBundle.SwaggerUIStandalonePreset
	],
	layout: "BaseLayout"
});
</script>
