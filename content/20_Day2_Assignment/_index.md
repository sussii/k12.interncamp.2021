---
title: "Day2: Classical Methods"
chapter: true
weight: 20
---

# Day2 Assignment

In Day2, we start diving deep into algorithms. If you happen to choose Computer Science(CS) in the future, you will do a lot of homework like today --- learning different kinds of algorithms. If you don't choose CS, today's work can also give you a sense of programming -- It will be useful anyway!

### Learning Objcetives
- Learn to use Amazon SageMaker to run notebooks
- Understand how TSP is solved with different methods

### Deliver Result
- 1 PPT Slide: Compare the given algorithms in the Notebook and understand how they work for TSP.
- 1 PPT Slide: Investigate on 3-opt  
- Code Ready: Try your best to complete the exercises. We know that they are quite challenging!

---

### Run Notebook in Amazon SageMaker


**Step 1**  : After logging into your AWS console, search and access [Amazon SageMaker](https://console.aws.amazon.com/sagemaker/home?region=us-east-1#/notebook-instances/create)

**Step 2** : In SageMaker console, on the left, find "Notebook instances". Let's "Create notebook instance". Give the instance name as `k12-interncamp-tsp-classical`

**Step 3** Select Instance type. SageMaker provides multiple instance types of different computational power with different prices. When creating an instance, we can specify the instance name and choose its type. In this project, we choose ml.c5.2xlarge. With 8-core CPU, this instance is powerful enough for most of our chapters.

![Instance Name](/k12.interncamp.2021/images/repo_link_classical.png)

**Step 4** Clone an GitHub Repository that we prepared for you. A Jupyter notebook version of this book for fitting SageMaker is available at `https://github.com/xiaotinghe/TSP_Classical_Method`. SageMaker will clone this repository during instance creation.

![Repo Link](/k12.interncamp.2021/images/notebook_name_classical.png)

**Step 5** It may take a few minutes before the instance is ready. When it gets ready, you should be able to click on the “Open Jupyter” link.

![notebook ready](/k12.interncamp.2021/images/notebook_ready_classical.png)

**Step 6** After finishing your work, do not forget to stop the instance to avoid extra cost.

---
### Read through the Notebooks

Please read through the Notebook carefully. Make sure you run the Notebooks and view the result for each step. Remember to do exercises at the end of each notebook.

| No | The Given Classic Alorithms |
| ---|:-------------:|
| 1  | Permutation   |
| 2  | Nearest neighbor   |
| 3  | Nearest insertion  |
| 4  | 2-Opt  |

---
### Quantum Computing in the Industry

Watch one video about the quantum technology from IBM

* [The IBM Quantum State of the Union (30 minutes)](https://wx.mail.qq.com/ftn/download?func=3&key=9d99e661d02acf1eafea48613463323981c72e64366332394749570757020601045e4b5905010714565705561b020109544b50030054005d54525f5750521d391b12531218005d544f320e04162a70744237130058174754423512004206125604461209534367570b09084f5b13062d90f588d8181d656a3f38cab2082a4b2941026fec&code=bffa6c29&k=9d99e661d02acf1eafea48613463323981c72e64366332394749570757020601045e4b5905010714565705561b020109544b50030054005d54525f5750521d391b12531218005d544f320e04162a70744237130058174754423512004206125604461209534367570b09084f5b13062d90f588d8181d656a3f38cab2082a4b2941026fec&fweb=1&cl=1)

---
### For your reference
Traveling Salesman Problem Visualization (3mins)
<a href="http://www.youtube.com/watch?feature=player_embedded&v=SC5CX8drAtU
" target="_blank"><img src="http://img.youtube.com/vi/SC5CX8drAtU/0.jpg" 
alt="Adam Selipsky's session" width="120" height="90" border="3" /></a>
