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
  - title: Senior Deep Learning Architect
    company: NVIDIA Corporation
    company_url: 'https://www.nvidia.com/en-us/'
    company_logo: org-nv
    location: Santa Clara, CA
    date_start: '2022-08-29'
    date_end: ''
    description: |2-
        * Understand, analyze, profile, and optimize deep learning training workloads on state-of-the-art hardware and software platforms.
        * Guide development of future generations of deep learning processors and computing platforms.
  - title: Research Assistant
    company: Parallel Programming Laboratory, UIUC
    company_url: 'https://charm.cs.illinois.edu/'
    company_logo: org-uiuc
    location: Urbana, IL
    date_start: '2016-08-01'
    date_end: '2022-08-15'
    description: |2-
        * Optimized performance for GPU-accelerated applications on modern heterogeneous HPC platforms by developing new features in the Charm++ parallel programming system, including asynchronous completion notification and GPU-aware communication.
        * Developed CharminG, a GPU-resident parallel programming framework built on CUDA and NVSHMEM, with the goal of performing task scheduling and communication inside the GPU devices.
        * Improved support for NVIDIA and Intel GPUs in the NAMD molecular dynamics simulation framework.
  - title: Graduate Technical Intern
    company: Intel Corporation
    company_url: 'https://www.intel.com/'
    company_logo: org-intel
    location: Austin, TX (Virtual)
    date_start: '2021-05-15'
    date_end: '2022-08-15'
    description: |2-
        * Developed support for Intel GPUs in OpenMPI using Intel oneAPI Level Zero and Libfabric/OFI.
        * Validated point-to-point and collective MPI calls on Intel GPU clusters with OSU micro-benchmark suite.
  - title: Research Intern
    company: Lawrence Livermore National Laboratory
    company_url: 'https://www.llnl.gov/'
    company_logo: org-llnl
    location: Livermore, CA
    date_start: '2019-05-15'
    date_end: '2019-08-15'
    description: |2-
        * Created performance models using parallel discrete event simulation (PDES) and roofline model to analyze and predict the performance of GPU-accelerated proxy applications in the Exascale Computing Project (ECP), including SW4lite and MiniFE.
  - title: Technology Research Intern
    company: Walt Disney Animation Studios
    company_url: 'https://disneyanimation.com/'
    company_logo: org-wdas
    location: Burbank, CA
    date_start: '2018-05-15'
    date_end: '2018-08-15'
    description: |2-
        * Optimized memory usage in a parallel path tracing renderer via de-duplication of scene objects.

design:
  columns: '2'
---
