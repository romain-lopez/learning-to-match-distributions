---
title: Home
layout: home
nav_order: 1
---

# Learning to Match Distributions: Optimal Transport, Flow Matching & Applications
{: .no_toc .mb-2 }

**CSCI-GA 3033-148** · New York University · Fall 2026
{: .fs-5 .text-grey-dk-000 }

{% include wip.html %}

In a growing range of problems across statistics and machine learning, the object of interest is not a single data point but an entire distribution. A patient is summarized by the cloud of their single cells; an experimental condition by the population of measurements it produces; a generative model by its output distribution. Once distributions become the primary entity, a few basic questions come to mind: How far apart are two distributions? How do we transform one into another? What lies on the path between them?

This class develops the mathematical machinery for exactly these three operations — measuring distances between distributions, learning maps that optimally move one onto another, and constructing flows that interpolate between them — alongside the statistical machine learning approaches (MMD, optimal transport, flow matching) that make them practical at scale. It also aims to arm students with the essential practical skills required to do further research in this rapidly evolving field.

---

## Instructor

<div class="staff-card">
  <img class="staff-photo" src="{{ '/assets/images/romain.jpg' | relative_url }}" alt="Romain Lopez">
  <div class="staff-info">
    <a class="staff-name" href="https://romain-lopez.github.io">Romain Lopez</a>
    <span class="staff-meta">Email: romain.lopez@nyu.edu</span>
    <span class="staff-meta">Office Hours: Mondays, 3:30–4:30 PM, 60 Fifth Avenue, Office 304</span>
  </div>
</div>

---

## Prerequisites

Students should have a **graduate-level machine learning** background plus
solid **probability and statistics** (at the level of Fernández-Granda's
[*Probability and Statistics for Data Science*](https://www.ps4ds.net/), 2024). Comfort with Python and
basic deep-learning tooling is expected for the project and demos.

---

## Logistics

**Time**: Mondays, 4:55–6:55 PM ET
**Location**: 60 Fifth Avenue, Room C10

**Format**: The course will adopt a hybrid format. Initially, the instructor will provide
lectures to offer a broad overview and context. Following this, the class will
seamlessly shift to student-led presentations and panel discussions, utilizing
Alec Jacobson and Colin Raffel's [role-play](https://colinraffel.com/blog/role-playing-seminar.html) seminar approach.

**Communication**: We will use [Discord](https://discord.com) to facilitate discussion. You can find the
invite link on [Brightspace](https://brightspace.nyu.edu).

---

## Course Schedule

The [Calendar](calendar) will be regularly updated with the full week-by-week schedule, readings and topics.

---

## Preparatory Homework

A problem set released at the first class (Mon Sep 14) and due at the start of the
second (Mon Sep 21). It covers the mathematical background the lectures assume —
conditional expectation, pushforward measures, the continuity equation, linear
programming duality, and convexity — and every exercise reappears later in the course.

It is worth **10% of the final grade**, and points are awarded for a genuine attempt
rather than for a correct answer. A well-prepared student should finish in about two
hours; being unable to complete most of it is a signal that this course may not be a
good match. Solutions are released after the deadline.

See the [Preparatory Homework](homework) page for the problem set and full details.

---

## Grading

Grading will be based on:
1. Semester-long project (60%): an application/demo or a research project, in teams of 1–4. See the [Project Logistics](project) page for options, milestones, and deadlines.
2. Preparatory homework (10%): a problem set on the mathematical background, released at the first class and due Sep 21. Graded on a genuine attempt rather than on correct answers. See the [Preparatory Homework](homework) page.
3. Paper presentation & panel participation (30%): Each student signs up to present papers and take on reading-group roles; graded on presentations and live panel participation (no written reviews). See the [Role-play Seminar](reading-group) page to learn more about the format.

---

## Collaboration and Use of AI

You may discuss coursework with other students, and you are encouraged to use AI
assistants (LLMs, coding copilots) as tools throughout the course — for coding,
brainstorming, and learning. Two conditions:

- You are fully responsible for everything you submit or present: correctness,
  claims, and citations are on you.
- Briefly disclose both in each deliverable: who you worked with, and how you used
  any AI assistant.

AI is no substitute for genuine understanding — in panels and discussions you
must be able to defend your work without it.


