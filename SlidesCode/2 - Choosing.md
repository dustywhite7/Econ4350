---
marp: true
title: Topic 2 - Choosing the Right Visual
theme: default
class: default
size: 4:3
---

# Choosing the Right Visual

---

# The Art of Visualizing Data
- Storytelling is an art
- Visualization is a form of storytelling

---

> Why should we be interested in visualization? Because the human visual system is a pattern seeker of enormous power and subtlety. The eye and the visual cortex of the brain form a massively parallel processor that provides the highest-bandwidth channel into human cognitive centers.... If we can understand how perception works, our knowledge can be translated into rules for displaying information.... [W]e can present our data in such a way that the important and informative patterns stand out. If we disobey the rules, our data will be incomprehensible or misleading.


-- Colin Ware (*Information Visualization: Perception for Design*)

---

# Data is the art of storytelling
### Let's really make it ART

When we present data, we are trying to tell a story. 
- Kids prefer stories with illustrations, because they are only just learning about how the world looks and works
- Visualization aids unfamiliar audiences

Find a clear story to tell, and let your visuals help you tell it.

---

# The challenges of visualization

1. Dimensionality
    - We often have a lot of different features in our data
    - We can’t easily process more than 2 or 3 at once
2. Context
    - It can be hard to understand a figure’s context

---

# Classic Visuals

![w:950px](london.png)

---

# Classic Visuals

![bg left w:500](moneyball.png)

Our visuals should be
1. Aesthetically Pleasing
2. Novel
3. Informative
4. Efficient

---

# Aesthetically Pleasing

- Don’t let beauty overwhelm data
- Aesthetics should accentuate the information
- Familiar looks and feels can help!

---

# Novel

A visual can be novel in many ways:

- Novel Data
- Novel Insights
- Novel Presentation

<br>

> Most often, designs that delight us do so not because they were designed to be novel, but because they were designed to be effective -- Beautiful Visualization

---

# Informative

> A visual that [is not informative] has failed. -- Beautiful Visualization

**Ask**: What is the intended usage of our visual?

> My goal is to display ______ so that ______ can _______.

- What is our context of use?
- Is it for presentation or exploration?

Catering a visual to our audience ensures that they can quickly obtain the most valuable information.

---

# Informative

![w:850px](london.png)

---

# Efficient

> Irrelevant data is the same thing as noise. If it’s not helping, it’s probably getting in the way. -- Beautiful Visualization

- The minimum viable product concept is critical in visualization of data
    - Each new element slows your audience's perception of the important points
    - BUT! Don't omit critical components

---

# Efficient

![w:700](moneyball.png)

---

# An amazing visual

![w:850](periodicTable.png)

---

# So terrible...

![bg left 90%](periodicBad.png)

Maybe we do [this](https://github.com/d3/d3/wiki/Gallery) instead...

Or [this](https://python-graph-gallery.com/)?

Or anything else!


---

# Another atrocity

![w:850](worstViz.png)

---

# A template process

1. Write down your goal and intent for the visual
2. Gather the data that will help you achieve that goal
3. Decide how to tell your intended story with the data
4. Apply a visual representation of your data

---

# Visual Options in Tableau

Let's walk through this process to address the following question:

> How have global civil liberties changed over time?


---

# Visual Options in Tableau

We will explore the following charts:
1. Bar Chart
2. Histogram
3. Packed Bubbles
4. Line Charts (revisited)

And the following techniques:
- Grouping
- Aggregating
- Trend Lines