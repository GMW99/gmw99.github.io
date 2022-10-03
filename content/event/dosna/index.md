---
title: An Introduction to DosNA
subtitle: Distributed Numpy Arrays for High-performance cloud computing

event: UKRI Cloud Workshop
event_url: https://cloud.ac.uk/2022/02/27/programme-for-ukri-cloud-workshop-2022/
doi: 10.5281/zenodo.6411812

location: Francis Crick Institute
address:
  street: 1 Midland Rd 
  city: London
  postcode: NW1 1AT
  country: United Kingdom

summary: An Introduction to DosNA
abstract: The cloud-primarily deals with data as object stores such as S3; however, HPC data processing is primarily done using filesystems such as HDF5, which can make offloading data to the cloud difficult. DosNa is a python wrapper that can distribute N-dimensional arrays over an Object Store server. The main goal of DosNa is to provide an easy and seamless interface to store and manage N-Dimensional datasets over a remote cloud. It supports S3 and Ceph backends and allows parallelised data access through the MPI engine. Currently, features to allow for converting HDF5 files to DosNa Objects, an API to visualise data, object locking, BLOSC compression, and checksums are underway. This talk introduces DosNa and showcases the current features and what’s to come.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-03-29T14:15:00Z'

authors: []
tags: []
url_slides: '/uploads/An_Introduction_to_DosNA.pdf'
links:
  # - name: Cite
  #   url: https://zenodo.org/record/6411813/export/hx#.Yy2V6tLMJH4
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/rosalindfranklininstitute/DosNA


# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---
<!-- 
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

