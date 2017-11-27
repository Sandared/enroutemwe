---
title: Web Server
layout: nested
description:
---
# Web Server

## GitHub Repository

Go to [GitHub - Sample Application](https://github.com/osgi/osgi.enroute.examples/tree/master/osgi.enroute.examples.webserver.application)
Go to [GitHub - Web Resource](https://github.com/osgi/osgi.enroute.examples/tree/master/osgi.enroute.examples.webserver.webresource)

## Description

A large part of a web site usually consists of static resources like images, scripts, html, etc. These resources must be mapped to a proper path on the local webserver. The webserver can provide this feature by mapping a folder in the bundle to a path (i.e. the URL) on the webserver.

In a large webserver it is likely that the same web resources must be present in multiple versions. This is especially opportune for Javascript. Such web resources also have dependencies that are managed by a myriad of dependency systems that also interact like amd, commonjs, bower, npm, and ES6. Even with these solutions it requires a lot of manual care to support multiple versions of the same web resources.

The webserver therefore provides the possibility to wrap the web resources in bundles and use the OSGi dependency model to create a coherent set. This set can then be included as a single file in the web application’s HTML.This is called [web resources][9].

This example shows a project with a Javascript part and it demonstrates the web resource concepts. Look at [web resources][9] for a description of how to use this. It basically consists of a [simple application][10] and a w[eb resource][11].

[9]: http://enroute.osgi.org/services/osgi.enroute.webserver.capabilities.html
[11]: https://github.com/osgi/osgi.enroute.examples/tree/master/osgi.enroute.examples.webserver.webresource