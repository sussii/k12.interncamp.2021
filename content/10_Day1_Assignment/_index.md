---
title: "Day1: Warm UP"
chapter: true
weight: 10
---

# Day1 Assignment

Day1 is for ramping up. No hurry. 

### Learning Objcetives
- Get familiar with AWS Products
- Set up development environment for the rest of days 
- Understand the application of TSP problem in real-world through research
- Onboarding to Quantum Computing

### Deliver Result
- 1 PPT Slide: Find at least 5 real scenarios for the application of TSP 
- 1 PPT Slide: Find at least 2 technologies for implementing quantum computing
- Demo: Successfully setup environment and launch the project UI in browser

---
#### Get Familiar with AWS Products

First, let's have an overview of AWS. Browse through [AWS Official Webpage](https://aws.amazon.com/). 

* [What is Cloud Computing](https://aws.amazon.com/what-is-cloud-computing/?nc1=f_cc)
* [AWS Cloud Products](https://aws.amazon.com/products/) 

In this two weeks, you will use three AWS Products. 

 * [Amazon WorkSpaces](https://aws.amazon.com/workspaces/) is used as a host to run the python project.
 * [Amazon SageMaker](https://aws.amazon.com/sagemaker/) is used for running the given Notebooks, where you learn algorithms step-by-step.
 * [Amazon Braket](https://aws.amazon.com/braket/) is used for accessing quantum computing resources. 



### Setup Development Environment

**Step 1**  : Download workspace client from https://clients.amazonworkspaces.com/.

**Step 2** : Log into Amazon WorkSpaces with the given registration code. (If you don't have the code, ask your mentor.)


{{% notice Note %}}
<p style='text-align: left;'>
The examples and sample code provided in this workshop are intended to be consumed as instructional content. The crendentials is given for camp learning experience, please do not share it with others.
</p>
{{% /notice %}}

**Step 3** : After login, you will see the desktop user interface. Now you are using a Amazon Linux system.

**Step 4** : Open a Terminal window.

**Step 5** : Execute the following commands in the Terminal to checkout project GitHub Repository and start running the project.
```
git clone  https://github.com/guming3d/TSP-workshop-Original.git
cd TSP-workshop-Original
pip3 install -r requirements.txt
python3 source/flask_app.py
```
**Step 6** : Open a web browser in the WorkSpace, visit http://127.0.0.1:5000, you should see a Web UI.

---
### Research about TSP Applications

### What Is the Traveling Salesman Problem?

The traveling salesman problem (TSP) is a problem that asks, with a list of stops and the distances between each of them, what is the shortest path/possible route that visits each location and returns to the origin?

figure_d1_1.png to be added!!! (AOYU)

For decades the TSP has been a challenge for many businesses that rely on route planning.

With just a starting point and a few stops, planning a route can seem complicated enough.

But once you start planning routes throughout the country, it reaches an almost unthinkable level of complexity.

This is what a route would look like if planned to every city in the US with over 500 inhabitants:

figure_d1_2.png to be added!!! (AOYU)

Just imagine the number of possible routes you could take when a single possible solution is this complex.

#### Why the Traveling Salesman Problem Is Still Hard to Solve in 2022

Mathematician Karl Menger discovered the TSP in 1930, over 90 years ago.

Since then, there have been many suggested solutions and algorithms. But they often struggle with the sheer scale, since the number of possible sales routes increases exponentially with each new stop.

And the truth is, real route planning in 2021 for real businesses is more complex than just a list of stops — making things even more complicated.

In the real world, it’s not as easy as simply finding the shortest route.

#### It’s not just about destinations and distance, there are many other factors in play

It’s not as easy as just taking a list of addresses and creating a route. 

A field sales rep, delivery driver, or technician also has to consider a lot of other factors, like time windows, vehicle capacities, and more.

#### Delivery time windows and planned sales meetings

What if your delivery drivers or salesperson have planned delivery times or sales meetings? Then it’s not enough to just consider the distance, you also have to factor in when they should be at each location.

This adds a whole new level of complexity, and is a challenge that most route planners simply can’t handle.

This particular instance of the problem is also known as the Vehicle Routing Problem with Time Windows (VRPTW). 

#### Required vehicle capacities or technician qualifications

For deliveries, each package that you plan for can have specific requirements in terms of shipping and handling, from refrigeration to unloading dimensions.

You also have to consider the overall loading capacity of each vehicle.

But even for maintenance and field service businesses, you have to consider the unique qualifications of each technician, and whether they match a job.

This is also known as the Capacitated Vehicle Routing Problem (CVRP).

#### Planning efficient routes that include both pickups and deliveries

If your business delivers any sort of reusable packaging or recyclable materials to your customers, chances are that reverse logistics are a huge priority.

To maximize the efficiency of your business, you want to integrate both pickup and delivery into all planned routes.

This adds another dimension and a level of complexity that most route optimization tools can’t handle.

This is also referred to as the Pick-up and Delivery Vehicle Routing Problem (PDVRP)

#### Considering priority of leads, existing clients, and deliveries

To run a business efficiently and keep VIP customers satisfied, you also need to make sure your staff prioritize things the right way.

If your routes don’t consider priority, every customer will be treated the same. So you risk alienating loyal customers if you suddenly switch to an automated solution that can’t handle that.

#### Balancing workloads between multiple drivers

Of course, when planning routes for multiple drivers, you also have to consider their workloads.

Drivers are only human, and have a maximum shift length of 14 hours and mandatory breaks.

What good is an “efficient route” if it’s not possible for a driver to handle it within the allotted time?

Good workload balancing tools will help you reduce overtime and cut driver costs, and make sure all drivers are HOS-compliant at all times.

Let's do some background research. Find at least 5 real-world problem related to TSP. You should be able to describe the use cases. 

---
### Onboarding to Quantum Computing

We will try to solve TSP problem with quantum computing(QC) resource in the second week. Today, we hope you get a basic concept of QC. 

* What is Quantum Computing? 
* Is Now the Right Time for QC? (30mins)
<a href="http://www.youtube.com/watch?feature=player_embedded&v=_ltGOs7aN3U
" target="_blank"><img src="http://img.youtube.com/vi/_ltGOs7aN3U/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="90" border="3" /></a>
* When will quantum computers become reality???

!!!!!!! video here

---
### For your reference (optional)
Do you know the latest event about AWS? 

* Checkout the [2021 Re:Invent](https://reinvent.awsevents.com/keynotes/?nc2=h_reik) , an annual event of AWS. 10-year Anniversary! 
* Adam Selipsky's Keynote (~2h)
<a href="http://www.youtube.com/watch?feature=player_embedded&v=WGA2P_oH5Xc
" target="_blank"><img src="http://img.youtube.com/vi/WGA2P_oH5Xc/0.jpg" 
alt="Adam Selipsky's session" width="120" height="90" border="3" /></a>