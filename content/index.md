---
layout: base.njk
title: How are we to live?
verdict: "Evidence-based pointers on living well — each one linked to the study design, the effect size, and the honest weakness behind it."
---

# How are we to live?

<p class="lede">Evidence-based pointers on living well. If you don't care what happens next, or whether your beliefs are true, you'll not find anything useful here.</p>

<ul class="slogan-index" id="pointers">
{% for s in collections.slogans %}
  <li>
    <a href="{{ s.url }}">
      <span class="s-title">{{ s.data.slogan }}</span>
      <span class="s-clock">{{ labels.clockShort[s.data.clock] }}</span>
    </a>
  </li>
{% endfor %}
</ul>

In a hurry? [The short version](/five-things/) boils it all down to five things for each age — each one linked back to its evidence.

## How to read each page

- **Pick your age.** Each page has three tabs — 8–11, 11–16 and 16+. The facts are the same; the explanation changes.
- **Which clock it's on.** The *ten-year clock* means the next ten years of your life — the things that could affect you soon. The *seventy-year clock* means your whole life ahead, roughly the next seventy years — things that build up slowly and mostly show up much later. Some pages are on both.
- **How sure we are.** From *near-certain* down to *contested*.
- **The evidence, and its weak spot.** Each page ends with the studies behind it, described in plain words, and the honest weakness in the evidence. Stuck on a word? See [Words we use](/words/).

---

*Prepared July 2026; revised September 2026 after a reader review. See [how this was made and how to contribute](https://github.com/drcjar/living-well). Effect sizes are given with the design that generated them, and with the honest weaknesses.*
