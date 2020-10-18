Hi there! Basically, people are very much less aware of git and Github. I'm sure that won't happen after going through this entire article.


Before that You need to know one more thing 

## Version Control:
The term version Control includes any system that helps people track of multiple versions of something.


Let me give you a brief understanding, Just imagine a girl named Pooja, she is a web developer at XYZ company. When her manager asked her to implement a new feature,
then she and her team started working on it, unfortunately, they messed up with the code causing the website to crash. what should they do?


Now! Here comes the actual use of Version control, It allows you to access the previous version of the code. So that we can time travel back to the last version where she messed up and can fix it. Pooja then found it easy to fix the bug instead of spending hours and hours of debugging.

## Git:


![1_8IKWl8Uw4HcGSxomJs4kBQ](https://user-images.githubusercontent.com/54079190/96337720-9c6df700-10a6-11eb-8b32-594af63b2ddb.png)

Git is a free open source version control system designed to handle everything from small to large projects with efficiency. It was developed by Linus Torvalds. Heard somewhere right! He is also the inventor of Kali Linux a computer operating system generally used for hacking.
Git is handy When many people are working on a single project. Since one will work on the different aspects of the project, It keeps track of every change that is made by your teammates and merges the code to the actual repository. It initializes an empty, hidden “.git” subfolder by default in your project folder and in that folder, it keeps track of every change from scratch.
When you come around playing with the code Github takes the action here.

## Introduction to Github:


<img src="https://user-images.githubusercontent.com/54079190/96337756-efe04500-10a6-11eb-95ab-5d21eb57e29d.png" width="15%"></img> 

GitHub is a social hosting code platform to collaborate with other programmers that is absolutely free to use and mostly used version control platform. It is a wonderful place where you can do magic with the code. You can find very vast open-source information, designs, features, emerging technologies.
After reading this article you can get a basic understanding of GitHub from scratch.

# Concepts You need to know:

## What is a Repository?
A repository is a storage place where you are going to store and manage code in your project. In other words, it is just a fancy word to keep track of your code and all of the changes made to your code.
It is often stored on a server and can be accessed by various users. It is by default come up with the Readme.md file of the project.

## Cloning:
When you want to actually work on the repository which is not yours, you can simply clone that on your local machine.
It's like making a copy of a repository (It might be yours or others) on your computer.
command used is

```
Git clone <Url of the repository>
```
## Forking:
Forking allows you to make your own changes to the repository, without affecting the main repository by
It is very easy to fork a repository, just hit the button with fork icon here 👇.

![0_4D7kvWdnGvQecrHl](https://user-images.githubusercontent.com/54079190/96346326-cd572780-10b8-11eb-907c-e650ba80ecef.png)


## Committing:
The changes that you had made in your repository are called commits.
Once you had made your changes in your local computer then you have to update that onto your server. So this includes the command:
```
git commit -m “the message you want to deliver”
```
here the option “-m” stands for a message and within brackets, you have to convey your message.

## branches:
For suppose you are working as a team in a project, all your teammates were assigned different work and your team leader holds the repository on his own account, then how will you add the code you did?
Here’s where branching does magic, It allows you to work with different versions of the repository at the same time and commit individually. If you are assigned the work of backend you can create the branch called backend and then commit the changes, similarly the one who works with frontend commits by the branch name frontend.


## Push and Pull:
Pushing sends the recent commit history to the Github, If you are the only one working on the repository push will be very good to use.
Command used:
```
git push -u origin master
```
Here you are pushing the code in the main branch ie master branch.
If there are some changes that are not yet updated on your local machine, then check out the master branch and pull it, the changes that are been there in the server are now on your computer.
Simply Pull updates the code on your local machine from the Github, the magical command used here is
```
git pull origin master
```
## Pull Request:
If you want to contribute to the places where you don't have access to push, then you can send them a pull request, where you can push but the one on the other side can pull changes from you.
This is what we do here for hactoberfest😜✌
