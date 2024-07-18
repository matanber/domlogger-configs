# Note
The configurations in the official [DomLogger++ repo](https://github.com/kevin-mizu/domloggerpp) are much better than the ones provided here, you should probably use them instead.

# DomLogger Configs
This repos includes some useful configurations for the [DomLogger++ extension](https://github.com/kevin-mizu/domloggerpp) by [Kévin - Mizu](https://github.com/kevin-mizu). To import one of the configurations, navigate to the settings page of the extension, and either paste in the configuration or click on the import icon.

## List of Configurations
- [URL params](URL-params.json) - This config displays some query parameters which the target site might be using, by hooking the `URLSearchParams.prototype.get` and `URLSearchParams.prototype.has` functions.
- [Query selectors](query-selectors.json) - This config displays all of the query selectors which the target has executed, by hooking the `document.querySelector` and `document.querySelectorAll` functions. I will add support for JQuery selectors to this config in the future.
