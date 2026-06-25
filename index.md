---
title: Home
layout: home
nav_order: 1
---

# Learning to Match Distributions: Optimal Transport, Flow Matching & Applications
{: .no_toc .mb-2 }

**CSCI-GA 3033-148** · New York University · Fall 2026
{: .fs-5 .text-grey-dk-000 }


In a growing range of problems across statistics and machine learning, the object of interest is not a single data point but an entire distribution. A patient is summarized by the cloud of their single cells; an experimental condition by the population of measurements it produces; a generative model by its output distribution. Once distributions become the primary entity, a few basic questions come to mind: How far apart are two distributions? How do we transform one into another? What lies on the path between them?

This class develops the mathematical machinery for exactly these three operations — measuring distances between distributions, learning maps that optimally move one onto another, and constructing flows that interpolate between them — alongside the statistical machine learning approaches (MMD, optimal transport, flow matching) that make them practical at scale. It also aims to arm students with the essential practical skills required to do further research in this rapidly evolving field.

---

## Instructor

<div class="staff-card">
  <img class="staff-photo" src="{{ '/assets/images/romain.jpg' | relative_url }}" alt="Romain Lopez">
  <div class="staff-info">
    <a class="staff-name" href="https://romain-lopez.github.io">Romain Lopez</a>
    <span class="staff-meta">Email: romain.lopez@nyu.edu</span>
    <span class="staff-meta">Office Hours: TBD</span>
  </div>
</div>

---

## Prerequisites

Students should have a **graduate-level machine learning** background plus
solid **probability and statistics** (at the level of Fernández-Granda's
*Probability and Statistics for Data Science*, 2024). Comfort with Python and
basic deep-learning tooling is expected for the project and demos.

---

## Logistics

**Time**: Mondays, 4:55–6:55 PM ET
**Location**: 60 Fifth Avenue, Room C10

**Format**: The course will adopt a hybrid format. Initially, the instructor will provide
lectures to offer a broad overview and context. Following this, the class will
seamlessly shift to student-led presentations and panel discussions, utilizing
Alec Jacobson and Colin Raffel's [role-play](https://colinraffel.com/blog/role-playing-seminar.html) seminar approach.

**Communication**: We will use [Discord](https://discord.com) to facilitate discussion. The instructor will provide the
link during the first class.

---

## Course Schedule

See the [Calendar](calendar) for the full week-by-week schedule, readings, and
the reading-session run-of-show.

---

## Course structure

The semester is organized around three operations on distributions:

1. **Distances** — how do we measure that two distributions are close?
   (Integral probability metrics, MMD, Wasserstein.)
2. **Coupling** — how do we map the mass of one distribution onto another?
   (Monge/Kantorovich, Sinkhorn, Brenier, Gromov–Wasserstein.)
3. **Interpolating** — what is the path *between* two distributions?
   (Dynamic OT, Wasserstein barycenters, continuous normalizing flows → flow matching.)

Each theme is motivated by real applications (generative modeling, domain
adaptation, single-cell genomics, causal inference, music generation) and paired
with a set of recent papers for the reading group.

---

## Grading

> **Note:** the grading breakdown below is a working default adapted from a
> comparable NYU seminar and is **subject to revision** before the first class.

| Component | Weight |
|---|---|
| Early assignment | 10% |
| Paper presentation & panel participation | 30% |
| Semester-long project | 60% |

- **Early assignment** — a short warm-up to get everyone on the same tooling.
- **Paper presentation & panel** — each student takes on reading-group roles
  (author / skeptic / archaeologist / hacker) across the semester; see
  [Calendar](calendar) for the run-of-show.
- **Project** — an application/demo or a research project, in teams of 1–4.
  See the [Project](project) page for options, milestones, and deadlines.

---

## Use of AI

> **TBD** — an explicit policy on the use of AI assistants for assignments,
> presentations, and the project will be announced at the first class.

