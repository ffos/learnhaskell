# How to learn Haskell

This is my recommended path for learning Haskell.


## For non-English speakers

* [Auf Deutsch](guide-de.md)

* [Στην ελληνική](guide-el.md)

* [En Español](guide-es.md)

* [En Français](guide-fr.md)

* [In Italiano](guide-it.md)

* [Em Português](guide-pt.md)


#### *Don't sweat the stuff you don't understand immediately*. Keep moving!

## Community

Our IRC channel is `#haskell-beginners` on Freenode.

IRC web client [here](http://webchat.freenode.net/).

The haskell [mailing lists](https://wiki.haskell.org/Mailing_lists).


### Community Guidelines

See [the community guidelines](coc.md) to understand the conduct that is expected in the IRC channel. You'll get a warning if you're not obviously trolling, but be aware the channel is exclusively for those learning or teaching Haskell.


# What are Haskell, GHC, and Cabal?

Haskell is a programming language as laid out in the reports, most recent one
being in 2010. The report is available as the
[onlinereport](http://www.haskell.org/onlinereport/haskell2010/).

## GHC

[GHC](http://www.haskell.org/ghc/) is the most popular way to work in the
Haskell language. It includes a compiler, REPL (interpreter), package
management, and other things besides.

## Cabal

[Cabal](https://www.haskell.org/cabal/download.html) does project management and
dependency resolution. It's how you'll install projects, typically into their
own sandbox.

Cabal is equivalent to Ruby's Bundler, Python's pip, Node's NPM, Maven, etc. GHC
manages packaging itself, Cabal chooses what versions to install.

# Getting set-up

See [the install instructions](install.md) for how to get GHC & Cabal installed.

# How should I learn Haskell?

The core recommendation is to read the lectures and complete all exercises/homework for the Spring 13 version of cis194 followed by the NICTA course. Both are linked below. Everything else should be considered optional and is mentioned so you know where to look for various topics.

## Yorgey's cis194 course

> *Do this first*, this is the primary way I recommend being introduced to
> Haskell.

Available [online](http://www.seas.upenn.edu/~cis194/spring13/lectures.html).

[Brent Yorgey](https://byorgey.wordpress.com)'s course is the best I've found so
far.  This course is valuable as it will not only equip you to write basic
Haskell but also help you to understand parser combinators.

The only reason you shouldn't start with cis194 is if you are not a programmer
or are an inexperienced one. If that's the case, start with
[Thompson's book](http://www.haskellcraft.com/craft3e/Home.html) and transition
to cis194.

---

## NICTA course

> This is the course I recommend doing after Yorgey's cis194 course

Available on github [here](https://github.com/NICTA/course).

This will reinforce and give you experience directly implementing the
abstractions introduced in cis194, this is practice which is *critical* to
becoming comfortable with everyday uses of Functor/Applicative/Monad/etc. in
Haskell. Doing cis194 and then the NICTA course represents the core
recommendation of my guide and is how I teach everyone Haskell.

---

## Supplementary course after cis194 and the NICTA course

> Provides more material on intermediate topics

cs240h is available [online](http://www.scs.stanford.edu/14sp-cs240h/).

This is [Bryan O'Sullivan](https://github.com/bos)'s online course from the
class he teaches at Stanford. If you don't know who he is, take a gander at half
the libraries any Haskell application ends up needing and his name is on it. Of
particular note if you've already done the Yorgey course are the modules on
phantom types, information flow control, language extensions, concurrency,
pipes, and lenses.

---

# Resources for specific topics in Haskell

These resources are not as aggressively vetted or tested with learners as cis194 and NICTA course have been, but they're linked in [the topic listing](specific_topics.md) so you have ideas on where to begin. This includes things like intermediate/advanced concepts and subjects like tooling and text editors.

# Extended Reading list

> Some are already included here

- [Essential Haskell Reading List](http://www.stephendiehl.com/posts/essential_haskell.html)

## Dialogues

> Hosted in this repository [here](dialogues.md).

These are actually pretty important and helpful. Look here for deep dives on a
variety of topics.
