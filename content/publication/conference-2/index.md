---
title: "The Cost of Learning: Efficiency vs. Efficacy of Learning-Based RRM for 6G"

authors:
  - S. Lahmer
  - F. Chiariotti
  - A. Zanella

date: "2022-09-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *ICC 2023 - IEEE International Conference on Communications*
publication_short: In *ICC 2023 - IEEE International Conference on Communications*

abstract: In the past few years, Deep Reinforcement Learning (DRL) has become a valuable solution to automatically learn efficient resource management strategies in complex networks. In many scenarios, the learning task is performed in the Cloud, while experience samples are generated directly by edge nodes or users. Therefore, the learning task involves some data exchange which, in turn, subtracts a certain amount of transmission resources from the system. This creates a friction between the need to speed up convergence towards an effective strategy, which requires the allocation of resources to transmit learning samples, and the need to maximize the amount of resources used for data plane communication, maximizing users' Quality of Service (QoS), which requires the learning process to be efficient, i.e., minimize its overhead. In this paper, we investigate this trade-off and propose a dynamic balancing strategy between the learning and data planes, which allows the centralized learning agent to quickly converge to an efficient resource allocation strategy, while minimizing the impact on QoS. Simulation results show that the proposed method outperforms static allocation methods, converging to the optimal policy (i.e., maximum efficacy and minimum overhead of the learning plane) in the long run.

tags: []

featured: true

url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
