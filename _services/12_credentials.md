---
layout: default
title: Credential Management
collection: services
permalink: services/credentials/
---
![Credential Service Diagram - Overview of diagram follows in the text below.]({{site.baseurl}}/img/Credential.png){:align="right"}
Credential Management is the set of practices that an organization uses to issue, track, update, and revoke
credentials for identities within their context.

A **CREDENTIAL** is authoritative evidence of an individual’s claimed identity. Credentials come in many types, from
physical papers and cards (a passport or ATM card) to electronic items (a password or digital certificate),
and often incorporate anti-tamper features.  Within the US Federal Government, we have **Personal Identity Verification (PIV)** as a credential.  

Every credential, no matter what type, associates an identity
with an individual (typically via an identifier) and identifies the
organization that issued the credential:

* A driver’s license includes a license number, a
name, and a state seal.

* An ATM card includes a card number, a name, and
a corporate symbol.

* A PIV credential includes a picture, the issuing agency logo, and cryptographic key pairs.

Some credentials indicate authorizations granted to the
identity by the issuing organization. For example, a driver’s
license includes the authorization to drive a car.

Unlike identities, credentials generally expire. If an identity
continues past the expiration date of the credential, the organization issues a new
credential:

* Your driver’s license expires after so many years, and
you receive a new one.

* Your ATM card expires after so many years, and you
receive a new one.

* Your PIV credential expires after three to six years, and you receive a new one.

An organization can revoke an issued credential that is lost or compromised before it expires.

Credentials can incorporate one or more of the following features to confirm an individual's identity:

* Something you know, such as a password or PIN.

* Something you have, such as a card.

* Something you are, such as a fingerprint or iris.

When a credential incorporates more than one of these features, is uses two-factor, three-factor, or multi-factor authentication.

As with identity proofing, credentials have different Levels of
Assurance depending on the strength required. The
credential to access your bank account is likely stronger
than the credential to access your health club.

  
### Credential Management Services
The Credential Management services in the Federal ICAM architecture include Sponsorship, Registration, Issuance, Maintenance, and Revocation.

![Credential Service Details Diagram - Service definitions follow in the text below.]({{site.baseurl}}/img/credential_services_detailed.png){:align="center"}

**Sponsorship**  

> Formally establish that a person or entity requires a credential.
_Keywords_: Sponsor, Authorizing Official, Affiliation, Request

**Registration**  

> Collect the information needed from a person or entity to issue them a credential.
_Keywords_: Enrollment  

**Issuance**  

> Transfer a credential to a person or entity.
_Keywords_: Activation, Token  

**Maintenance**  

> Maintain a credential over its life cycle.
_Keywords_: Renewal, Reset, Suspension, Blocking, Reissuance  

**Revocation**  

> Withdraw a credential from a person or entity.  
_Keywords_: Termination  
