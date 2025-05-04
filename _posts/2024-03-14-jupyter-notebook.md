---
layout: post
title: What Makes a Good Prune
date: 2024-03-14 09:00:00
description: This notebook demonstrates the method for calculating the optimal amount to prune a neural network as shown in the paper "What Makes a Good Prune? Maximal Unstructured Pruning for Maximal Cosine Similarity" by G. Mason-Williams and F. Dahlqvist 2024.
tags: published-code jupyter
categories: paper-code
giscus_comments: false
related_posts: false
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/what_makes_a_good_prune.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/what_makes_a_good_prune.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
