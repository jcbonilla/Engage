# Engage resources

The existing Engage take-home kit remains at the site root.

## Enrollify podcast analytics

Staff hub: https://jcbonilla.github.io/Engage/enrollify/

- [Q3 episode explorer](https://jcbonilla.github.io/Engage/enrollify/episode-explorer/): eight show timelines, all 80 Q3 episodes, download comparisons against each show's Q3 mean, and CSV downloads.
- [YTD and Q3 report](https://jcbonilla.github.io/Engage/enrollify/ytd-q3/): quarterly and show comparisons, content hypotheses, adjustable proposed Q4 targets, episode filters, and scenario exports.

### Data and interpretation

Source: Enrollify Q1–Q3 2026 episode export supplied for this analysis. The 279 episodes span January 1 through September 30, 2026. Lifetime downloads were captured October 21, 2026. Publication ages differ, so quarterly comparisons do not measure equal-window growth. Content patterns are descriptive hypotheses. Q4 goals are proposed, not approved commitments. Metric owners are podcast creators.

### Hosting and updates

GitHub Pages publishes the main branch at the repository root. All tool files are static in `enrollify/`, with locally bundled Plotly. No build, backend, API keys, or login is required. The site and included CSV/JSON data are public. Browser controls do not save changes to shared data.

To update the analysis, replace each report and its matching data exports together, retain relative links, verify chart/filter/target interactions, and push to main. Updating a CSV alone does not update calculations embedded in the HTML. Keep the snapshot date consistent across reports and source exports.
