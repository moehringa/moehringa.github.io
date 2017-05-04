---
title: Document Center
---

##### the_Blog_

### ONE
* What Software Engineering Means to Me...
  * Software Engineering is the design, building, and ultimately creation of
  tools that can be used to enhance or boost the performance and/or quality of
  what they are being applied to.  Take for instance recommendation algorithms.  
  These algorithms raise the quality of the system to which they are applied by
  making recommendations or items to its users that they may not have know about
  otherwise.  The Software Engineering was the design and subsequent problem
  solving that took place to make automated relevant recommendations a reality.
  The engineers get to be the creators, making something from nothing, or redesigning
  an already existing project.  

### TWO
* _The Pragmatic Programmer_ Chapter 1...
  * During chapter one, the authors stressed the importance of being interactive
  within the working community, and communicating effectively with colleagues as
  well as clients.  One part that stuck out was "Good-Enough Software."  I know
  that its very easy to go somewhat overboard when finishing programs sometimes.
  Often more features are considered better when it may be true that by adding
  more we can actually be taking away from a program.  Good-Enough, it was stated,
  does not necessarily imply shoddy, but a product that works and does the job
  reliably.  
  * Another part I found interesting was the section when the author brought up
  the "broken windows" metaphor, and how important it is to pay attention to
  detail.  Although leaving something out or not fully refining a small detail
  may save a little time or energy, that small detail may imply a larger problem
  and snowball into more headaches down the road.  Having unfinished, or less than
  adequate pieces also gives off the impression that you may not care about the
  project, position, or job.
  * Finally, reading some of the timelines such as "read a technical book once per
  quarter," and "learn a new language each year" were good to give an idea of the
  expectations in the industry.  Also to start learning the new language this week
  was good as its easy to put it off and make the excuse of being to busy all of
  the time.  

### THREE
* _The Pragmatic Programmer_ Chapter 2...
  * In this chapter I noticed, after the information on duplicating code, the advice on setting up a forum or area in which developers could discuss problems and ideas.  Although this has been brought up in many of my classes I don't believe we (the students) have ever actually implemented this successfully.
  * I found the tracer code section to be interesting, in that as soon as you believe you can successfully begin to distribute or implement something, likely after prototyping, the best thing to do is likely to begin implementing it.  This way the feedback begins to come back as soon as possible.  This also opens up the lines for communication which was brought up in chapter one.
  * Another piece of advice I found helpful was to not give out quick estimates, they may come back to haunt you.  If for instance you give a fairly optimistic estimate but then find the problem to be a little more difficult than expected you may well have dug yourself into a hole that could have been avoided by using a slightly longer estimate.

### FOUR
* _The Pragmatic Programmer_ Chapter 3...
  * The first concept that struck my attention in this chapter was to find an editor to write code in and get well acquainted with it.  The more well versed on can be with their machine, the better equipped they are to trim excess work or inefficiencies out of their load.  This is one area in which I can definitely improve upon, especially using keyboard shortcuts rather than meandering around with the mouse or trackpad all the time.  This also gives more reason to learn to use a powerful IDE well since it has to the potential to be a very powerful tool.  Another concept was that of text manipulation languages.  Im not sure I understood this concept all that well but it seemed as though a language such as Perl or Python could be used to generate the same amount of code that may take upwards of 100 lines in C in less than 20 lines.  I have heard that scripting languages such as Python are slower so although they may be quicker to write prototypes in, when it comes time to deploy the final product they are then written in C++ or the like.  This is an interesting topic to continue or look further into.


  ### SIX

  * _The Mythical Man Month_
    * After reading, it makes a lot of sense that although there are instances when the work can be evenly distributed among many people, this is not usually the case in software engineering.  In software engineering it is usually the case that people need to be trained on the specific project and everyone needs to be on the same page as far as goals and checkpoints go. Though it may seem that more manpower may be better all the time, if the project deadline is coming up adding a new member who may be able to code may not help so much as they wouldn't know anything about the project and training the individual would impede work that could be taking place during that time.  In this instance, by the time this person is fully trained and prepared to help the amount of work possible to get done may be even less than it would have been if everyone on the team just buckled down and didn't take the time to train new man power.
    * Another point that was brought up again was that of estimating time to implement software.  The point was made that programmers tend to be overly optimistic, which in the Pragmatic Programmer it was also stated to not be quick to give short timeframes and estimations as a project estimated at 5 months but taking 4.5 months will be seen in much brighter light than if the same project was estimated at 2.5 months but took 3.5 months, a month less time but also a month overdue.
    * Lastly, I found the partitioning of the schedule recommended in the reading to be contrary to what I think is normally assumed among students.  The schedule dedicated 1/3 of the time to planning, 1/6 of the the time to coding, 1/4 of the time to test components, and 1/4 of the time to test the whole system.  I would have thought that much of the time would have been spent coding, although after the past few homework assignments it is becoming increasingly clear how important testing is rather than crossing your fingers and hoping everything works in the end.

    ### SIX

    * _Pragmatic Paranoia_
      * "Lazy Code" was a nice concept to see in the chapter.  The advice was to be strict in what will be accepted as parameters, but returns as little, or rather as broad of an object as possible.  I can now see that when coding some of the services, we would take broad, large objects and then try to return them all different kinds of ways which ended up being a lot of code; exactly what this chapter said would happen...great.  Although we did have to do it both ways, specific to broad and also broad to specific.
      * It seemed that Design By Contract meant to ensure that the program will meet the requirements that it is meant to meet.  The program can have contracts between classes and methods if it uses inheritance, so we have to ensure that all of the methods do what they should and are used as they should be.  Also, programs have contracts with the users, to protect not only the users from the software but also parts of the software from the users.  Although this is actually part of ch. 6 we also need to be making sure we test to verify that our code honors all of its contracts.  
      * The assert section was relevant, and that's how it seems most teachers teach when coding; to never say never and always make sure to test the edge cases and ensure a string isn't null.  The use of optionals made this easier and more smooth since now optionals can be passed around instead of strings and other data structures that may or may not be null.
      * This led into the section on ensuring we handle data correctly and precisely.  Instead of writing methods and praying nothing can go wrong, write methods that handle errors and exceptions correctly.  Also, make sure that the data is handled correctly when it is deleted or destructed so there aren't random memory leaks.

    ### Seven
    * _Bend, or Break_
      * First, try not to make classes dependent on many different classes.  The less classes that any single class requires in order to function (loose coupling), the less possibility of errors arising when changes are made.  The details can be held in the metadata rather than in the actual program methods or being required by the program's structures.  This data can be held within some container that's more abstract rather than just floating around on its own.
      * Next, limit the Temporal Coupling.  The order in which methods are called (one must be called before an other), time based dependencies should be limited to add to the flexibility of the code.
      * I can now see some time based dependencies in our OOOTracker app.  Some methods were required to be called in order like the method to display the users for a manager, or sometimes to request days off.  As our applications grew from the first homework to the last, the directory structure started to make more sense and follows the loose coupling and also sort of the blackboard implementations since each layer has its own responsibility and each object within that layer has its own responsibility which come together to produce, store, and manipulate the data.

    ### Eight
    * _While You Are Coding_
      * Avoid programming by coincidence, attempting to add and remove snippets of code in order to just the method or program to run without taking time to look at the whole piece of code and devise a strategy.  Also, avoid assuming that code works and will continue to work without debugging or testing it just because it has worked in the past attempts.
      * Try and code deliberately.  Don't assume your code will always work, know that it always will by being aware of the code that is being written by debbugging and testing as it progresses; testing not only code by assumptions of edge cases that are believed to work as well.  Keep aware the the estimated run time as well as it will be useful when trying to scale the project to hand greater loads.
      * Don't be afraid to refactor the code if there is duplication, outdated snippets/knowledge, can improve performance, or it could be made more orthogonal.  Refactor is small steps starting with fields, then maybe smaller methods, to entire classes perhaps ensuring the tests still pass after each snippet is refactored.

    ### Nine
    * _Before the Project_
      * Make sure there is some planning and also that the actual creation of the project isn't delayed for too long.  When sitting down with users to get more information on requirements try to understand why they are using certain features or want certain features, not just how they use features.  By doing this the problem can be further solved more effectively and thoroughly since the actual problem is being addressed rather than trying to recreate a similar solution to an interpretation of the problem.  
      * Try and be vague in creating requirements rather than overly specific, and also be aware of the number of features at any given time since they may tend to become too much to handle.  Requirements can also change over time, so be weary about hard coding in any requirements,  I did notice this during the project and wasn't sure the best way to get around this so I just created variables and documented them at the top of the class that would hold all of them.  Thus they could be changed in one area rather than throughout the code.
      * Discern whether it is best to wait, to move forward, or if it may not really be best to wait and at this point its just procrastination.  
