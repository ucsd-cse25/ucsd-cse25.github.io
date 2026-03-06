---
title: Final Project
downloads: []
---

Final Project [guidelines](resources/CSE25_Project_Guidelines_release.pdf).

::::{admonition} 📝 Teams Formation – Due: Thu, Feb 5, **11:59 PM PT**
:icon: false
:open: false
:class: danger

(teams-formation)=

## Teams Formation

 Fill in one of the following: [Group Signup Sheet](https://docs.google.com/spreadsheets/d/11wSzBmQYf0C_DHbRLCRDeGJGreLiNq-HbNQJaInQ74E/edit?usp=sharing) or [Random Assignment Form](https://forms.gle/kR9RjnWQNpP4DBVG9).

 Groups will be finalized by Mon, Feb 9 with assigned mentor.

**Grading**

- 5% of Final Project Grade

**Submission**

- Fill in either sheet or form by deadline.

**Late policy**

- Late submissions accepted but will be penalized.
::::

::::{admonition} 📝 Project Proposal – Due: Thu, Feb 12, **11:59 PM PT**
:icon: false
:open: false
:class: danger

(Project-Proposal)=

## Project Proposal

Submit a brief (<2 page) proposal describing your problem, dataset, general approach etc.

Some times to address:
- What type of problem are you trying to solve? (e.g. image classification, recommender systems, etc.) Describe the problem in greater detail. Why is it interesting?
- What dataset are you using?
- How will you process the data?
- What is your main model? (e.g. Convolutional Neural Networks, Tabular Q-learning, etc.)
- What evaluation metrics will you use to assess model performance?
- What baseline models will you use to evaluate performance of the main model?

**Grading**

- 5% of Final Project Grade

**Submission**

- Gradescope by the designated deadline.
- Group Submission (see directions [here](https://guides.gradescope.com/hc/en-us/articles/21863861823373-Adding-Group-Members-to-a-Submission)).

**Late policy**

- Late submissions accepted but will be penalized.
::::

::::{admonition} 💻 Example Projects Starter Code
:icon: false
:open: false
:class: danger

(starter-code)=

## Starter Code

Attached are starter code files for the example projects given in the project guidelines. The files are meant to give you a general start on the project and generally focuses on loading and preprocessing the dataset. We recommend running your project in datahub to avoid import issues. 

Notes:
 - Image Captioning project provides the generl encoder-decoder architecture. While we have provided the encoder [(Resnet 50)](https://docs.pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html), it is your job to fill in the rest of the code.
 - For MSCOCO and MovieLens projects, we've downloaded smaller versions of the total dataset. This is primarily to prevent issues with Datahub's storage limits and to allow for faster training. If you wish, you may download the full dataset.
 - Note the Blackjack project uses no data and runs simualations using OpenAI's Gymnasium enviroment. 

Files:
 - [Pedestrian Dection in Penn-Fudan](https://github.com/tbonjour-courses/cse25-wi26/blob/main/Final%20Project/Example%20Projects/Pedestrian_Detection.ipynb)
 - [Image Captioning in MSCOCO](https://github.com/tbonjour-courses/cse25-wi26/blob/main/Final%20Project/Example%20Projects/Image_Captioning.ipynb)
 - [Movie Recommendations in MovieLens](https://github.com/tbonjour-courses/cse25-wi26/blob/main/Final%Projects/Example%20Projects/Movie_Recommendation.ipynb)
 - [Reinforcement Learning in Blackjack](https://github.com/tbonjour-courses/cse25-wi26/blob/main/Final%Projects/Example%20Projects/Blackjack.ipynb)
::::

::::{admonition} 📝 Project Progress Report – Due: Thu, Mar 5, **11:59 PM PT**
:icon: false
:open: false
:class: danger

(Progress-Report)=

## Project Report

Submit a draft of your project report. Expectations:
- Well formatted with all major section headers.
- Sections 1-3 (Intro, Data, and Model Description) mostly done.
- Some results (tables, figures, plots, etc.) and discussion (analysis of results).

**Grading**

- 10% of Final Project Grade

**Submission**

- Gradescope by the designated deadline.
- Group Submission (see directions [here](https://guides.gradescope.com/hc/en-us/articles/21863861823373-Adding-Group-Members-to-a-Submission)).

**Late policy**

- Late submissions accepted but will be penalized.
::::
