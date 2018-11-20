---
title: "Getting Started"
date: 2018-11-19T16:06:45-08:00
draft: true
---


YourBase is a build and test runner that accelerates building and testing of software. It can be used during local development or as part of continuous integration (CI).

YourBase uses incremental operations to speed-up the processes of re-compiling, re-assembling and re-testing projects. YourBase caches artifacts between builds and skips unnecessary build steps or tests that are not relevant for a given change.

This document explains how to setup and use YourBase.

Preparing the Repository
---

To setup YourBase for your repository, create a yourbase.yml file with the list of commands and variables required to run your build and test.
