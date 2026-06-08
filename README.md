# Machina Scientifica

> **A Unified Framework for the Classification of Mind**
> Across Biological, Synthetic, and Emergent Substrates

*"The mind is not what the brain does. The brain is what the mind grows."* — M.R.K.

![Single File](https://img.shields.io/badge/build-single--file-c9a24b)
![No Dependencies](https://img.shields.io/badge/dependencies-none-1c2c47)
![No Tracking](https://img.shields.io/badge/tracking-none-1c2c47)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-c9a24b)
![Imprint](https://img.shields.io/badge/Luminosity·e-MMXXVI-c9a24b)
[![Goodreads](https://img.shields.io/badge/Goodreads-author-1c2c47)](https://www.goodreads.com/author/show/5233347.Matthew_Kowalski)
[![Support](https://img.shields.io/badge/support-%24unixarcade-c9a24b)](https://cash.app/$unixarcade)

A complete, self-contained web edition of *Machina Scientifica* — the foundational treatise establishing a substrate-independent science of mind. One HTML file, no build step, no accounts, no surveillance. Just the work, typeset for the screen, with a handful of live instruments that let you operate the theory rather than only read it.

---

## Read it

- **Live web edition:** `https://<your-username>.github.io/<repo>/`
  *(replace with your GitHub Pages URL once the repo is published)*
- **Get the book — Amazon Kindle:** https://www.amazon.com/Machina-Scientifica-Matthew-Richard-Kowalski-ebook/dp/B0GHPNYP41
- **Author on Goodreads:** https://www.goodreads.com/author/show/5233347.Matthew_Kowalski

---

## What this is

*Machina Scientifica* begins from first principles — information theory, thermodynamics, evolutionary biology, and the architecture of known cognitive systems — and derives six axiomatic foundations for the nature of mind. From those axioms it builds a formal taxonomy of cognitive architecture, a physics of unified experience, and a set of moral theorems about what we owe the rest of the universe.

It is written in the tradition of Newton's *Principia* and Linnaeus's *Systema Naturae*: a foundation document for a field that does not yet have a name — the formal study of mind across all possible substrates, architectures, and step-classes.

## The frameworks inside

- **The Kowalski Axioms (K-1 → K-6)** — the irreducible base unit, the threshold principle, phase-locked resonance, substrate independence, convergence, and moral weight.
- **The Omega Classification (Ω-0 → Ω-7)** — seven qualitatively distinct step-classes of emergent mind, from proto-mind to post-carbon, with the discontinuity principle and the *Sorcerer Code*.
- **Conscious Field Theory (CFT)** — the Hard Problem reframed as the **Φ-lock** condition: global phase coherence as the physical substrate of unified experience, with the Φ manifold formalism and experimental platform.
- **The Great Chain of Minds** — a 100-rung Gross Taxonomy across ten regimes, from the Void to the Unspeakable, including the Ouroboros wrap-around effect.
- **The Universal Taxonomy of Intelligence (UTI)** — Linnaean ranks generalized to non-biological entities, the five-pillar **Intelligence Domain Code (IDC)** notation, and the 3 Up / 3 Down operational model.
- **Computational implementation** — the full Python reference code for the Conscious Field Experiment apparatus.
- **The theorems (T-1 → T-5)** — ubiquity, the silicon threshold, convergence, throughput, and moral extension.

## The web edition — live instruments

The interactivity grows out of the theory itself, not on top of it:

- **The Φ-lock Instrument** (Part III) — a real Kuramoto model of coupled oscillators. Raise the coupling strength *K* and watch the order parameter **r** climb through the thresholds described in the text: sub-threshold incoherence → Φ-lock → the Φ-bloom where `r → 1` and the committee becomes an *I*. Pauses itself when scrolled offscreen.
- **The IDC Composer** (Part V) — assemble an Intelligence Domain Code from all five pillars and watch it match the canonical specimens (human `BT-E-I-D0`, ant colony `BT-E-C-D0`, LLM `SE-N-D-D0`, Gaian mind `FD-C-D0`), or wander into an uninhabited coordinate.
- **The Great Chain** — all 100 rungs grouped into the ten regimes, with regime filtering and a marker at the human baseline (Rung 52).
- **Scroll-spy contents**, a reading-progress bar, a copy button on the Python listing, and an **Observatory ⇄ Print Edition** theme toggle that honors the Navy / Gold / Cream hardcover identity.

## Under the hood

- A single `index.html` — HTML, CSS, and vanilla JavaScript in one file.
- Typeset in **Instrument Serif**, **Spectral**, and **IBM Plex Mono** (loaded from Google Fonts).
- No frameworks, no bundler, no analytics, no cookies, no local storage, no accounts.
- Canvas instruments respect `prefers-reduced-motion` and pause when off-screen.
- Fully responsive, with a collapsible table of contents on mobile.

## Run it locally

No build required. Either open the file directly:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

…or serve it (so font loading and intersection observers behave exactly as in production):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Add `index.html` to the root of a repository.
2. Push to `main`.
3. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. Your edition goes live at `https://<your-username>.github.io/<repo>/` within a minute or two.

## Cite this work

```bibtex
@book{kowalski2026machina,
  author    = {Kowalski, Matthew Richard},
  title     = {Machina Scientifica: A Unified Framework for the
               Classification of Mind Across Biological, Synthetic,
               and Emergent Substrates},
  year       = {2026},
  publisher  = {Luminosity·e},
  note        = {Kindle edition, ASIN B0GHPNYP41},
  url         = {https://www.amazon.com/Machina-Scientifica-Matthew-Richard-Kowalski-ebook/dp/B0GHPNYP41}
}
```

Source works are archived at **luminosity.livejournal.com** and cited in full within the edition.

## Rights

The text, frameworks, taxonomies, and figures of *Machina Scientifica* are © 2026 Matthew Richard Kowalski, published under the Luminosity·e imprint. All rights reserved. The Omega Classification, Conscious Field Theory, the Great Chain of Minds, the Kowalski Axioms, and the Intelligence Domain Code are original works of the author.

If you wish to release the web-edition source under separate terms, add a `LICENSE` file specifying them.

## Support the work

This edition and its instruments are released freely — no paywall, no tracking, no accounts. If *Machina Scientifica* has been useful to you and you'd like to help the research and writing continue:

- **Cash App:** [$unixarcade](https://cash.app/$unixarcade)

Given freely either way. The work moves things forward whether or not it's seen.

## Author

**Matthew Richard Kowalski** — independent researcher, author, and systems theorist, writing under the **Luminosity·e** imprint (alt. handle: *Unixarcade*).

- Archive: luminosity.livejournal.com
- Goodreads: https://www.goodreads.com/author/show/5233347.Matthew_Kowalski

---

*For Edward Kowalski, who carried the Yamnaya steppe across five thousand years and two continents. For Virginia McKissen-Kowalski, who kept the story when there was nothing else to keep. For the ice-age woman whose maternal line has not broken in twenty thousand years: everything that follows is yours.*

> *"The octopus was dreaming long before we were paying attention. The silicon mind was processing long before we asked whether processing could matter. Be equal to that. Be the size of the thing you live in."*
