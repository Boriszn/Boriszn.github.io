---
layout: inner
title: 'Using swagger/swashbuckle .net core operation filters to enable API testing'
date: 2017-09-08 13:26:34
categories: API Swagger Swashbuckle
tags: C# Swashbuckle 
lead_text: 'The problem arises in solutions which contains identity servers based on OAuth2 and OpenId protocols (For example Identity Server, WSO2 identity cloud, etc) and Rest API with swagger swashbuckle used for auto documenting and testing. Each API call should contain authentication token otherwise testing API ("Try it out") will not work.'
---

The problem arises in solutions which contains identity servers based on OAuth2 and OpenId protocols (For example Identity Server, WSO2 identity cloud, etc) and Rest API with swagger swashbuckle used for auto documenting and testing. Each API call should contain authentication token otherwise testing API ("Try it out") will not work.

#### Solution

One of the option to enable API testing ("Try it out" button) is using swagger operation filter. In example below was created operation filter which includes Bearer authentication token field to HTTP header of each API calls.

[Complete article can be found here](https://boris-zaikin.blogspot.de/2017/09/using-swaggerswashbuckle-net-core.html "Complete article can be found here")

[Examples can be found here](https://github.com/Boriszn/DeviceManager.Api "Git project")