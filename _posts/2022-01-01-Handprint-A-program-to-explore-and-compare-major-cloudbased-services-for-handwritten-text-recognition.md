---
layout: presentation
type: talk 
startTime: 2022-05-25T16:25
speakers-text: Michael Hucka
categories: talks
day: 2
group: 7
spot: 3
time: 4:25 PM
speakers:
- michael-hucka
length: 15
slugTitle: handprint-a-program-to-explore-and-compare-major-cloud-based-services-for-handwritten-text-recognition
location: Auditorium 2120 A&B
title: Handprint&#58; A program to explore and compare major cloud-based services for handwritten text recognition
---
Several companies have developed machine learning-based methods for handwritten text recognition (HTR), and offer them as on-demand services. These network-based services can be applied to images of document pages without the need for training on samples of handwriting. The results are remarkably good overall, but there are differences in quality and features between the different offerings. Comparing the results produced by the competing services is complicated by the fact that they each have unique application programming interfaces (APIs). The purpose of Handprint (HANDwritten Page RecognitIoN Test) is to make comparisons simple and easy, without the need for users to learn how to program with the different APIs. Handprint is a command-line application that can invoke HTR services from (currently) Amazon, Google, and Microsoft. It accepts images in various popular formats, sends them over the Internet to the service providers, gathers the results, and then annotates copies of the images to show the results to the user. Handprint includes some additional, more advanced features, such as the ability to filter the displayed results by confidence scores, and a facility to compare text results to expected (ground truth) text. This presentation will summarize Handprint and its implementation, and provide some demonstrations of its use.