---
title: JSON RPC
layout: nested
description:
---
#  JSON RPC

## GitHub Repository

Go to [GitHub](https://github.com/osgi/osgi.enroute.examples/tree/master/osgi.enroute.examples.jsonrpc.application)

## Description
REST APIs are fantastic until they are not. Though they definitely have a role to play in modern distributed system they do suck when two closely tied parties have to interact on the details. At that level, a significant time is lost on designing URLs, parameters, and payload formats and making sure Roy Fielding does not get upset. This is especially true when you have a Javascript front-end that needs to collaborate with a Java/OSGi back-end. This is very chatty and mapping it to a RESTful API is about as pleasant as doing tax returns.
The OSGi enRoute JSON RPC is therefore a relief. It is based on the simple idea that the public methods on an OSGi service should be available on a Javascript object. So adding a method to the service makes it immediately available in Javascript without having to worry for three days if the arguments should be passed in the URL, the parameter, or the payload. Quite productive!
Though the beaming up of the methods is extremely pleasant, it does cause a bit of a problem in initialization before those methods have arrived. This example shows you in detail how to setup the Angular initialization code to make it work.