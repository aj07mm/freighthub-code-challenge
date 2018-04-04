# FreightHub Software Code Challenge

We ask that you do not spend more than a few hours of your time on this
project.

We strongly encourage the use of TypeScript and NodeJS, but something else may
be used if the use case is overwhelmingly beneficial. If you use your favourite
language simply because you're more familiar we won't grade it. There needs to
be a very strong case for not using TypeScript. Over 95% of our code is in TS.

In your interview this project will be the basis for a discussion between you
and us about building software.

## Description

There are many websites that have information related to shipping containers,
vessels, or otherwise. We want to request multiple websites on a cron and save
that data somewhere to be processed in the future.

We should poll HTTP URLs for updates on the internet and save the data
somewhere that we can make use of it. You have full authority to design the
entire system however you see fit, but you have to explain your reasoning by
writing about why by updating the README.

The websites we scrape should be easily configurable in terms of how often, and
where they are on the internet.

### Requirements

* Must request a website on a schedule
* Must save all the related data somewhere

## Submission Instructions

1. Clone this repository.
1. Complete your project as described above within your local repository.
1. Ensure everything you want to commit is committed.
1. Create a git bundle: `git bundle create your_name.bundle --all`
1. Email the bundle file to your point of contact.

## Grading Criteria

1. Does your app do the bare minimum described?
1. Is your app production-ready? (deployable, has logging, stats tracking, reasonable build processes)
1. Are there good tests?
1. How are you saving the artifacts from polling a web request?
1. How are you requesting website endpoints? 
1. How do you deal with failures?
1. Does it scale?
1. How maintainable is the code?
1. How readable is the code?
1. Write a description explaining the direction you took and document your
   deliberate choices so a reviewer can understand your decisions.
1. How does your application receive criteria for web requests?
1. Do you use TypeScript correctly?
1. What packages do you use? Why?

## Just a code challenge

We already do this in production, we use this as a test as it is closely
related to one of the many problems we solve.
