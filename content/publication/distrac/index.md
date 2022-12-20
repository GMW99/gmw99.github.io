---
title: 'DisTRaC: Accelerating High Performance Compute Processing for Temporary Data Storage'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gabryel Mason-Williams
  - Dave Bond
  - Mark Basham

date: '2022-12-06T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2212.03054'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv cs.DC
publication_short: arXiv 

abstract: High Performance Compute (HPC) clusters often produce intermediate files as part of code execution and message passing is not always possible to supply data to these cluster jobs. In these cases, I/O goes back to central distributed storage to allow cross node data sharing. These systems are often high performance and characterised by their high cost per TB and sensitivity to workload type such as being tuned to small or large file I/O. However, compute nodes often have large amounts of RAM, so when dealing with intermediate files where longevity or reliability of the system is not as important, local RAM disks can be used to obtain performance benefits. In this paper we show how this problem was tackled by creating a RAM block that could interact with the object storage system Ceph, as well as creating a deployment tool to deploy Ceph on HPC infrastructure effectively. This work resulted in a system that was more performant than the central high performance distributed storage system used at Diamond reducing I/O overhead and processing time for Savu, a tomography data processing application, by 81.04% and 8.32% respectively.


tags: 
    - HPC


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2212.03054.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - distrac

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->
<!-- 
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
