---
layout: default
title: Access Management
collection: services
permalink: services/access/
---
![Access Service Diagram - Overview of diagram follows in the text below.]({{site.baseurl}}/img/Access.png){:align="right"}
Access Management is the set of practices that allows an organization to permit an individual to perform an action on a
particular resource.  The three most common Access Management services are Policy Administration, Authentication, and Authorization.

**POLICY ADMINISTRATION** is the process by which an organization executes laws, regulations, rules, and corporate access
policies. Depending on an organization's needs, these policies can be simple, complex, or anywhere in between. For example:

* “Grant access to anyone who knows the secret
handshake.”

* “Grant access to anyone on this list of people.”

* “Grant access to anyone in Human Resources.”

* “Grant access to anyone who is a federal employee,
GS-12 or higher, cleared Top Secret, trained in first
aid, and certified as a project manager.”


**AUTHENTICATION** is the process by which an organization confirms a claimed identity, generally through the use of a credential:

* When you go through airport security, you present your driver’s
license, verifying your identity as the ticketed passenger.

* When you withdraw cash at an ATM, you present your
ATM card and enter your personal identification number (PIN),
verifying your identity as the account holder.

* When you attempt to log in to a US Government website, you present the digital certificate on your PIV credential
and enter a PIN, verifying your identity as the PIV credential holder.

Authentication is generally a two-step process:

**Step 1**. Authenticate the credential:

>  - Did a trusted organization issue the credential?
  - Has the credential expired?
  - Has the credential been revoked, voided, or tampered?

**Step 2**. Ensure that the individual to whom the credential was issued is the
same individual that is presenting the credential:

>  - Does the person match the photo and height/weight on the driver’s license?
  - Does the person know the PIN for the ATM card?
  - Does the person have the private key on the PIV card for the certificate presented to the website?


You initially establish your identity via identity proofing, and you confirm who you are via authentication.


**AUTHORIZATION** is how an organization determines whether or not to grant access. In other words authorization is the process by which an organization decides, according to policy, whether or not to approve a request to perform an action on a resource. The range of possible requests is broad:

* A request to read a particular document.

* A request to receive a benefit.

* A request to enter a facility or location.

In some cases, an organization must first perform authentication in order to
perform authorization:

> When you present your driver’s license at a bar, the bartender simultaneously authenticates (the bartender ensures the photo on
the license matches the person) and authorizes (the bartender
ensures you are old enough).  

In other cases, authorization can occur without authentication:  

> When you unlock your car, the car authorizes you without
knowing who is holding your keys. If you give your keys to a friend,
he or she is just as able to unlock your car as you are, and the car
does not know the difference.  

### Access Management Services
The Access Management services in the Federal ICAM architecture include Policy Administration, Entitlement Management, Provisioning, Authentication, and Authorization.  

![Access Service Details Diagram - Service definitions follow in the text below.]({{site.baseurl}}/img/access_services_detailed.png){:align="center"}

**Policy Administration**  

> Create and maintain the rule sets that govern access to protected resources.  
_Keywords_: Policy Decision, Policy Enforcement  

**Entitlement Management**  

> Establish and maintain the authoritative access permissions for a person or entity.  
_Keywords_: Privilege, Right, Access Recertification, Account Management  

**Provisioning**

> Link and unlink access permissions for a person or entity to a protected resource.  
_Keywords_: Workflow, Deprovisioning  

**Authentication**  

> Verify that a claimed identity is genuine and has valid credentials.  
_Keywords_: Validation, Two-Factor, Multi-Factor  

**Authorization**  

> Grant or deny access requests to protected resources based on a policy determination.  
_Keywords_: Policy Decision, Policy Enforcement
