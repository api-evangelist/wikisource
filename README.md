# Wikisource

Wikisource is the Wikimedia Foundation's free library of source texts — public-domain and freely-licensed books, historical documents, legal texts, constitutions, speeches, and other transcribed primary-source works in over 70 languages.

## APIs

- **MediaWiki Action API** — `https://en.wikisource.org/w/api.php` — full read/write access via action= dispatch; JSON preferred.
- **MediaWiki Core REST API** — `https://en.wikisource.org/w/rest.php/v1` — page CRUD, search, history, transforms.
- **Wikimedia REST API v1** — `https://en.wikisource.org/api/rest_v1` — cached reads at up to 200 RPS; page summaries and HTML.

## Key Links

- Website: https://wikisource.org
- English edition: https://en.wikisource.org
- API documentation: https://www.mediawiki.org/wiki/API:Main_page
- API usage guidelines: https://foundation.wikimedia.org/wiki/Policy:Wikimedia_Foundation_API_Usage_Guidelines
- Bulk dumps: https://dumps.wikimedia.org/
- Status: https://www.wikimediastatus.net/

## Usage Requirements

All requests must include a contactable User-Agent header. Read access requires no API key. Write access requires a free OAuth 2.0 account via meta.wikimedia.org. Requests should be serial rather than parallel.

## Maintainer

Kin Lane — kin@apievangelist.com
