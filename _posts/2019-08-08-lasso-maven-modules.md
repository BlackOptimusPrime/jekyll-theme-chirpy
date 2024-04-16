---
title: Lasso Maven Modules
description: Description of modules goes here.
author: cotes
date: 2019-08-08 11:33:00 +0800
categories: [Modules]
tags: [maven]
pin: true
math: true
mermaid: true
image:
  path: /commons/devices-mockup.png
  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
  alt: .
---

Note: For up-to-date information, have a look at the modules [here](https://github.com/SoftwareObservatorium/lasso/blob/main/pom.xml)

- pom.xml - parent POM of all modules (sets global properties and versions)
- evosuite-maven-plugin - customized version of EvoSuite's maven plugin
- randoop-maven-plugin - customized version of a Randoop's maven plugin
- lasso-maven-extension - LASSO's Maven Spy for maven-based test drivers (reports events etc.)
- ranking - Ranking module that offers preference-based ranking of software components based on multiple objectives
- crawler - LASSO's Maven Artifact Crawler
- analyzer - LASSO's Maven Artifact Analyzer (index creation etc.)
- index-maven-plugin - LASSO's plug in to index any (built) maven-managed projects
- core - Core module shared with other LASSO modules (mainly contains common data models, interfaces etc.)
- lql - LASSO's Query Language (describing interfaces and method signatures)
- datasource-maven - Query layer for LASSO's executable corpus
- sandbox - LASSO's sandbox execution environment based on Docker containerization
- lsl - LASSO's domain language (pipeline language)
- benchmarks - Temporary module that integrates various (LLM) benchmarks
- gai - contains interfaces for generative AI (e.g., OpenAI API etc.)
- engine - LASSO's workflow engine and actions API
- arena-support - Arena support module (shared classes)
- arena - LASSO Arena module (arena test driver)
- worker - LASSO's cluster worker application (web-based using spring-boot)
- webui - LASSO's next-generation web application based on Angular 16 and Material
- service - LASSO's cluster service and manager (web-based using spring-boot)
- lasso-llm - Companion module to benchmarks (facilities to integrate generated code obtained by MultiPL-E experiment)
