---
title: "Day2: Classical Method"
chapter: true
weight: 20
---

# Day2 Assignment

Day2 is coming

### Learning Objcetives
- Learn to use Amazon SageMaker to run notebooks
- Understand how TSP is solved with 3 different classical algorithms
- 

### Deliver Result
- 1 PPT Slide: Understand classical notebook for TSP（pyTSP）
- 1 PPT Slide: Research topic for 3-opt problem

---

#### Get Familiar with AWS Products

First, let's have an overview of AWS. Browse through [AWS Official Webpage](https://aws.amazon.com/). 

* [What is Cloud Computing](https://aws.amazon.com/what-is-cloud-computing/?nc1=f_cc)
* [AWS Cloud Products](https://aws.amazon.com/products/) 

In this two weeks, you will use three AWS Products. 

 * [Amazon WorkSpaces](https://aws.amazon.com/workspaces/) is used as a host to run the python project.
 * [Amazon SageMaker](https://aws.amazon.com/sagemaker/) is used for running the given Notebooks, where you learn algorithms step-by-step.
 * [Amazon Braket](https://aws.amazon.com/braket/) is used for accessing quantum computing resources. 


---

### Run Notebook in Amazon SageMaker


**Step 1**  : After logging into your AWS console and click the link for [Amazon SageMaker](https://console.aws.amazon.com/sagemaker/home?region=us-east-1#/notebook-instances/create)

**Step 2** : Next, let us create a notebook instance and fill the name with `k12-interncamp-tsp-classical`

![Notebook with name](/k12.interncamp.2021/images/notebook_name_classical.png)

**Step 3** Select Instance type. SageMaker provides multiple instance types of different computational power and prices. When creating an instance, we can specify the instance name and choose its type. we choose ml.c5.2xlarge. With 8-core CPU, this instance is powerful enough for most of our chapters.

**Step 4** Checkout the given GitHub Repo. A Jupyter notebook version of this book for fitting SageMaker is available at `https://github.com/xiaotinghe/TSP_Classical_Method`. We can specify this GitHub repository URL to let SageMaker clone this repository during instance creation.

![Repo link](/k12.interncamp.2021/images/repo_link_classical.png)

**Step 5** It may take a few minutes before the instance is ready. When it is ready, you can click on the “Open Jupyter” link.

![notebook ready](/k12.interncamp.2021/images/notebook_ready_classical.png)

**Step 6** After finishing your work, do not forget to stop the instance to avoid extra cost.

---
### Read through the Notebooks

Please read through the Notebook carefully. Make sure you run Notebook to view the result for each step. Remember to do exercises at the last of each notebook.

| No | The Given Classic Alorithms |
| ---|:-------------:|
| 1  | Nearest neighbor   |
| 2  | Nearest insertion  |
| 3  | 2-Opt  |

---
### Quantum Computing in the Industry

Let's look the quantum technology from IBM

* [The IBM Quantum State of the Union (30 minutes)](https://wx.mail.qq.com/ftn/download?func=3&key=9d99e661d02acf1eafea48613463323981c72e64366332394749570757020601045e4b5905010714565705561b020109544b50030054005d54525f5750521d391b12531218005d544f320e04162a70744237130058174754423512004206125604461209534367570b09084f5b13062d90f588d8181d656a3f38cab2082a4b2941026fec&code=bffa6c29&k=9d99e661d02acf1eafea48613463323981c72e64366332394749570757020601045e4b5905010714565705561b020109544b50030054005d54525f5750521d391b12531218005d544f320e04162a70744237130058174754423512004206125604461209534367570b09084f5b13062d90f588d8181d656a3f38cab2082a4b2941026fec&fweb=1&cl=1)

---
### For your reference (optional)
Traveling Salesman Problem Visualization
<a href="http://www.youtube.com/watch?feature=player_embedded&v=SC5CX8drAtU
" target="_blank"><img src="http://img.youtube.com/vi/SC5CX8drAtU/0.jpg" 
alt="Adam Selipsky's session" width="120" height="90" border="3" /></a>
