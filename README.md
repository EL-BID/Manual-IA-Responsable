### IA responsable

### Description and Context
---

#### Why this handbook?

Although there are a significant number of principles that seek ethical AI, they only provide high-level guidance on what should or should not be done in its development and there is very little clarity on what the best practices are for putting them into operation(Vayena, 2019). The objective of this manual is to provide these recommendations and good technical practices in order to avoid results contrary (often unexpected) to the objectives of decision makers. These purposes are varied: they can refer to undesirable consequences from the point of view of decision makers, wasting of resources due to inadequate targeting or any other objective that the decision maker is seeking to achieve.

#### Who is this manual for? 

This manual is intended for technical teams working on the application of machine learning algorithms for public policy. However, all the challenges it covers are common to any application of this technology. It is assumed that the reader has basic knowledge of statistics and programming, although when concepts are named, brief descriptions are included and additional bibliography is shared. The manual includes workbooks with various examples of the challenges and solutions explained. Different types of models (linear, tree-based, and others) and different implementations (R, Keras, Xgboost) are used to show that these problems arise regardless of the choice of particular tools. Although the codes and examples were developed in R, all the topics and methodologies applied and described in this manual can be implemented in any other programming language.

### Installation Guide
---
Using the rocker/rstudio container

#### Using the rocker/rstudio container

##### Quickstart

Build image
    docker build -t ia-responsable . 

Run container
    docker run -d -p 8787:8787 -e PASSWORD=mipass -e ROOT=TRUE -v $PWD/:/home/rstudio/ ia-responsable

Visit `localhost:8787` in your browser and log in with username `rstudio` and the password you set. **NB: Setting a password is now REQUIRED.**  Container will error otherwise.



#### Dependencies
---

### License 
---

### Limitation of responsibilities
---
The IDB is not responsible, under any circumstance, for damage or compensation, moral or patrimonial; direct or indirect; accessory or special; or by way of consequence, foreseen or unforeseen, that could arise:

I. Under any concept of intellectual property, negligence or detriment of another part theory; I
ii. Following the use of the Digital Tool, including, but not limited to defects in the Digital Tool, or the loss or inaccuracy of data of any kind. The foregoing includes expenses or damages associated with communication failures and / or malfunctions of computers, linked to the use of the Digital Tool.