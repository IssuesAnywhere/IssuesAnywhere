One solution could be that one of the conflicting issues is assigned the next available ID, taking into consideration that other issues may have been created in the meantime.

Potential problems with this approach include:

* Outdated references when IDs are reassigned.
* Preserving the chronological order of comments.

All of these concerns can be addressed by defining procedures for ID reassignment, executed by the implementation of a library.

While it may be cumbersome to resolve these type of conflicts without such a client, it would be far from impossible.
