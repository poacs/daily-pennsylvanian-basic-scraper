## Contents of the `robots.txt` file on 02/24/25
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /

## Explanation

- User-agent: \* indicates that all web crawlers are allowed to crawl the website.
- Crawl-delay: 10 specifies that automated crawlers should wait at least 10 seconds between requests, but since this only does the front page once per day, it should be fine.
- Allow: / confirms that all general paths on the site are permitted for crawlers under `User-agent: *`.
- These rules are all met!