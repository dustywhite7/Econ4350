---
marp: true
title: Topic 5 - Custom Maps
theme: default
class: default
size: 4:3
---

# Making Custom Maps

---

# Why?

Sometimes the maps that are available aren't enough for what we want. Fortunately, we have several ways to create **custom** maps to suit our needs.

---

# Some examples

1) Want to create a map of regions not included in Tableau's default database
2) Want to create a map of events in a custom space (a sports venue, grocery store, etc.)

---

# Mapping Nepal

Tableau has 5 development regions within Nepal that are available to map:
- Far West, Midwest, West, Central, and East

What if we wanted more refined control over data in Nepal?

---

# Finding the Information

In order to add detail to a map of Nepal, we need to find a way to access those details. Often, they will be stored in one of two ways:

- Shapefiles
- GeoJSON objects/files

---

# Finding the Information

[Nepal Shapefiles Link](https://data.humdata.org/dataset/admin-shapefiles-of-nepal-mofald)

---

# Putting it into Tableau

Now that we have some crazy detailed geographic data, we need to incorporate it into Tableau. Let's move over to Tableau now and check it out!

---

# Summary

If Tableau doesn't have the geographic data we want already, but we can find that data, we can use the imported geographic data to create the visuals that we need!

---

# Mapping without Maps

Sometimes, we want to map data that isn't really a map, but kind of is.
- This would really make more sense with an example...

---

# Mapping the Women's World Cup Final!

Let's map out the locations of various events in the Women's World Cup final from 2019 (wow that feels like a lifetime ago...)

---

# Mapping the Women's World Cup Final!

In this case, we don't have geographic information, per se, but we do have the coordinates on the soccer pitch at which each event occurred.
- We will use that information to create a map of the game!
- Let's switch back to Tableau

---

# Summary

We can create maps out of locational data, whether or not it is geographic.
- Map athletic events!
- Create a map of your store, what items are on what shelves, and start to visualize sales!
- Our limitations are knowing the shape of an area, and knowing where things are at
    - If we know this, we can map it!