jbosh
=====

forked from https://kenai.com/projects/jbosh

Introduction
============

This project is a Java implementation of XMPP.org's XEP-0124 "Bidirectional-streams Over Synchronous HTTP (BOSH)" specification. This specification defines a protocol for transporting arbitrary XML content bidirectionally over HTTP from potentially constrained clients.

This API is licensed under the Apache 2.0 License.

Goals
=====

The goals of this API are to:

Provide a simple mechanism implementing the protocol and handshaking defined in the XEP-0124 specification.
Define an API which can be expanded over time with minimal impact to the existing user base.
Maintain high levels of code quality, maintaining comprehensive unit and functional tests.
Be as performant as possible without compromising the other goals.
