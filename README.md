# Notes on Scribble

## Demos and examples



* [FASE'16 paper](https://www.doc.ic.ac.uk/~rhu/scribble/index.html) Hybrid Session Verification through Endpoint API Generation
  - Adder and SMTP ([code](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/fase16/src/fase16))

* [FASE'17 paper](https://www.doc.ic.ac.uk/~rhu/scribble/explicit.html) Explicit Connection Actions in Multiparty Session Types
  - [Scribble source](https://github.com/rhu1/scribble-java/tree/rhu1-res/f17/scribble-f17/src/test/scrib/f17/paper) with **"explicit connection"**
  - [Travel Agency 2](https://github.com/rhu1/scribble-java/blob/rhu1-res/f17/scribble-f17/src/test/scrib/f17/travel/shchan/Travel3.scr) with **"explicit connection"** and **"binary connection correlation"**
  - [Microservices use case](https://github.com/rhu1/scribble-java/blob/rhu1-res/f17/scribble-f17/src/test/scrib/f17/paper/AppD.scr) in Appendix D

* [BETTY Summer School 2016](http://summerschool2016.behavioural-types.eu/)
  - Lecture 1 [PDF](http://summerschool2016.behavioural-types.eu/programme/betty16a.pdf)
    - HTTP (short and long), OOI Agent negotiation (nego), and various exercises (misc)
  - Lecture 2 [PDF](http://summerschool2016.behavioural-types.eu/programme/betty16b.pdf)
    - Adder (and its Fibonacci client), SMTP and OOI Resource Usage Control (**interruptible**)
  - [Scribble source code](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/betty16/src/betty16)
  - [Scribble source](https://github.com/scribble/scribble-python/blob/master/test/popl14/ResourceControl.scr)  for "**interruptible**" (from [POPL'14 tutorial](http://popl.mpi-sws.org/2014/tutorials2.html#session), in scribble-python)
    - [Play-Resume pattern](https://confluence.oceanobservatories.org/display/CIDev/Resource+Control+in+Scribble), a page with figures in OOI website
    - [Original paper](http://mrg.doc.ic.ac.uk/publications/practical-interruptible-conversations-distributed-dynamic-verification-with-multiparty-session-types-and-python/) on interruptible (FMSD'15)

* Other examples on **"interruptible"** and **"parallel composition"** (par)
  - [Scribble source](https://github.com/rumineykova/scribble-java/tree/master/extensions/monitor-rest/src/test/resources/scribble/examples)

* Others
  - [Game](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/game/src/game) with **delegation** from [A Linear Decomposition of Multiparty Sessions (ECOOP'17)](http://mrg.doc.ic.ac.uk/publications/a-linear-decomposition-of-multiparty-sessions-for-safe-distributed-programming/) paper and [artifact](https://www.doc.ic.ac.uk/~ascalas/mpst-linear/)
  - [Three Buyer Protocol](https://github.com/scribble/scribble-java/blob/master/scribble-demos/scrib/threebuyer/src/threebuyer/ThreeBuyer.scr), dynamically interleaved sessions from [MSCS'16](http://mrg.doc.ic.ac.uk/publications/global-progress-for-dynamically-interleaved-multiparty-sessions/) paper
  - [LoanApplication](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/loan/src/loan)
  - [Remote Procedure Call](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/rpc/src/rpc)
  - [Travel agency](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/travel/src/travel)
  - [Java RMI (remote method invocation)](https://github.com/scribble/scribble-java/tree/master/scribble-demos/scrib/bettybook/src/bettybook/math/rmi)
  

## Features

* Explicit connection and binary connection correlation (above)
* Delegation (above)
* Interruption (above)
* [Multiparty Protocol Induced Recovery (CC'17)](http://mrg.doc.ic.ac.uk/publications/let-it-recover-multiparty-protocol-induced-recovery/) and its [implementation](https://gitlab.doc.ic.ac.uk/rn710/codeINspire)
* Timed features (delay?) [Timed Multiparty Session Types (CONCUR'14)](http://mrg.doc.ic.ac.uk/publications/timed-multiparty-session-types/) and its [implementation](https://www.doc.ic.ac.uk/~lbocchi/TimeApp.html)


