Extra Credit Ruby Exercise
=================

#### Points: 1/4th of a homework (0.4% of your final grade)
#### Due: Saturday Mar 19, 2016, 11:59 PM PST

Hey everyone, welcome to the extra-credit ruby exercise! 

In this exercise, you will solve a simple programming problem with the help of Autostyle, a system that will provide automatic real-time style feedback for your code. The goal of this exercise is to help you better understand programming style concepts and improve your understanding and ability to write stylistically good code.  

Getting Started
--------

1. Clone this repo to your Cloud9 instance (or your own laptop).
2. Solve the programming problem described in next section on your cloud9 instance. We have provided a spec script to check your correctness locally (simply `cd` into the repo and run `rspec spec/combine_anagrams_spec.rb`).
3. Once you have a *correct working solution*, go to <a href="https://codestyle.herokuapp.com" target="_blank">codestyle.herokuapp.com</a>.
4. You will be asked for an email (you can use any email -- it doesn't have to be your Berkeley one).
5. Once you submit your code (which should already pass the local correctness tests) to Autostyle, it will analyze your code and give you a **style score** and some **style feedback** (usually takes about 10 seconds but can take up to a minute). 
6. Use the feedback to improve your code and resubmit. Repeat this step as many times as you need. Try to get to the best possible style score (93.2 for this assignment). 
7. **NOTE**: You don't need to achieve the best style score to get full extra-credit -- see the Grading section below.
8. **NOTE**: the system is _still under development_ so you may face errors/bugs. Please email ```auto.style@berkeley.edu``` if you face any problems. 

Grading
-------

This is an extra-credit assignment **worth 1/4th of a homework** (0.4% of your final grade) in the class. 

There is no partial credit. You can earn full extra-credit by either:
  * achieving a **style score >= 90**.
  * **OR** spending **at least 45 minutes** using the Autostyle system to improve your code's style.

Once you have met the minimum criteria for extra-credit, Autostyle will automatically display a form. **Fill out that form to receive extra-credit**. You can continue to improve your style using Autostyle even after submitting this form.

Exercise: Combine Anagrams
--------

An anagram group is a group of words such that any one can be converted
into any other just by rearranging the letters.  For example, "rats",
"tars" and "star" are an anagram group.

Given an array of words, write a method that groups them into anagram groups 
and returns a nested array of those groups (an array of arrays).
Case doesn't matter in classifying words as anagrams (but case should be preserved in the output). The order of the anagrams in the groups doesn't matter. 

For example:
``` combine_anagrams(["sCAr", "four", "CaRS", "scREAM", "fOr", "CreamS"])``` should return ```[["CaRS", "sCAr"], ["CreamS", "scREAM"], ["fOr"], ["four"]]```.
