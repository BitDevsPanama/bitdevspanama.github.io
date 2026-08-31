# BitDevs Panamá

Site for [BitDevs Panamá](https://bitdevs.org/cities) — a monthly Socratic
Seminar for Bitcoin developers in Panama City.

Forked from [BitDevsNYC/BitDevsNYC.github.io](https://github.com/BitDevsNYC/BitDevsNYC.github.io),
the template every BitDevs chapter uses. Jekyll, hosted on GitHub Pages.

## Development

Needs [Ruby & Jekyll](https://jekyllrb.com/docs/installation/):

    bundle install
    bundle exec jekyll serve

Then open http://localhost:4000

## Adding a seminar

Copy `_posts/_template.md` to `_posts/YYYY-MM-DD-socratic-seminar-N.md`, fill in
the links, and remove `published: false` when it's ready to go live.
