[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/skJdUf3s)
# Principles of Programming and Programming Languages
# Mini-Project

See [instructions.md](instructions.md) for submission instructions.

# Big Step Mutable State Arrays

## Description

For this project, we change the Small-Step Operational Semantics from review 35 into Big-Step Operational Semantics. For the first part of the project, we needed to explain what the judgement forms for Addr Value, Array Index Location, as well as the definition of memories were. In the video, we talk about why it’s necessary for addresses to be valid (mapping to a value v) and for memory lookups to retrieve the correct value in order to make Big Step evaluations. 

We decided to go over the Mutable State: Describing Arrays section of the review because we felt like it was something that could really help me understand the topics covered in unit five. So then to make it something new and original, we described the big step semantics and how they were different from the small step.

In the final step we went over the code execution of this big step implementation. Most of it used what was previously made in the review. However using the previous rules that we had made it was easy enough to translate it over to be big step. For instance changing from a mapFirstWith to a standard map function. There was also the concern of how to take care of the memory properly now that we had big step but this was all written out in our rules.


## Building and Testing Instructions

NONE

## Presentation

TODO: Update the following links and remove this line.

- YouTube: https://www.youtube.com/watch?v=31prcY01JKA&list=PLFNbBlDoHwn7H43FCfZqpgr1xgRmmYkkq&index=2&ab_channel=DanielDesmond
- Script: Resources/PPL Extra Credit Script .pdf
- Recording: TOO BIG FOR GITHUB UPLOAD YOUTUBE LINK IS INCLUDED
- Slides: ./Resources/35.2.3 Big Step Operational Semantics.pdf
