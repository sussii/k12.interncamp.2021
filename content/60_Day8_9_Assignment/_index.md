---
title: "Day8-9: Project for Quantum Method"
chapter: true
weight: 60
---

# Day8-9 Assignment

Day8-9 is for integrating the quantum computing algorithm

### Learning Objcetives

- Configure the AWS CLI
- Implement the quantum method for your TSP problem

### Deliver Result
- 1 PPT Slide: Test the quantum method for your TSP problem

---

#### Configure the AWS CLI

**Step 1** : Log into Amazon Workspaces with the given code (please refer to your day1_assignment)

**Step 2** : Open your terminal and use the following command to check your aws cli verion

```
aws --version
```

![aws.version](/k12.interncamp.2021/images/awscliversion.png)

**Step 3** : Configure your own command line environment to interact with AWS services. Please replace **AWS Access Key ID** and **AWS Secret Access Key** with your own values (Contact your PM). You can set the default region to us-east-1

```
aws configure
```

![aws.configure](/k12.interncamp.2021/images/awsconfigure.png)

---

### Implement the quantum method for your TSP problem

**Step 1**  : Execute the following commands in the Terminal to pull latest project code

```
cd TSP-workshop-Original
git commit -am "finish day6-7 assignment"
git pull --rebase
```

**Step 2**  : The logic for running quantum algorithm is that each time you re-run the flask program, the quantum algorithm will run at first and save the results as .pkl file locally. After that, when you click the button for quantum algorithm, the results will be playback.

![qc.qc_logic](/k12.interncamp.2021/images/qclogic.png)

**Step 3**  : Fill the s3 bucket of your own account and replace the prefix as you like

![s3bucket](/k12.interncamp.2021/images/s3bucket.png)

**Step 4**  : Find the **TODO** part in the qc.py. When you implement the quantum annealing for tsp, the whole program should work smoothly. (Hints: you could find similar implementation in the notebook in Day4_5_assignment. You could also find some good implementations in qc.py. Good luck :) )

![QCToDO](/k12.interncamp.2021/images/QCToDo.png)
