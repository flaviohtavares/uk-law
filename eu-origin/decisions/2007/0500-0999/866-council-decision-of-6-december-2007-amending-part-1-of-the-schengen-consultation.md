---
title: Council Decision of 6 December 2007 amending Part 1 of the Schengen consultation network (technical specifications) (2007/866/EC)
id: eudn/2007/866
type: EuropeanUnionDecision
category: euretained
status: revised
made_date: '2007-12-06'
text_date: '2007-12-06'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eudn/2007/866
pdf_urls:
- http://www.legislation.gov.uk/eudn/2007/866/pdfs/eudn_20070866_adopted_en.pdf
- http://www.legislation.gov.uk/eudn/2007/866/data.pdf
pending_changes: 0
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Council Decision of 6 December 2007 amending Part 1 of the Schengen consultation network (technical specifications) (2007/866/EC)

> Text as at 2007-12-06.
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Council Decision

of 6 December 2007

amending Part 1 of the Schengen consultation network (technical specifications)

(2007/866/EC)

THE COUNCIL OF THE EUROPEAN UNION,

Having regard to Council Regulation (EC) No 789/2001 of 24 April 2001 reserving to the Council implementing powers with regard to certain detailed provisions and practical procedures for examining visa applications[^f00001], and in particular Article 1(2) thereof,

Having regard to the initiative by the Republic of Portugal,

Whereas:

(1)

The Vision network has been established to allow consultation between the central authorities of the partner States for visa applications made by nationals from sensitive countries.

(2)

Formerly, the Vision network operated using the X400 communication system. In order to remain in line with modern techniques for electronic mail transfer, the mail transport protocol of the Vision network had to be migrated from the X400 to the SMTP system.

(3)

In order to allow for the participation in the system of the nine Member States which became Members of the EU in 2004 and which are due to apply the provisions of the Schengen *acquis* in full from 21 December 2007, the Member Sates that joined the EU before 2004 migrated on 15 October 2007 from the X400 to the SMTP mail protocol. This protocol has a particular configuration that now needs to be specified.

(4)

It is necessary to update the technical specifications of the Schengen Consultation Network to ensure that they reflect these changes.

(5)

In accordance with Articles 1 and 2 of the Protocol on the position of Denmark, annexed to the Treaty on European Union and to the Treaty establishing the European Community, Denmark is not taking part in the adoption of this Decision and is not bound by it or subject to its application. As this Decision builds upon the Schengen *acquis* under the provisions of Title IV of Part Three of the Treaty establishing the European Community, Denmark is to decide, in accordance with Article 5 of that Protocol, within a period of six months after the Council has adopted this Decision, whether it will implement the Decision in its national law.

(6)

As regards Iceland and Norway, this Decision constitutes a development of provisions of the Schengen *acquis*, within the meaning of the Agreement concluded by the Council of the European Union and the Republic of Iceland and the Kingdom of Norway concerning the association of those two States with the implementation, application and development of the Schengen *acquis* [^f00002], which fall within the area referred to in Article 1(A) of Council Decision 1999/437/EC of 17 May 1999 on certain arrangements for the application of that Agreement[^f00003].

(7)

As regards Switzerland, this Decision constitutes a development of provisions of the Schengen *acquis*, within the meaning of the Agreement signed between the European Union, the European Community and the Swiss Confederation concerning the Swiss Confederation's association with the implementation, application and development of the Schengen *acquis*, which fall within the area referred to in Article 1(A) of Decision 1999/437/EC in conjunction with Article 4(1) of the Council Decisions of 25 October 2004 on the signing, on behalf of the European Union and the European Community respectively, and on the provisional application of certain provisions of that Agreement.

(8)

This Decision constitutes a development of provisions of the Schengen *acquis* in which the United Kingdom does not take part, in accordance with Council Decision 2000/365/EC of 29 May 2000 concerning the request of the United Kingdom of Great Britain and Northern Ireland to take part in some of the provisions of the Schengen *acquis* [^f00004]; the United Kingdom is therefore not taking part in its adoption and is not bound by it or subject to its application.

(9)

This Decision constitutes a development of provisions of the Schengen *acquis* in which Ireland does not take part, in accordance with Council Decision 2002/192/EC of 28 February 2002 concerning Ireland's request to take part in some of the provisions of the Schengen *acquis* [^f00005]; Ireland is therefore not taking part in its adoption and is not bound by it or subject to its application.

(10)

This Decision constitutes an act building upon the Schengen *acquis* or otherwise related to it, within the meaning of Article 3(2) and Article 4(2) of the 2003 and 2005 Acts of Accession respectively,

HAS ADOPTED THIS DECISION:

**Article 1.** In Part 1, point 1.1., of the Schengen Consultation Network (Technical Specifications), a new point 1.1.4. is hereby inserted, as shown in the Annex.

**Article 2.** This Decision shall apply from 21 December 2007.

**Article 3.** This Decision is addressed to the Member States in accordance with the Treaty establishing the European Community.

Done at Brussels, 6 December 2007.

*For the Council*

*The President*

A. Costa

## ANNEX

The following text is inserted in Part 1, point 1.1. — General characteristics of the communication system of the Schengen Consultation Network (Technical Specifications):

> 1.1.4.
>
> OPERATIONAL MAILBOX CONFIGURATION REQUIREMENTS
>
> Each Schengen State must configure its VISION OPERATIONAL MAIL SYSTEM according to:
>
> - NETWORK ENVIRONMENT
>   - DNS/HOST FILE: Since there is no common Domain Name Service, it is necessary to add records concerning every remote SMTP server
>   - Firewall: Open incoming and outgoing packets on port 25.
> - MIME CONTENT
>
>   The mail server encoding for messages will be configured to these values:
>
>   - Content-Type: text/plain RFC 2046
>   - Charset: iso-8859-15 (Western Europe)
>   - Content-Transfer-Encoding: quoted-printable.
> - The SMTP domain used is visionmail.eu, where every Schengen State has its own third-level domain “xx”. This means that each Schengen State must configure its own mail server in order to manage the xx.visionmail.eu SMTP subdomain name (xx is the two-character Schengen State code).
> - The recipient mailbox address will be in the format: operxx@xx.visionmail.eu
>
>   For Schengen States with a second mailbox (for sending), the sending mailbox address will be in the format:
>
>   operxx-out@xx.visionmail.eu (Note: this is an optional address).

## Annotations

[^f00001]: Footnote: [OJ L 116, 26.4.2001, p. 2](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2001.116.01.0002.01.ENG).

[^f00002]: Footnote: [OJ L 176, 10.7.1999, p. 36](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.1999.176.01.0036.01.ENG).

[^f00003]: Footnote: [OJ L 176, 10.7.1999, p. 31](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.1999.176.01.0031.01.ENG).

[^f00004]: Footnote: [OJ L 131, 1.6.2000, p. 43](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2000.131.01.0043.01.ENG).

[^f00005]: Footnote: [OJ L 64, 7.3.2002, p. 20](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2002.064.01.0020.01.ENG).
