# lhcb-starterkit

The LHCb starterkit is a four day event which
will get you ready for analysing LHCb data.

This is a hands-on workshop, bring your laptop!

Days one and two will focus on teaching you
the basics: lab skills for scientific computing.

Days three and four will focus on LHCb specific
tasks and questions.

Specific dates and topics are not set in stone yet.


## Potential dates

Loosly targeting the first week of June.


## Target Audience

This workshop is aimed at new PhD students.
Ambitious Master students or young PostDocs
are also welcome.


## Be Social

The registration fee will be used for coffee breaks
and a BBQ at the lake.


## Day One and Two

These will cover general computing skills and
will be in the form of a [Software Carpentry Workshop](//software-carpentry.org).

This hands-on workshop will cover basic concepts
and tools, including program design, version control,
data management, and task automation. Participants will
be encouraged to help one another and to apply
what they have learned to their own research problems.

The following modules from their full set of [lessons](//software-carpentry.org/lessons.html)
will be covered:

 * The Unix Shell
 * Version control with git/svn
 * Programming in Python
 * ...

We need to think of something for the fourth slot.

 
## Day Three and Four

These will cover LHCb specific topics. We would like
to see these topics approached in a
"This is the target, how do I achieve it" manner.
Compare "DecayTreeTuple is a Gaudi algorithm which is
executed in DaVinci which is based on the Gaudi framework
and it uses DecayTreeTupleTools to write individual branches"
with "I want to make an nTuple, for this you use the
DecayTreeTuple algorithm."

We will cover everything you need to know to measure
the branching ratio of B -> J/Psi K.

We are conducting a [survey][] to get some input on what
people think they would like to learn or think
others should learn.

[survey]: https://docs.google.com/forms/d/1IqU_u6sirC7vnBINNoiMzHj7mumm6xem9N2gssmfOfA/viewform

Current best guess:

 * half day: how to make a basic nTuple on the grid
 * half day: mass hypo susbtitution pi <-> K
 * half day Fun with Loki functors
 * half day: decay tree fitter

The idea is to cover things which lots of people need
but are not "basic". What do you do once you have
your simple nTuple. Things that you will need to do
and will be painful because they are not explained.

Below a growing list of additional topics/ideas to cover. Ideally
these will be combined/slimmed down into four hands-on
sessions each half a day (3hrs) long.

 * svn (if not in SWC)
 * Data flow from collision to nTuple
 * Reconstruction from A-Z
 * Questions the Physics coordinator is sick of (issues everyone has): multiple candidates, TISTOS, PID efficiencies, ...
 * What is a trigger anyway? Why do I need one? Which ones can I choose from?
 * Stripping? Why do I need this? Which ones can I choose from? Where do I find them? Candidates are where?
 * Make a nTuple
 * Act local, think global. Your first grid job.
 * $YourIdeaHere

