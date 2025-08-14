# AI-Learning-Playground

Building AI Course Project

## Summary

This is a tool for AI scholars where it first assesses users' personal interest and current code skill level through a short questionnaire (with coding test) and then offers personalized AI learning experience for users to improve and become professional AI developers.

## Background

As AI become wide-spread in our daily lives, more people would be interested in learning AI so that they will not fall behind or they can develop their own AI tools. However, people sometimes are not sure what kind of AI skills they should learn and what coding practice they should do to build that tool as soon as possible. I would to develop a tool for users to input their interest related to AI, and finishing some coding problems, so that the tool classifies what kind of AI they are building and what coding exercises they need. Users can have a personalized learning experience regarding building their own AI tools.

## How is it used?

Users should first answer a short questionnaire regarding their interest, which includes short response questions for them to explain their AI ideas. The tool will analyze their interest and their current coding skill level. A set of coding exercises will then be provided that fits into user's level and helps user to gain more coding skills so that they can turn their ideas into products quickly.

## Data sources and AI methods

I would have to collect data related to a person's coding experience and their coding skill level by myself. Regarding the user's interest, I can use a text transformer to analyze what their interest is from their response. For the user's coding skill level, I can build a classifier similar to KNN (or using unsupervised methods like K-means clustering) to determine what kind of coding exercises they should receive.

## Challenges

Not too much data would be available based on a user's coding experience and their coding skill level in AI. Also, the entire process should be focusing on using AI to assess user's interests and skills rather than using some fixed test problems.

## What next?

This tool should also allow users to creatively express their AI ideas and realize them, so that it not only teaches users about AI, but also learns from users regarding how to develop next-generation AI.

## Acknowledgments

- There are some other websites that offers AI classes online, like [Elements of AI](https://www.elementsofai.com/), but what I want to design is an experience that combines personal interest and professional guidance based on a user's interest and current code skill level.
- I retrieved the code files in this repository from a video on the Bilibili website. These files can be useful for designing AI coding exercises in this tool.
