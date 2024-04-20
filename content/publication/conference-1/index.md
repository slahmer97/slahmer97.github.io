---
title: "Energy Consumption of Neural Networks on NVIDIA Edge Boards: an Empirical Model"

authors:
  - S. Lahmer
  - A. Khoshsirat
  - M. Rossi
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
publication: In *2022 20th International Symposium on Modeling and Optimization in Mobile, Ad hoc, and Wireless Networks*
publication_short: In *WiOpt*

abstract: Recently, there has been a trend of shifting the execution of deep learning inference tasks toward the edge of the network, closer to the user, to reduce latency and preserve data privacy. At the same time, growing interest is being devoted to the energetic sustainability of machine learning. At the intersection of these trends, in this paper we focus on the energetic characterization of machine learning at the edge, which is attracting increasing attention. Unfortunately, calculating the energy consumption of a given neural network during inference is complicated by the heterogeneity of the possible underlying hardware implementation. In this work, we aim at profiling the energetic consumption of inference tasks for some modern edge nodes by deriving simple but accurate models. To this end, we performed a large number of experiments to collect the energy consumption of fully connected and convolutional layers on two well-known edge boards by NVIDIA, namely, Jetson TX2 and Xavier. From these experimental measurements, we have then distilled a simple and practical model that can provide an estimate of the energy consumption of a certain inference task on these edge computers. We believe that this model can prove useful in many contexts as, for instance, to guide the search for efficient neural network architectures, as a heuristic in neural network pruning, to find energy-efficient offloading strategies in a split computing context, or to evaluate and compare the energy performance of deep neural network architectures.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

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
projects:
  - example

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
