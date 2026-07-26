Public Technical Boundary

What contributors may work with

Public contributors may work from approved:

* User-facing requirements
* Capability descriptions
* Expected inputs and outputs
* External integration contracts
* Permission and consent requirements
* Error and availability behavior
* Accessibility requirements
* Privacy and child-safety requirements
* Test cases using synthetic, non-sensitive information

Protected black-box layer

The project contains a non-public Protected Intelligence and Memory Layer. Contributors may be told what authorized result the layer provides, but not how it produces that result.

The public repository must not disclose or attempt to document:

* Internal component names or relationships
* Processing sequences
* Algorithms, prompts, scoring, weighting, thresholds, or decision rules
* Memory evaluation, classification, retention, routing, or retrieval logic
* Behavioral methods
* Internal schemas or interfaces
* Security and enforcement mechanisms
* Patent-sensitive implementation details
* Source code, credentials, deployment details, models, or private datasets

Integration rule

Public components should connect only through an approved external interface. That interface may define the minimum information required to make a request and the allowed structure of a response. It must not reveal, imitate, bypass, reverse engineer, or reconstruct the internal operation of the protected layer.

Disclosure review

When uncertain, do not publish. Mark the proposed material for private disclosure review by the project owner before it is added to GitHub.
