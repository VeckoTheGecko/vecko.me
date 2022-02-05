---
title: "Solving sudokus using depth first search"
date: 2022-02-07T08:00:00+08:00
author: Nick Hodgskin
draft: false
maths: false # Bool. Katex support

# Organisation
tags: [Python, YouTube] # Relevant tags
categories: Projects # Category (only 1 category allowed)
series: # Optional
thumbnail: # URL to post thumbnail

# Linking
github: https://github.com/VeckoTheGecko/sudoku-solver # Optional: URL for specific GitHub repo
youtube: https://www.youtube.com/watch?v=RlJN6F4copU # Optional: URL for specific YouTube video from the channel

summary: # Optional
slug: sudoku-solver
---

I've never been much of a sudoku fan, but ever since I've started coding I've wanted to create a program that is able to solve them. I found out it was a bit of a tall ask for a newbie programmer a few years ago, but stumbling across my failed attempt, I decided to give it another go.

This time the goal not only to make a program to solve sudokus, but also to give consideration to the style of the code. By structuring my code using object oriented programming, it allows the code to be expanded upon down the line without refactoring everything. The separation between the view and logic of the application would allow views to be used, and even allows the logic to be switched out in a way that also enables sudoku variants.

In the algorithmic portion of the code, I used a backtracking/depth first search algorithm in order to solve the sudokus. Although not the most efficient way to solve a sudoku, it still works to solve the grid in a fraction of a second!

{{< youtube RlJN6F4copU >}}
