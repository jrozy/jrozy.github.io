This is very very scuffed for now, but hopefully I can bother someone at my workplace soon to help me make this webpage into an actual pretty looking thing. Anyways I think I did pretty well considering that I'm a mathematician that was forced to use Git maybe twice before.

I'll try to keep this blog user-friendly. And hopefully it stays user-friendly for people that don't currently work with me.

9-01-2023 Practical is still strange to me

This might be fault of the fact that I slept 3 hours 
or so during the night, but I had a lot of trouble 
grasping concepts today. As a mathematician whenever 
I try to invent a concept that measures something 
or gives me information, I tend to first think of
what do I want from this thing. And today I've ran
into about 10 definitions of various notions of provenance
in a paper (provenance is meant to be some mathematical object
that gives you ready information about the data you have without
having to search for it, at least as far as I understand, 
maybe that's wrong). And having 10 different variants of a certain
measure is fine, because you might use a different one
depending on what you want. But later in the paper I've
learnt, that only 2 of these notions for decent mathematical
objects with nice properties of... for example, always having 
a definition or being able to manage updating the data. 
The worst part is, I read the first notion last week 
and I figured that first notion was a little silly, 
so I came up with how you'd do an improved version of it. 
Guess what, the first notion and the notion I came up are
the only two that have good properties. I'm meeting my 
supervisor tomorrow, hopefully I'll get an explanation to
why all these other notions are mentioned at all, because 
in my eyes they're just useless right now.

6-01-2023 Hello world (of databases)!

New year, new me! Or something like that... All of these new year resolutions where you completely change the way you're doing things work 100% of the time, right..? Well this whole 45/15 techinque or whatever it's called has been working well for a week so that's something. And I also have to have a work calendar, so at least something is organized.

Moving onto maths... I'm saying I'm working on database theory, but what does that really mean? Well a database is just a set of things you know, i.e. facts. Since you're not only smart, but you also studied things for a while, you know a lot. Therefore databases are big. Despite being smart, you probably know that one guy that doesn't really study much, but can figure almost anything out with a speed of a computer program when you tell them him the data from your database of knowledge. Let's call that guy a Datalog program. If you imagine what a person could be if you combined your knowledge and his deduction skills, that hypothetical person could be a rolemodel for many students, therefore we call it a model. And that's a quick real-life explanation to terms used in databases. Oh well terms... that's also a term, but I don't think anyone needs to actually know the way of that one.

Now imagine that your knowledge base is a set of axioms and you want to figure out if your favorite theorem requires axiom of infinity for example. Actually, no, you're cool, so of course it requires the axiom of infinity. Let's go with the axiom of powerset. And not only that, you'd like to also measure how much it relies on the axiom of infinity. Well I have a recipe for you. Recall all the facts that you're using in the proof of your favorite theorem and draw a downwards line from it to each of those facts to the theorem. Then take the proofs of those facts and repeat, until you get to axioms. And then do that for every possible proof. Then you assign a value x to axiom of infinity and value y to the axiom of powerset and 1 to all other axioms. And then for each proof you multiply the values assigned to axioms that show up at the bottom and you add them all up. Oh, infinity is a number now. If your result has a monomial without a y, then you have a proof that doesn't require the axiom of powerset. And if you have x^infinity somewhere there, then you're really cool. This example probably works better on a table of movies, theater locations and the Pariscope (weekly publication that lists cultural events in Paris), but the point of math is to be pretty, not practical :)

I'll try to do these daily, at least on weekdays because I'm supposed to write about what I worked on during the day anyways. And this is a fun way of doing it.
