---
title: Lecture 4.1 - PowerQuery with Excel & PowerBI
layout: lecture
tags: 
  - data
  - powerbi
  - powerquery
  - hands-on
description: >-
  How to use PowerQuery for basic data manipulation.
date: 2025-09-18
---

<br><br><br>
# Quick intro to PowerQuery 

---

## Why use PowerQuery?

Short answer: PowerQuery is for when you need to modify your data in Excel before visualizing it.

notes:
so we saw from walkthrough 2 that using our data "as is" doesn't allow us to do what we want in power bi

so we need a way to transform our data

---

## Why use PowerQuery?

We want to take our data from this:
<img src="images/datapivoted.png" style='border:1px solid #000000'>

---

## Why use PowerQuery?

We want to take our data from this:
<img src="images/datapivoted.png" style='border:1px solid #000000'>

to this:
<img src="images/dataunpivoted.png" style='border:1px solid #000000'>

---

## Why use PowerQuery?

We want to take our data from this:
<img src="images/datapivoted.png" style='border:1px solid #000000'>

to this:
<img src="images/dataunpivoted.png" style='border:1px solid #000000'>

in order to "play nice" with PowerBI.

notes:
the technical term is that we are unpivoting our data or sort of "unwrapping it"

looking forward -- if we have our data like this then if we select a year/country pair, we get the number of corgis born over time in that combination

---

## What is PowerQuery?

notes:
so we are mostly going to learn by doing, but lets just look at a quick overview of the interface we'll be using

---

## What is PowerQuery?

<img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Power_Query_User_Interface.png">

notes:
there are 5 main sections of the powerquery interface

---

## What is PowerQuery?

<img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Power_Query_User_Interface.png" width="80%">

An [overview of the Power Query](https://en.wikipedia.org/wiki/Power_Query#/media/File:Power_Query_User_Interface.png) user interface, including
1. the ribbon 
2. the queries panel 
3. the data view 
4. the query settings, and 
5. the status bar

---

## What is PowerQuery?

<img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Power_Query_User_Interface.png" width="80%">

An [overview of the Power Query](https://en.wikipedia.org/wiki/Power_Query#/media/File:Power_Query_User_Interface.png) user interface, including
1. the ribbon $\leftarrow$
2. the queries panel 
3. the data view $\leftarrow$
4. the query settings, and 
5. the status bar

notes:
we'll spend most of our time clicking buttons in the top ribbon and the data view (and only look at the query settings in 4 to see a history of what we are doing)

---

## How to change the language

<img src="images/changingLanguageExcel.png" style='border:1px solid #000000'>
(on a Mac)

notes:
this is how it looks to change the language in Excel on a Mac, it might be a little different on a Windows or Linux machine

---

# Let's open up Excel and give it a try!