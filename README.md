# a-pattern-language-for-services
Heavy work in progress :smile:

Try to establish a pattern language that deals with service-oriented architectures.

Inspired by http://microservices.io/patterns/ and Christopher Alexander.


## application patterns

* Database architecture
  * shared database
  * database per service

* Security
  * authorization
    * role-based
    * activity-based
  * authentication
    * multi-factor (MFA)
    * one-time password (OTP)


## application-infrastructure patterns

* Cross-cutting concerns
  * Service chassis
* Communication style
  * Messaging
  * RPC


## infrastructure patterns

* Deployment
* Communication
  * External API
  * Discovery
  
## Pattern format

Inspired by http://gee.cs.oswego.edu/dl/ca/ca/ca.html

* **Name**
  A short familiar, descriptive name or phrase, usually more indicative of the solution than of the problem or context.
  Examples include Alcoves, Main entrance, Public outdoor room, Parallel roads, Density rings, Office connections, Sequence of
  sitting spaces, and Interior windows.
  
* **Example**
  One or more pictures, diagrams, and/or descriptions that illustrate prototypical application.
  
* **Context**
  Delineation of situations under which the pattern applies. Often includes background, discussions of why this pattern
  exists, and evidence for generality.
  
* **Problem**
  A description of the relevant forces and constraints, and how they interact. In many cases, entries focus almost entirely on
  problem constraints that a reader has probably never thought about. Design and construction issues sometimes themselves form
  parts of the constraints.

* **Solution**
  Static relationships and dynamic rules (microprocess) describing how to construct artifacts in accord with the pattern,
  often listing several variants and/or ways to adjust to circumstances. Solutions reference and relate other higher- and
  lower-level patterns.
