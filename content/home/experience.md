---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Software Associate
    company: Rosalind Franklin Institute
    company_url: 'https://www.rfi.ac.uk/'
    location: Oxfordshire
    date_start: '2022-07-01'
    date_end: ''
    description: |2-
        At the Rosalind Franklin Institute (RFI), I am presently involved in two research projects. DisTRaX, which I lead, is the productionisation and improvement of previous research and Kompressor, a machine learning project to create a novel neural losses compression algorithm for extensive volumetric scientific data.
  - title: Junior Research Software Engineer
    company: Rosalind Franklin Institute
    company_url: 'https://www.rfi.ac.uk/'
    location: Oxfordshire
    date_start: '2021-07-01'
    date_end: '2022-07-01'
    description: |2-
        In this role I conducted research in High-performance computing (HPC) for big data processing. Within this research, I lead the development and maintenance of two significant projects, DosNa [0] and DisTRaC [1]. I was also involved in writing a successful grant bid for £10,000 in research funding for "Using Novel Cluster Technology to improve performance of Cryo EM analysis" with the University of Bristol. This was successful and lead to a reduction in processing times of 4.37%.

  - title: AI & I Research Project- Automating Lab Book Data Collection With Edge Machine Learning
    company: Rosalind Franklin Institute
    company_url: 'https://www.rfi.ac.uk/'
    location: Oxfordshire
    date_start: '2020-09-01'
    date_end: '2021-06-01'
    description: |2-
        The dissertation/research project aimed to develop an automated way to collect lab book information and automatically record it in a central database. This object was achieved using classical computer vision techniques to recognise when to take a photo of the lab book and machine learning to generate a synthetic handwritten keyword dataset for training and testing and to extract the handwritten keywords from the lab book. The data captured was then stored in an s3 data store, and words extracted were attached in the metadata of the uploaded images. This dissertation was awarded 81.68% and is currently under further development at the Rosalind Franklin Institute. 


- title: Maths Circle Mentor
    company: Exeter Maths School
    company_url: 'https://exetermathematicsschool.ac.uk/'
    location: Exeter
    date_start: '2021-10-01'
    date_end: '2022-07-01'
    description: |2-
        I mentored students in years 8 and 9 in mathematics to encourage the development of mathematical thinking outside of school context- the aim is to improve their ability to be adventurous, articulate and accepting by providing them challenging questions to become better mathematicians. 

  - title: Scientific Computing Research Placement
    company: Diamond Light Source
    company_url: 'https://www.diamond.ac.uk/'
    location: Oxfordshire
    date_start: '2019-06-01'
    date_end: '2020-09-01'
    description: I worked on a 12-month research project entitled "High Performance Object Stores for Intermediate Data processing" this involved using technologies such as High Performance Compute Clusters, Univa Grid Engine, Savu, Ceph and relevant deployment tools as well as programming technologies such as MPI, C, python and bash. During this time, I deployed and maintained a semi-production Ceph cluster using ansible, created a way to visualise objects with an object store which formed part of a display at SC19, made GRAM a kernel module to represent RAM as a block device for Ceph and DisTRaC an application that allows Ceph to run on to on a High Performance Computing cluster using RAM. I also presented a poster at Ceph Day CERN as well as giving well-attended talks on the work within Diamond and the Ceph Science Group.

design:
  columns: '2'
---
