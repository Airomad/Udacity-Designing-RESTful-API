# Udacity Designing RESTful APIs Notes


## Notes:

### OSI Model:
**OSI Model** - The Open Systems Interconnection model (OSI model) is a conceptual model that characterizes and standardizes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. Its goal is the interoperability of diverse communication systems with standard protocols. The model partitions a communication system into abstraction layers. The original version of the model defined seven layers.

A layer serves the layer above it and is served by the layer below it. For example, a layer that provides error-free communications across a network provides the path needed by applications above it, while it calls the next lower layer to send and receive packets that comprise the contents of that path. Two instances at the same layer are visualized as connected by a horizontal connection in that layer.

#### Layers:
- [Physical Layer](https://en.wikipedia.org/wiki/Physical_layer)
- [Data Link Layer](https://en.wikipedia.org/wiki/Data_link_layer)
- [Network Layer](https://en.wikipedia.org/wiki/Network_layer)
- [Transport Layer](https://en.wikipedia.org/wiki/Transport_layer)
- [Session Layer](https://en.wikipedia.org/wiki/Session_layer)
- [Presentation Layer](https://en.wikipedia.org/wiki/Presentation_layer)
- [Application Layer](https://en.wikipedia.org/wiki/Application_layer)

## Useful links:
- [Representational State Transfer (REST)](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
- [REST, where’s my state?](https://ruben.verborgh.org/blog/2012/08/24/rest-wheres-my-state/)