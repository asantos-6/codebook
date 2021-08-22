# Writing good research code

> Is my code fast? No. But is it well documented? No. But does it work? Also no. --[@KyleMorgenstein](https://twitter.com/KyleMorgenstein)

## Who is this for?

The primary target audience for this book are grad students and postdocs who do a lot of programming as part of their research. Most people who write a lot of research code are not trained in computer science or software engineering. It can feel like an uphill battle when you have to write code without the right training. You might:

* Feel like you don't know what you're doing
* Feel like an impostor
* Write code with lots of bugs
* Hate your code and don't want to work on it
* Have trouble finishing projects
* Contemplate buying a small organic farm in upstate Vermont and read far too much about goat husbandry

Did I hit a nerve? Yes! Then you're in for a treat! This book is there to help you get from 0 to 1 on good software engineering practices for software projects. 

## Prerequisites

* **Python**: this intro is Python-centric. You can write good code for Matlab, R, or Julia, but we won't cover that here. You don't need to be a Python expert, but you'll get the most out of this if you've been using Python on a regular basis for at least a month, and if you have some passing familiarity with the python data science ecosystem (numpy, matplotlib, pandas, etc.).
* **Git & Github**: a lot of the practices introduced here will require you to change your code, which could cause existing functionality to break, or even accidentally delete something important! You can think of git and github as a time machine for your code, so you can revert to an earlier state. [There's a great intro to git for beginners from software carpentries](https://swcarpentry.github.io/git-novice/).

Some of the examples I use are neuroscience-inspired - but neuroscience background is absolutely not a requirement. 

## Why did I make this?

I did my PhD in computational neuroscience at McGill University, in Montreal. I wrote a lot of not very good code, mostly in Matlab. One time, my code was in a non-working state for an entire month - I would furiously type on the keyboard all day in the hopes it would eventually work, and it didn't. It made me sad. Then I did a postdoc. More of the same. 

Eventually, I decided to study data structures, algorithms and software engineering practices, and I got a big-boy job as a software engineer at Google in California. It was then that I learned the error of my ways. I had lost so much time during my research days because I didn't know how to organize and write code that didn't self-destruct out of spite.

At the invitation of Ella Batty, I gave a workshop for the students in neuroscience at Harvard on writing good research code - the feedback was positive, so I decided to expand it into this booklet. I hope you enjoy it!

![It me](figures/pic.jpeg)