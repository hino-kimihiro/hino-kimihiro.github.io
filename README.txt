Kimihiro Hino – homepage update package

Upload to the existing GitHub repository hino-kimihiro/hino-kimihiro.github.io:
- index.html (replace existing file)
- news.html
- _config.yml
- _data/news.yml
- assets/style.css

GitHub Pages settings: deploy from main branch, /(root). Jekyll processes the Liquid templates and generates both news lists from _data/news.yml.

To add news: prepend a new YAML entry to _data/news.yml. Include display_date, title, and optional url. Keep entries newest first. Homepage shows 3; news.html shows all.

NOTE: Not yet migrated: original Google Sites image; full publication and lecture sections.
