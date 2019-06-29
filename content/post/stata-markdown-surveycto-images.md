---
title: "Managing images from SurveyCTO using Stata, Markdown, and Pandoc"
date: 2018-10-23T21:18:12-05:00
Description: ""
Tags: []
Categories: []
Draft: true

---

This is a short guide for programmatically generating documents,
with embedded images, from SurveyCTO data. It uses the excellent
[markstat](https://data.princeton.edu/stata/markdown), which in
turn relies on [pandoc](https://pandoc.org/) to create PDFs or Word Documents.

Markstat relies on executing a *.stmd* file which mixes
Markdown documentation with indented Stata code. 

## Step 1: *file write*
The first step uses Stata's *file write* to generate the *.stmd* document.

