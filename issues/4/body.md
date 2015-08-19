## Format

Features will be modeled after GitHub issues and strive for parity as the service progresses and the API changes.


## Medium

Artifacts must be able to be recognized, versioned, and distributed by version control software.

It should be possible to create, update, and navigate these artifacts without any dedicated software.


## Portability

It should be possible to move artifacts between hosting providers and version control software while maintaining core functionality.


## Connectivity

Connectivity should only be limited by the version control software in use. For example, if commits can be made while offline (such as in distributed systems, like git) then it should also be possible to create and manage issues without an internet connection.


## State

It should be possible to close issues in feature branches and have other branches consider them as open until merged.

There should not be a singular global state which represents the status of a project.


## Pollution

It should not be necessary to preface commit messages with special keywords in order to provide additional functionality.
