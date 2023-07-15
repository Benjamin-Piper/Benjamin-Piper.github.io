+++
title = "Diversifying the Toolset"
description = "‘I suppose it is tempting, if the only tool you have is a hammer, to treat everything as if it were a nail’ ― Abraham Maslow"
date = 2022-04-27
+++

For the past couple years I've been really interested in using or at least
knowing about different tools for different jobs. I decided to write this post
because this topic popped up in my work (I currently write code for a living),
but it's actually applicable everywhere.

## In Handiwork

[The Law of the instrument](https://en.wikipedia.org/wiki/Law_of_the_instrument)
summarises this post. According to Wikipedia, it is attributed to both Abraham 
Kaplan and Abraham Maslow. I prefer the latter Abraham's variant:

{% blockquote(url="https://philpapers.org/rec/MASTPO-14") %}
I suppose it is tempting, if the only tool you have is a hammer, to treat
everything as if it were a nail.
{% end %}

I think that bolts and screws look like nails. All have flat heads and narrow 
bodies. A screw may also have a pointed end. Now I haven't actually done this,
but I'm sure you could hammer in certain screws and bolts—if you were careful 
about it.

But if I had a screwdriver and a screw that wasn't
[stripped](https://www.bobvila.com/articles/how-to-remove-a-stripped-screw/),
I wouldn't use a hammer. I would use the more appropriate tool for the job.

## In Programming Languages

I see this same idea with programming languages. Sure, you could write every 
program using a general-purpose language like [Python](https://www.python.org/), 
but should you?

There are multiple programming languages that can be classified into multiple
programming paradigms. I am using The Indicative Team's definition of a
programming paradigm:

{% blockquote(author="The Indicative Team", url="https://www.indicative.com/resource/programming-paradigm/") %}
A programming paradigm is the classification, style or way of programming. It is
an approach to solve problems by using programming languages. Depending on the 
language, the difficulty of using a paradigm differs.
{% end %}

[Prolog](https://www.swi-prolog.org/) is a programming language well-suited to 
the logic programming paradigm. One can easily query about and solve
well-defined problems by specifying facts and rules. This isn't limited to 
logic puzzles, but any system governed by constraints. Here's one example from
Michael Hendricks:

{% youtube(id="G_eYTctGZw8", start=1551, end=1593) %}
Let's imagine you define some constraints. Your business maybe ships on Monday
through Saturday and the U.S. Postal Service operates most Monday through 
Saturdays, but some of them they don't because it's a holiday.
//
You have these two independent constraints that define your shipping logic and 
that define the Postal Service calendar and I want to know on what two days do 
those coincide.
//
I simply combine those constraints, I simply say these constraints must be true
and these constraints must also be true. Then you can query it for things like 
‘is today a shipping day?’, what about ‘is tomorrow a shipping day?’, ‘how many
shipping days are there between now and Christmas?’.
//
Those same logical constraints you can solve in all those different ways to get
some really really cool stuff. 
{% end %}

If the facts you're dealing with have probability you can go to the probability 
paradigm and use a language like [ProbLog](https://dtai.cs.kuleuven.be/problog/).
The tutorial on ProbLog's website starts off with tossing coins and takes you
through to Bayesian networks.

The language [APL](https://tryapl.org/) is array-oriented. That
is, anything you can do on a single number you can do on an array of any
dimension: no loops required. APL also represents all of its primitive functions
mnemonically by using unique glyphs. E.g. the glyph to represent natural log is
⍟, which resembles a cross-section of a log! The ease of working with arrays
combined with such terseness enables concise expressesion of computation. Aaron 
Hsu remarks in
[this blog post](https://www.sacrideo.us/un-structured-programming/) that in APL
he can make multiple sketches of approaching a problem and view them all at once
on the screen. I think this quote from A. N. Whitehead neatly sums this up:

{% blockquote(url="https://quod.lib.umich.edu/u/umhistmath/AAW5995.0001.001") %}
By relieving the brain of all unnecessary work, a good notation sets it free to
concentrate on more advanced problems, and in effect increases the mental power
of the race.
{% end %}

Some languages like
[JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript) are 
multi-paradigm. One can write in the (prototype-based) object-oriented style by
defining properties and methods in a function or class and then instantiating
them. Or write in the functional style as functions are first-class citizens,
they can be treated as data as well, so you can store them in variables and pass
them around like any other type.

Personally, I like to use the functional approach when I can. I understand
when object-oriented succeeds, but I believe that using lots of small 
[pure functions](https://www.30secondsofcode.org/articles/s/javascript-pure-functions)
leads to more predictable and testable code.


## In Spoken Languages

I view languages as tools of expression. What can be said in one might be more
easily expressed in another. Just the blurb of the book <cite>Schottenfreude: 
German Words for the Human Condition</cite> stated things that I've never thought
of expressing:

{% blockquote(url="https://www.goodreads.com/book/show/17707491-schottenfreude") %}
In what other language but German could you construct <em>le mot juste</em> for
a secret love of bad foods, the inability to remember jokes, Sunday-afternoon
depression, the urge to yawn, the glee of gossip, reassuring your hairdresser,
delight at the changing of the seasons, the urge to hoard, or the ineffable
pleasure of a cold pillow?
{% end %}

This blurb also reminds me of
[The Dictionary of Obscure Sorrows](https://www.dictionaryofobscuresorrows.com/archive)
where the words denote specific experiences. Having these words makes it easier
to talk about these experiences. One example is sonder: the realisation that
everyone has a story (although I do not believe this is a sorrow but rather
something to be celebrated, everyone is a main character).

[Lojban](https://lojban.io) is an artificial language and its grammar is 
completely different to anything I've seen. It's inspired by predicate logic, 
being mainly made up of relations, arguments, and helper-particles. There are no
nouns, verbs, or any part of speech you'd expect from a natural 
language, but Lojban uses relations to act as them depending on the sentence. By
design, Lojban is syntactically unambiguous, culturally neutral, has a rich 
attitudinal system for expressing emotions, and more that I won't mention in 
this post.

I think its syntactic unambiguity makes it a good auxiliary language when 
precision is required. There was actually a
[lobby](https://mail.lojban.org/lists/lojban-list/msg11837.html) for it to be 
used this way in the European Patent Office.

I believe that the [Sapir-Whorf hypothesis](https://en.wikipedia.org/wiki/Linguistic_relativity) is true in a weak sense, that languages influence the 
thought of the speaker. I currently know a decent amount of Hungarian, and I'm 
learning Lojban. I believe that this knowledge has increased my expressive power
and how I structure my thoughts.

## In Summary

These lists could go on and on. I hope now that you can look at any discipline
and see the different tools that can be used.

The takeaway is that even if you mostly use one tool, I believe that you will
benefit from knowing that other tools exist. That way you can call on this
knowledge when facing wicked problems.
