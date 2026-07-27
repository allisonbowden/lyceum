# Lyceum Roadmap

Ideas and design changes to come back to later.

## Design: clearer structure per work

Right now the different link types on a page (buy/watch/read link, review, deeper analysis/podcast) aren't visually distinguished — they mostly look like a flat list. Consider labeling or grouping them more explicitly, something like:

- **The work itself** — where to watch/read/listen to the primary source
- **A review** — a quick take on whether it holds up (e.g. Roger Ebert, Smarthistory)
- **An analysis/follow-up** — a deeper dive (e.g. a podcast episode, academic commentary)

Goal: make it obvious at a glance which of the three a given link is, without cluttering the clean layout.

## Embed timestamps (skip the ads)

Apple Podcasts embeds support `&r=<seconds>` to start playback partway in; Spotify embeds support `?t=<seconds>`; native `<audio>`/`<video>` elements support `#t=<seconds>`. Confirmed `&r=` works via a live iframe test. Not yet applied site-wide — would let us skip past ad reads at the start of an episode.

## Sources page

A dedicated page describing/crediting the third-party analysis sources used across the site — The Lonely Palette, The Great Books podcast, ThinkND Podcast, History of Philosophy Without Any Gaps, Historic Royal Palaces, ArtCurious, Painting of the Week, Bloomsbury Academic Podcast, RogerEbert.com, etc.

## Remaining artwork podcast candidates (user to review)

Found but not yet added, pending your own listen:
- Holbein / *The Ambassadors* — Historic Royal Palaces
- Manet / *Olympia* — ArtCurious
- Turner / *Rain, Steam and Speed* — Painting of the Week
- Friedrich / *Wanderer above the Sea of Fog* — weak match ("Inside the Masterpiece", not academic-hosted)
- Magritte — no dedicated episode found
- David / *The Death of Socrates* — no dedicated episode found
