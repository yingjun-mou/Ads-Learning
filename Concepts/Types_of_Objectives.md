# Types of Objectives

## What are the common advertising objectives
* awareness (impression, reach)
* engagement (clicks, likes)
* conversions (purchases, sign-ups)
* ROAS (short for return on ad spend)
* app installs (or app usage goals)

## CTR vs. CVR
CRT: click-through rate - number of people click on an ad or link over the number of times it was shown.
CRV: conversion rate - number of people completes a desired action (e.g. making a purchase) over the number of people who clicked on an ad or link.

## How does the objective affect ad ranking and selection?
The system will have different scoring and optimization algorithms based on the objectives. E.g. optimizing CTR for clicks vs. predicted conversion value for ROAS.

## What is conversion attribution and how does it relate to ad objectives?
Attribution models (e.g. last-click, linear, data-driven) determine how credit for conversions is assigned to ads, which directly impacts learning and optimization.

## How would you design a model differently if the objective is click-through rate vs. return on ad spend?
For CTR, you use binary labels(click or not) with a log-loss objective. For LOAS, you can use a regression model to predict value per impression and optimize accordingly.

## How can multi-objective optimization be used in ad ranking systems?
You are use multi-task learning or scalarization techniques to balance multiple objectives, such as CTR, CVR, and revenue, depending on the business needs.