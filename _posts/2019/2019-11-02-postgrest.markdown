---
layout: post
title:  "PostGrest"
comments: true
date:   2019-11-02 12:00:00 -0500
categories: technology
draft: false
---

A super cool new project I just learned about, creating a lot of [discussion on HN](https://news.ycombinator.com/item?id=21435195).

> PostgREST is a standalone web server that turns your PostgreSQL database directly into a RESTful API. The structural constraints and permissions in the database determine the API endpoints and operations.

The motivation for PostGREST feels very Rails-ish in spirit - focusing on convention over configuration and preventing room for programming errors.

> Using PostgREST is an alternative to manual CRUD programming. Custom API servers suffer problems. Writing business logic often duplicates, ignores or hobbles database structure. Object-relational mapping is a leaky abstraction leading to slow imperative code. The PostgREST philosophy establishes a single declarative source of truth: the data itself.

This works only for Postgres DB's right now. I think we'll see a lot more of these trends that help app developers create data interoperability into their products. 

This reminds me of apps like [Sheetsu](https://sheetsu.com/), which turns any Google spreadsheet into an API.