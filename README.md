# Spot the Misleading Chart

Six charts built from real numbers, each drawn to mislead. Students pick what’s wrong with each one, then see the same data drawn honestly next to it. The page ends with a checklist for reading any chart. By Gwen Sharp, as a companion to Chapter 2 (Research Methods) of *A Sociology Experiment*.

**Live site:** https://gsharpokie.github.io/misleadingcharts/

## The six tricks

1. **Cut-off axis:** life expectancy, 2023 vs. 2024.
2. **Cherry-picked time window:** violent victimization, 2020–2022 only.
3. **Size that exaggerates:** wealth shares drawn as circles scaled by width.
4. **Uneven spacing and skipped years:** four hand-picked years of Gallup’s crime question.
5. **Upside-down axis:** violent victimization with zero at the top.
6. **Groups that aren’t comparable:** cancer death rates in 1900 and 2024, ignoring how much longer people live.

Every misleading chart is in a dashed frame labeled “Misleading on purpose,” so a screenshot can’t be mistaken for a real chart.

## For instructors

- To go straight to the checklist, add `#checklist` to the link: https://gsharpokie.github.io/misleadingcharts/#checklist
- Chart 6 is drawn correctly and still misleads, which makes a good discussion of why honest charts need context.
- Nothing a student selects is saved or sent anywhere.

## Data

All figures were checked against their sources in November 2026:

- National Center for Health Statistics: “Mortality in the United States, 2024” (life expectancy 78.4 and 79.0; cancer deaths) and “Leading Causes of Death, 1900–1998.” The 2024 cancer rate (182.3 per 100,000) is deaths divided by population.
- Bureau of Justice Statistics, *Criminal Victimization, 2024*, appendix table 1.
- Gallup annual Crime survey, 1989–2025.
- Federal Reserve, Distributional Financial Accounts, 2026:Q2.

## Editing

Each chart is one entry in `const CHARTS = [` in the `<script>` section of `index.html`: `head` (the misleading headline), `opts` (the answer choices), `a` (which choice is right, counting from 0), and `why` (the explanation). The data series are at the top of the script.

## Turning on the site (one time)

Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and select **Save**. Keep Issues turned on so the “Suggest a correction” link works.

## Author

Created by Gwen Sharp ([@gsharpokie](https://x.com/gsharpokie)).

## License

© 2026 Gwen Sharp. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): you may share and adapt it for noncommercial purposes with credit. See [LICENSE](LICENSE). The figures belong to their sources; this license covers the page’s design, text, and code.
