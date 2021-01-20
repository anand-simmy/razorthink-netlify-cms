---
title: Create Pipeline
author: Anand Simmy
date: 2021-01-20T07:31:52.251Z
thumbnail: /images/download-1-.jpeg
---


# Creating and publishing blocks and pipelines

This tutorial guides you through the steps required to publish custom built blocks and pipelines to RZT aiOS. A published block can be later imported in Jupyter notebook and it will also be shown in IDE pipeline builder. Similarly, a pipeline created in Jupyter notebook using published blocks can be saved so that it can be accessed later from IDE and Jupyter notebook.

Every block is published with an associated`bundle name`which is analogous to a python module name. In order to publish a block, the block code should be placed in certain hierarchy of directories. A block can be published with two different scopes

*