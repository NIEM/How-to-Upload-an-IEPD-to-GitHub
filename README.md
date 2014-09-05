IEPD-Repository
===============

A golden rule of NIEM is "if it exists, use it." So share your IEPDs for reuse! They can be reused partially or fully, saving time and money.


NIEM is about the data and how it’s structured as it moves between systems—as “data is in motion.” The NIEM model provides building blocks, such as “person name,” “birth date,” or “activity” that define exchange message content.

How do you structure the NIEM model content?

To actually use NIEM, you need to build an IEPD (or Information Exchange Package Documentation). The IEPD is where a developer pulls the necessary NIEM core and domain model content and extends it to create an information exchange—they package up what is needed of the model to meet exchange business requirements. Any extensions should be considered for future model updates. Model updates are defined as part of the NIEM release cycle.

An IEPD is a source for both business and technical information of an information exchange.

Technically, an IEPD is a set of files (or artifacts) that is a combination of XML schemas. The XML schemas define instance XML documents which, in turn, are the data-carrying entities. For example, when you want to exchange “person” data with its related attributes, you leverage XML schemas to define the tags and structure.

For the business side, an IEPD provides a mechanism to define key documentation such as business scenarios and other aspects of the business requirements for the exchange, as well as maintain a change log, etc. In addition, reusing existing IEPDs that meet similar business requirements is encouraged—and can save time and money!

NOTE: Information exchange relies on many capabilities. NIEM provides a solid starting point. You never use NIEM by itself—there are also access controls, policy automation, and other aspects of systems implementation, depending on business requirements, that may be needed to complete the information exchange.
