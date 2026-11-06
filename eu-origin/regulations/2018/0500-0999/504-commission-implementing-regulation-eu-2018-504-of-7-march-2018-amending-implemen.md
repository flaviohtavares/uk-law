---
title: Commission Implementing Regulation (EU) 2018/504 of 7 March 2018 amending Implementing Regulation (EU) No 612/2013 on the operation of the register of economic operators and tax warehouses, related statistics and reporting pursuant to Council Regulation (EU) No 389/2012 on administrative cooperation in the field of excise duties
id: eur/2018/504
type: EuropeanUnionRegulation
category: euretained
status: revised
made_date: '2018-03-07'
text_date: '2018-03-07'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eur/2018/504
pdf_urls:
- http://www.legislation.gov.uk/eur/2018/504/pdfs/eur_20180504_adopted_en.pdf
- http://www.legislation.gov.uk/eur/2018/504/data.pdf
pending_changes: 0
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Commission Implementing Regulation (EU) 2018/504 of 7 March 2018 amending Implementing Regulation (EU) No 612/2013 on the operation of the register of economic operators and tax warehouses, related statistics and reporting pursuant to Council Regulation (EU) No 389/2012 on administrative cooperation in the field of excise duties

> Text as at 2018-03-07.
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Commission Implementing Regulation (EU) 2018/504

of 7 March 2018

amending Implementing Regulation (EU) No 612/2013 on the operation of the register of economic operators and tax warehouses, related statistics and reporting pursuant to Council Regulation (EU) No 389/2012 on administrative cooperation in the field of excise duties

THE EUROPEAN COMMISSION,

Having regard to the Treaty on the Functioning of the European Union,

Having regard to Council Regulation (EU) No 389/2012 of 2 May 2012 on administrative cooperation in the field of excise duties and repealing Regulation (EC) No 2073/2004[^f00001], and in particular Article 22 thereof,

Whereas:

(1)

Annex I to Commission Implementing Regulation (EU) No 612/2013[^f00002] lays down the structure and content of messages relating to the registration of economic operators and tax warehouses in the national registers and the Central Register. In order to improve the quality of data used in those messages Tables 1, 2 and 4 of Annex I to Implementing Regulation (EU) No 612/2013 should be amended.

(2)

In accordance with Article 22 of Council Directive 2008/118/EC[^f00003] in the case of movement of energy products under a duty suspension arrangement by sea or inland waterways, the competent authorities of the Member State of dispatch may authorise the consignor to omit the details of the consignee at the time of dispatch in the draft electronic administrative document referred to in Article 21(2) of that Directive. In accordance with Regulation (EU) No 612/2013 only an authorised warehouse keeper is allowed to omit the details of the consignee. Therefore it is also necessary to enable a registered consignor to leave empty the destination fields in the draft electronic administrative document when moving energy products under duty suspension arrangement by sea or inland waterways in order to align with Article 22 of Directive 2008/118/EC.

(3)

The explanation in column F of Table 1 of Annex I to Implementing Regulation (EU) No 612/2013 should provide a clearer identification of the ‘Requesting Office’ data element in order to align with the definition in Annex II to Regulation (EC) No 684/2009.

(4)

Implementing Regulation (EU) No 612/2013 should therefore be amended accordingly.

(5)

In order to align the application date of this Regulation with the application date for a new version of the computerised system established by Decision No 1152/2003/EC of the European Parliament and of the Council[^f00004] and to allow the Member States adequate time to prepare for the changes resulting from this Regulation, it should apply from 15 February 2018.

(6)

The measures provided for in this Regulation are in accordance with the opinion of the Committee on Excise Duty,

HAS ADOPTED THIS REGULATION:

**Article 1.** Annex I of Implementing Regulation (EU) No 612/2013 is amended as set out in the Annex to this Regulation.

**Article 2.** This Regulation shall enter into force on the twentieth day following that of its publication in the *Official Journal of the European Union*.

It shall apply from 15 February 2018.

This Regulation shall be binding in its entirety and directly applicable in all Member States.

Done at Brussels, 7 March 2018.

*For the Commission*

*The President*

Jean-Claude Juncker

## ANNEX

Annex I to Implementing Regulation (EU) No 612/2013 is amended as follows:

- ((1)) Tables 1 and 2 are replaced by the following:

  > *Table 1*
  >
  > **Common request**
  >
  > (referred to in Article 4(5), Article 7(2) and Article 8(2))
  >
  > <table>
  > <tbody>
  > <tr><th>A</th><th>B</th><th>C</th><th>D</th><th>E</th><th>F</th><th>G</th></tr>
  > <tr><td colspan="2"><strong>1</strong></td><td><strong>ATTRIBUTES</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Request Type</td><td>R</td><td></td><td>The possible values are:<br>2<br>Request for extraction of reference data<br>3<br>Request for retrieval of reference data<br>4<br>Request for extraction of economic operators<br>5<br>Request for retrieval of economic operators<br>6<br>Request for EOL<br>7<br>Request for retrieval of a list of e-ADs<br>8<br>Request for SEED statistics</td><td>n1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Request Message Name</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’ or ‘3’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td>The possible values are:<br>“C_COD_DAT”<br>Common list of codes<br>“C_PAR_DAT”<br>Common system parameters<br>“ALL”<br>For complete structure</td><td>a..9</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Requesting Office</td><td>R</td><td></td><td><em>(see Code list 5 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an8</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Request Correlation Identifier</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’, ‘3’, ‘4’, ‘5’, ‘7’, or ‘8’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td>The value of &lt;Request Correlation Identifier&gt; is unique per Member State</td><td>an..44</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Start Date</td><td>C</td><td rowspan="2">For 1 <em>e</em> and <em>f</em>:<br>‘R’ if &lt;Request Type&gt; is ‘3’ or ‘5’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>f</em></td><td>End Date</td><td>C</td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>g</em></td><td>Single Date</td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’ or ‘4’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td>date</td></tr>
  > <tr><td colspan="2"><strong>2</strong></td><td><strong>E-AD LIST REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘7’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>2.1</strong></td><td><strong>RA_PRIMARY CRITERION</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Primary Criterion Type Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>ARC<br>2<br>Brand name of product<br>3<br>Categories of excise products of the movement<br>4<br>(reserved)<br>5<br>(reserved)<br>6<br>(reserved)<br>7<br>(reserved)<br>8<br>City of consignee<br>9<br>City of consignor<br>10<br>City of guarantor<br>11<br>(reserved)<br>12<br>City of place of delivery<br>13<br>City of tax warehouse of dispatch<br>14<br>City of transporter<br>15<br>CN code of product<br>16<br>Date of invoice<br>17<br>Excise number of consignee<br>18<br>Excise number of consignor<br>19<br>Excise number of guarantor<br>20<br>(reserved)<br>21<br>(reserved)<br>22<br>Excise number of the tax warehouse of destination<br>23<br>Excise number of the tax warehouse of dispatch<br>24<br>(reserved)<br>25<br>Excise product code<br>26<br>Journey time<br>27<br>Member State of destination<br>28<br>Member State of dispatch<br>29<br>Name of consignee<br>30<br>Name of consignor<br>31<br>Name of guarantor<br>32<br>(reserved)<br>33<br>Name of place of delivery<br>34<br>Name of tax warehouse of dispatch<br>35<br>Name of transporter<br>36<br>Number of invoice<br>37<br>Postal code of consignee<br>38<br>Postal code of consignor<br>39<br>Postal code of guarantor<br>40<br>(reserved)<br>41<br>Postal code of place of delivery<br>42<br>Postal code of tax warehouse of dispatch<br>43<br>Postal code of transporter<br>44<br>Quantity of goods (in an e-AD body)<br>45<br>Local Reference Number, being a serial number, assigned by the consignor<br>46<br>Type of transport<br>47<br>(reserved)<br>48<br>(reserved)<br>49<br>VAT number of the consignee<br>50<br>(reserved)<br>51<br>VAT number of the transporter<br>52<br>Change of destination (sequence number ≥ 2)</td><td>n..2</td></tr>
  > <tr><td colspan="2"><strong>2.1.1</strong></td><td><strong>RA_PRIMARY VALUE</strong></td><td>O</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Value</td><td>R</td><td></td><td></td><td>an..255</td></tr>
  > <tr><td colspan="2"><strong>3</strong></td><td><strong>STA_REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘8’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Statistic Type</td><td>R</td><td></td><td>The possible values are:<br>1<br>Active and inactive economic operators<br>2<br>Pending expirations<br>3<br>Economic operators by type and tax warehouses<br>4<br>Excise activity<br>5<br>Changes to excise authorisations</td><td>n1</td></tr>
  > <tr><td colspan="2"><strong>3.1</strong></td><td><strong>LIST OF MEMBER STATES Code</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>4</strong></td><td><strong>STA_PERIOD</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘8’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Year</td><td>R</td><td></td><td></td><td>n4</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Semester</td><td>C</td><td rowspan="3">For 4 <em>b</em>, <em>c</em>, and <em>d</em>:<br>The three following data fields are optional and exclusive:<br>&lt;Semester&gt;<br>&lt;Quarter&gt;<br>&lt;Month&gt;<br>i.e. If one of these data fields is given then the two other data fields do not apply</td><td>The possible values are:<br>1<br>First semester<br>2<br>Second semester</td><td>n1</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Quarter</td><td>C</td><td>The possible values are:<br>1<br>First quarter<br>2<br>Second quarter<br>3<br>Third quarter<br>4<br>Fourth quarter</td><td>n1</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Month</td><td>C</td><td>The possible values are:<br>1<br>January<br>2<br>February<br>3<br>March<br>4<br>April<br>5<br>May<br>6<br>June<br>7<br>July<br>8<br>August<br>9<br>September<br>10<br>October<br>11<br>November<br>12<br>December</td><td>n..2</td></tr>
  > <tr><td colspan="2"><strong>5</strong></td><td><strong>REF_REQUEST</strong></td><td>C</td><td>‘R’ if &lt;Request Type&gt; is ‘2’ or ‘3’<br>Does not apply otherwise<br><em>(see Request Type in box 1a)</em></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Common Risk Assessment Criteria flag</td><td>O</td><td></td><td>The possible values are:<br>0<br>No or False<br>1<br>Yes or True</td><td>n1</td></tr>
  > <tr><td colspan="2"><strong>5.1</strong></td><td><strong>LIST OF CODES Code</strong></td><td>O</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Requested List of Code</td><td>O</td><td></td><td>The possible values are:<br>1<br>Units of measure<br>2<br>Events types<br>3<br>Evidence types<br>4<br>(reserved)<br>5<br>(reserved)<br>6<br>Language codes<br>7<br>Member states<br>8<br>Country codes<br>9<br>Packaging codes<br>10<br>Reasons for unsatisfactory receipt or control report<br>11<br>Reasons for interruption<br>12<br>(reserved)<br>13<br>Transport modes<br>14<br>Transport units<br>15<br>Wine-growing zones<br>16<br>Wine operation codes<br>17<br>Excise product categories<br>18<br>Excise products<br>19<br>CN codes<br>20<br>Correspondences CN code Excise product<br>21<br>Cancellation reasons<br>22<br>Alert or rejection of e-AD reasons<br>23<br>Delay explanations<br>24<br>(reserved)<br>25<br>Event submitting persons<br>26<br>Refusal reasons<br>27<br>Reasons for delayed result<br>28<br>Administrative cooperation actions<br>29<br>Administrative cooperation request reasons<br>30<br>(reserved)<br>31<br>(reserved)<br>32<br>(reserved)<br>33<br>(reserved)<br>34<br>Administrative cooperation action not possible reasons<br>35<br>Common request rejection reasons<br>36<br>(reserved)<br>37<br>Movement verification request reasons<br>38<br>Movement verification actions</td><td>n..2</td></tr>
  > </tbody>
  > </table>
  >
  > *Table 2*
  >
  > **Operations on the register of economic operators**
  >
  > (referred to in Article 3(3), Article 4(2) and (3) and Article 6(3))
  >
  > <table>
  > <tbody>
  > <tr><th>A</th><th>B</th><th>C</th><th>D</th><th>E</th><th>F</th><th>G</th></tr>
  > <tr><td colspan="2"><strong>1</strong></td><td><strong>ATTRIBUTES</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Message Type</td><td>R</td><td></td><td>The possible values are:<br>1<br>Update of economic operators (Notification of changes to CD/RD)<br>2<br>Dissemination of updates of economic operators<br>3<br>Retrieval of economic operators<br>4<br>Extraction of economic operators</td><td>n1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Request Correlation Identifier</td><td>C</td><td>‘R’ if &lt;Message Type&gt; is ‘3’ or ‘4’<br>Does not apply otherwise<br><em>(see Message Type in box 1a)</em></td><td>The value of &lt;Request Correlation Identifier&gt; is unique per Member State</td><td>an..44</td></tr>
  > <tr><td colspan="2"><strong>2</strong></td><td><strong>TRADER AUTHORISATION</strong></td><td>O</td><td></td><td></td><td>999999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Trader Excise Number</td><td>R</td><td></td><td><em>(See Code list 1 in Annex II)</em><br>The &lt;Trader Excise Number&gt; must be unique in the list of &lt;TRADER AUTHORISATION&gt;.</td><td>an13</td></tr>
  > <tr><td></td><td><em>b</em></td><td>VAT Number</td><td>O</td><td></td><td></td><td>an..14</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Authorisation Start Date</td><td>R</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Authorisation End Date</td><td>O</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Operator Type Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>Authorised warehouse keeper<br>2<br>Registered consignee<br>3<br>Registered consignor<br>The value of the &lt;Operator Type Code&gt; data item cannot be changed after the creation of the TRADER AUTHORISATION</td><td>n1</td></tr>
  > <tr><td></td><td><em>f</em></td><td>Excise Office Reference Number</td><td>R</td><td></td><td><em>(see Code list 5 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an8</td></tr>
  > <tr><td colspan="2"><strong>2.1</strong></td><td><strong>ACTION</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operation</td><td>R</td><td></td><td>The possible values are:<br>C<br>Create<br>U<br>Update<br>I<br>Invalidate</td><td>a1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Activation Date</td><td>C</td><td>‘R’ if &lt;Operation&gt; is ‘C’ or ‘U’<br>‘O’ otherwise<br><em>(see Operation in box 2.1a)</em></td><td>If &lt;Activation Date&gt; is not entered the Activation Date of the Invalidate operation is considered to be the date that the Invalidate operation is incorporated into the central register.</td><td>date</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Responsible Data Manager</td><td>O</td><td></td><td></td><td>an..35</td></tr>
  > <tr><td colspan="2"><strong>2.2</strong></td><td><strong>NAME AND ADDRESS</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Name</td><td>R</td><td></td><td></td><td>an..182</td></tr>
  > <tr><td></td><td><em>b</em></td><td>NAD_LNG</td><td>R</td><td></td><td><em>(see Code list 1 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>2.2.1</strong></td><td><strong>ADDRESS</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Street Name</td><td>R</td><td></td><td></td><td>an..65</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Street Number</td><td>O</td><td></td><td></td><td>an..11</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Postcode</td><td>R</td><td></td><td></td><td>an..10</td></tr>
  > <tr><td></td><td><em>d</em></td><td>City</td><td>R</td><td></td><td></td><td>an..50</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>2.3</strong></td><td><strong>OPERATOR ROLE Code</strong></td><td>O</td><td></td><td></td><td>9x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operator Role Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>Allowed to practise direct delivery<br>2<br>Allowed to leave empty the destination fields according to Article 22 of Directive 2008/118/EC.<br>The couplings &lt;Operator Type / Operator Role Code&gt; are as follows:<br><table><tbody><tr><th>OP/OR TYPE / OP/OR ROLE</th><th>AUTH. WH KEEPER</th><th>REG. CON/EE</th><th>REG. CON/OR</th></tr><tr><td>Allowed to practise direct delivery</td><td>X</td><td>X</td><td></td></tr><tr><td>Allowed to leave empty the destination fields according to Article 22 of Directive 2008/118/EC</td><td>X</td><td></td><td>X</td></tr></tbody></table></td><td>n1</td></tr>
  > <tr><td colspan="2"><strong>2.4</strong></td><td><strong>EXCISE PRODUCTS CATEGORY Code</strong></td><td>C</td><td>At least one of the &lt;EXCISE PRODUCTS CATEGORY code&gt; or &lt;EXCISE PRODUCT code&gt; data groups must be present</td><td></td><td>999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Products Category Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II)</em><br>The &lt;Excise Products Category Code&gt; must be unique in the list of &lt;EXCISE PRODUCTS CATEGORY Code&gt; inside the same &lt;TRADER AUTHORISATION&gt; or &lt;TAX WAREHOUSE&gt;</td><td>a1</td></tr>
  > <tr><td colspan="2"><strong>2.5</strong></td><td><strong>EXCISE PRODUCT Code</strong></td><td>C</td><td>At least one of the &lt;EXCISE PRODUCTS CATEGORY code&gt; or &lt;EXCISE PRODUCT code&gt; data groups must be present</td><td></td><td>999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Product Code</td><td>R</td><td></td><td><em>(see Code list 11 in Annex II to Regulation (EC) No 684/2009)</em><br>The &lt;Excise Products Category Code&gt; of the &lt;Excise Product Code&gt; must not exist inside the same &lt;TRADER AUTHORISATION&gt; or &lt;TAX WAREHOUSE&gt;<br>The &lt;Excise Product Code&gt; must be unique in the list of &lt;EXCISE PRODUCT Code&gt; inside the same &lt;TRADER AUTHORISATION&gt;, &lt;TAX WAREHOUSE&gt;, or &lt;TEMPORARY AUTHORISATION&gt;</td><td>an..4</td></tr>
  > <tr><td colspan="2"><strong>2.6</strong></td><td><strong>(USING) TAX WAREHOUSE</strong></td><td>C</td><td>‘R’ if &lt;Operator Type Code&gt; is ‘Authorised warehouse keeper’<br>Does not apply otherwise<br><em>(see Operator Type Code in box 2e)</em></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Tax Warehouse Reference</td><td>R</td><td></td><td><em>(see Code list 1in Annex II)</em><br>The “Tax Warehouse Reference” shall be one of the &lt;TAX WAREHOUSE. Tax Warehouse Reference&gt; such that there exists at least one Active version having its Validity Interval intersecting the Validity Interval of the &lt;TRADER AUTHORISATION&gt;, after the Activation Date of the latter, by at least one day<br>The &lt;Tax Warehouse Reference&gt; must be unique in the list of &lt;TAX WAREHOUSE&gt;.</td><td>an13</td></tr>
  > <tr><td colspan="2"><strong>3</strong></td><td><strong>TAX WAREHOUSE</strong></td><td>O</td><td></td><td></td><td>999999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Tax Warehouse Reference</td><td>R</td><td></td><td><em>(see Code list 1 in Annex II)</em><br>The &lt;Tax Warehouse Reference&gt; must be unique in the list of &lt;TAX WAREHOUSE&gt;.<br>The “Tax Warehouse Reference” shall be the same as one of the &lt;(USING) TAX WAREHOUSE. Tax Warehouse Reference&gt; within one or more &lt;TRADER AUTHORISATION&gt; data groups of “Authorised Warehouse Keeper” type satisfying also Rule204</td><td>an13</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Validity Begin Date</td><td>R</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Validity End Date</td><td>O</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Excise Office Reference Number</td><td>R</td><td></td><td><em>(see Code list 5 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an8</td></tr>
  > <tr><td colspan="2"><strong>3.1</strong></td><td><strong>ACTION</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operation</td><td>R</td><td></td><td>The possible values are:<br>C<br>Create<br>U<br>Update<br>I<br>Invalidate</td><td>a1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Activation Date</td><td>C</td><td>‘R’ if &lt;Operation&gt; is ‘C’ or ‘U’<br>‘O’ otherwise<br><em>(see Operation in box 3.1a)</em></td><td>If &lt;Activation Date&gt; is not entered the Activation Date of the Invalidate operation is considered to be the date that the Invalidate operation is incorporated into the central register.</td><td>date</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Responsible Data Manager</td><td>O</td><td></td><td></td><td>an..35</td></tr>
  > <tr><td colspan="2"><strong>3.2</strong></td><td><strong>NAME AND ADDRESS</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Name</td><td>R</td><td></td><td></td><td>an..182</td></tr>
  > <tr><td></td><td><em>b</em></td><td>NAD_LNG</td><td>R</td><td></td><td><em>(see Code list 1 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>3.2.1</strong></td><td><strong>ADDRESS</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Street Name</td><td>R</td><td></td><td></td><td>an..65</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Street Number</td><td>O</td><td></td><td></td><td>an..11</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Postcode</td><td>R</td><td></td><td></td><td>an..10</td></tr>
  > <tr><td></td><td><em>d</em></td><td>City</td><td>R</td><td></td><td></td><td>an..50</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>3.4</strong></td><td><strong>EXCISE PRODUCTS CATEGORY Code</strong></td><td>C</td><td>At least one of the &lt;EXCISE PRODUCTS CATEGORY code&gt; or &lt;EXCISE PRODUCT code&gt; data groups must be present</td><td></td><td>999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Products Category Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II)</em><br>The &lt;Excise Products Category Code&gt; must be unique in the list of &lt;EXCISE PRODUCTS CATEGORY Code&gt; inside the same &lt;TRADER AUTHORISATION&gt; or &lt;TAX WAREHOUSE&gt;</td><td>an1</td></tr>
  > <tr><td colspan="2"><strong>3.5</strong></td><td><strong>EXCISE PRODUCT Code</strong></td><td>C</td><td>At least one of the &lt;EXCISE PRODUCTS CATEGORY code&gt; or &lt;EXCISE PRODUCT code&gt; data groups must be present</td><td></td><td>999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Product Code</td><td>R</td><td></td><td><em>(see Code list 11 in Annex II to Regulation (EC) No 684/2009)</em><br>The &lt;Excise Products Category Code&gt; of the &lt;Excise Product Code&gt; must not exist inside the same &lt;TRADER AUTHORISATION&gt; or &lt;TAX WAREHOUSE&gt;<br>The &lt;Excise Product Code&gt; must be unique in the list of &lt;EXCISE PRODUCT Code&gt; inside the same &lt;TRADER AUTHORISATION&gt;, &lt;TAX WAREHOUSE&gt;, or &lt;TEMPORARY AUTHORISATION&gt;</td><td>an..4</td></tr>
  > <tr><td colspan="2"><strong>4</strong></td><td><strong>TEMPORARY AUTHORISATION</strong></td><td>O</td><td></td><td></td><td>999999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Temporary Authorisation Reference</td><td>R</td><td></td><td><em>(see Code list 2 in Annex II)</em></td><td>an13</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Office Reference Number of Issuance</td><td>R</td><td></td><td><em>(see Code list 5 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an8</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Date of Expiry</td><td>R</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Re-usable Temporary Authorisation flag</td><td>R</td><td></td><td>The possible values are:<br>0<br>No or False<br>1<br>Yes or True</td><td>n1</td></tr>
  > <tr><td></td><td><em>e</em></td><td>VAT Number</td><td>O</td><td></td><td></td><td>an..14</td></tr>
  > <tr><td></td><td><em>f</em></td><td>Authorisation Start Date</td><td>R</td><td></td><td></td><td>date</td></tr>
  > <tr><td></td><td><em>g</em></td><td>Small Wine Producer flag</td><td>O</td><td></td><td>The possible values are:<br>0<br>No or False<br>1<br>Yes or True</td><td>n1</td></tr>
  > <tr><td colspan="2"><strong>4.1</strong></td><td><strong>ACTION</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operation</td><td>R</td><td></td><td>The possible values are:<br>C<br>Create<br>U<br>Update<br>I<br>Invalidate</td><td>a1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Activation Date</td><td>C</td><td>‘R’ if &lt;Operation&gt; is ‘C’ or ‘U’<br>‘O’ otherwise<br><em>(see Operation in box 4.1a)</em></td><td>If &lt;Activation Date&gt; is not entered the Activation Date of the Invalidate operation is considered to be the date that the Invalidate operation is incorporated into the central register.</td><td>date</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Responsible Data Manager</td><td>O</td><td></td><td></td><td>an..35</td></tr>
  > <tr><td colspan="2"><strong>4.2</strong></td><td><strong>TRADER Consignor</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Trader Excise Number</td><td>C</td><td>‘R’ if &lt;Temporary Authorisation – Small Wine Producer flag&gt; is not present or is False<br>‘O’ otherwise</td><td>For TRADER Consignor<br>An existing identifier &lt;Trader Excise Number&gt; in the set of &lt;TRADER AUTHORISATION&gt;<br>The &lt;Operator Type Code&gt; of the referred &lt;TRADER&gt; must be:<br>“Authorised warehouse keeper”; OR<br>“Registered consignor”</td><td>an13</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Trader Name</td><td>R</td><td></td><td></td><td>an..182</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Street Name</td><td>R</td><td></td><td></td><td>an..65</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Street Number</td><td>O</td><td></td><td></td><td>an..11</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Postcode</td><td>R</td><td></td><td></td><td>an..10</td></tr>
  > <tr><td></td><td><em>f</em></td><td>City</td><td>R</td><td></td><td></td><td>an..50</td></tr>
  > <tr><td></td><td><em>g</em></td><td>NAD_LNG</td><td>R</td><td></td><td><em>(see Code list 1 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>4.3</strong></td><td><strong>TEMPORARY AUTHORISATION DETAILS</strong></td><td>R</td><td></td><td></td><td>999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Product Code</td><td>R</td><td></td><td><em>(see Code list 11 in Annex II to Regulation (EC) No 684/2009)</em><br>The &lt;Excise Product Code&gt; must be unique in the list of &lt;EXCISE PRODUCT Code&gt; inside the same &lt;TRADER AUTHORISATION&gt;, &lt;TAX WAREHOUSE&gt;, or &lt;TEMPORARY AUTHORISATION&gt;<br>If &lt;Temporary Authorisation – Small Wine Producer&gt; is present and is True THEN the<br>&lt;Excise Product Code&gt; must be either:<br>“W200”; OR<br>“W300”</td><td>an..4</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Quantity</td><td>R</td><td></td><td></td><td>n..15,3</td></tr>
  > <tr><td colspan="2"><strong>4.4</strong></td><td><strong>NAME AND ADDRESS</strong></td><td>R</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Name</td><td>R</td><td></td><td></td><td>an..182</td></tr>
  > <tr><td></td><td><em>b</em></td><td>NAD_LNG</td><td>R</td><td></td><td><em>(see Annex II, Code list 1 of Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td colspan="2"><strong>4.4.1</strong></td><td><strong>ADDRESS</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Street Name</td><td>R</td><td></td><td></td><td>an..65</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Street Number</td><td>O</td><td></td><td></td><td>an..11</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Postcode</td><td>R</td><td></td><td></td><td>an..10</td></tr>
  > <tr><td></td><td><em>d</em></td><td>City</td><td>R</td><td></td><td></td><td>an..50</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > </tbody>
  > </table>
- ((2)) Table 4 is replaced by the following:

  > *Table 4*
  >
  > **SEED statistics**
  >
  > (referred to in Article 7(2))
  >
  > <table>
  > <tbody>
  > <tr><th>A</th><th>B</th><th>C</th><th>D</th><th>E</th><th>F</th><th>G</th></tr>
  > <tr><td colspan="2"><strong>1</strong></td><td><strong>ATTRIBUTES</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Request Correlation Identifier</td><td>R</td><td></td><td>The value of &lt;Request Correlation Identifier&gt; is unique per Member State.</td><td>an..44</td></tr>
  > <tr><td colspan="2"><strong>2</strong></td><td><strong>STA_PERIOD</strong></td><td>R</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Year</td><td>R</td><td></td><td></td><td>n4</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Semester</td><td>C</td><td rowspan="3">For 2 <em>b</em>, <em>c</em>, and <em>d</em>:<br>The three following data fields are optional and exclusive:<br>&lt;Semester&gt;<br>&lt;Quarter&gt;<br>&lt;Month&gt;<br>i.e. If one of these data fields is given then the two other data fields do not apply</td><td>The possible values are:<br>1<br>First semester<br>2<br>Second semester</td><td>n1</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Quarter</td><td>C</td><td>The possible values are:<br>1<br>First quarter<br>2<br>Second quarter<br>3<br>Third quarter<br>4<br>Fourth quarter</td><td>n1</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Month</td><td>C</td><td>The possible values are:<br>1<br>January<br>2<br>February<br>3<br>March<br>4<br>April<br>5<br>May<br>6<br>June<br>7<br>July<br>8<br>August<br>9<br>September<br>10<br>October<br>11<br>November<br>12<br>December</td><td>n..2</td></tr>
  > <tr><td colspan="2"><strong>3</strong></td><td><strong>STA_PER_MS</strong></td><td>O</td><td></td><td></td><td>99x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Member State Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II to Regulation (EC) No 684/2009)</em></td><td>a2</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Number of Active Economic Operators</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Number of Inactive Economic Operators</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Number of Pending Expirations</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Number of Tax Warehouses</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>f</em></td><td>Number of Excise Authorisation Changes</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>3.1</strong></td><td><strong>OPERATOR_TYPE</strong></td><td>O</td><td></td><td></td><td>9x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operator Type Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>Authorised warehouse keeper<br>2<br>Registered consignee<br>3<br>Registered consignor</td><td>n1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>3.2</strong></td><td><strong>EXCISE_PRODUCT_ CATEGORY_ACTIVITY</strong></td><td>O</td><td></td><td></td><td>9x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Products Category Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II)</em></td><td>a1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>3.3</strong></td><td><strong>EXCISE_PRODUCT_ ACTIVITY</strong></td><td>O</td><td></td><td></td><td>9999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Product Code</td><td>R</td><td></td><td><em>(see Code list 11 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an..4</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>4</strong></td><td><strong>STA_ALL_MS</strong></td><td>O</td><td></td><td></td><td></td></tr>
  > <tr><td></td><td><em>a</em></td><td>Total Number of Active Economic Operators</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Total Number of Inactive Economic Operators</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>c</em></td><td>Total Number of Pending Expirations</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>d</em></td><td>Total Number of Tax Warehouses</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td></td><td><em>e</em></td><td>Total Number of Excise Authorisation Changes</td><td>O</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>4.1</strong></td><td><strong>OPERATOR_TYPE_ALL_MS</strong></td><td>O</td><td></td><td></td><td>9x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Operator Type Code</td><td>R</td><td></td><td>The possible values are:<br>1<br>Authorised warehouse keeper<br>2<br>Registered consignee<br>3<br>Registered consignor</td><td>n1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Total Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>4.2</strong></td><td><strong>EXCISE_PRODUCT_ CATEGORY_ACTIVITY_ ALL_MS</strong></td><td>O</td><td></td><td></td><td>9x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Products Category Code</td><td>R</td><td></td><td><em>(see Code list 3 in Annex II)</em></td><td>a1</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Total Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > <tr><td colspan="2"><strong>4.3</strong></td><td><strong>EXCISE_PRODUCT_ ACTIVITY_ALL_MS</strong></td><td>O</td><td></td><td></td><td>9999x</td></tr>
  > <tr><td></td><td><em>a</em></td><td>Excise Product Code</td><td>R</td><td></td><td><em>(see Code list 11 in Annex II to Regulation (EC) No 684/2009)</em></td><td>an..4</td></tr>
  > <tr><td></td><td><em>b</em></td><td>Total Number of Economic Operators</td><td>R</td><td></td><td></td><td>n..15</td></tr>
  > </tbody>
  > </table>

## Annotations

[^f00001]: Footnote: [OJ L 121, 8.5.2012, p. 1](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2012.121.01.0001.01.ENG).

[^f00002]: Footnote: Commission Implementing Regulation (EU) No 612/2013 of 25 June 2013 on the operation of the register of economic operators and tax warehouses, related statistics and reporting pursuant to Council Regulation (EU) No 389/2012 on administrative cooperation in the field of excise duties ([OJ L 173, 26.6.2013, p. 9](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2013.173.01.0009.01.ENG)).

[^f00003]: Footnote: Council Directive 2008/118/EC of 16 December 2008 concerning the general arrangements for excise duty and repealing Directive 92/12/EEC ([OJ L 9, 14.1.2009, p. 12](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2009.009.01.0012.01.ENG)).

[^f00004]: Footnote: Decision No 1152/2003/EC of the European Parliament and of the Council of 16 June 2003 on computerising the movement and surveillance of excisable products ([OJ L 162, 1.7.2003, p. 5](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2003.162.01.0005.01.ENG)).
