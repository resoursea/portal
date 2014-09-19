---
layout: post
title : What is Resoursea ?
description: Resoursea is an open source framework that provides a resource based service through an REST interface.
author:
  name: Rafael Henrique Moreira
  email: rafadev7@gmail.com
  github: rafadev7
  twitter: rafadev7
tags : [introduction]
reference: 
---
It is a new way of thinking about how we write web services.

The REST has become the main architecture used for developing web services for its simplicity and scalability, fitting perfectly to the current architecture of the web. As Fielding wrote in his doctoral dissertation: REST is how the web should work.

Fielding proposed a set of architectural principles for design web services with a focus on resources, including how they are addressed and transferred through the HTTP protocol for a wide range of clients written in different languages​​.

However, there is no current tool on the market that allows a level of abstraction that allows you to focus only on the resources and how they are served.

It's time to think differently. The best techniques for creating web servers are already known and they need not to be re-implemented everytime we need to create a web service. With an efficient and scalable open source web server that can provide resources through a REST interface we can focus on only the resources and how they are served. We need a framework for implementing web services as fast as our needs.

We can no longer create services the old way. Today the services need to be scalable and automatically adapt to user demand. The easiest way to achieve scalability in the server component is by adding one more constraint in the server component: it is not allowed to store session states on the server. It's a architectural style is called Client-stateless-server.

To achieve this we need to store all the session state entirely on the client and the client always has to pass to the server all the necessary information to process the request. This is the model already used by large companies such as Google, Yahoo!, Facebook and Twitter.

In this architectural style the bottleneck of the service becomes the access to the state of the resource, for this problem there are already techniques such as replication and mirroring that works very well.

In a resource based service only the state of resources is transferred between the agents, in other words, the value of their properties. The service may serialize their structures in JSON, XML or both, allowing a wide range of applications written in different languages ​​to consume their resources.

Ok, big companies have shown that REST is a good architecture to provide scalable services for a wide range of customers. But if the service I am offering are resources and their states, so why do I need to worry about the implementation of a whole web server? Why is there no tool that allows me to focus on only the resources and how they are served?

Thinking in a resource based service is not limited to the resources provided by the service to its clients. All necessary components to process the request can be thought as resources that are injected until you have everything you need to answer the request.

Of this need was born the Resoursea. With this tool you focus only on resources and how they are served and the tool takes care of automatically deploy a web server that can provide this resource through an REST interface.

And the advantages do not stop there. Besides automating the deployment of the the web service, you also has a high software reuse through the sharing of components already created by the community.

Think about a resource used by virtually all web services, like an instance of the database. Most web services require this resource to process the request. This resource and its behavior not need to be implemented by all the developers. It is much better if everyone uses and contribute with just one package that contains this resource. Thus we'll have stable and secure packages with resources to suit most of the needs. Allowing the exclusive focus on particular business rule, of your service.

Thinking about the infrastructure, your service can be served by a secure and cheap cloud. This cloud that can cut the costs the infrastructure by sharing hardware resources and scaling your service only with the increase in traffic. All this services can be automated by the architectural style being implemented. The cloud will be able to generate detailed reports of the use of the resources and which are consuming more computational resources and need to be optimized or scaled to offer a better service.

Again, it is a new way of thinking about web services. Resoursea is a new layer of abstraction that hides the difficulties of implementation of efficient and scalable web servers that can provide your resource based service through an REST interface. Design your resources and how they should behave, and using one command it is already in the cloud and accessible worldwide.

Reducing the complexity of software components that need to be designed is possible to use more accurate metrics of the software engineering and have greater predictability of costs and development time of the system. Furthermore, simpler components to be implemented results in faster implementation and algorithms with more readability and maintainability.

This is just the beginning and we know that has a lot that needs to be done, but the project is ready and we know it's viable. The main reason for this website is to share this idea and create a community interested in maintaining this open source project.

The automation of the process for creating web services can be a very profitable tool in a little time. Reducing the costs of design and development of software gives a very big advantage over other companies. Contributing to a project like this, besides developing your programmer abilities and teamwork, can become your main source of income.

You can engage the community by signing the [mailing list](https://groups.google.com/d/forum/resoursea) and contributing to the [repositories on github](https://github.com/resoursea/).
