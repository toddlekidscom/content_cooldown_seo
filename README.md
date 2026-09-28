# content_cooldown_seo

The live `sitemap.xml` and `llms.txt` for [toddlekids.com](https://toddlekids.com).

These files are generated. The `SEO refresh` job in the site's repository rebuilds
them from WordPress every six hours and pushes here only when something changed.
toddlekids.com serves them at `/sitemap.xml` and `/llms.txt`.

Keeping them here rather than in the site's repository means a content change
never triggers a site deploy. **Do not connect this repository to Vercel**, and
do not edit the files by hand — the next run would overwrite them.
