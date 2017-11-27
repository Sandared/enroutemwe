---
title: Backend Application
layout: nested
description:
---
#  Backend Application

## GitHub Repository

Go to [GitHub](https://github.com/osgi/osgi.enroute.examples/tree/master/osgi.enroute.examples.backend.application)

## Description

This example helped a person that wanted to solve a problem in an elegant way but did not find appropriate pieces yet. He described the problem as follows:

	I want to create some abstraction for a little 
	data management system which should be connected 
	to different data backends at the same time 
	(e.g. S3, Dropbox, local/network filesystem, ...).

	Now let's consider a simple example of the 
	logic involving the following standard CRUD 
	operations (because I want to publish that 
	in a single ReST endpoint):

The example shows a solution to the classic _dispatch problem_. In this case we need to dispatch the operations on a BLOB (Binary Large Object). 