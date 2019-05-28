---
layout: default
title: Federation
collection: services
permalink: services/federation/
---
![Federation Service Diagram - Overview of diagram follows in text below.]({{site.baseurl}}/img/Federation.png){:align="right"}

Federation is the ability of one organization to accept another
organization’s work. Federation depends on inter-organizational trust.
The trusting organization must confirm that the trusted
organization has similar policies, and that those policies are being
followed. For example:

* The security staff at the White House likely won't trust a credential issued by your local library.

* Your health club may trust a credential issued by your bank.

* A state website may trust a PIV credential issued by the Federal Government.

Federation can occur at different points within ICAM. For example:

* An organization can accept credentials issued by another organization,
but still locally authenticate and authorize the individual:
  * A passport issued by the U.S. Department of State is recognized as a
valid credential by a foreign country, but that country’s immigration
office still authenticates the holder and requires a visa
(authorization).

* An organization can accept specific characteristics (attributes) describing
an individual from another organization:
  * Your bank requests your credit score from one of the credit
bureaus rather than maintaining that information itself.

* An organization can accept an authorization decision from another
organization:
  * A driver’s license authorizing you to drive in one state is accepted by
another.

### Federation Services
The Federation services in the Federal ICAM architecture include Attribute Exchange, Credential Translation, Credential Bridging, and Policy Alignment.
![Federation Service Details Diagram - Service definitions follow in the text below.]({{site.baseurl}}/img/federation_services_detailed.png){:align="center"}

**Attribute Exchange**  

> Discover and share identity attributes between different systems to promote interoperability and simplify the process to establish an identity.  
_Keywords_: Attribute Definition, ARS  

**Credential Translation**  

> Transform a token or credential into an alternative format, potentially containing claims about the client, for acceptance at a relying party.
_Keywords_: Secure Token Service, Assertion Service  

**Credential Bridging**  

> Establish a cross-certified, affiliated relationship to trust credentials at a level of assurance asserted by those credentials.  
_Keywords_: Federal PKI Bridge  

**Policy Alignment**  

> Establish a mutual relationship between parties by deliberately establishing common standards and principles.  
_Keywords_: Trust Relationship  
