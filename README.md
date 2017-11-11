# Bootcamp review site

## Overview

Bootcamp review site that organizes bootcamps based on voting.


## Goal
My goal for this project is to not make the next Facebook but rather to understand the process of taking a project from zero lines of code to a fully deployed web app. In order to learn the most from this project I will be documenting the entire process.



## Using behavioral-driven development

The first thing I want to do is to allocate enough time to planning the project. I will be using a combination of users stories organized from the most simple action I want the program to complete and growing in complexity. Next, I will match these user stories with specific technical specifications that I will test against.

Here are the steps for behavioral-driven development:

1. Describe the way our program should work
2. Start with the simplest Tasks
3. Then we add code to our program to accomplish these behaviors using automated Tests
4. Refactor code and repeat from step 1


> We are describing **what** the app should do and not **how** it should do it.

Interface before implementation - BDD requires me to think about the inputs and outputs of the program before building in the implementation.

## MVC - Minimal viable product

#### User Story

- User sees a list of bootcamps that have the most up-votes
- User can click on a bootcamp and see some details about the bootcamp including reviews
- User can log in to write a review for a bootcamp
- Logged in users can up-vote or down-vote bootcamps
- Logged in users can up-vote or down-vote reviews

# Design

> Base webiste on using CSS Grid if the browser doesn't support grid then serve mobile experience.

## Inspiration

[Product Hunt](https://producthunt.com)

![](/img/home.png)

## Elements to use

### [Grid layout](/css/grid-layout.md)

### Using `minmax()` with track sizing

Problem: When defining an explicit grid with `grid-template-columns` / `grid-template-rows` or automatically creating rows or columns, we want to give tracks a minimum size, but make sure they expand to fit any content that is added.
> For example if someone is writing a review we would want a minimum row and column width and height if they only write a small amount of text but want it to expand with the text if someone writes a lot.
