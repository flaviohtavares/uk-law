---
title: Commission Implementing Regulation (EU) No 1249/2012 of 19 December 2012 laying down implementing technical standards with regard to the format of the records to be maintained by central counterparties according to Regulation (EU) No 648/2012 of the European Parliament and of the Council on OTC derivatives, central counterparties and trade repositories (Text with EEA relevance)
id: eur/2012/1249
type: EuropeanUnionRegulation
category: euretained
status: revised-with-pending-changes
made_date: '2012-12-19'
text_date: '2023-07-11'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eur/2012/1249
pdf_urls:
- http://www.legislation.gov.uk/eur/2012/1249/pdfs/eur_20121249_adopted_en.pdf
- http://www.legislation.gov.uk/eur/2012/1249/data.pdf
pending_changes: 1
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Commission Implementing Regulation (EU) No 1249/2012 of 19 December 2012 laying down implementing technical standards with regard to the format of the records to be maintained by central counterparties according to Regulation (EU) No 648/2012 of the European Parliament and of the Council on OTC derivatives, central counterparties and trade repositories (Text with EEA relevance)

> **Warning: changes not yet applied to this text (1).** Text as at 2023-07-11. See https://www.legislation.gov.uk/changes/affected/eur/2012/1249
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Commission Implementing Regulation (EU) No 1249/2012

of 19 December 2012

laying down implementing technical standards with regard to the format of the records to be maintained by central counterparties according to Regulation (EU) No 648/2012 of the European Parliament and of the Council on OTC derivatives, central counterparties and trade repositories

(Text with EEA relevance)

[^key-cb16621150d7c7fa74d9ab3a2c6740a3][^key-7e7ecb1d4ae73acd8e41a7713e1930fe]

THE EUROPEAN COMMISSION,

Having regard to the Treaty on the Functioning of the European Union,

Having regard to the opinion of the European Central Bank[^f00001],

Having regard to Regulation (EU) No 648/2012 of the European Parliament and of the Council of 4 July 2012 on OTC derivatives, central counterparties and trade repositories[^f00002], and in particular Article 29(5) thereof,

Whereas:

(1)

In accordance with Article 29(4) of Regulation (EU) No 648/2012, Articles 13, 14 and 15 of the delegated act with regard to regulatory technical standards specifying the details of the records and information to be kept by central counterparties (CCPs) adopted pursuant to Article 29(4) of Regulation (EU) No 648/2012, rules should also be laid down to specify the format of the record and information kept in accordance those Articles.

(2)

To carry out their duties effectively and consistently, the relevant authorities should be provided with data that are comparable among CCPs. The use of common formats also facilitates the reconciliation of data between CCPs.

(3)

A CCP should be required to retain data for record keeping purposes in a format compatible with the format in which data is retained by trade repositories, taking into account that in certain circumstances CCPs and trade repositories are required to maintain or report the same information. The use of a common format across different financial market infrastructures facilitates the greater use of these formats by a wide variety of market participants, thus promoting standardisation.

(4)

To facilitate straight through processing and reduction of costs to market participants, it is important to use standardised procedures and data formats across CCPs as much as possible.

(5)

The underlying should be identified by using a single identifier, however there is currently no market wide standardised code to identify the underlyings within a basket. CCPs should therefore indicate at least that the underlying is a basket and use International Securities Identification numbers (ISINs) for standardised indices where possible.

(6)

This Regulation is based on the draft implementing technical standards submitted by the European Securities and Markets Authority (ESMA) to the Commission.

(7)

In accordance with Article 15 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council of 24 November 2010 establishing a European Supervisory Authority (European Securities and Markets Authority)[^f00003], ESMA has conducted an open public consultation before submitting the draft implementing technical standards on which this Regulation is based, analysed the potential related costs and benefits and requested the opinion of the Securities and Markets Stakeholder Group established in accordance with Article 37 of Regulation (EU) No 1095/2010,

HAS ADOPTED THIS REGULATION:

## Article 1. Formats of records

1. A CCP shall retain the records specified in Article 20 of the delegated act with regard to regulatory technical standards on requirements specifying the details of the records and information to be kept by central counterparties (CCPs) adopted pursuant to Article 29(4) of Regulation (EU) No 648/2012 for each contract processed in the format set out in Table 1 in the Annex.

2. A CCP shall retain the records specified in Article 21 of the delegated act with regard to regulatory technical standards on requirements specifying the details of the records and information to be kept by central counterparties (CCPs) adopted pursuant to Article 29(4) of Regulation (EU) No 648/2012 for each position in the format set out in Table 2 in the Annex.

3. A CCP shall retain the records specified in Article 22 of the delegated act with regard to regulatory technical standards on requirements specifying the details of the records and information to be kept by central counterparties (CCPs) adopted pursuant to Article 29(4) of Regulation (EU) No 648/2012 for activities related to its business and internal organisation in the format set out in Table 3 in the Annex.

4. A CCP shall provide the competent authority the records and information under paragraphs 1, 2 and 3 in a format that allows a direct data feed between the CCP and the competent authority. A CCP shall establish such data feed within six months after the request of the competent authority.

## Article 2. Entry into force

This Regulation shall enter into force on the twentieth day following that of its publication in the *Official Journal of the European Union*.

This Regulation shall be binding in its entirety and directly applicable in all Member States.

Done at Brussels, 19 December 2012.

*For the Commission*

*The President*

José Manuel Barroso

## ANNEX

**Tables of fields to be recorded as referred to in Article 1**

<table>
<thead>
<tr><td colspan="4"><em>Table 1</em></td></tr>
<tr><td colspan="4"><strong>Records of transactions processed</strong></td></tr>
</thead>
<tbody>
<tr><th></th><th>Field</th><th>Format</th><th>Description</th></tr>
<tr><td>1</td><td>Reporting timestamp</td><td><em>ISO 8601 date format / UTC time format.</em></td><td>Date and time of reporting.</td></tr>
<tr><td>2</td><td>Price/rate</td><td><em>Up to 20 numerical digits in the format xxxx,yyyyy.</em></td><td>The price per security or derivative contract excluding commission and (where relevant) accrued interest. In the case of a debt instrument, the price may be expressed either in terms of currency or as a percentage.</td></tr>
<tr><td>2a</td><td>Price notation</td><td><em>E.g. ISO 4217 Currency Code, 3 alphabetical digits, percentage.</em></td><td>The manner in which the price is expressed.</td></tr>
<tr><td>3</td><td>Notional Currency</td><td><em>ISO 4217 Currency Code, 3 alphabetical digits.</em></td><td>The currency in which the price is expressed. If, in the case of a bond or other form of securitised debt, the price is expressed as a percentage, that percentage shall be included.</td></tr>
<tr><td>3a</td><td>Deliverable currency</td><td><em>ISO 4217 Currency Code, 3 alphabetical digits.</em></td><td>The currency to be delivered.</td></tr>
<tr><td>4</td><td>Quantity</td><td><em>Up to 10 numerical digits.</em></td><td>The number of units of the financial instruments, the nominal value of bonds, or the number of derivative contracts included in the transaction.</td></tr>
<tr><td>5</td><td>Quantity notation</td><td><em>Up to 10 numerical digits.</em></td><td>An indication as to whether the quantity is the number of units of financial instruments, the nominal value of bonds or the number of derivative contracts.</td></tr>
<tr><td>6</td><td>CCP side</td><td><em>B=Buyer / S=Seller.</em></td><td></td></tr>
<tr><td>7</td><td>Product ID</td><td><em>Interim taxonomy in accordance with the information in Article 4 of Regulation (EC) xx/2012 [draft ITS on format and frequency of trade reports to trade repositories], ISIN or a unique product identifier (UPI).</em></td><td>The contract shall be identified by using a product identifier, where available.</td></tr>
<tr><td>8</td><td>Clearing member ID</td><td><em>Legal Entity Identifier (LEI) (20 alphanumerical digits), interim entity identifier (20 alphanumerical digits), BIC (11 alphanumerical digits) or client code (50 alphanumerical digits).</em></td><td>In case the reporting counterparty is not a clearing member, its clearing member shall be identified in this field by a unique code. In case of an individual, a client code, as assigned by the CCP, shall be used.</td></tr>
<tr><td>9</td><td>Beneficiary ID</td><td><em>Legal Entity Identifier (LEI) (20 alphanumerical digits), interim entity identifier (20 alphanumerical digits), BIC (11 alphanumerical digits) or client code (50 alphanumerical digits).</em></td><td>If the beneficiary of the contract is not a C/P to this contract it has to be identified by a unique code or, in case of individuals, by a client code as assigned by the legal entity used by the individual.</td></tr>
<tr><td>10</td><td>Party that transferred the contract (in case of give-up)</td><td><em>Legal Entity Identifier (LEI) (20 alphanumerical digits), interim entity identifier (20 alphanumerical digits), BIC (11 alphanumerical digits) or client code (50 alphanumerical digits).</em></td><td></td></tr>
<tr><td>11</td><td>Venue of execution</td><td><em>ISO 10383 Market Identifier Code (MIC) where relevant, XOFF for listed derivatives that are traded off-exchange or XXXX for OTC derivatives.</em></td><td>Identification of the venue where the transaction was executed. In case of a contract concluded OTC, it has to be identified whether the respective instrument is admitted to trading but traded OTC or not admitted to trading and traded OTC.</td></tr>
<tr><td>12</td><td>Date of interposition</td><td><em>ISO 8601 date format.</em></td><td>The day on which the interposition of the CCP in the contract was executed.</td></tr>
<tr><td>13</td><td>Time of interposition</td><td><em>UTC time format.</em></td><td>The time at which the interposition of the CCP in the contract was executed, reported in the local time of the competent authority to which the transaction will be reported, and the basis in which the transaction is reported expressed as Coordinated Universal Time (UTC) +/- hours.</td></tr>
<tr><td>14</td><td>Date of termination of the contract</td><td><em>ISO 8601 date format.</em></td><td>The day on which the termination of the contract occurred.</td></tr>
<tr><td>15</td><td>Time of termination of the contract</td><td><em>UTC time format.</em></td><td>The time at which the termination of the contract occurred, reported in the local time of the competent authority to which the transaction will be reported, and the basis in which the transaction is reported expressed as Coordinated Universal Time (UTC) +/- hours.</td></tr>
<tr><td>16</td><td>Delivery type</td><td><em>C = cash, P = physical, O = optional for counterparty.</em></td><td>Whether the contract is settled physically or in cash.</td></tr>
<tr><td>17</td><td>Settlement date</td><td><em>ISO 8601 date format.</em></td><td>The day on which the settlement or the buy-in of the contract is executed. If more than one, further fields may be identified.</td></tr>
<tr><td>18</td><td>Time of settlement or of buy-in in the contract</td><td><em>UTC time format.</em></td><td>The time at which the settlement or the buy-in of the contract is executed, reported in the local time of the competent authority to which the transaction will be reported, and the basis in which the transaction is reported expressed as Coordinated Universal Time (UTC) +/- hours.</td></tr>
<tr><th colspan="4">Details on the original terms of the contracts cleared, to be provided to the extent they are applicable</th></tr>
<tr><td>19</td><td>Date</td><td><em>ISO 8601 date format.</em></td><td>The day on which the contract was originally concluded.</td></tr>
<tr><td>20</td><td>Time</td><td><em>UTC time format.</em></td><td>The time at which the original contract was originally concluded, reported in the local time of the competent authority to which the transaction will be reported, and the basis in which the transaction is reported expressed as Coordinated Universal Time (UTC) +/- hours.</td></tr>
<tr><td>21</td><td>Product ID</td><td><em>Interim taxonomy in accordance with the information in Article 4 of Regulation (EC) xx/2012 [draft ITS on format and frequency of trade reports to trade repositories], ISIN or a unique product identifier (UPI).</em></td><td>The contract shall be identified by using a unique product identifier where available.</td></tr>
<tr><td>22</td><td>Underlying</td><td><em>A unique product identifier, ISIN (12 alphanumerical digits and CFI (6 alphanumerical digits). Legal Entity Identifier (LEI) (20 alphanumerical digits), interim entity identifier (20 alphanumerical digits), B= Basket, or I=Index.</em></td><td>The instrument identification applicable to the security that is the underlying asset in a derivative contract as well as the transferable security falling within Article 4(1)(18)(c) of Directive 2004/39/EC.</td></tr>
<tr><td>23</td><td>Derivative type (in case of derivative contract)</td><td>The harmonised description of the derivative type should be done according to one of the top level categories as provided by a uniform internationally accepted standard for financial instrument classification.</td><td></td></tr>
<tr><td>24</td><td>Inclusion of the instrument in the ESMA register of contracts subject to the clearing obligation (in case of derivative contract)</td><td><em>Y=Yes / N=No.</em></td><td></td></tr>
<tr><th colspan="4">Other information to be provided to the extent they are applicable</th></tr>
<tr><td>25</td><td>Identification of the interoperable CCP clearing one leg of the transaction</td><td><em>Legal Entity Identifier (LEI) (20 alphanumerical digits), interim entity identifier (20 alphanumerical digits), BIC (11 alphanumerical digits) or client code (50 alphanumerical digits).</em></td><td></td></tr>
</tbody>
</table>

<table>
<thead>
<tr><td colspan="3"><em>Table 2</em></td></tr>
<tr><td colspan="3"><strong>Position records</strong></td></tr>
</thead>
<tbody>
<tr><th></th><th>Field</th><th>Format</th></tr>
<tr><td>1</td><td>Clearing member ID</td><td><em>Legal Entity Identifier (LEI), interim entity identifier or BIC</em></td></tr>
<tr><td>2</td><td>Beneficiary ID</td><td><em>Legal Entity Identifier (LEI), interim entity identifier, BIC or Client Code</em></td></tr>
<tr><td>3</td><td>Interoperable CCP maintaining the position</td><td><em>Legal Entity Identifier (LEI), interim entity identifier, BIC or Client Code</em></td></tr>
<tr><td>4</td><td>Sign of the position</td><td><em>B=Buyer / S=Seller</em></td></tr>
<tr><td>5</td><td>Value of the position</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>6</td><td>Price at which the contracts are valued</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>7</td><td>Currency</td><td><em>ISO Currency Code.</em></td></tr>
<tr><td>8</td><td>Other relevant information</td><td><em>Free Text</em></td></tr>
<tr><td>9</td><td>Amount of margins called by the CCP</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>10</td><td>Amount of default fund contributions called by the CCP</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>11</td><td>Amount of other financial resources called by the CCP</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>12A</td><td>Amount of margins posted by the Clearing Member with reference to client account A</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>13A</td><td>Amount of default fund contributions posted by the Clearing Member with reference to client account A</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>14A</td><td>Amount of other financial resources posted by the Clearing Member with reference to client account A</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>15B</td><td>Amount of margins posted by the Clearing Member with reference to client account B</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>16B</td><td>Amount of default fund contributions posted by the Clearing Member with reference to client account B</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
<tr><td>17B</td><td>Amount of other financial resources posted by the Clearing Member with reference to client account B</td><td><em>Up to 10 numerical digits (xxxx,yy).</em></td></tr>
</tbody>
</table>

<table>
<thead>
<tr><td colspan="4"><em>Table 3</em></td></tr>
<tr><td colspan="4"><strong>Business records</strong></td></tr>
</thead>
<tbody>
<tr><th></th><th>Field</th><th>Format</th><th>Description</th></tr>
<tr><td>1</td><td>Organisational charts</td><td><em>Free text</em></td><td>Board and relevant committees, clearing unit, risk management unit, and all other relevant units or divisions.</td></tr>
<tr><th colspan="4">Shareholders or members that have qualifying holdings (fields to be added for each of the relevant shareholder/member)</th></tr>
<tr><td>2</td><td>Type</td><td><em>S=Shareholder / M=member.</em></td><td></td></tr>
<tr><td>3</td><td>Type of qualified holding</td><td><em>D=direct / I=indirect.</em></td><td></td></tr>
<tr><td>4</td><td>Type of entity</td><td><em>N=natural person / L=legal person.</em></td><td></td></tr>
<tr><td>5</td><td>Amount of the holding</td><td><em>Up to 10 numerical digits (xxxx,yyyyy).</em></td><td></td></tr>
<tr><th colspan="4">Other documents</th></tr>
<tr><td>6</td><td>Policies, procedures, processes required under organisational requirements</td><td><em>Documents</em></td><td></td></tr>
<tr><td>7</td><td>Minutes of Board meetings, meeting of sub-committees (if applicable) and of Senior Management Committees (if applicable)</td><td><em>Documents</em></td><td></td></tr>
<tr><td>8</td><td>Minutes of meetings of the risk committee</td><td><em>Documents</em></td><td></td></tr>
<tr><td>9</td><td>Minutes of consultation group with clearing members and clients (if any)</td><td><em>Documents</em></td><td></td></tr>
<tr><td>10</td><td>Reports of internal and external audit, risk management, compliance and consultant</td><td><em>Documents</em></td><td></td></tr>
<tr><td>11</td><td>Business continuity policy and disaster recovery plan</td><td><em>Documents</em></td><td></td></tr>
<tr><td>12</td><td>Liquidity plan and daily liquidity reports</td><td><em>Documents</em></td><td></td></tr>
<tr><td>13</td><td>Documents reflecting all assets and liabilities and capital accounts</td><td><em>Documents</em></td><td></td></tr>
<tr><td>14</td><td>Complaints received</td><td><em>Free text</em></td><td>For each complaint: information on complaint’s name, address and account number; date of receiving the complaint; names of all persons identified in the complaint; description of the nature of the complaint; disposition of the complaint; date at which the complaint was resolved.</td></tr>
<tr><td>15</td><td>Information on interruption of services or dysfunction</td><td><em>Free text</em></td><td>Information on any interruption of services or dysfunction, including a detailed report on the timing, effects and remedial actions.</td></tr>
<tr><td>16</td><td>Results of back and stress test performed</td><td><em>Free text</em></td><td></td></tr>
<tr><td>17</td><td>Written communications with competent Authorities, ESMA and the relevant members of the ESCB</td><td><em>Documents</em></td><td></td></tr>
<tr><td>18</td><td>Legal opinions received in accordance with organisational requirements</td><td><em>Documents</em></td><td></td></tr>
<tr><td>19</td><td>Interoperability arrangements with other CCPs (where applicable)</td><td><em>Documents</em></td><td></td></tr>
<tr><td>20</td><td>List of all clearing members (Article 17 of Regulation (EU) No XXX/2012)</td><td><em>Free text / Document</em></td><td>List in accordance with Article 17 of Regulation (EU) No XXX/2012.</td></tr>
<tr><td>21</td><td>Information required by Article 17 of Regulation (EU) No XXX/2012</td><td><em>Free text / Documents</em></td><td>Law and Rules governing (i) the access to the CCP, (ii) the contracts concluded by the CCP with clearing members and, where practicable, clients, (iii) the contracts that the CCP accepts for clearing, (iv) any interoperability arrangements, (v) the use of collateral and default fund contributions, including the liquidation of positions and collateral and the extent to which collateral is protected against third party claims (level of segregation).</td></tr>
<tr><td>22</td><td>Development on new initiative processes</td><td><em>Free text</em></td><td>In case of the provision of new services.</td></tr>
</tbody>
</table>

## Annotations

[^key-cb16621150d7c7fa74d9ab3a2c6740a3]: Modification: The “appropriate regulator” has power to make such provision as they consider appropriate by means of an instrument in writing to prevent, remedy or mitigate any failure of the provisions of this Regulation to operate effectively or any other deficiency arising from the withdrawal of the United Kingdom from the EU, see The Financial Regulators' Powers (Technical Standards etc.) (Amendment etc.) (EU Exit) Regulations 2018 (S.I. 2018/1115), [regs. 2](https://www.legislation.gov.uk/uksi/2018/1115/regulation/2), [3](https://www.legislation.gov.uk/uksi/2018/1115/regulation/3), [Sch. Pt. 3](https://www.legislation.gov.uk/uksi/2018/1115/schedule/part/3) (with saving on [I](https://www.legislation.gov.uk/uksi/2018/1115/schedule/part/I)P completion day by S.I. 2019/680, [regs. 1(2)](https://www.legislation.gov.uk/uksi/2019/680/regulation/1/2), [11](https://www.legislation.gov.uk/uksi/2019/680/regulation/11); 2020 c. 1, [Sch. 5 para. 1(1)](https://www.legislation.gov.uk/ukpga/2020/1/schedule/5/paragraph/1/1))

[^key-7e7ecb1d4ae73acd8e41a7713e1930fe]: Modification: Regulation: power to modify conferred (11.7.2023) by [Financial Services and Markets Act 2023 (c. 29)](https://www.legislation.gov.uk/ukpga/2023/29), [ss. 3](https://www.legislation.gov.uk/ukpga/2023/29/section/3), [86(3)](https://www.legislation.gov.uk/ukpga/2023/29/section/86/3), [Sch. 1 Pts. 1](https://www.legislation.gov.uk/ukpga/2023/29/schedule/1/part/1), [3](https://www.legislation.gov.uk/ukpga/2023/29/schedule/1/part/3); [S.I. 2023/779](https://www.legislation.gov.uk/uksi/2023/779), [reg. 2(d)](https://www.legislation.gov.uk/uksi/2023/779/regulation/2/d)

[^f00001]: Footnote: Not yet published in the Official Journal.

[^f00002]: Footnote: [OJ L 201. 27.7.2012, p. 1](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2012.201.01.0001.01.ENG).

[^f00003]: Footnote: [OJ L 331, 15.12.2010, p. 84](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2010.331.01.0084.01.ENG).
