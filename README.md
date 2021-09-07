
This is the master reository of the set of repositories that
work together.

Why is it so?

- Keeping this documentation repository as central one allows
implementations and platforms to evolve with similar feature
sets

- The need for independent implementations of the same design
comes from the need of supporting different platforms.

- One approach to solving this problem of several platforms has
been an abstraction layer which can be translated into several
native implementations, for example React Native or Cordova

- This approach is good for fast delivery but not desirable for
security and privacy, since the abstractions may leak data in unknown
ways.  Therefore we avoid those and have multiple implementations,
one per platform.

## The Development Backlog

The backlog for entire project is run from the issues of this
repository (for now)

Every issue will have some pull requests and we should be able
to correlate them across repos (to be verified)


## How to Contribute

Add your name to people.md

Make a pull request and merge for significant changes

Typos and such meta/higher level stuff can be pushed to master but need more thoughtful comments


## Repos

| Repository  | Purpose |
| ----------- | ----------- |
| docs        | This repository  |
| RaviReporter_*   | Apps for varios platforms  |
| web   |  Website   |
| voting-protocol   | Technical White Paper on voting   |
| server   | Scala implementation of the voting protocol  |
| db  | Database used by the server  |
| benchmarks | Benchmarks |
| client | Nodejs client talking to server |
| olddocs | Old documents with lot of irrelevant material (to be deleted)


## Files within this repo

Business and functional requirements etc are described to some detail in
the two presentations :

 - RaviReporter.pptx , which is a full end to end but shallow coverage of
   the technical correctness and properties of the Ravi Reporter apps

 - RaviReporterIntro.pptx , is a quick intro as to why Ravi Reporter is important.

Tasklist.csv and TODO.md are older files with such contents that will be maintained
as isses of this repo.   Once these are ported we could delete these files

technology directory has tech specs, meeting-notes Archive assets finance and planning are created to hold the appropriate documents.




