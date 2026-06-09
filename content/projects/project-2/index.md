+++
title = "Data Cleaning Checklist"
date = 2020-08-22

[taxonomies]
categories = ["data-science"]
+++

A practical checklist for turning a messy dataset into something ready for analysis.

<!-- more -->

Before modeling or visualization, I like to slow down and make sure the data can be trusted. A clean table makes every later step easier to explain.

My usual pass includes:

- Check row counts before and after every filter.
- Review missing values by column and by group.
- Standardize units, categories, and date formats.
- Look for duplicate records and impossible values.
- Keep raw data unchanged and document transformations.

This writeup reflects the kind of careful preparation I want every data project to start with: simple checks, clear notes, and transformations that can be reproduced later.
