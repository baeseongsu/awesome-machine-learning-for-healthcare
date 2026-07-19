# Contributing

Thank you for helping maintain this curated bibliography. Keep additions
focused on machine learning research with a clear healthcare application and
follow the curation rules below.

## Paper year

Assign a paper to the year of its earliest verifiable public research version,
such as its first arXiv submission, conference proceedings publication, or
online journal publication. A later venue publication does not move the paper
to a new year group.

When the earliest year is unclear, use the earliest date shown by a canonical
paper page or bibliographic record. Do not infer a year from an identifier
alone. Keep the canonical venue and its publication year in the citation.

## Year groups

The README uses a rolling three-year window. For calendar year `Y`, show
separate groups for `Y - 2`, `Y - 1`, and `Y`, and consolidate all earlier
papers under `Through Y - 3`. Omit groups that contain no papers.

For 2026, use:

```text
**Through 2023**
**2024**
**2025**
**2026**
```

At the first maintenance update in a new calendar year, advance the window. In
2027, merge the 2024 group into `Through 2024` and retain separate groups for
2025, 2026, and 2027.

## Entry format

Place each paper under the most specific relevant topic and use the existing
README format:

```text
- [Paper title](canonical-paper-url) | Venue, year | [Code](repository-url)
```

The code link is optional. Preserve the order of existing entries unless a
separate curation change explicitly calls for reordering.
