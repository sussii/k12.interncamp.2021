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
cd TSP-workshop
pip3 install -r requirements.txt
python3 source/flask_app.py
```
**Step 6** : Open a web browser in the WorkSpace, visit http://127.0.0.1:5000, you should see a Web UI.

---
### Research about TSP Applications

Let's do some background research. Find at least 5 real-world problem related to TSP. You should be able to describe the use cases. 

---
### Onboarding to Quantum Computing

We will try to solve TSP problem with quantum computing(QC) resource in the second week. Today, we hope you get a basic concept of QC. 

* What is Quantum Computing? 
* Is Now the Right Time for QC? (30 minutes)
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
