# Public learning site

This directory is the complete publication allowlist for the public RIA compliance learning site.

- `learning.json` controls the current module, next listening item, and public module sequence.
- `index.html` renders the mobile-friendly public page.
- Do not place prospect, customer, schedule, activity, or private operating information here.

Publish from the private operations repository with:

```bash
scripts/publish-learning.sh
```

The script uses `git subtree split`, so this directory becomes the root of the separate
public `lihtness/ria-compliance-learning` repository. No other repository content is published.
