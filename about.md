---
layout: page
title: About
description: >-
    Course policies and information.
nav_order: 2
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About CS 276

Cryptography enables encrypted communication, digital signatures, and verifiable computation, among other applications. In abstract terms, cryptography is the science of designing algorithms that enable secure communication and computation in an untrusted environment. Over the last four decades, cryptography has transformed from an ad hoc collection of mysterious tricks into a rigorous science based on complexity theory. Modern cryptography emphasizes precise mathematical definitions of security, and proofs of security that reduce to well-studied computational hardness assumptions.

In this course, students will practice writing mathematically rigorous security proofs and doing original research in the field of cryptography.

## Prerequisites
This course is designed for graduate students with some prior coursework and research experience in cryptography.
We recommend that students be familiar with the content from [CS 170](https://cs170.org/) (Efficient Algorithms and Intractable Problems) and [CS 171](https://eecs171.com/) (Undergraduate Cryptography). In particular, students should be comfortable writing security proofs.

## Course Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}

## How To Get Started
* Join the course on [Gradescope](https://www.gradescope.com/courses/799228){:target="_blank"} using entry code **2BKDD8**. Gradescope is where you will submit your assignments and view your grades.
* Join the Ed Discussion forum with this [join link](https://edstem.org/us/join/feHXXN){:target="_blank"}. You will need a *berkeley.edu* email address to join. Ed is where you can post and answer questions about the course.
* Sign up to scribe a lecture [here](https://docs.google.com/spreadsheets/d/174bPvR3db2Uvda138NZWzITQixrS3XxK4Cn-1Ie1gLM/edit?usp=sharing){:target="_blank"}.
* If you need DSP accommodations, please have your accommodation letters sent to the instructors as soon as possible. Also, please email bhaskarr@berkeley.edu with any logistical questions.
