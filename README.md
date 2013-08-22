jena-domains
============

This tool and library is developed with the intention of providing
high-performance jena-based `Java Domain Entity Models`. A
`Java Domain Entity Model` (domain model) is not analogous to 
Java Persistance Annotation (JPA) annotated classes.

Other projects, such as [jenabean](https://code.google.com/p/jenabean/)
seek to provide such facilities. Instead, a domain model seeks to provide
a high-performance and high level abstraction for the underlying RDF data.

This tool, thus, generates code that is an extension of Jena's own
RDF abstraction, yet specialized for a particular domain. The domain
itself is provided by consumption of an existing OWL document (schema)
which users specify as input. For those who wish to have a jena-style
API to abstract their RDF domain, this can be extremly useful.

This project is built with Apache Maven.

