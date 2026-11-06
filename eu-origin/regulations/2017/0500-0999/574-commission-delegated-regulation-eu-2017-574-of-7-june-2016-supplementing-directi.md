---
title: Commission Delegated Regulation (EU) 2017/574 of 7 June 2016 supplementing Directive 2014/65/EU of the European Parliament and of the Council with regard to regulatory technical standards for the level of accuracy of business clocks (Text with EEA relevance)
id: eur/2017/574
type: EuropeanUnionRegulation
category: euretained
status: revised-with-pending-changes
made_date: '2016-06-07'
text_date: '2023-07-11'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eur/2017/574
pdf_urls:
- http://www.legislation.gov.uk/eur/2017/574/pdfs/eur_20170574_adopted_en.pdf
- http://www.legislation.gov.uk/eur/2017/574/data.pdf
pending_changes: 1
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Commission Delegated Regulation (EU) 2017/574 of 7 June 2016 supplementing Directive 2014/65/EU of the European Parliament and of the Council with regard to regulatory technical standards for the level of accuracy of business clocks (Text with EEA relevance)

> **Warning: changes not yet applied to this text (1).** Text as at 2023-07-11. See https://www.legislation.gov.uk/changes/affected/eur/2017/574
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Commission Delegated Regulation (EU) 2017/574

of 7 June 2016

supplementing Directive 2014/65/EU of the European Parliament and of the Council with regard to regulatory technical standards for the level of accuracy of business clocks

(Text with EEA relevance)

[^c-459e843c158c54e18e028089a2950368][^c-a21c5c108d617e5a6a81a36a05545a30]

THE EUROPEAN COMMISSION,

Having regard to the Treaty on the Functioning of the European Union,

Having regard to Directive 2014/65/EU of the European Parliament and of the Council of 15 May 2014 on markets in financial instruments and amending Directive 2002/92/EC and Directive 2011/61/EU[^f00001], and in particular the third subparagraph of Article 50(2) thereof,

Whereas:

(1)

Clock synchronisation has a direct impact in many areas. In particular it contributes to ensuring that post-trade transparency data can readily be part of a reliable consolidated tape. It is also essential for conducting cross-venue monitoring of orders and detecting instances of market abuse and allows for a clearer comparison between the transaction and the market conditions prevailing at the time of their execution.

(2)

The number of orders received every second by a trading venue can be very high, much higher than that of executed transactions. This may extend to several thousands of orders per second depending on the trading venue, the type of members or participants or clients of a given trading venue, and the financial instruments' volatility and liquidity. As a result, a time granularity of one second would not be sufficient for the purposes of effective market manipulation surveillance of certain types of trading activities. Therefore, it is necessary to establish minimum granularity requirements for recording the date and time of reportable events by operators of trading venues and their members or participants.

(3)

Competent authorities need to be able to reconstruct all events relating to an order throughout the lifetime of each order in an accurate time sequence. Competent authorities need to be able to reconstruct these events over multiple trading venues on a consolidated level to be able to conduct effective cross-venue monitoring on market abuse. It is therefore necessary to establish a common reference time and rules on maximum divergence from the common reference time to ensure that all operators of trading venues and their members or participants are recording the date and time based on the same time source and in accordance with consistent standards. It is also necessary to provide for accurate time stamping to allow competent authorities to distinguish between different reportable events which may otherwise appear to have taken place at the same time.

(4)

There are however, trading models for which increased accuracy might not be relevant or feasible. Voice trading systems or request for quote systems where the response requires human intervention or does not allow algorithmic trading, or systems which are used for concluding negotiated transactions should be subject to different accuracy standards. Trading venues operating those trading systems are not typically susceptible to the high volume of events that can happen within the same second, meaning that it is not necessary to impose a finer granularity to time stamping of those events since it is less likely that there would be multiple events occurring at the same time. In addition, trades on those trading venues may be agreed using manual methods which can take time to agree. In those trading venues there is also an inherent delay between the moment when the trade is executed and the moment when the trade is recorded in the trading system, meaning that applying more stringent accuracy requirements would not necessarily lead to more meaningful and accurate record keeping by the operator of the trading venue, its members or participants.

(5)

Competent authorities need to understand how trading venues and their members or participants are ensuring their traceability to Coordinated Universal Time (UTC). This is because of the complexity of the different systems and the number of alternative methods that can be used to synchronise to UTC. Given that clock drift can be affected by many different elements, it is also appropriate to determine an acceptance level for the maximum divergence from UTC.

(6)

For reasons of consistency and in order to ensure the smooth functioning of the financial markets, it is necessary that the provisions laid down in this Regulation and the related national provisions transposing Directive 2014/65/EU apply from the same date.

(7)

This Regulation is based on the draft regulatory technical standards submitted by the European Securities and Markets Authority (ESMA) to the Commission.

(8)

ESMA has conducted open public consultations on the draft regulatory technical standards on which this Regulation is based, analysed the potential related costs and benefits and requested the opinion of the Securities and Markets Stakeholder Group established by Article 37 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council[^f00002],

HAS ADOPTED THIS REGULATION:

## Article 1. Reference time

Operators of trading venues and their members or participants shall synchronise the business clocks they use to record the date and time of any reportable event with the Coordinated Universal Time (UTC) issued and maintained by the timing centres listed in the latest Bureau international des poids et mesures Annual Report on Time Activities. Operators of trading venues and their members or participants may also synchronise the business clocks they use to record the date and time of any reportable event with UTC disseminated by a satellite system, provided that any offset from UTC is accounted for and removed from the timestamp.

## Article 2. Level of accuracy for operators of trading venues

1. Operators of trading venues shall ensure that their business clocks adhere to the levels of accuracy specified in Table 1 of the Annex according to the gateway to gateway latency of each of their trading systems.

Gateway to gateway latency shall be the time measured from the moment a message is received by an outer gateway of the trading venue's system, sent through the order submission protocol, processed by the matching engine, and then sent back until an acknowledgement is sent from the gateway.

2. By derogation from paragraph 1, operators of trading venues that operate a voice trading system, request for quote system where the response requires human intervention or does not allow algorithmic trading, or a system that formalises negotiated transactions in accordance with Article 4(1)(b) of Regulation (EU) No 600/2014 of the European Parliament and of the Council[^f00003] shall ensure that their business clocks do not diverge by more than one second from UTC referred to in Article 1 of this Regulation. The operator of the trading venue shall ensure that times are recorded to at least a one second granularity.

3. Operators of trading venues that operate multiple types of trading systems shall ensure that each system adheres to the level of accuracy applicable to that system in accordance with paragraphs 1 and 2.

## Article 3. Level of accuracy for members or participants of a trading venue

1. Members or participants of trading venues shall ensure that their business clocks used to record the time of reportable events adhere to the level of accuracy specified in Table 2 of the Annex.

2. Members or participants of trading venues that engage in multiple types of trading activities shall ensure that the systems that they use to record reportable events adhere to the level of accuracy applicable to each of these trading activities in accordance with the requirements set out in Table 2 of the Annex.

## Article 4. Compliance with the maximum divergence requirements

Operators of trading venues and their members or participants shall establish a system of traceability to UTC. They shall be able to demonstrate traceability to UTC by documenting the system design, functioning and specifications. They shall be able to identify the exact point at which a timestamp is applied and demonstrate that the point within the system where the timestamp is applied remains consistent. They shall conduct a review of the compliance of the traceability system with this Regulation at least once a year.

## Article 5. Entry into force and application

This Regulation shall enter into force on the twentieth day following that of its publication in the *Official Journal of the European Union*.

It shall apply from 3 January 2018.

This Regulation shall be binding in its entirety and directly applicable in all Member States.

Done at Brussels, 7 June 2016.

*For the Commission*

*The President*

Jean-Claude Juncker

## ANNEX

*Table 1*

**Level of accuracy for operators of trading venues**

| Gateway-to-gateway latency time of the trading system | Maximum divergence from UTC | Granularity of the timestamp |
| --- | --- | --- |
| \> 1 millisecond | 1 millisecond | 1 millisecond or better |
| ≤ 1 millisecond | 100 microseconds | 1 microsecond or better |

*Table 2*

**Level of accuracy for members or participants of a trading venue**

<table>
<tfoot>
<tr><td colspan="4">Commission Delegated Regulation (EU) 2017/583 of 14 July 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council on markets in financial instruments with regard to regulatory technical standards on transparency requirements for trading venues and investment firms in respect of bonds, structured finance products, emission allowances and derivatives (see page 229 of this Official Journal).</td></tr>
</tfoot>
<tbody>
<tr><th>Type of trading activity</th><th>Description</th><th>Maximum divergence from UTC</th><th>Granularity of the timestamp</th></tr>
<tr><td>Activity using high frequency algorithmic trading technique</td><td>High frequency algorithmic trading technique.</td><td>100 microseconds</td><td>1 microsecond or better</td></tr>
<tr><td>Activity on voice trading systems</td><td>Voice trading systems as defined in Article 5(5) of Commission Delegated Regulation (EU) 2017/583</td><td>1 second</td><td>1 second or better</td></tr>
<tr><td>Activity on request for quote systems where the response requires human intervention or where the system does not allow algorithmic trading</td><td>Request for quotes systems as defined in Article 5(4) of Delegated Regulation (EU) 2017/583</td><td>1 second</td><td>1 second or better</td></tr>
<tr><td>Activity of concluding negotiated transactions</td><td>Negotiated transaction as set out in Article 4(1)(b) of Regulation (EU) No 600/2014.</td><td>1 second</td><td>1 second or better</td></tr>
<tr><td>Any other trading activity</td><td>All other trading activity not covered by this table.</td><td>1 millisecond</td><td>1 millisecond or better</td></tr>
</tbody>
</table>

[^f00004]

## Annotations

[^c-459e843c158c54e18e028089a2950368]: Modification: The “appropriate regulator” has power to make such provision as they consider appropriate by means of an instrument in writing to prevent, remedy or mitigate any failure of the provisions of this Regulation to operate effectively or any other deficiency arising from the withdrawal of the United Kingdom from the EU, see [The Financial Regulators' Powers (Technical Standards etc.) (Amendment etc.) (EU Exit) Regulations 2018 (S.I. 2018/1115)](https://www.legislation.gov.uk/uksi/2018/1115), [regs. 2](https://www.legislation.gov.uk/uksi/2018/1115/regulation/2), [3](https://www.legislation.gov.uk/uksi/2018/1115/regulation/3), [Sch. para. 32](https://www.legislation.gov.uk/uksi/2018/1115/schedule/paragraph/32) (with saving on [I](https://www.legislation.gov.uk/uksi/2018/1115/schedule/paragraph/I)P completion day by [S.I. 2019/680](https://www.legislation.gov.uk/uksi/2019/680), [regs. 1(2)](https://www.legislation.gov.uk/uksi/2019/680/regulation/1/2), [11](https://www.legislation.gov.uk/uksi/2019/680/regulation/11); [2020 c. 1](https://www.legislation.gov.uk/ukpga/2020/1), [Sch. 5 para. 1(1)](https://www.legislation.gov.uk/ukpga/2020/1/schedule/5/paragraph/1/1))

[^c-a21c5c108d617e5a6a81a36a05545a30]: Modification: Regulation: power to modify conferred (11.7.2023) by [Financial Services and Markets Act 2023 (c. 29)](https://www.legislation.gov.uk/ukpga/2023/29), [ss. 3](https://www.legislation.gov.uk/ukpga/2023/29/section/3), [86(3)](https://www.legislation.gov.uk/ukpga/2023/29/section/86/3), [Sch. 1 Pt. 3](https://www.legislation.gov.uk/ukpga/2023/29/schedule/1/part/3); [S.I. 2023/779](https://www.legislation.gov.uk/uksi/2023/779), [reg. 2(d)](https://www.legislation.gov.uk/uksi/2023/779/regulation/2/d)

[^f00001]: Footnote: [OJ L 173, 12.6.2014, p. 349](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2014.173.01.0349.01.ENG).

[^f00002]: Footnote: Regulation (EU) No 1095/2010 of the European Parliament and of the Council of 24 November 2010 establishing a European Supervisory Authority (European Securities and Markets Authority), amending Decision No 716/2009/EC and repealing Commission Decision 2009/77/EC ([OJ L 331, 15.12.2010, p. 84](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2010.331.01.0084.01.ENG)).

[^f00003]: Footnote: Regulation (EU) No 600/2014 of the European Parliament and of the Council of 15 May 2014 on markets in financial instruments and amending Regulation (EU) No 648/2012 ([OJ L 173, 12.6.2014, p. 84](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2014.173.01.0084.01.ENG)).

[^f00004]: Footnote: Commission Delegated Regulation (EU) 2017/583 of 14 July 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council on markets in financial instruments with regard to regulatory technical standards on transparency requirements for trading venues and investment firms in respect of bonds, structured finance products, emission allowances and derivatives (see page 229 of this Official Journal).
