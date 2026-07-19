# What's it like being a D(Her) in India ?!

A living archive of reflections on resilience shared by women in Digital Humanities in India. The form of the site pays homage to Jason Heppler's [What Is Digital Humanities?](https://whatisdigitalhumanities.com/).

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire website: design, interactions, and all contributor reflections embedded within |
| `resilience_definitions.csv` | The open dataset (one row per question and answer), kept for reference |
| `LICENSE` | CC BY 4.0 |

The site is fully self-contained in `index.html`; no other file is needed for it to work.

## How the site works

A random reflection (one of 87 answers across six questions from 16 contributors) is shown with the contributor's name in her own spring colour, her affiliation, and the question she was answering. "New voice" draws another at random, "Read all voices" opens the full archive grouped by contributor, and "Add your voice" opens the Google Form for new contributions.

## Updating the site

Small text corrections (for example, replacing an "Anonymous" entry once a contributor confirms her name): edit `index.html` directly on GitHub with the pencil icon, use Ctrl+F to find the entry, and commit.

Larger updates (new form responses): regenerate `index.html` from the updated response sheet, then replace the file via Add file, then Upload files. The filename must be exactly `index.html`.

Every commit triggers a GitHub Pages rebuild; wait for the green tick under the Actions tab, then hard-refresh the site.

## Pending checks

- Confirm consent with the three earliest respondents (their submissions predate the consent question).
- Two contributors chose name-and-affiliation but the early form did not record their names; they display as Anonymous until confirmed.
