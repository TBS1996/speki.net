---
title: "About"
date: 2018-01-27T15:42:17+01:00
anchor: "introduction"
weight: 10
---

### Speki brings the power of flashcards to your terminal


[![Watch the video](https://i.imgur.com/njEoYNL.png)](https://youtu.be/hV1iETM6T8g)



... But the fact that it's in the terminal is not the reason you should be interested. Normal flashcards apps are all about memorization of learned knowledge. With Speki you can discover new concepts through incremental reading, solidify your understanding through a sophisticated knowledge-dependency system, and eventually reinforcing what you've learned with spaced repetition. 

First of all, if for now you just want "anki in the terminal" and nothing more, then that's totally fine too! In fact, you can from within the app download any anki deck and get started right away. Skip to the installation and then manual section if this is you! If you wanna learn about Speki's most powerful features however, keep on reading!  
  

### Knowledge dependency  
  
Quick! Memorize the following fact!  

> the nucleus is a membrane-bound organelle found in eukaryotic cells

Using anki, you can probably memorize this fact fairly easily by simply making a flashcard to it, but if you're like me you have no idea what this actually means. A seasoned anki-user would know you're not supposed to memorize what you don't understand, and wouldn't put it into anki before they've tried to fully understand what this means, or they'd simply skip it. 
This is a perfect example of where Speki's system of knowledge-depencies shines through. To explain it, you must know two key concepts of cards in Speki.  
 
1. A card can have the status of *unfinished*. Meaning it has the question, but you have yet to find the answer to it. 
2. A card can have the status of *unresolved*. This is when understanding the card depends on understanding other cards. If any of its dependencies are unfinished, or unresolved,  then that card is also unresolved and will not be shown.  
 
If you look back to the example card I gave you, it's clear that to understand what a nucleus is, you would have to understand what a eukaryotic cell is, what an organelle is, and what it means for an organelle to be membrane-bound. 

In Speki, you can simply add the "what is a nucleus card" as normal, and then you add new *dependency-cards* to it, with where you ask about other concepts you need to learn first. You can add those cards as unfinished when you don't know the answer to them yet. The "what is the nucleus card" is now marked as *unresolved* because understanding it depends on knowledge that you do not yet have.  
 
You will not be asked to memorize this card, but instead you will be shown its unfinished dependencies such as "what is an organelle" and it's your job to find out the answer. This graph of dependencies work recursively, meaning that when you find a definition for an organelle, it might also itself depend on knowledge that you don't have. This process would then repeat itself until you've mapped out all the dependencies to "what is a nucleus". When you've learned all its dependencies, only then will you be asked to memorize the original card.  
 
This means that instead of needing a separate study method for learning concepts next to your flashcard-learning, you can put advanced concepts directly in a card and let the sophisticated dependency-logic ensure that you will fully understand it before you memorize it.


### Incremental reading  
 
So I've explained how you can learn any concept you want with Speki, but how about the process of learning about what you want to learn? That's where *incremental reading* comes in. A concept from a program called supermemo, it is the process of taking a long-form text and incrementally taking extracts of the information you find interesting, and then making flashcards from those extracts.  
 
If for example you need to read a book or a scientific paper and understand it fully, you can navigate to the incremental reading tab, paste it all in and work your way through it. When you come across something you want to remember, simplky make a cloze-card out of it. If you come across something you don't understand, you can follow the dependency-solution as outlined above.  
 

