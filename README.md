# Canasta Tech Docs

Canasta Tech Docs is a package of wiki pages (templates, forms and categories) that provide a structure for creating and displaying technical documentation. It is meant to be installed via the MediaWiki extension [Page Exchange](https://www.mediawiki.org/wiki/Extension:Page_Exchange).

Though it includes "Canasta" in its name, Canasta PM does not require the [Canasta](https://canasta.wiki/) MediaWiki bundle to be used. Nevertheless, all the extensions that Canasta PM requires (including [MintyDocs](https://www.mediawiki.org/wiki/Extension:MintyDocs), [Page Forms](https://www.mediawiki.org/wiki/Extension:Page_Forms) and [Cargo](https://www.mediawiki.org/wiki/Extension:Cargo)) are included in Canasta.

To make use of this package within your wiki, add the following lines to LocalSettings.php, below the inclusion of Page Exchange:

```php
$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/CanastaWiki/CanastaTechDocs/main/page-exchange.json';
$wgRestrictDisplayTitle = false;
```
