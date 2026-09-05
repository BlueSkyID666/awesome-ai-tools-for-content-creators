# Repository and pattern review

What was looked at before building this list, and what was taken from it. No editorial
content, description, category wording, or dataset was copied from any of these sources.

## Reviewed

| Source | What it is | What it was useful for |
|---|---|---|
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) — `awesome.md` | The Awesome list quality requirements | Entry format, table-of-contents expectation, licensing guidance, badge rules |
| [GitHub Docs — community profiles](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories) | Platform documentation | The community health file set GitHub actually checks for |
| [GitHub Docs — syntax for issue forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms) | Platform documentation | Required keys and element types for `.github/ISSUE_TEMPLATE/*.yml` |
| Established curated lists in this subject area | Community lists with substantial history | Structural patterns that hold up at scale, and the failure modes that do not |

Two decisions are specific to this repository.

**Voice cloning is listed, with the consent requirement stated before the category rather than
inside it.** Leaving those tools out was considered. It would have made the list less useful and
no safer: a creator dubbing their own back catalogue is the ordinary case, and they would have
found the products anyway. What the repository does instead is put the consent rule in the
methodology, where a reader meets it before the entries, and refuse the products whose purpose
is impersonation rather than production.

**Nothing is ranked on output quality, and that will read as a gap.** A list of image and music
generators invites a verdict on which produces the better result. That verdict is taste, it
differs by channel and by audience, and it changes with every model update. What the
descriptions say instead is what each product does differently, which is the part that stays
true long enough to be worth writing down.

## What was adopted

**One entry format, without exception.** Every entry takes the same shape:

```text
- **[Name](https://example.com/)** — What it does, in one sentence. `Freemium` `Web`
```

Deviation is what makes a list unscannable and unparseable, and it costs more than it appears
to.

**A contents block that maps one-to-one onto the headings.** Every `##` section appears in
it, every anchor resolves, and the block fits on one screen.

**Per-entry metadata from a closed vocabulary.** Pricing and platform labels mean the same
thing here as in every other TiorAI repository, so they can be relied on rather than read.

**An explicit review date.** Most lists in this space carry no freshness signal at all, so a
reader cannot distinguish a list reviewed last week from one abandoned two years ago.

**A written selection policy.** What qualifies, what does not, how entries are ordered, and a
plain statement that there is no paid placement, sponsorship, or affiliate link.

## What was deliberately not adopted

**Size as a selling point.** Several lists in this space advertise their entry count. A list
nobody can finish reading has not curated anything, and the counts are usually inflated by
dead links nobody has checked.

**Year-branded naming.** `awesome-<topic>-2026` reads as current for a few months and as
abandoned forever afterwards.

**The Awesome badge.** It signifies acceptance into the official Awesome index. This
repository has not been submitted, so displaying it would be a false claim.

**Deep hierarchy.** No `###` subcategories inside the list body. That is the point at which
these lists stop being navigable.

**Emoji as meaning.** Decorative only at best, and inaccessible at worst.
