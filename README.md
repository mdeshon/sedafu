# sedafu
A security analytics framework. Data Fusion for Security.

## Introduction
by Markus De Shon

sedafu is a framework and a proof-of-concept implementation
of a "Multisensor Data Fusion" approach to security
analytics. This approach grew out of my experience with
security analysis since 2000, attempts to define what
automated analysis would look like, and attempts to
implement automated analysis.

The essence of this approach is to focus on the objects that
we are operating on:

* [Data](1%20Data/README.md): Collection of raw data (e.g.
network packets)
* [Features](2%20Features/README.md): Semantically meaningful
elements in the data (e.g. IP addresses)
* [Entities](3%20Entities/README.md): The subjects of analysis
(e.g. hosts)
* [Relations](4%20Relations/README.md): How the entities
are interacting (e.g. a client is making a request to a
server)
* [Impacts](5%20Impacts/README.md): The security consequences
of the interaction (e.g. the client is attacking the server)
* [Responses](6%20Responses/README.md): Action to take (e.g.
drop the client request)

While the primary path of automation would be to transition
from each of these objects to the next in the series (e.g.
Data -> Features == Feature Extraction),
there are also feedbacks and feed-forwards possible, such
that we have a 6x6 matrix of processes. Note that these
are processes that analysts are already doing, most of them
manually.


