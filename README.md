gorest-hooks
============

Go REST Hooks

## Background

I've been doing systems integrations for a long time.  But I've never had the budget to leverage fancy ESB's
or message queues.  And depending on your perspective, that may be a good thing.

It's no secret that the cloud is transforming (no integrations pun intended) how we do things.  So I've been 
thinking about how I might leverage the cloud to make my integration tasks easier, more scalable and fault
tolerant.

A few weeks ago I stumbled upon this blog [post](https://zapier.com/engineering/introducing-resthooksorg/) about [REST Hooks](http://resthooks.org/).  The concepts behind 
RESTful hooks are not complicated. But getting the individual components (e.g. authentication, multi-tenancy,
subscriptions) working together in a cohesive, robust fashion is a bit more challenging.

## Goals 

* Multi-tenant. 
* Pluggable architecture.
* Write some Go!

## Components 

* Authentication/Authorization
* Customer setup
* Subscriptions
* Publications
* Event Processing
* Misc.

## Acknowledgments

* [Zapier](https://zapier.com/)

### TODO's

* 
