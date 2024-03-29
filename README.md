# Introduction
This is going to be my first experience with a real repo management. For this exercise, I will do an interactive course from Datacamp/[Machine Learning Scientist with Python track](https://app.datacamp.com/learn/career-tracks/machine-learning-scientist-with-python?version=1).

# Get Started
I created a project `intro-to-kaggle-competition` in my GitHub account and clone it to my local PC using the following command `git clone`. Next, I opened a new project in my PyCharm editor. Before starting work on a project, it is a good practice to create a virtual environments for it. I have created a virtual environment using the following steps:
1.  Open Anaconda prompt or PyCharm terminal
2.  Create a virtual environment for the repo: `conda create --name intro-to-kaggle-competition`
3.  Activate the inviroment: `conda activate intro-to-kaggle-competition` (the enviroment will change from `base` to `conda activate intro-to-kaggle-competition`, and we will see it in the propmt)
4.  Install ipykernel `conda install -c anaconda ipykernel` and after installing it execute `python -m ipykernel install --user --name=intro-to-kaggle-competition`
5.  Install jupyter `conda install jupyter`
6.  If needed install the requirement of the repo: `conda install pip` or `conda install -r requirements.txt`

Now we are all set 🦾.

# INTERACTIVE COURSE: Winning a Kaggle Competition in Python
_"Kaggle is the most famous platform for Data Science competitions. Taking part in such competitions allows you to work with real-world datasets, explore various machine learning problems, compete with other participants and, finally, get invaluable hands-on experience. In this course, you will learn how to approach and structure any Data Science competition. You will be able to select the correct local validation scheme and to avoid overfitting. Moreover, you will master advanced feature engineering together with model ensembling approaches. All these techniques will be practiced on Kaggle competitions datasets."_ [[Ref.](https://app.datacamp.com/learn/courses/winning-a-kaggle-competition-in-python)]

These course consists of four parts:
1. Kaggle competitions process
2. Dive into the Competition
3. Feature Engineering
4. Modeling

The execution of all parts will be conducted via Jupyter notebook. Two very common GitHub essentials are branches and pull requests. To practice these two, I will create a separate branch for each part of the course, commint push the changes, open a pull request and merge branch.

