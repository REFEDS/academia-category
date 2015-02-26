
The Academia Entity Catagory
=======================

1. Overview
----------------

Research and Education Federations are encouraged to use the REFEDS Academia Entity Category to annotate such member identity providers that represents academic institutions in order to distinguish them from identity providers that are not able to claim any affiliation with the international research and education community.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119 [RFC2119]. This definition is written in compliance with the Entity Category SAML Entity Metadata Attribute Types specification [EntityCatTypes].

2. Definition
----------------

An indentity provider that is being operated by or behalf of and by contract with an organization represented by a legal entity in good standing in the community of other academic institutions which fulfills at least one of the criteria below:

(a) the organization is dedicated to education and research and which grants academic degrees at the first stage or above according to the Bologna Process [Bologna] or equivalent internationally recognized structure of academic degrees.
(b) the organization is a research library or archive
(c) the organzation is primarily dedicated to conducting research
(d) the organization is a teaching hospital
(e) any organization explicitly denoted as an acedemic institution by a goverment entity in the jurisdiction where the claim of being an academic institution is made

Note that the funding mechanism (private, public or mixed) is not a factor in the definition of an academic institution. For instance, privately funded research institutions are eligible for the entity category if they fulfill at least one of the criteria above.

3. Syntax
-------------

The following URI is used as the attribute value for the Entity Category and Entity Category Support attribute: http://refeds.org/category/academia

4. Semantics
------------------

By asserting an Identity Provider to be a member of the academia entity category a registrar claims that the Identity Provider fulfils the criteria described above in the jurisdiction of the registrar.

5. References
-------------------

[Bologna] http://www.wes.org/ewenr/03Sept/BolognaGlossary.htm#degreestructure
[AcademicInstitutionWikipedia] http://en.wikipedia.org/wiki/Academic_institution
[EntityCatTypes] Young, I, Johansson, L, and Cantor, S Ed., "The Entity Category SAML Attribute Types", July 2014.
[RFC2119] Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels", BCP 14, RFC 2119, March 1997.