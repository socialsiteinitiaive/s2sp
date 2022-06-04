= Site to Site Protocol

This repository contains both the Site to Site Protocol (s2sp) and the
Site to Site Client Protocol (s2scp).

== s2sp

These s2sp communication protocol is intended for sites perform the
following RPC calls to each other:

* Establish a connection between sites.
* Validate both a new connection and an existing connection.
* Provide a login sequence using a social site as a login identity.

== s2scp

The s2scp communication protocol is intended for sites to provide the
following RPC calls to clients:

* Login
* Streaming updates on new connections.
* Streaming updates on incoming login requests.
* Validation of login requests.
