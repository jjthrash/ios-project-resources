## Short version

Send users to http://whatsmyudid.com/

## Long version

iOS7 introduced a change which broke all the UDID-fetching apps we’ve known and loved. The result is
that these apps now produce invalid UDIDs which start with a number of 0’s.

The supported way is to use iTunes or XCode, but since typical ad hoc users don’t have XCode, iTunes
is what we use.
