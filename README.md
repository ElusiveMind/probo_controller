# OpenProboCI: Probo Controller v1.0.0
Michael R. Bagnall - @mbags17 - [Email](mbagnall@zivtech.com)

This is a companion module to the OpenProboCI Stack. It's mission is to act as an API conduit and liason between Probo builds and the Drupal web site. This is a service module with endpoints designed around the existing [Probo Coordiantor](https://proboci.com). This does things such as report build sizes, current build styatus, provides branch build and hash build information to the various git handlers so that they know when to kick off builds and various other functions.

Endpoints will be documented here as they are fleshed out and developed for the communication from Probo builds top the web site and vice versa. And so version 1 of the Probo API begins.
