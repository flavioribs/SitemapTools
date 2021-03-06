# sitemap-dotnet

Provides parsing and querying support for sitemaps.

## Key features
- Parses both XML sitemaps and [sitemap index files](http://www.sitemaps.org/protocol.html#index)
- Handles GZ-compressed XML sitemaps

## Notes
- Does not enforce sitemap standards [as described at sitemaps.org](http://www.sitemaps.org/protocol.html)
- Does not validate the sitemaps
- Does not support TXT sitemaps
- Does not support RSS sitemaps

## Planned features
- Use "Robots.txt" to identify potential sitemaps
- Support other sitemap file formats (TXT, RSS)