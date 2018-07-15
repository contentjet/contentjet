---
title: Overview
layout: doc.ejs
order: 0
---
# Overview

Contentjet is an open source API-first content management system built for the modern web. What sets Contentjet apart from traditional content management systems is that it is _headless_ by design.

## Headless? Say what?

Traditional content management systems bind content to presentation by passing content through a templating system which generates HTML for viewing in a web browser. In contrast a headless CMS makes no assumptions about how content is to be presented by removing the presentation layer (the head) entirely in favour of a more flexible RESTful API.

The key design philosophy behind Contentjet is that _**content should exist free from it's presentation**_. As we now live in a world where content is consumed on numerous devices tightly coupling content to a single presentation is not always feasible.

## Features

### Custom Entry types

Unlike traditional content management systems which limit content creation to a single _title_ and _body_ field, Contentjet let's you create your own entry types with custom fields. There are 13 fields to choose from such as text, boolean, date, multiple choice, colour and more!

### Multiple projects

Projects are top-level buckets for holding content. Each project holds it's own entry types, entries, media and users. How you choose to use projects is entirely up to you.

Users may be members of multiple projects. Each project maintains it's own user access list. For example a user may be an _administrator_ of one project but only an _author_ in another project.

### Media management

A CMS wouldn't be complete without the ability to upload images and files. Media can be attached to entries via the aptly named _media_ field or inlined as markdown into text fields.

## Technology

The application is built on a stack of awesome open source projects namely [Node.js][4], [Koa.js][5], [Objection.js][6], [PostgreSQL][7] and [React][8]. The CMS is composed of 2 discreet applications, the backend API [contentjet-api][2] and the frontend HTML user interface [contentjet-ui][1].


[1]: https://github.com/contentjet/contentjet-ui
[2]: https://github.com/contentjet/contentjet-api
[3]: https://github.com/contentjet/contentjet.github.io
[4]: https://nodejs.org
[5]: http://koajs.com/
[6]: http://vincit.github.io/objection.js/
[7]: https://www.postgresql.org/
[8]: https://reactjs.org/