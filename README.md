# bblrm-spec

The API spec for Bokbasen LRM implementation.

The API exposes resources (Work, Agent, Genre) and the relationships between them.

Resources are identified by URNs in the form:
`urn:bb:work:89QPPRK1EDJPW835E8G64SBKEG` where `89QPPRK1EDJPW835E8G64SBKEG` is the ID of the resource.
The ID is an 26 character alphanumeric string (actually Crockford Base32)

