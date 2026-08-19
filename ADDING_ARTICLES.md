# Adding a new article

The website is the canonical index; each card points to the original publication on WeChat, LinkedIn, or another channel.

1. Open `index.html` and find `<section class="writing" id="writing">`.
2. Duplicate the existing `.article-card` link.
3. Update the original URL, accessible label, source, publication date, title, summary, and topic tags.
4. Pick one real result or idea from the article for the `.article-signal` panel. Avoid a generic statistic.
5. Keep newest articles first, test English and Chinese modes, then push to the Pages publishing branch.

GitHub Pages republishes the site when the publishing source is updated. This manual index is intentionally reliable: WeChat does not expose a stable public feed for arbitrary accounts, and LinkedIn publishing APIs require restricted access. A GitHub Actions importer can be added later for any channel that provides an authenticated API or RSS feed.
