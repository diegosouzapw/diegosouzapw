# Community work and open-source impact

I am Diego Rodrigues de Sa e Souza, creator and maintainer of
[OmniRoute](https://github.com/diegosouzapw/OmniRoute). I work on open-source AI
infrastructure and help people use, improve, and contribute to it.

## A dated snapshot

Measured through GitHub's APIs on **October 18, 2026, at 14:06 UTC**. These are repository and
account counters, not a count of active users or a measure of software quality.
The profile's automatic badges provide more recent figures between updates to this page.

| Measure | Snapshot |
| --- | ---: |
| OmniRoute stars | 77,956 |
| Forks | 11,306 |
| Followers of my GitHub account | 2,693 |
| Watchers subscribed to the repository | 455 |
| Merged pull requests in the repository | 9,183 |
| Discussions | 544 |
| Published releases | 281 |

Sources: [repository](https://github.com/diegosouzapw/OmniRoute),
[profile](https://github.com/diegosouzapw),
[merged pull requests](https://github.com/diegosouzapw/OmniRoute/pulls?q=is%3Apr+is%3Amerged),
[Discussions](https://github.com/diegosouzapw/OmniRoute/discussions), and
[releases](https://github.com/diegosouzapw/OmniRoute/releases).
Merged pull requests include maintainer and automated work.

The project is built with hundreds of contributors. A paginated API query including
anonymous authors returned 846 records: 429 user accounts, 2 bots, and 415 anonymous
author records. This is **not** 846 verified unique people. The
[GitHub API documentation](https://docs.github.com/en/rest/repos/repos#list-repository-contributors)
explains author-email grouping, caching, and limits on linking author addresses to accounts.
The profile badge counts GitHub-linked accounts, including bots: the same-day query without
anonymous authors returned 431 accounts, including 2 bots. GitHub links only the first 500
author email addresses to accounts for this endpoint, so this account counter can change
independently of the number of people contributing. It should not be used as a complete
community headcount or a reliable measure of community growth.

## Examples of maintenance and collaboration

- **Review that leaves the contributor in control.** In October,
  [PR #16033](https://github.com/diegosouzapw/OmniRoute/pull/16033) by HouMinXi
  went through a review of shutdown behavior. My
  [review](https://github.com/diegosouzapw/OmniRoute/pull/16033#pullrequestreview-5470239224)
  explained two reproducible gaps and separated Linux boundary tests from actual macOS
  validation. HouMinXi supplied the corrections, and my
  [follow-up](https://github.com/diegosouzapw/OmniRoute/pull/16033#pullrequestreview-5472091239)
  verified the focused fixes while keeping broader CI status distinct. The changes stayed
  in the contributor's pull request and were merged on October 16.
- **Technical feedback into contributions.** In
  [Discussion #14270](https://github.com/diegosouzapw/OmniRoute/discussions/14270),
  shannonlowder brought detailed observations about quota scoring. My replies work through
  those observations and establish a path of focused issues, regression tests, and credit
  for the contributor. The usage figures in that discussion are the user's own report.
- **Repairing attribution.**
  [PR #14362](https://github.com/diegosouzapw/OmniRoute/pull/14362) records credit for
  BillyOutlast, mdigitalbh81, and ggiak after attribution was lost during merges. Recovering
  credit is part of maintaining the project, as well as acknowledging the original mistake.
- **Reusable support.**
  [Discussion #14158](https://github.com/diegosouzapw/OmniRoute/discussions/14158)
  contains guidance on the distinction between provider visibility, configured connections,
  and blocking. Public explanations help the next person with the same question.

These are specific examples, not a claim that every contribution, translation, or support
interaction has been audited. Credit belongs to the people who contributed the work.

## Learning and contributing

Start with the project's
[contribution guide](https://github.com/diegosouzapw/OmniRoute/blob/v3.8.51/CONTRIBUTING.md)
and [public Discussions](https://github.com/diegosouzapw/OmniRoute/discussions).
I also wrote a short [guide to turning feedback into a contribution](notes/turning-feedback-into-contributions.md)
based on the public examples above.

## Supporting the work

[GitHub Sponsors](https://github.com/sponsors/diegosouzapw) supports ongoing open-source
maintenance. The work includes reviewing contributions, improving documentation, investigating
reported problems, and making fixes reproducible. Current sponsorship options are listed on
that page.
