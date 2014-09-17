---
layout: post
title : What is Resoursea
description: Resoursea - resource based services
author:
  name: Rafael Henrique Moreira
  email: rafadev7@gmail.com
  url: http://resoursea.com/
  github: rafadev7
  twitter: rafadev7
tags : [concept]
reference: 
---
It is a new way of thinking about web services.

The REST proved the main architecture used for developing web services for its simplicity and scalability fitting perfectly to the current architecture of the web. As Fielding wrote in his doctoral dissertation: REST is how the web should work.

Fielding proposed a set of architectural principles for design services with a focus on resources, including how they are addressed and transferred through the HTTP protocol for a wide range of clients written in different languages​​.

However, there is no current tool on the market that allows a level of abstraction that allows you to focus only on resources and service offered.

It's time to think different. Automating the creation of the whole software agent that communicates over the network. Yes, there is already a better way of doing this. Why reinvent the wheel? Thus we focus only on the resources offered and how they are offered and let the agent providing this resource on the network.

We can no longer create services the old way. Today the services need to be scalable and automatically adapt to user demand. The easiest way to achieve scalability in the server component is by adding one more constraint: it is not allowed to store session states on the server, it's a stateless-server.

To achieve this we need to store all the session state entirely on the client and always pass all the necessary information to process the request to the server. This is the model already used by large companies such as Google, Facebook and Twitter.

In this way the bottleneck of service becomes the access to state of the resource, for this problem there are already techniques such as replication and mirroring that work very well.

In a resource based service only the state of resources is transferred between the agents, in other words, the value of their properties. The service may serialize their structures in JSON, XML or both, allowing a wide range of applications written in different languages ​​to consume their resources.

Ok, big companies have shown that REST is a good architecture to provide scalable services for a wide range of customers. But if the service I am offering are resources and their states, so why do I need to worry about the implementation of a whole web server? Why is there no tool that allows me to focus on only the resources and how they are provided?

Think about the resources of a resourcebased service is not just limited to the resources provided by the service to its clients. All necessary components to process the request can be thought as resources that are injected layer-by-layer until you have everything you need to answer the request.

Of this need was born the Resoursea. With it you focus only on resources and how they are provided and the tool takes care of automatically deploy a Web agent that can provide this resource through an REST interface.

And the advantages do not stop there. Besides automating the deployment of the the web service, you also has a high software reuse through the sharing of components already created by the community.

Consider an instance of the database, most services require this resource to process the request. This resource and its behavior not need to be implemented by all the developers. It is much better if everyone uses and contribute with just one package. Thus we'll have stable and secure packages with resources to suit most of the needs. Allowing the exclusive focus on particular business rule, of your service.

To cut costs the infrastructure has to be shared and your service should be scaled only with the increase in traffic. All this can be automated by the architectural style being implemented. The tool will be able to generate detailed reports of the use of the resources and which are consuming more computational resources and need to be optimized.

Again, it is a new way of thinking about web services. Resoursea is a new layer of abstraction that hides the difficulties of implementation of efficient and scalable agents who can provide the resources on the web. Design your resources and how they should behave, and using one command it is already in the cloud and accessible worldwide.

Reducing the complexity of software components that need to be designed is possible to use more accurate metrics of the software engineering and have greater predictability of costs and development time of the system. Furthermore, simpler components to be implemented results in faster implementation and algorithms with more readability and maintainability.

This is just the beginning and we know that has a lot that needs to be done, but the project is ready and we know it's viable. The main reason for this website is to share this idea and create a community interested in maintaining this project.

The automation of the process for creating web services can be a very profitable tool in no time. Reducing the costs of design and development of software giving a very big advantage over other companies. Contribute to a project like this, besides developing your programmer abilities and teamwork, can become your main source of income.

You can engage the community by signing the [mailing list](https://groups.google.com/d/forum/resoursea) and contributing to the [repositories on github](https://github.com/resoursea/).

