---
layout: inner
title: 'Using swagger/swashbuckle .net core operation filters to enable API testing'
date: 2017-11-20 15:26:34
categories: blog development
tags: C#, Multi-Tenant architecure, UnitOfWork, Repository
lead_text: 'Businesses need to grow in order to be successful and handle an increasing number of clients and partners, and if a company is not ready to respond to this load then there is a big chance that opportunities will be missed.'
---

Businesses need to grow in order to be successful and handle an increasing number of clients and partners, and if a company is not ready to respond to this load then there is a big chance that opportunities will be missed. This brings the topic of scalability into the game, as one of the main requirements that a company should address. One of the possible ways to address this requirement is to build a multi-tenant solution. And as this topic gains more importance, lots of options are available to achieve this, for example, using Microsoft Elastic database (elastic tools). However, in particular cases, like the case I faced on my project, not all of the product requirements could be satisfied with the available options. This brought me to the idea of gathering my experience on this topic and presenting it below.

As we all are aware, there are two main approaches to tackling application scaling – horizontal and vertical. Horizontal scaling will bring you the benefit of scaling on the fly and will imply dealing with multiple databases, as each tenant has its own database/shard. The vertical approach to scaling presumes that you have one database that serves several tenants.

In my article, I will address the approach of horizontal scaling with a step-by-step guide on how to build a multi-tenant web API application.

[Complete article can be found here](https://dzone.com/articles/multi-tenant-api-based-on-swagger-entity-framework-1 "Complete article can be found here")

[Git project](https://github.com/Boriszn/DeviceManager.Api "Git project")