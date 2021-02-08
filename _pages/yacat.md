---
 layout: default
 title: YaCat
 permalink: /yacat/
---
 
# YaCat

Yacat is a side project. It is the abbreviation for *Yet Another Cloud Automation Tools*. It was created to automate and accelerate access to the cloud through an interface for building and executing docker workloads as well as terraform.

This tool is also designed to host marketplaces. The tool is designed to be fully multi-tenant and in SaaS. The base of the product is made to be totally Cloud Agnostic but can be subsequently implemented in a cloud through Kubernetes layers

The project is mainly written in golang. The front for its part is created so as not to host any intelligence. It is therefore fully replaceable by another technology.


The heart of the project is a Rest API allowing to interact with all the available sub-bricks (Database, file storage, registry or even cache system). The project is fully configurable through a configuration file allowing you to consume a registry or a database.

As far as possible, the project respects the [12FactorApp](https://12factor.net/).