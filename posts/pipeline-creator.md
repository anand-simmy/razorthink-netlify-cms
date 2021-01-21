---
title: Introducing Pipelines
author: Anand Simmy
date: 2021-01-20T07:21:10.448Z
thumbnail: /images/download.jpeg
---
# Introducing Pipelines

## Pipeline Basics

### Problem

You want to chain blocks together so that the output of one block is fed into another.

### Solution

Up until now, each block was run individually using the`.execute`method of the block. While it is possible to manually collect the output from one block and provide it as an input parameter to the next, to reap the full benefits of all the features of inter-connecting blocks, you'll need to create a pipeline.

A Pipeline is essentially a DAG (Directed Acyclic Graph) of blocks where data flows only in one direction. An example of a pipeline is as shown bellow.

The first step would be define the blocks for the pipeline as bellow