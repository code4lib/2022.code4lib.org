---
layout: presentation
type: talk 
startTime: 2022-05-25T13:30
speakers-text: Niqui O'Neill
categories: talks
day: 2
group: 6
spot: 1
time: 1:30 PM
speakers:
- niqui-o'neill
length: 15
slugTitle: replacing-traditional-storage-of-structured-information-with-github-and-jekyll
location: Auditorium 2120 A&B
title: Replacing traditional storage of structured information with GitHub and Jekyll
---
This presentation will talk about how we were able to build a web application that uses stored data without a built in database. At the beginning of 2020, we were looking for a low barrier of entry way to allow users to create W3 Web Annotations. Annotations are stored in JavaScript Object Notation (JSON) format, a form of structured data. Instead of saving the JSON object into a database that would require continued maintenance, we looked to GitHub to give each user a personalized repo to save their JSON objects that would exist independent of the application. Each repo contains a Jekyll site where the JSON objects are written. The Jekyll site is hosted using GitHub pages, allowing users to have persistent URLs to all their objects, and providing the user with complete ownership of their content. Using Jekyll and GitHub has allowed for each site to have an automatically updating API which is used for the web application, and allows for structured data outside the JSON object to be easily accessible. This allows for more traditional access to data, similar to that of a database. The presentation will provide insights into how the system was structured, how everything interacts, along with the benefits and drawbacks.