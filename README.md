# Punk Society Site

Public landing site for the Punk Society movement and its Cognify standards work.  
This repo powers `www.punk-society.org` on GitHub Pages.

## Purpose
- Share the manifesto (`manifesto.html` for public viewing, `manifesto.md` as source) and campaign context around mapping cognitive friction and the Cognitive Revolution.
- Explain how Punk Society (culture) and Cognify (framework) work together.
- Provide immediate calls-to-action for stories, funding, and partnerships.
- Offer a public intake path using GitHub Issues until the standalone form launches.
- Host in-progress research shells (`neurodiversity.html`, `stories.html`) so collaborators know what’s coming.

## Local Development
This is a static site—open `index.html` in a browser or serve the folder locally:

```bash
npx serve .
```

## Contributing
1. Update copy by editing `index.html`.
2. Adjust styling in `styles.css`.
3. Story submissions land as GitHub issues via `.github/ISSUE_TEMPLATE/story.yml`.
4. Open a PR and include screenshots for major visual changes.

## Story Intake (Temporary)
Until the automated intake form is online, contributors can:
- Use the “Share your story” issue template in this repo.
- Include anonymised details only; no personal identifiers.
- Mention preferred follow-up channels inside the issue body.

## Working TODOs
- Populate the neurodiversity field guide with official research once it lands in the `punk-society` repo.
- Import the first anonymised story set into `stories.html` and link to their GitHub intake IDs.
- Replace the GitHub Issue stopgap with the n8n intake form when ready.
- Add analytics/meta tags once the content stabilises.

## Related Repos
- `punk-society` — private strategy + manifesto source of truth.
- `nd-audit-network-site` — legacy story form host (being phased out).

Questions? Open an issue. This site is intentionally lightweight so we can iterate fast.
