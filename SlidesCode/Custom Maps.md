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

1) Want to create a map of regions not included in Power BI's default database
2) Want to create a map of events in a custom space (a sports venue, grocery store, etc.)

---

# Mapping Regions

Power BI allows us to map states within the US. Sometimes we want to map a different set of geographic entities, though.

---

# Finding the Information

In order to add regions to a map of the US, we need to find a way to access those details. Often, they will be stored in one of two ways:

- Shapefiles
- GeoJSON objects/files

---

# Finding the Information

[Mapstarter](http://mapstarter.com/) is where we can go to get some basic maps that we will be able to edit and reshape

[mapshaper](https://mapshaper.org/) is where we can edit those files to make the map that we need

---

# Regional Data

[US Census Regions](https://www2.census.gov/geo/pdfs/maps-data/maps/reference/us_regdiv.pdf)

[Some regional data](https://data.census.gov/cedsci/table?q=United%20States&tid=ACSDP1Y2017.DP05&vintage=2017&layer=state&cid=DP05_0001E). We just need to select the regions that we want to map (the 4 main census regions for now) and export the data

---

# Mapshaper

1) Use the select tool to click on all of the states belonging to a specific region
2) Use split to separate those states into a new layer
3) Rename that layer
4) `--dissolve` each layer in the console
5) `merge-layers` in the console. Our command looks like this: `merge-layers target=West,South,Midwest,Northeast force`

---

# Mapshaper continued

6) Add a region field to the map: `each region=region`
7) Edit each region field to reflect the name of the region
8) Export the resulting map to "TopoJSON" format for Power BI

---

# Putting it into Power BI

Now that we have some more useful geographic data, we need to incorporate it into Power BI. Let's move over to Power BI now and check it out!

---

# Summary

If Power BI doesn't have the geographic data we want already, but we can find that data, we can use the imported geographic data to create the visuals that we need!

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
- Let's switch back to Power BI

---

# Summary

We can create maps out of locational data, whether or not it is geographic.
- Map athletic events!
- Create a map of your store, what items are on what shelves, and start to visualize sales! (an example of the [Chicago Field Museum Map](https://arcataroger.github.io/openlayers_indoor_map/#))
- Our limitations are knowing the shape of an area, and knowing where things are at
    - If we know this, we can map it!