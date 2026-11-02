<h1 align="center">Blueprint</h1>
<p align="center"><b>Learn system design through diagrams that evolve one tradeoff at a time.</b></p>
<p align="center">Concise system design lessons with step-through, interactive diagrams.</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-15-black" />
  <img alt="Go" src="https://img.shields.io/badge/Go-1.22+-00ADD8" />
  <img alt="Status" src="https://img.shields.io/badge/status-v1-blueviolet" />
</p>

<p align="center">
  <img width="1880" height="977" alt="Blueprint System Design Made Visual" src="https://github.com/user-attachments/assets/63d2a35b-0260-456e-aa91-5c77cc577d34" />
</p>

## Overview

Blueprint is a system design teaching platform. Rather than presenting architectures as collections of components to memorise, each lesson begins with the simplest viable design, identifies where it fails, introduces the smallest effective fix, and states the cost of that fix. The goal is for learners to understand why each component exists and when it can be omitted.

**Version 1 scope.** Lessons in this release are concise, focused reads covering the core idea and its tradeoffs. Deeper treatment, with more worked numbers and edge cases, is the primary objective of the next release.


## Features

- **51 lessons across 11 modules**, covering system design and low-level design.
- **Live diagrams embedded in the text.** Diagrams update as the lesson progresses: adding a cache adds it to the diagram, and a failed server is highlighted in red.
- **A consistent lesson structure:** the problem, the naive design, why it fails, the fix, the cost of the fix, and when not to use it.
- **Worked calculations** wherever numbers drive design decisions, shown step by step.
- **No sign-up or login required.**

### Lesson Map

**System Design**

| Module | Topics |
| --- | --- |
| What is system design? | Fundamentals, back-of-the-envelope estimation, the interview framework |
| Building blocks | Scalability, load balancers, caching, databases, sharding, CAP and PACELC, client communication |
| Classic designs | URL shortener, Pastebin, Instagram, Dropbox, Messenger, Twitter, YouTube, Netflix, Typeahead, rate limiter, web crawler, Yelp, Uber, Ticketmaster |
| Systems under the hood | Dynamo, Cassandra, Kafka, Chubby, GFS and HDFS, BigTable |
| Patterns | Bloom filters, quorum, leader election, logs, heartbeat and gossip, leases and fencing, vector clocks |

**Low-Level Design**

| Module | Topics |
| --- | --- |
| Programming foundations | Data, functions and state, mutability, modules and interfaces |
| Design principles | SOLID, GRASP, DRY, KISS, YAGNI, composition, Law of Demeter |
| Modeling with UML | Use cases, class diagrams, sequence, state and activity diagrams |
| Design patterns | Creational, structural, behavioral |
| Advanced LLD | Concurrency, error handling, caching and rate limiting in code, extensibility, testability |
| LLD problems | Tic-tac-toe, parking lot, vending machine, airport gate assignment |


## Known Limitations

- **Lesson depth:** lessons are concise in v1; deeper versions are the main goal of the next release.
- **Progress is not persisted:** completed lessons are not tracked.
- **Search is limited to titles**, not lesson body text.
- **Side navigation is hidden on small screens.** The chapter index at the top of each lesson remains available.
- **Hands-on design labs** are referenced on the home page but are not yet implemented.
- **Content is read from disk on every request.** This is adequate for the current 51 lessons; in-memory caching of parsed files is the planned next step as the library grows.

## Roadmap

The roadmap is indicative and does not constitute a commitment.

**Next release: deeper lessons**
- Expand shorter lessons with more worked numbers, failure cases and guidance on when not to apply a technique
- Bring earlier lessons up to the same standard as later ones


## Acknowledgements

[Breakscale](https://github.com/xevrion) by **xevrion** is an excellent simulator for hands-on experimentation and is recommended as a companion to these lessons.

## Contact

Questions and feedback are welcome on X: [@the_unfinishedd](https://x.com/the_unfinishedd).

## License

Released under the [MIT License](LICENSE).

<div align="right">

<img src="https://github.com/user-attachments/assets/7d2faa7f-b28e-4161-9bf8-ec6e561c72fb" width="300" />

<br/>

~ This Side Roy, Signing Of , Bye....

</div>
