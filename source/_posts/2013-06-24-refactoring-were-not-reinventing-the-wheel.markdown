---
layout: post
title: "Refactoring: We're Not Reinventing The Wheel"
date: 2013-06-24 22:34
comments: true
categories:

---

This weekend’s assignment at the Flatiron School involved watching a slide deck on a technical Ruby topic on Speaker Deck. It’s a great website for sharing presentations online that was created by the wizards at GitHub.

I chose a presentation by Anatoli Makarevich called [“Refactoring. Ruby Edition.”](http://speakerdeck.com/makaroni4/refactoring-in-ruby) As a student at the Flatiron School, we had recently covered refactoring in class and thought it would be entertaining to delve into the formal process.

##### Refactoring, per Wikipedia: 

According to Wikipedia, refactoring is a “disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.”

English, please?

##### Refactoring 101:

The purpose of refactoring is to reduce complexity and improve readability, maintainability, and extensibility. When a developer refactors, he/she is not adding new features. Instead, the developer is writing tests, changing code, and removing complexities.

##### Pepé Le Pew? No, it's "Code Smell"

One of the topics covered in the slide deck is “code smell,” a phrase coined by Kent Beck (follow him on Twitter [@kentbeck](http://www.twitter.com/kentbeck)). Code smell is “any symptom  in the source code of a program that possibly indicates a deeper problem.”

##### The Refactoring Cycle:

1. Find code smells

2. Check test coverage

3. Write new tests, if needed

4. Refactor

5. Change code

6. Ensure that tests pass

7. Automate complexity analysis

##### My Favorite Slides:

+ “to grow fast, you must grow right”

+ reFACToring != reHACKing

##### Refactoring, In Real Life 

One week into class at the Flatiron School, I briefly caught up with my cousin, Rajiv Makhijani. Rajiv is a software developer at Hulu and is currently developing an application for [Google Glass](http://www.bbc.co.uk/news/technology-22538854). He was ecstatic that I’m learning how to code and making a career switch (read here). He mentioned that he was looking back at code he had written less than a year ago and was amazed at how verbose it was and how much better he could have written it now. It’s comforting that other seasoned developers aren’t spewing out perfect code and they too, must revisit older code.

The greatest takeaway from this slide deck is that we’re not reinventing the wheel. Instead, we’re improving upon its design. As with all things tech, code isn’t written in stone. It’s digital, ever-changing, and increasingly elegant.

##### Digging Refactoring? Read More About It, by Martin Fowler:

+ [http://www.refactoring.com/ ](http://www.refactoring.com/)

+ [Refactoring, Ruby Edition](http://martinfowler.com/books/refactoringRubyEd.html)