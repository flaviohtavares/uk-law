---
title: Commission Implementing Regulation (EU) 2019/2221 of 12 December 2019 amending Implementing Regulation (EU) No 612/2013 as regards the data registered in messages relating to the registration of economic operators and tax warehouses in the national registers and the Central Register
id: eur/2019/2221
type: EuropeanUnionRegulation
category: euretained
status: revised
made_date: '2019-12-12'
text_date: '2019-12-12'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eur/2019/2221
pdf_urls:
- http://www.legislation.gov.uk/eur/2019/2221/pdfs/eur_20192221_adopted_en.pdf
- http://www.legislation.gov.uk/eur/2019/2221/data.pdf
pending_changes: 0
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Commission Implementing Regulation (EU) 2019/2221 of 12 December 2019 amending Implementing Regulation (EU) No 612/2013 as regards the data registered in messages relating to the registration of economic operators and tax warehouses in the national registers and the Central Register

> Text as at 2019-12-12.
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Commission Implementing Regulation (EU) 2019/2221

of 12 December 2019

amending Implementing Regulation (EU) No 612/2013 as regards the data registered in messages relating to the registration of economic operators and tax warehouses in the national registers and the Central Register

THE EUROPEAN COMMISSION,

Having regard to the Treaty on the Functioning of the European Union,

Having regard to Council Regulation (EU) No 389/2012 of 2 May 2012 on administrative cooperation in the field of excise duties and repealing Regulation (EC) No 2073/2004[^f00001], and in particular Article 22 thereof,

Whereas:

(1)

Annex I to Commission Implementing Regulation (EU) No 612/2013[^f00002] lays down the structure and content of messages relating to the registration of economic operators and tax warehouses in the national registers and the Central Register.

(2)

In order to achieve consistency between the structure of common request messages defined in Implementing Regulation (EU) No 612/2013 and in Commission Implementing Regulation (EU) 2016/323[^f00003], the possible values for the ‘Request Type’ data item should be modified in Table 1 of Annex I to Implementing Regulation (EU) No 612/2013 taking into account changes in the data requirements of a new version of the computerised system established by Decision No 1152/2003/EC of the European Parliament and of the Council[^f00004].

(3)

The explanation in column F in Table 1 of Annex I to Implementing Regulation (EU) No 612/2013 should be updated to provide a clear identification of the ‘Value’ data element when the ‘Primary Criterion’ type code is set to the value ‘46 = Type of Transport’.

(4)

There is a need for further technical corrections of Table 1 of Annex I to Implementing Regulation (EU) No 612/2013 in order to bring clarity and precision to the applicable provisions.

(5)

Implementing Regulation (EU) No 612/2013 should therefore be amended accordingly.

(6)

In order to align the application date of this Regulation with the application date for a new version of the computerised system established by Decision No 1152/2003/EC, this Regulation should apply from 13 February 2020.

(7)

The measures provided for in this Regulation are in accordance with the opinion of the Committee on Excise Duty,

HAS ADOPTED THIS REGULATION:

**Article 1.** Annex I to Implementing Regulation (EU) No 612/2013 is amended in accordance with the Annex to this Regulation.

**Article 2.** This Regulation shall enter into force on the twentieth day following that of its publication in the *Official Journal of the European Union*.

It shall apply from 13 February 2020.

This Regulation shall be binding in its entirety and directly applicable in all Member States.

Done at Brussels, 12 December 2019.

*For the Commission*

*The President*

Ursula Von Der Leyen

## ANNEX

In Annex I to Regulation (EU) No 612/2013, Table 1 is replaced by the following:

*‘Table 1*

**Common request**

<table>
<thead>
<tr><td colspan="7">(referred to in Article 4(5), Article 7(2) and Article 8(2))</td></tr>
</thead>
<tbody>
<tr><th>A</th><th>B</th><th>C</th><th>D</th><th>E</th><th>F</th><th>G</th></tr>
<tr><td colspan="2"><strong>1</strong></td><td><strong>ATTRIBUTES</strong></td><td>R</td><td></td><td></td><td></td></tr>
<tr><td></td><td><em>a</em></td><td>Request Type</td><td>R</td><td></td><td>The possible values are:<br>1<br>(reserved)<br>2<br>Request for reference data<br>3<br>(reserved)<br>4<br>(reserved)<br>5<br>Request for re-synchronisation of the register of economic operators<br>6<br>Request for retrieval of a list of e-ADs<br>7<br>Request for SEED statistics</td><td>n1</td></tr>
<tr><td></td><td><em>b</em></td><td>Request Message Name</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td>The possible values are:<br>‘C_COD_DAT’<br>Common list of codes<br>‘C_PAR_DAT’<br>Common system parameters<br>‘ALL’<br>For complete structure</td><td>a..9</td></tr>
<tr><td></td><td><em>c</em></td><td>Requesting Office</td><td>R</td><td></td><td><em>(see Code list 5 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an8</td></tr>
<tr><td></td><td><em>d</em></td><td>Request Correlation Identifier</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’, ‘5’, ‘6’ or ‘7’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td>The value of &lt;Request Correlation Identifier&gt; is unique per Member State.</td><td>an..44</td></tr>
<tr><td></td><td><em>e</em></td><td>Start Date</td><td>C</td><td rowspan="2">For 1 <em>e</em> and <em>f</em>:<br>‘R’ if &lt;Request Type&gt; is ‘2’ or ‘5’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td>date</td></tr>
<tr><td></td><td><em>f</em></td><td>End Date</td><td>C</td><td></td><td>date</td></tr>
<tr><td></td><td><em>g</em></td><td>Single Date</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’ or ‘5’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td>date</td></tr>
<tr><td colspan="2"><strong>2</strong></td><td><strong>E-AD LIST REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘6’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
<tr><td></td><td><em>a</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
<tr><td colspan="2"><strong>2.1</strong></td><td><strong>RA_PRIMARY CRITERION</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
<tr><td></td><td><em>a</em></td><td>Primary Criterion Type Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>ARC<br>2<br>Brand name of product<br>3<br>Categories of excise products of the movement<br>4<br>(reserved)<br>5<br>(reserved)<br>6<br>(reserved)<br>7<br>(reserved)<br>8<br>City of consignee<br>9<br>City of consignor<br>10<br>City of guarantor<br>11<br>(reserved)<br>12<br>City of place of delivery<br>13<br>City of tax warehouse of dispatch<br>14<br>City of transporter<br>15<br>CN code of product<br>16<br>Date of invoice<br>17<br>Excise number of consignee<br>18<br>Excise number of consignor<br>19<br>Excise number of guarantor<br>20<br>(reserved)<br>21<br>(reserved)<br>22<br>Excise number of the tax warehouse of destination<br>23<br>Excise number of the tax warehouse of dispatch<br>24<br>(reserved)<br>25<br>Excise product code<br>26<br>Journey time<br>27<br>Member State of destination<br>28<br>Member State of dispatch<br>29<br>Name of consignee<br>30<br>Name of consignor<br>31<br>Name of guarantor<br>32<br>(reserved)<br>33<br>Name of place of delivery<br>34<br>Name of tax warehouse of dispatch<br>35<br>Name of transporter<br>36<br>Number of invoice<br>37<br>Postal code of consignee<br>38<br>Postal code of consignor<br>39<br>Postal code of guarantor<br>40<br>(reserved)<br>41<br>Postal code of place of delivery<br>42<br>Postal code of tax warehouse of dispatch<br>43<br>Postal code of transporter<br>44<br>Quantity of goods (in an e-AD body)<br>45<br>Local Reference Number, being a serial number, assigned by the consignor<br>46<br>Type of transport<br>47<br>(reserved)<br>48<br>(reserved)<br>49<br>VAT number of the consignee<br>50<br>(reserved)<br>51<br>VAT number of the transporter<br>52<br>Change of destination (sequence number ≥ 2)</td><td>n..2</td></tr>
<tr><td colspan="2"><strong>2.1.1</strong></td><td><strong>RA_PRIMARY VALUE</strong></td><td>O</td><td></td><td></td><td>99x</td></tr>
<tr><td></td><td><em>a</em></td><td>Value</td><td>R</td><td></td><td>If &lt;Primary Criterion Type Code&gt; is ‘46’ (Type of transport), then an existing &lt;Transport Mode Code&gt; in the list of &lt;TRANSPORT MODES&gt; shall be used.</td><td>an..255</td></tr>
<tr><td colspan="2"><strong>3</strong></td><td><strong>STA_REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘7’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
<tr><td></td><td><em>a</em></td><td>Statistic Type</td><td>R</td><td></td><td>The possible values are:<br>1<br>Active and inactive economic operators<br>2<br>Pending expirations<br>3<br>Economic operators by type and tax warehouses<br>4<br>Excise activity<br>5<br>Changes to excise authorisations</td><td>n1</td></tr>
<tr><td colspan="2"><strong>3.1</strong></td><td><strong>LIST OF MEMBER STATES Code</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
<tr><td></td><td><em>a</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
<tr><td colspan="2"><strong>4</strong></td><td><strong>STA_PERIOD</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘7’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
<tr><td></td><td><em>a</em></td><td>Year</td><td>R</td><td></td><td></td><td>n4</td></tr>
<tr><td></td><td><em>b</em></td><td>Semester</td><td>C</td><td rowspan="3">For 4 <em>b</em>, <em>c</em>, and <em>d</em>:<br>The three following data fields are optional and exclusive:<br>&lt;Semester&gt;<br>&lt;Quarter&gt;<br>&lt;Month&gt;<br>i.e. If one of these data fields is given then the two other data fields do not apply</td><td>The possible values are:<br>1<br>First semester<br>2<br>Second semester</td><td>n1</td></tr>
<tr><td></td><td><em>c</em></td><td>Quarter</td><td>C</td><td>The possible values are:<br>1<br>First quarter<br>2<br>Second quarter<br>3<br>Third quarter<br>4<br>Fourth quarter</td><td>n1</td></tr>
<tr><td></td><td><em>d</em></td><td>Month</td><td>C</td><td>The possible values are:<br>1<br>January<br>2<br>February<br>3<br>March<br>4<br>April<br>5<br>May<br>6<br>June<br>7<br>July<br>8<br>August<br>9<br>September<br>10<br>October<br>11<br>November<br>12<br>December</td><td>n..2</td></tr>
<tr><td colspan="2"><strong>5</strong></td><td><strong>REF_REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
<tr><td></td><td><em>a</em></td><td>Common Risk Assessment Criteria flag</td><td>O</td><td></td><td>The possible values are:<br>0<br>No or False<br>1<br>Yes or True</td><td>n1</td></tr>
<tr><td colspan="2"><strong>5.1</strong></td><td><strong>LIST OF CODES Code</strong></td><td>O</td><td></td><td></td><td>99x</td></tr>
<tr><td></td><td><em>a</em></td><td>Requested List of Code</td><td>O</td><td></td><td>The possible values are:<br>1<br>Units of measure<br>2<br>Events types<br>3<br>Evidence types<br>4<br>(reserved)<br>5<br>(reserved)<br>6<br>Language codes<br>7<br>Member States<br>8<br>Country codes<br>9<br>Packaging codes<br>10<br>Reasons for unsatisfactory receipt or control report<br>11<br>Reasons for interruption<br>12<br>(reserved)<br>13<br>Transport modes<br>14<br>Transport units<br>15<br>Wine-growing zones<br>16<br>Wine operation codes<br>17<br>Excise product categories<br>18<br>Excise products<br>19<br>CN codes<br>20<br>Correspondences CN code Excise product<br>21<br>Cancellation reasons<br>22<br>Alert or rejection of e-AD reasons<br>23<br>Delay explanations<br>24<br>(reserved)<br>25<br>Event submitting persons<br>26<br>Refusal reasons<br>27<br>Reasons for delayed result<br>28<br>Request actions<br>29<br>Request reasons<br>30<br>(reserved)<br>31<br>(reserved)<br>32<br>(reserved)<br>33<br>(reserved)<br>34<br>Administrative cooperation action not possible reasons<br>35<br>(reserved)<br>36<br>Type of document<br>37<br>(reserved)<br>38<br>(reserved)<br>39<br>Manual Closure Request Reasons<br>40<br>Manual Closure Rejection Reasons’</td><td>n..2</td></tr>
</tbody>
</table>

## Annotations

[^f00001]: Footnote: [OJ L 121, 8.5.2012, p. 1](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2012.121.01.0001.01.ENG).

[^f00002]: Footnote: Commission Implementing Regulation (EU) No 612/2013 of 25 June 2013 on the operation of the register of economic operators and tax warehouses, related statistics and reporting pursuant to Council Regulation (EU) No 389/2012 on administrative cooperation in the field of excise duties ([OJ L 173, 26.6.2013, p. 9](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2013.173.01.0009.01.ENG)).

[^f00003]: Footnote: Commission Implementing Regulation (EU) 2016/323 of 24 February 2016 laying down detailed rules on cooperation and exchange of information between Member States regarding goods under excise duty suspension pursuant to Council Regulation (EU) No 389/2012 ([OJ L 66, 11.3.2016, p. 1](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2016.066.01.0001.01.ENG)).

[^f00004]: Footnote: Decision No 1152/2003/EC of the European Parliament and of the Council of 16 June 2003 on computerising the movement and surveillance of excisable products ([OJ L 162, 1.7.2003, p. 5](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2003.162.01.0005.01.ENG)).
