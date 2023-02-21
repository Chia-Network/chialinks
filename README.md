# ChiaLinks.com

ChiaLinks.com is a collection of curated links and resources for the Chia community.

Besides the collection of links, there are a number of resources original to ChiaLinks.com:
- [Chia Network Roadmap](https://chialinks.com/roadmap/) - is mostly a lookback as the forward looking roadmap has been replaced by the official Chia Network roadmap.
- [Collection of Chia mentions in news articles](https://chialinks.com/news/)
- [Chia Ecosystem Map](https://chialinks.com/ecosystem/)
- Getting started guides for [Chia](https://chialinks.com/get-started/) and [Chia NFTs](https://chialinks.com/get-started-with-chia-nfts/)
- [Chia CHIP Tracker](https://chialinks.com/chips/)
- [Donate and Support Ecosystem](https://chialinks.com/donate/)
- [F.A.Q. from AMAs and transcribed answers](https://chialinks.com/faq/#chia-network-amas)
- [General F.A.Q. and answers](https://chialinks.com/faq/#faqs)
- (not part of ChiaLinks) [Chia Dev Tracker](https://dev.chialinks.com/) for open source development activity
- (removed) Chia Friends and Space Marmots NFT rarity list

## Build and deployment
The site is a static site built with [Jekyll](https://jekyllrb.com/) with the [Just The Docs](https://github.com/just-the-docs/just-the-docs) template. *Flat* icon set by [baianat](https://www.flaticon.com/authors/baianat) from www.flaticon.com used with attribution.

### Local build
1. Install Jekyll (incl. ruby) - [Instructions](https://jekyllrb.com/docs/installation/)
1. Clone this repo
1. Install required gems with `bundle install`
1. Compile and serve site to localhost with `bundle exec jekyll serve`

### Triggered deployment
 It is currently hosted on a DigitalOcean's App Platform (basic free tier) with builds triggered on any code change on the `main` GitHub branch.

It can alternatively be [deployed to GitHub pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## Code structure

The general design of the site involves flat files of link entries associated with a set of one or more predefined *tags*. These *tags* determine which page and/or section a link shows up under.

### Main tag categories (_labels)
Each page here contains a short page introduction and fetches & formats all links associated with that particular tag. Some pages such as `wallets` or `exchanges` contains custom formatting besides the default link listing.

`featured` and `verified` tags are handled uniquely to display them on the front page or add a green checkmark respectively.

### Data Files (_data)
These YAML flat files contain the items and link entries that are parsed by the various pages and layouts.
- `links.yml` entries for all links on the site 
- `news.yml` entries for [news mentions of Chia](https://chialinks.com/news/)
- `roadmap.yml roadmap-future.yml` entries to populate the [Chia Roadmap/Timeline](https://chialinks.com/roadmap/)
- `tags.yml` specifies special handlings of tags such as which tags should use sections and which tags are considered sections themselves.

### Link iteration and formatting (_includes)
The various `includes` code blocks are used throughout the individual pages to format arrays of data (usually links). See comments in each for how the logical flow works.
