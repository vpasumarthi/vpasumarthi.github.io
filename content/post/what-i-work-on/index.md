---
title: What I work on
summary: How I use DFT, AIMD, and software development to study catalytic materials and build workflows that scale.
date: '2024-05-01T00:00:00Z'
tags:
  - Catalysis
  - Materials Modeling
  - Scientific Software
  - Automation
featured: false
authors:
  - admin
---

I am a computational scientist focused on connecting atomistic simulations, automation, and data-driven analysis to understand catalytic materials. Most of my time is spent in the Greeley group at Purdue University, where I work on ab initio molecular dynamics (AIMD) and density functional theory (DFT) studies that probe how catalysts activate and convert energy-relevant molecules. The problems I like most sit at the intersection of chemistry, materials, and software—places where careful physics-based modeling can be accelerated by good engineering practices.

## How I study catalysts

I build models that capture the energetics and dynamics of reactions on surfaces. For early mechanism exploration, I rely on DFT to map adsorption energies, transition states, and reaction coordinates. When temperature effects or solvent interactions become important, AIMD lets me track how structures evolve in time and how entropic contributions shift reaction pathways. These calculations are tied together with microkinetic models so that rate predictions and selectivity trends are grounded in first-principles energetics.

A large part of the job is data management. Individual calculations produce thousands of structures and energetic values, and organizing them so that they can be compared or reused is crucial. I have built routines to standardize input generation, parse outputs, and validate geometries so that downstream analysis is reliable. This work feeds into my open source projects, PyCD and CatEnergy, which turn these routines into reusable tools for other researchers.

## Building reliable workflows

To make these studies repeatable, I treat simulation campaigns as software projects. Each workflow is version-controlled, containerized when practical, and instrumented with logging so that failures are visible early. Automated job submission and restart logic keep large batches of calculations moving on HPC systems. Lightweight continuous integration catches simple issues in templates and parsing scripts before they reach production clusters.

I also think about developer experience for scientists. Command line interfaces and clear documentation help teammates launch new studies without digging through internals. Where possible, I expose configuration through YAML or JSON schemas and include sensible defaults so that new projects can start from a consistent scaffold.

## Data-driven insights

Physics-based models are the foundation, but structured data enables faster iteration. I maintain curated datasets of adsorption energies, vibrational modes, and reaction barriers that can be mined for patterns. Simple regressions or kernel methods often reveal which descriptors control activity or stability. When the data volume supports it, I experiment with graph-based or physically inspired machine learning models that can suggest promising catalyst compositions or surface motifs before running the next set of expensive calculations.

The goal is not to replace DFT or AIMD, but to prioritize them. By ranking candidate materials and reaction steps with inexpensive models, we can focus high-fidelity simulations where they matter most and shorten the path from hypothesis to validated mechanism.

## What I am looking for

I am interested in roles that blend computational chemistry, materials modeling, and scientific software development. I enjoy collaborating with experimentalists to interpret spectra or design new catalysts, and I like building tools that make complex workflows accessible to a broader team. If you are working on energy conversion, electrification of chemical processes, or data platforms for R&D, I would love to connect.

Feel free to reach out if you want to discuss potential collaborations or how these approaches could support your projects.
