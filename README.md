
# The 0 to 100 AI research guide



# Intro:
   This course assumes you know literally nothing about math and computer science, and also assumes you want to become a great mathematician and AI researcher. To get started just go to the math and computer science sections down below; there is an intro for each section.

   I spent 4 years gathering the best courses and books I could find, shortening the list to what I think are only the necessities, and now I’m publishing it here. The goal of this guide is to become a competent mathematician and computer scientist as fast as possible. However long this takes will be up to you and your schedule; I have no timeframes. But the old rule of the more time you put in, the more you get out will be helpful.


   I gutted these guides to make this one;
   
   [Open Source University](https://github.com/ossu/computer-science)
   
   [Self-learning-Computer-Science](https://github.com/PKUFlyingPig/Self-learning-Computer-Science) / Alt https://csdiy.wiki/en/
   
    
   Worth checking out for more options / other choices of courses / other tangential fields of knowledge.


   Don't get lost finding the perfect guide or book or course. If you don’t understand something in your course just look up youtube videos and do practice problems, no course is perfect and learning from multiple sources is always good, just don’t keep restarting courses when you get stuck (and you will get stuck). You can look occasionally but if you spend more time looking at courses than you do studying you are just distracting yourself.


# How to use:

Starting at the beginning of both sections, I would recommend splitting your study time if >= 2 hours a day where 1 hour is a course from the math section and 1 hour is from the computation section. If you can only do one course at a time, go math -> computation -> math -> computation -> repeating until done. 

Your skills will be bottlenecked by your math proficiency, focus on math first

 **This will not be easy**, you will meet many points of frustration, just breathe, take some time and stick with it. Learning to deal with difficult problems will be one of the most important skills you will gain from all this.

You may find this taking longer than you expected, but you are trying to get good at a mathematics and computationally heavy discipline, how fast did you think it would take? If you are truly planning on doing this for the rest of your life don’t worry about the bumps in the road or the time commitment too much. 

After you get through CS61B in the software engineer series **start working on personal projects**. There is a lot of cool stuff that can be made with big models and frameworks like langchain and ollama. Working on personal AI projects even if you are not training the models will get you used to the practical AI ecosystem.  


 
# General tips:

   
Set yourself a goal for X amount of work a day. 10 pages a day will get a 500 page textbook done in under two months! Consistency is key.
   
Don't worry if it's hard to study at first, think of your brain as a muscle that gets stronger the more you train it. 

Lectures are good for after you are introduced to a topic IMO, read the chapter first then if you are stuck watch a lecture video on it.

Don’t rush, if a math problem is stumping you and you get frustrated take some time off and come back to it. I figure at least spend 2 or so hours on a hard problem and then if you can’t get it look it up a hint. Usually for me it’s a way of manipulating the problem into another form that I couldn't figure out / forgot about. 

Don’t skip proof based questions if they are a part of the homework, proofs are the language of mathematics and if you ignore them you are shooting yourself in the foot. 

Math requires almost a zen like state, being a place with little distractions and relaxing your mind will do a lot of good in helping you study.

Don’t force it, if you can’t study some day due to stress, fatigue, or general life things just take the day off and come back tomorrow. But in the same vein be consistent and disciplined, don’t randomly take days off because you don’t feel like, take days off because you can’t do it, you will learn how to distinguish those feelings over time.

Just keep trying and be realistically consistent.

Also, if any of these websites have gone down, I highly recommend checking out https://web.archive.org/ to see if there is a backup
    
 
--------------------------------------------------------------------------------------------------------------------------------------------------
# Math:
  
 **How to go through math:**

 Broad overview: High-school math -> Calculus -> Linear Algebra -> Discrete  Math  + Probability  + Statistics -> Optimization + Numerical linear algebra  -> Machine Learning  -> Deep Learning -> Deep Unsupervised learning


--------------------------------------------------------------------------------------------------------------------------------------------------
**Pre-Calculus**
If you have been out of school for a while I highly suggest going to [Kahn Academy](https://www.khanacademy.org/math), starting at algebra 1 or further back if you need it, and working your way up through pre-calculus. It will make your life much easier than just diving into calc (which I did and it didn't work well, because I didn't have a good foundation). 

**Don’t let your pride fool you here, unless you have been routinely doing math after highschool you have probably forgotten a lot stuff that will be vital down the road, at least check it out and make sure you recognize everything**

This is mainly about getting your math manipulation skills up a solid level and getting you introduced to the basics in geometry and functions. 

Don’t watch the videos, they are too long.

Just do the test problems on the side and learn what you're supposed to do if you get the problems wrong.
    
Don't go for perfection, getting 3 out of 4 problems right and moving on to the next sub-unit is fine. 
   
Do the unit tests if you feel like it.
    
--------------------------------------------------------------------------------------------------------------------------------------------
   
---------------------------------------------------------------------------------------------------------------------------------------------
**Calculus**

 Calculus is the study of small changes and the accumulations of those small changes, applicable to everything, foundational to just about everything you will be doing as well.


Single Variable Calculus (also known as Calculus 1 & 2):
 

https://math.berkeley.edu/~ogus/Math_1A/index.html     ( Calc 1)

https://math.berkeley.edu/~hutching/teach/1b/                ( Calc 2)


Multivariate (AKA Calculus 3):
   
Book: Stewart, Multiple Variable Calculus (8th edition)

https://math.berkeley.edu/~pkoroteev/math53.html 
   
   
       

--------------------------------------------------------------------------------------------------------------------------------------------------

**Linear Algebra**

Linear algebra gives great tools for working with large amounts of data.
A good chunk of computer research relies on linear algebra and it is essentially the cornerstone of ML along with Probability. Which you will see why after this course.


First course:

This is call the first course because it mainly focused on computations

   
https://lin-lin.github.io/MATH54/


Second course:

Goes over the first course now from a rigorous proof based perspective:

https://math.berkeley.edu/~mcivor/math110su13/ 
   
--------------------------------------------------------------------------------------------------------------------------------------------------

** Discrete Math, Probability and Statistics:**

   The study of randomness and probability is useful for everything in life since we live in an uncertain world.
   
Discrete math and probability:

No textbook needed. This will serve as training for more complex proofs as well as a very broad introduction to the area’s that computer scientists focus on like cryptography, graph theory, and computability.

The second half is an introduction to probability

www.eecs70.org


Statistics:

Note that this is more from an engineering perspective but I think it does a good job. It’s not really a statistics course, but it will serve as a good enough way to work with real world probabilities. 

https://inst.eecs.berkeley.edu/~ee126/sp24/content.html   

    
--------------------------------------------------------------------------------------------------------------------------------------------------

**Optimization** 

Foundation of Machine Learning, will be very useful to know going into machine learning for that reason. 

https://eecs127.github.io/index.html

--------------------------------------------------------------------------------------------------------------------------------------------------

**Machine and Deep Learning**


Probably what you're here for I’m guessing, the above courses I got mainly from going into these courses and pulling out their prerequisites. 

Used for predictions and learning from very large amounts of data. 

Machine Learning:

https://people.eecs.berkeley.edu/~jrs/189/


Deep Learning:

This is also were courses start getting dicy, Deep learning is a rapidly advancing field with a lot of innovations happening, these courses being over a year old is not a death sentence but you should be aware some of their more experimental topics like transformers and diffusion models could have probably been taught better and in other places is, if you know of a place they are reach out to me.

After this course is also where you will now need to get more “frontier” information from reach papers themselves, and which you will now (hopefully) have the mathematical and programming maturity to read and iterate upon, doing your own research! 

https://inst.eecs.berkeley.edu/~cs182/sp23/

---------------------------------------------------------------------------------------------------------------------------------------------

**Deep Unsupervised Learning**

A very recent look at diffusion models, multimodal models, and more. With practice problems so you can incorporate them yourself.


https://sites.google.com/view/berkeley-cs294-158-sp24/home


---------------------------------------------------------------------------------------------------------------------------------------------
**Extra**

Past here you specialize in what you want, I’m really interest in RL and Robotics, 

So here's some courses I found for them:

Advanced decision making (2021): 
https://sites.google.com/view/berkeley-cs294-190-fa21/home 

Robotics: 
https://ucb-ee106.github.io/eecs106a-fa23site/ , 
https://ucb-ee106.github.io/106b-sp23site/


Deep RL:
https://rail.eecs.berkeley.edu/deeprlcourse/


Numerical Linear Algebra:
https://people.eecs.berkeley.edu/~demmel/ma221_Fall23/



---------------------------------------------------------------------------------------------------------------------------------------------

# Computation

Learning computers and electronics. 

 **How to go through Computations:**
Python Intro ->  CS 61A + B + C -> Missing semester -> Distributed Programming - > Extra

--------------------------------------------------------------------------------------------------------------------------------------------------

   **Learning Python**

If you don’t know any programming language this will ease you in to Python, once you get done start the Software Engineer Series. If you already know the fundamentals of python or other programming languages skip it.
   

   [A Whirlwind Tour of Python](https://s3-us-west-2.amazonaws.com/python-notes/a-whirlwind-tour-of-python-2.pdf)
    


   --------------------------------------------------------------------------------------------------------------------------------------------------

**The Software Engineer Series**

This is mainly a trial by fire, expect to struggle a bit and come out a lot stronger, along the way you will learn the most popular programming languages more in depth and at a software engineer level. Languages are Python, Java, and C. 

Do these in order. The projects and homework are the most important part, do them all.

CS 61A: Structure and Interpretation of Computer Programs
https://cs61a.org/
    
CS 61B Data Structures, Fall 2023
https://fa23.datastructur.es/

CS 61C Great Ideas in Computer Architecture (Machine Structures)
https://inst.eecs.berkeley.edu/~cs61c/sp22/

--------------------------------------------------------------------------------------------------------------------------------------------------

**Missing semester**:

A more practical addendum to the SWE series, focusing on some helpful practical things that you will need in your career that might have been missed in the above classes.

https://missing.csail.mit.edu/


--------------------------------------------------------------------------------------------------------------------------------------------------


**Parallel computing:**

Parallel computing is how all major projects get done in the modern computing world. Goes over CPU and GPU parallel programs

https://gfxcourses.stanford.edu/cs149/fall24


--------------------------------------------------------------------------------------------------------------------------------------------------

**Extra**

EECS 16A + B:

Get comfortable with building and designing circuits and using signals, the bedrock of how electronics work. How to get data from the real world onto a computer.

E16A is an introductory mix of linear algebra, intro to circuits, and signal processing.
https://inst.eecs.berkeley.edu/~ee16a/sp23/

E16B is an extension of the introductions into more advanced topics in their respective areas
https://eecs16b.org/


E16A is structured weird
Use https://inst.eecs.berkeley.edu/~ee16a/fa22/ for discussion and solutions
And https://inst.eecs.berkeley.edu/~ee16a/su20/ for lab files (also made to be done at home since the Pandemic was in full swing that year)


Signals and Systems:
https://inst.eecs.berkeley.edu/~ee120/fa19/


Theory of computation:
https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/
alt https://www.avishaytal.org/cs-172-computability-and-complexity

--------------------------------------------------------------------------------------------------------------------------------------------------



# Beyond

From here if you have completed all the base courses, or if you are eager to see what the current frontier is doing and are will to struggle, check out the BEYOND.md for the the more recent advances in the Deep Learning Field


As far as getting caught up yourself, if you have done the above up to this point you should be able to pick an area of interest, read the research papers, and do your own experiments! Good Luck! And remember to **have fun!** 
