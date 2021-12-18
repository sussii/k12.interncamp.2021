---
title: "Day6-7: Project for Classical Methods"
chapter: true
weight: 50
---

# Day6-7 Assignment

Day6-7, try to replace the data source with 10 cities in China, and then use 3-opt algorithm to solve the TSP problem in the project

### Learning Objcetives
- Get familiar with pyTSP project
- prepare data for the rest of days 

### Deliver Result
- Demo: Successfully implement 3-opt algorithm on chinese data and launch the project UI in browser

---

### Replace the data source with 10 cities in China

**Step 1**  : Open the data file in the project: `TSP-workshop-Original/data/cities.json`

**Step 2**  : Find the longitude and latitude coordinates of 10 cities in China on the Internet and 

**Step 3**  : Replace longitude and latitude coordinates and city name in the `cities.json`

### Implement 3-opt algorithm in project

**Step 1**  : Open the code file in the project: `source/algorithms/local_optimization.py`

**Step 2**  : Implement 3-opt algorithm in the `opt3` function in `local_optimization.py`. You need to return a `tours` variable, which is a nested list. The outer layer is the output of each iteration, and the inner layer is the list of routes. For example:

```
tours = [[6, 5, 4, 3, 2, 1],
         [2, 3, 5, 4, 1, 6],
         [4, 6, 3, 2, 1, 5],
         [1, 2, 3, 4, 5, 6]]
return tours
```

Where `[2, 3, 5, 4, 1, 6]` is the result of the second iteration and `[1, 2, 3, 4, 5, 6]` is the result of final iteration.

---
### For your reference (optional)
Do you know the latest event about AWS? 

* Checkout the [2021 Re:Invent](https://reinvent.awsevents.com/keynotes/?nc2=h_reik) , an annual event of AWS. 10-year Anniversary! 
* Adam Selipsky's Keynote (~2h)
<a href="http://www.youtube.com/watch?feature=player_embedded&v=WGA2P_oH5Xc
" target="_blank"><img src="http://img.youtube.com/vi/WGA2P_oH5Xc/0.jpg" 
alt="Adam Selipsky's session" width="120" height="90" border="3" /></a>
