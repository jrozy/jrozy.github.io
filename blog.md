This is very very scuffed for now, but hopefully I can bother someone at my workplace soon to help me make this webpage into an actual pretty looking thing. Anyways I think I did pretty well considering that I'm a mathematician that was forced to use Git maybe twice before.

I'll try to keep this blog user-friendly. And hopefully it stays user-friendly for people that don't currently work with me.

11-01-2023 I don't feel like I'm doing much

I started feeling why being a PhD and especially starting one
can be really difficult at times. It really feels like I'm
just trying to study papers with very little progress done
each month and nothing comes out of it. But then I talked to
my supervisor about this, and apparently taking a week to read
a paper throughly is completely normal, not only that, he said
that it's really good if I manage to thoroughly understand the
paper I was working on in a week. I was stunned by this,
because I normally wouldn't expect taking a week to read a
10-page long document. But I guess that's how researcher life
works. 

I also am trying to learn some other than thorough ways
to read a paper. One of them is supposed to come down to just
reading the introduction and summary and deducing what paper
is about from them. The problem is what if a paper doesn't
have a proper introduction and a summary. Becuase people do
that. Why? Who knows. 

Oh also apparently throwing in spikey brackets around words
in a text documents makes .md files not show what's inside.
I removed them so that the end of yesterday's post makes sense.


10-01-2023 Sleeping is good

I've decided to sleep for like 4 hours after sleeping 3 the 
previous day and then go straight into a meeting with my
supervisor. I was super sleepy and couldn't really understand
a thing. So for all PhD students that somehow made it work during
the undergrad/masters - it only really worked because those
studies just aren't that hard. If you wanna actually be able
to work properly, you gotta sleep properly too.

The other realization I had is that being a PhD student is
a wonderful job, but with that wonderful job also comes
a responsibilty to show up to your work ready. And I want to
show up to work ready because what I'm doing is great. None
of this staying up all night for very little reason nonsense.

I've learnt things about the reasons why things didn't make any
sense to me yesterday when reading the paper. Apparently they
wanted to start with properties, but they couldn't prove the
properties -> unique object implication, therefore they had to
settle on some things used in practice -> their properties.


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
