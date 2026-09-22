# Website analytics

Dashboard: https://vityavitalich.goatcounter.com/ (login required).

The published HTML on `gh-pages` contains the pageview script and click attributes. The older `master` branch is not the current website source; rebuilding it would replace newer content and analytics changes.

Click events cover navigation, paper links, BibTeX and abstract buttons, PDF links, social profiles, contact links, and other outbound content links. Theme-credit links are excluded.

Event names contain the source page, category, and destination or action, for example:

- `home-social-github`
- `cv-download-cv`
- `publications-paper-minder-2026-spp-arxiv`
- `home-paper-minder-2026-spp-bibtex`

To track a new link or button, add `data-goatcounter-click="page-category-action"`, a readable `data-goatcounter-title`, and `data-goatcounter-no-session="1"`. GoatCounter binds these elements automatically. Repeated clicks are counted; identical destinations on the same page can share an event name.

These events count clicks, not completed downloads, sent emails, or visits to the destination. Click tracking starts when this change is deployed. Verification clicks are included in the dashboard.

Reference: https://www.goatcounter.com/help/events
