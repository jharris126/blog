---
title: "So I have a .hyper file, now what? Part 1"
date: 2022-09-16
---

## What even is a Hyper File and how do I use the Tableau Hyper API to create one?

### The Problem

Tableau has created an incredibly rich and powerful [Hyper API](https://help.tableau.com/current/api/hyper_api/en-us/index.html) for working with and generating `.hyper` files, the file format for Hyper, Tableau's data extract engine. However, though they've made creating creating the files relatively straightforward for anyone with a bit of coding under their belt, how to most effectively use and maintain the files you create can be much less intuative. In the multi-part series, we will walk through how to create, deploy, and maintain a data pipleline using Tableau's Hyper API and [tableauserverclient](https://tableau.github.io/server-client-python/) python library wrapper for the [REST API](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm). In this first part, we will kick off by using the Hyper API to generate a Hyper exract from a source which cannot be natively generated from within [Tableau Desktop](https://www.tableau.com/products/desktop) or even [Tableau Prep](https://www.tableau.com/products/prep).

---

### Creating Your First Hyper File via the Tableau Hyper API

Interesting blog content here.

Test python code block
```python
import tableauhyperapi
```
