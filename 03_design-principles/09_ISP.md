# Interface Segregation Principle (ISP)

The Interface Segregation Principle (ISP) is a design guideline that states that
clients should not be forced to depend on methods they do not use. This means
that you should avoid creating large, monolithic interfaces that require clients
to implement many methods that they may not need. Instead, you should create
small, specific interfaces that only include the methods that are relevant to a
particular client.

The ISP is based on the idea that large, monolithic interfaces can be difficult
to work with, especially if a client only needs to use a small subset of the
methods defined in the interface. For example, if a client only needs to use a
few of the methods in a large interface, then implementing that interface will
require the client to implement all of the methods in the interface, even if
they are not needed. This can make your code less flexible and more difficult to
maintain.

To follow the ISP in your software development, you should design your
interfaces to be small and specific, and to only include the methods that are
relevant to a particular client. This means creating multiple, small interfaces
that each define a specific set of methods, rather than creating a single, large
interface that defines all of the possible methods. By doing this, you can make
your code more flexible and adaptable, and you can make it easier for clients to
implement the interfaces that they need.

One way to ensure that your interfaces follow the ISP is to use the Interface
Segregation Principle Checklist. This checklist provides a set of guidelines for
designing interfaces that are small, specific, and easy to implement. By
following these guidelines, you can create interfaces that are more flexible and
adaptable, and that will be easier to maintain and reuse over time.
