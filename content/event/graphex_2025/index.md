---
title: A Multi-Agent Graph Neural Network for Efficient Task Assignments

event: 2025 Graph Exploitation Symposium
event_url: https://graphex.mit.edu/

location: Boston, MA
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Invited talk at the 2025 Graph Exploitation Symposium.
abstract: 'Assignment problems are prevalent in a multitude of autonomous agent and artificial intelligence (AI) contexts, where the learning task involves mapping elements from a domain set to a range set. While current state-of-the-art machine learning solutions employ graph neural networks (GNNs) on bipartite agent-task graphs, these approaches frequently fall short when addressing more complex constraints and objectives. To broaden the utility of GNNs for a wider variety of assignment problems, we introduce MAGNET -- a novel Multi-Agent Graph Neural network designed for Efficient Task assignment. MAGNET is composed of three integral components that together deliver enhanced performance: (1) a pre-processor that expands the bipartite graph such that it is amenable to multi-task assignment, (2) an edge-centric GNN, enabled through a line graph transformation, which generates candidate assignments, and (3) a post-processor that filters these candidate assignments to ensure they meet the feasibility criteria. Recognizing that the line graph transformation can affect execution time, we enhance MAGNET''s efficiency by incorporating an inference-time pruning strategy. This strategy leverages both GNN scoring and sparsification techniques to streamline the assignment process. Experimental evaluations demonstrate that MAGNET delivers substantial performance improvements over previous GNN-based and heuristic methods, and notably reduces execution time by several orders of magnitude compared to state-of-the-art commercial solvers.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-21T14:30:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
url_pdf: 'https://byu-my.sharepoint.com/:b:/g/personal/jamesbu_byu_edu/EcejqTdxmklHtBdwiaSADgUBUaRjRryyM7UhLmnqjDgSYg?e=fdT2GV'
url_slides: 'https://byu-my.sharepoint.com/:p:/g/personal/jamesbu_byu_edu/EQpCRTMhBD1FjGNL9FzP9CcBeYPNq4qqt7m6j_0w_Es2lg?e=IOhqBT'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - graphex_2025
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
