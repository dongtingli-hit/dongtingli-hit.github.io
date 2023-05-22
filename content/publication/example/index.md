---
title: 'Sampling-based 3-D line-of-sight PWA model predictive control for autonomous rendezvous and docking with a tumbling target'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dongting Li
  - Rui-Qi Dong
  - Yanning Guo*
  - Guangtao Ran
  - Dongyu Li

# Author notes (optional)
##author_notes:
##  - 'Equal contribution'
##  - 'Equal contribution'

date: '2023-05-22'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Robust and Nonlinear Control*
publication_short: In *International Journal of Robust and Nonlinear Control*

abstract: This article introduces a line-of-sight (LOS)-Euler rendezvous and docking (RVD) framework to dock with a tumbling target under several RVD constraints. By a double-loop control scheme, the chaser’s position is controlled to track the target’s docking port which is coupled with its rotation. The chaser’s attitude is driven to track the target’s rotation, while satisfying the field of view constraint which is coupled with the LOS range. These complex couplings are linearly described in the proposed framework. To this end, the 6 DoF information interactions among the sensor mea- surements, states, and RVD constraints need no transformation and linearization. Consider the online piecewise affine (PWA) model predictive controller (MPC) may be unsolvable under complex constraints, which is caused by the accumulated pre- diction error, a sampling-based method is proposed. The linear predictions are driven to the closer neighborhoods of the actual nonlinear states by constructing directional sampling intervals. Besides, a singularity free strategy is provided to realize con- tinuous tracking with crossing the singularities of angle states. Detailed numerical simulations illustrate the validity of the proposed methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: ture

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
