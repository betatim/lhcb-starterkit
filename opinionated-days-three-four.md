# Possible topics for days 3+4

## What is Gaudi and which problems does it solve?
  - A framework for event stream processing
  - Basic components: Algorithm, Tool
  - What is the TES?
  - How is Gaudi configured? -> Python options
  - What is CMake and how do I use it?
  - What is DaVinci and what does it add on top of Gaudi?
  - Hands-on
    - (I think we should teach `screen` on lx+ during days 1/2 so we can rely on it here)
    - Running DaVinci with a simple option file to print TES contents
      - We provide an MC file on public afs and hard-code the path into the options
    - How to read the output of Gaudi in case something goes wrong

## My first DecayTreeTuple
  - How do I dump my data to a ROOT file? -> DecayTreeTuple
  - How do I need to change my options file (from before) to run DecayTreeTuple?
  - What is a TupleTool and how do I add one?
  - Hands-on
    - We can use the previous MC file and adjust the options file
    - Just run this locally on lx+ (just over a few events)
    - Look at the output with TBrowser

## Working with the LHC grid
  - Why do we want to use the grid?
    - hands-on: Running a hello world job on the grid using the Dirac API
  - We don't need to use the Dirac API manually -> ganga
    - hands-on: Creating a hello world job with ganga
  - Running DaVinci on the grid using ganga
    - How to make set DaVinci as the application and configure it
    - How to use BKQuery
    - How to split your jobs (and decide how many files to use per job)
    - hands-on: Creating a "real" DecayTreeTuple using everything we've learned so far
  - What is EOS and how do I access it?
  - How do I grab some of those LFNs for local testing?
    - hands-on: using dirac-dms-getfile

## The quick intro to stripping
  - What is a stripping line?
  - How do I look up the stripping selection for my line? -> stripping web page
  - How do I calculate the stripping efficiency using signal MC? -> TupleToolStripping
  - How do I extend a stripping line to build my candidates of choice and run it?

## Trigger efficiencies using TISTOS
  - TisTos intro for users
  - TupleTools you can use
  - Interpreting the result
  - Possible caveats (Tis correlations, etc.)

## Getting creative with LoKi functors

## Swapping mass hypotheses

## Running DecayTreeFitter
  - What does DecayTreeFitter do and why would I want to use it?
  - Repeating our previous tuple with a mass-constrained fit

## How to apply multivariate tools in DecayTreeTuple

## I have a problem, how do I debug it
  - Mailing lists
  - Finding out where your problem is
  - GaudiPython is your friend
  - Debug builds and gdb (this one might be too much)
