---
title: "Day6-7: Project for Classical Methods"
chapter: true
weight: 50
---

# Day6-7 Assignment

Day6-7, try to replace the data source , and then use 3-opt algorithm to solve the TSP problem in the project

### Learning Objcetives
- Replace the original data with other cities (<10), like cities in China
- Add two buttons for classical and quantum methods
- Add 3-opt algorithm for TSP with new data

### Deliver Result
- Demo: Successfully implement 3-opt algorithm and launch the project UI in browser
![demo.exmple](/k12.interncamp.2021/images/demo.png)

---
### Install the vs-code for the remaining project

**Step 1**  : Go to the [website](https://code.visualstudio.com/download) and download the right version for your system. Here, you should choose .deb for your Ubuntu system.

### Replace the original data with other cities (<10), like cities in China

**Step 1**  : Execute the following commands in the Terminal to pull latest project code

```
cd TSP-workshop-Original
git pull -f
```

Note: This will lose all current code changes.

**Step 2**  : Find the longitude and latitude coordinates cities on the Internet. (Hint: Take cities in China for instance,  `https://github.com/88250/city-geo`)

**Step 3**  : Replace longitude and latitude coordinates and city name in `data/cities.json`.

![cities.json](/k12.interncamp.2021/images/cities.png)

You need to replace each red box.

### Add two buttons for classical and quantum methods

**Step 1**  : Open the html file in the project: `source/templates/index.html`

**Step 2**  : Ref to `source/templates/index.html#L68`, add a button to call the 3-opt. You need to add the following actions for the button:

`onclick="tourConstruction('opt_3')"` 

### Add 3-opt algorithm for TSP with new data

**Step 1**  : Open the python file in the project: `source/algorithms/local_optimization.py`

**Step 2**  : Implement 3-opt algorithm in `_custom_algorithm` function in `local_optimization.py`. You need to return a `tours` variable, which is a nested list. The outer layer is the output of each iteration, and the inner layer is the list of routes. 

For example:

```
tours = [[6, 5, 4, 3, 2, 1],
         [2, 3, 5, 4, 1, 6],
         [4, 6, 3, 2, 1, 5],
         [1, 2, 3, 4, 5, 6]]
return tours
```

Where `[2, 3, 5, 4, 1, 6]` is the result of the second iteration and `[1, 2, 3, 4, 5, 6]` is the result of final iteration.


---
### Videos for better understanding quantum annealing

We have prepared some videos for you to better understand quantum annealing technology

* [D-Wave Customer Applications Quantum Computing Qubits 2021 (13 minutes)](https://wx.mail.qq.com/ftn/download?func=3&key=cf9abe368478c411fde9193660313936b6b23f1362313936154a0f0f52060b0456501a0453520b1b04560e014f500904534803030109080f01530e0503010136491102454c52565b1d211a6103475c166400545e0c5e5559571c176312555842554567440d554c554445724e12505745590a59164c5c490224f9d0b7f3d039d809602671e347b9af8fccc5565b&code=0e76b196&k=cf9abe368478c411fde9193660313936b6b23f1362313936154a0f0f52060b0456501a0453520b1b04560e014f500904534803030109080f01530e0503010136491102454c52565b1d211a6103475c166400545e0c5e5559571c176312555842554567440d554c554445724e12505745590a59164c5c490224f9d0b7f3d039d809602671e347b9af8fccc5565b&fweb=1&cl=1)

* [D-Wave Technology Update Product Expansion  (1.7 hours)](https://wx.mail.qq.com/ftn/download?func=3&key=cf9abe368478c411fde9193660313936b6b23f1362313936154a0f0f52060b0456501a0453520b1b04560e014f500904534803030109080f01530e0503010136491102454c52565b1d211a6103475c166400545e0c5e5559571c176312555842554567440d554c554445724e12505745590a59164c5c490224f9d0b7f3d039d809602671e347b9af8fccc5565b&code=0e76b196&k=cf9abe368478c411fde9193660313936b6b23f1362313936154a0f0f52060b0456501a0453520b1b04560e014f500904534803030109080f01530e0503010136491102454c52565b1d211a6103475c166400545e0c5e5559571c176312555842554567440d554c554445724e12505745590a59164c5c490224f9d0b7f3d039d809602671e347b9af8fccc5565b&fweb=1&cl=1)