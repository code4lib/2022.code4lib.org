---
layout: presentation
type: workshop
categories: workshops
full: false
learning-outcomes: How to think about monitoring, How to automate and maintain your monitoring infrastructure, How to deal with alert fatigue.
attendee-requirements: We expect attendees to be System Administrators of Linux based servers with comfort with use of the command line interface.
max-attendees: 24
startTime: 1:30pm
endTime: 4:30pm
time: pm
location: hayes-hall
room:
speakers:
- francis-kayiwa
- alicia-cozine
- james-griffin-iii
- bess-sadler
speaker-text: Francis Kayiwa, Alicia Cozine, James Griffin III, Bess Sadler
title: Belt and Suspenders&#58; Crafting Full Coverage Monitoring for Library Applications
---
We use the term "monitoring" to describe a collection of components that make up a system comprised of fault detection, metric collection, analytics, visualization, and notification. We will talk about our composable system, with modular design, combining several tools to fulfill the functions of each component.

We will look at how we use Sensu, an open source monitoring tool designed for today’s systems and Datadog (we will address budget neutral alternatives). Sensu is commonly referred to as "the monitoring framework," allowing its users to compose a monitoring system to meet their unique demands. Sensu provides a monitoring agent, transport, event processor, HTTP API, etc.  Datadog is an extensive, easy-to-use platform for understanding your infrastructure.

In this presentation, we will discuss each component of a modern monitoring system, comparing several approaches to each of them. We will also cover the advantages and disadvantages of specific tool architectures, talk about Sensu and Datadigs approach to monitoring.
