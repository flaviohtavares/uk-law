---
title: Commission Implementing Regulation (EU) 2016/378 of 11 March 2016 laying down implementing technical standards with regard to the timing, format and template of the submission of notifications to competent authorities according to Regulation (EU) No 596/2014 of the European Parliament and of the Council (Text with EEA relevance)
id: eur/2016/378
type: EuropeanUnionRegulation
category: euretained
status: revised-with-pending-changes
made_date: '2016-03-11'
text_date: '2023-07-11'
extent: E+W+S+N.I.
source_url: https://www.legislation.gov.uk/eur/2016/378
pdf_urls:
- http://www.legislation.gov.uk/eur/2016/378/pdfs/eur_20160378_adopted_en.pdf
- http://www.legislation.gov.uk/eur/2016/378/data.pdf
pending_changes: 1
repealed_on: null
attribution: © Crown and database right. Derived from content available under the Open Government Licence v3.0 from legislation.gov.uk. Contains material from the European Union, re-used under Commission Decision 2011/833/EU. The EU does not endorse this repository.
summary: ''
---

# Commission Implementing Regulation (EU) 2016/378 of 11 March 2016 laying down implementing technical standards with regard to the timing, format and template of the submission of notifications to competent authorities according to Regulation (EU) No 596/2014 of the European Parliament and of the Council (Text with EEA relevance)

> **Warning: changes not yet applied to this text (1).** Text as at 2023-07-11. See https://www.legislation.gov.uk/changes/affected/eur/2016/378
>
> Extent: England, Wales, Scotland, Northern Ireland.

*Extent: E+W+S+N.I.*

Commission Implementing Regulation (EU) 2016/378

of 11 March 2016

laying down implementing technical standards with regard to the timing, format and template of the submission of notifications to competent authorities according to Regulation (EU) No 596/2014 of the European Parliament and of the Council

(Text with EEA relevance)

[^c-cfdf77eee7733e7bd5783037596be4a3][^c-01b03140f6fc197aff0ccfac151b3c53]

THE EUROPEAN COMMISSION,

Having regard to the Treaty on the Functioning of the European Union,

Having regard to Regulation (EU) No 596/2014 of the European Parliament and of the Council of 16 April 2014 on market abuse (market abuse regulation) and repealing Directive 2003/6/EC of the European Parliament and of the Council and Commission Directives 2003/124/EC, 2003/125/EC and 2004/72/EC[^f00001], and in particular, the third subparagraph of Article 4(5) thereof,

Whereas:

(1)

In order to ensure the coherence of reporting obligations and to reduce the administrative burden for entities subject to such obligations, it is necessary to align the reporting obligations under this Regulation and under Commission Delegated Regulation to be adopted in accordance with the third subparagraph of Article 27(3) of Regulation (EU) No 600/2014 of the European Parliament and of the Council[^f00002].

(2)

In order to enable the competent authorities and the European Securities and Markets Authority (ESMA) to ensure data quality and effective market monitoring, for the benefit of market integrity, the competent authorities and ESMA should be able to promptly receive complete notifications in respect of each trading day.

(3)

For the purposes of effective and efficient use of data by competent authorities, there should be consistency in the templates and formats used when submitting notifications of financial instruments. Adherence to the relevant international standards with regard to the details included in those notifications promotes those purposes.

(4)

This Regulation is based on the draft implementing technical standards submitted by ESMA to the Commission.

(5)

ESMA has conducted open public consultations on the draft implementing technical standard on which this Regulation is based, analysed the potential related costs and benefits and requested the opinion of the Securities and Markets Stakeholder Group established by Article 37 of Regulation (EU) No 1095/2010 of the European Parliament and of the Council[^f00003].

(6)

In order to ensure the smooth functioning of the financial markets, it is necessary that this Regulation enters into force as a matter of urgency and that the provisions laid down in this Regulation apply from the same date as those laid down in Regulation (EU) No 596/2014,

HAS ADOPTED THIS REGULATION:

**Article 1.** 1. By no later than 21.00 CET on each day that it is open for trading, a trading venue shall, using automated processes, provide to its competent authority pursuant to Article 4(1) of Regulation (EU) No 596/2014 the notifications of all financial instruments which, before 18.00 CET on that day, were for the first time subject to a request for admission to trading or admitted to trading or traded on that trading venue, including where orders or quotes were placed through its system, or ceased to be traded or to be admitted to trading on the trading venue.

2. Notifications of financial instruments which, after 18.00 CET, were for the first time subject to a request for admission to trading or admitted to trading or traded on the trading venue, including where orders or quotes were placed through its system, or ceased to be traded or to be admitted to trading on the trading venue, shall be made, using automated processes, by the trading venue to the competent authority by no later than 21.00 CET of the next day on which it is open for trading.

3. Competent authorities shall transmit notifications referred to in paragraphs 1 and 2 pursuant to Article 4(2) of Regulation (EU) No 596/2014 to ESMA each day by no later than 23.59 CET using automated processes and secure electronic communication channels between them and ESMA.

**Article 2.** All details to be included in notifications pursuant to Article 4(1) and (2) of Regulation (EU) No 596/2014 shall be submitted in accordance with the standards and formats specified in the Annex to this Regulation, in an electronic and machine-readable form and in a common XML template in accordance with the ISO 20022 methodology.

**Article 3.** This Regulation shall enter into force on the day following that of its publication in the *Official Journal of the European Union*.

It shall apply from 3 July 2016.

This Regulation shall be binding in its entirety and directly applicable in all Member States.

Done at Brussels, 11 March 2016.

*For the Commission*

*The President*

Jean-Claude Juncker

## ANNEX — Standards and formats of the submission of notifications to competent authorities according to Regulation (EU) No 596/2014

*Table 1*

**Legend for Table 3**

| SYMBOL | DATA TYPE | DEFINITION |
| --- | --- | --- |
| {ALPHANUM-n} | Up to n alphanumerical characters | Free text field. |
| {CFI\_CODE} | 6 characters | ISO 10962 CFI code. |
| {COUNTRYCODE\_2} | 2 alphanumerical characters | 2-letter country code, as defined by ISO 3166-1 alpha-2 country code. |
| {CURRENCYCODE\_3} | 3 alphanumerical characters | 3-letter currency code, as defined by ISO 4217 currency codes |
| {DATE\_TIME\_FORMAT} | ISO 8601 date and time format | - Date and time in the following format:<br>- YYYY-MM-DDThh:mm:ss.ddddddZ.<br>- ‘YYYY’ is the year;<br>- ‘MM’ is the month;<br>- ‘DD’ is the day;<br>- ‘T’ — means that the letter ‘T’ shall be used<br>- ‘hh’ is the hour;<br>- ‘mm’ is the minute;<br>- ‘ss.dddddd’ is the second and its fraction of a second;<br>- Z is UTC time.<br>Dates and times shall be reported in UTC. |
| {DATEFORMAT} | ISO 8601 date format | Dates shall be formatted by the following format:<br>YYYY-MM-DD. |
| {DECIMAL-n/m} | Decimal number of up to n digits in total of which up to m digits can be fraction digits | Numerical field for both positive and negative values.<br>- decimal separator is ‘.’ (full stop);<br>- negative numbers are prefixed with ‘-’ (minus);<br>Values are rounded and not truncated. |
| {INDEX} | 4 alphabetic characters | ‘EONA’ — EONIA<br>‘EONS’ — EONIA SWAP<br>‘EURI’ — EURIBOR<br>‘EUUS’ — EURODOLLAR<br>‘EUCH’ — EuroSwiss<br>‘GCFR’ — GCF REPO<br>‘ISDA’ — ISDAFIX<br>‘LIBI’ — LIBID<br>‘LIBO’ — LIBOR<br>‘MAAA’ — Muni AAA<br>‘PFAN’ — Pfandbriefe<br>‘TIBO’ — TIBOR<br>‘STBO’ — STIBOR<br>‘BBSW’ — BBSW<br>‘JIBA’ — JIBAR<br>‘BUBO’ — BUBOR<br>‘CDOR’ — CDOR<br>‘CIBO’ — CIBOR<br>‘MOSP’ — MOSPRIM<br>‘NIBO’ — NIBOR<br>‘PRBO’ — PRIBOR<br>‘TLBO’ — TELBOR<br>‘WIBO’ — WIBOR<br>‘TREA’ — Treasury<br>‘SWAP’ — SWAP<br>‘FUSW’ — Future SWAP |
| {INTEGER-n} | Integer number of up to n digits in total | Numerical field for both positive and negative integer values. |
| {ISIN} | 12 alphanumerical characters | ISIN code, as defined in ISO 6166. |
| {LEI} | 20 alphanumerical characters | Legal entity identifier as defined in ISO 17442. |
| {MIC} | 4 alphanumerical characters | Market identifier as defined in ISO 10383. |
| {FISN} | 35 alphanumeric characters | FISN code as defined in ISO 18774. |

*Table 2*

**Classification of commodity and emission allowances derivatives for Table 3 (fields 35-37)**

<table>
<tbody>
<tr><th>Base product</th><th>Sub product</th><th>Further sub product</th></tr>
<tr><td rowspan="9">‘AGRI’ — Agricultural</td><td>‘GROS’ — Grains and Oil Seeds</td><td>‘FWHT’ — Feed Wheat<br>‘SOYB’ — Soybeans<br>‘CORN’ — Maize<br>‘RPSD’ — Rapeseed<br>‘RICE’ — Rice<br>‘OTHR’ — Other</td></tr>
<tr><td>‘SOFT’ — Softs</td><td>‘CCOA’ — Cocoa<br>‘ROBU’ — Robusta Coffee<br>‘WHSG’ — White Sugar<br>‘BRWN’ — Raw Sugar<br>‘OTHR’ — Other</td></tr>
<tr><td>‘POTA’ — Potato</td><td></td></tr>
<tr><td>‘OOLI’ — Olive oil</td><td>‘LAMP’ — Lampante'</td></tr>
<tr><td>‘DIRY’ — Dairy</td><td></td></tr>
<tr><td>‘FRST’ — Forestry</td><td></td></tr>
<tr><td>‘SEAF’ — Seafood</td><td></td></tr>
<tr><td>‘LSTK’ — Livestock</td><td></td></tr>
<tr><td>‘GRIN’ — Grain</td><td>‘MWHT’ — Milling Wheat</td></tr>
<tr><td rowspan="4">‘NRGY’ — Energy</td><td>‘ELEC’ -Electricity</td><td>‘BSLD’ — Base load<br>‘FITR’ — Financial Transmission Rights<br>‘PKLD’ — Peak load<br>‘OFFP’ — Off-peak<br>‘OTHR’ — Other</td></tr>
<tr><td>‘NGAS’ — Natural Gas</td><td>‘GASP’ — GASPOOL<br>‘LNGG’ — LNG<br>‘NBPG’ — NBP<br>‘NCGG’ — NCG<br>‘TTFG’ — TTF</td></tr>
<tr><td>‘OILP’ — Oil</td><td>‘BAKK’ — Bakken<br>‘BDSL’ — Biodiesel<br>‘BRNT’ — Brent<br>‘BRNX’ — Brent NX<br>‘CNDA’ — Canadian<br>‘COND’ — Condensate<br>‘DSEL’ — Diesel<br>‘DUBA’ — Dubai<br>‘ESPO’ — ESPO<br>‘ETHA’ — Ethanol<br>‘FUEL’ — Fuel<br>‘FOIL’ — Fuel Oil<br>‘GOIL’ — Gasoil<br>‘GSLN’ — Gasoline<br>‘HEAT’ — Heating Oil<br>‘JTFL’ — Jet Fuel<br>‘KERO’ — Kerosene<br>‘LLSO’ — Light Louisiana Sweet (LLS)<br>‘MARS’ — Mars<br>‘NAPH’ — Naptha<br>‘NGLO’ — NGL<br>‘TAPI’ — Tapis<br>‘URAL’ — Urals<br>‘WTIO’ — WTI</td></tr>
<tr><td>‘COAL’ — Coal<br>‘INRG’ — Inter Energy<br>‘RNNG’ — Renewable energy<br>‘LGHT’ — Light ends<br>‘DIST’ — Distillates</td><td></td></tr>
<tr><td rowspan="2">‘ENVR’ — Environmental</td><td>‘EMIS’ — Emissions</td><td>‘CERE’ — CER<br>‘ERUE’ — ERU<br>‘EUAE’ — EUA<br>‘EUAA’ — EUAA<br>‘OTHR’ — Other</td></tr>
<tr><td>‘WTHR’ — Weather<br>‘CRBR’ — Carbon-related'</td><td></td></tr>
<tr><td rowspan="3">‘FRGT’ — ‘Freight’</td><td>‘WETF’ — Wet</td><td>‘TNKR’ -Tankers</td></tr>
<tr><td>‘DRYF’ — Dry</td><td>‘DBCR’ -Dry bulk carriers</td></tr>
<tr><td>‘CSHP’ — Container ships</td><td></td></tr>
<tr><td>‘FRTL’ — ‘Fertilizer’</td><td>‘AMMO’ — Ammonia<br>‘DAPH’ — DAP (Diammonium Phosphate)<br>‘PTSH’ — Potash<br>‘SLPH’ — Sulphur<br>‘UREA’ — Urea<br>‘UAAN’ — UAN (urea and ammonium nitrate)</td><td></td></tr>
<tr><td>‘INDP’ — Industrial products'</td><td>‘CSTR’ — Construction<br>‘MFTG’ — Manufacturing</td><td></td></tr>
<tr><td rowspan="2">‘METL’ — Metals'</td><td>‘NPRM’ — Non-Precious</td><td>‘ALUM’ — Aluminium<br>‘ALUA’ — Aluminium Alloy<br>‘CBLT’ — Cobalt<br>‘COPR’ — Copper<br>‘IRON’ — Iron ore<br>‘LEAD’ — Lead<br>‘MOLY’ — Molybdenum<br>‘NASC’ — NASAAC<br>‘NICK’ — Nickel<br>‘STEL’ — Steel<br>‘TINN’ — Tin<br>‘ZINC’ — Zinc<br>‘OTHR’ — Other</td></tr>
<tr><td>‘PRME’ — Precious</td><td>‘GOLD’ — Gold<br>‘SLVR’ — Silver<br>‘PTNM’ — Platinum<br>‘PLDM’ — Palladium<br>‘OTHR’ — Other</td></tr>
<tr><td>‘MCEX’ — Multi Commodity Exotic'</td><td></td><td></td></tr>
<tr><td>‘PAPR’ — Paper</td><td>‘CBRD’ — Containerboard<br>‘NSPT’ — Newsprint<br>‘PULP’ — Pulp<br>‘RCVP’ — Recovered paper</td><td></td></tr>
<tr><td>‘POLY’ — Polypropylene</td><td>‘PLST’ — Plastic</td><td></td></tr>
<tr><td>‘INFL’ — Inflation</td><td></td><td></td></tr>
<tr><td>‘OEST’ — Official economic statistics'</td><td></td><td></td></tr>
<tr><td>‘OTHC’ — Other C10 ‘as defined in Table 10.1 Section 10 of Annex III to Commission Delegated Regulation supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council with regard to regulatory technical standards on transparency requirements for trading venues and investment firms in respect of bonds, structured finance products, emission allowances and derivatives.</td><td>'DLVR’ — Deliverable<br>‘NDLV’ — Non-deliverable</td><td></td></tr>
<tr><td>‘OTHR’ — Other</td><td></td><td></td></tr>
</tbody>
</table>

*Table 3*

**Standards and formats to be used in the notifications to be submitted in accordance with Article 4(1) and (2) of Regulation (EU) No 596/2014**

<table>
<tbody>
<tr><th>N.</th><th>FIELD</th><th>STANDARDS AND FORMATS TO BE USED FOR REPORTING</th></tr>
<tr><th colspan="3"><strong>General Fields</strong></th></tr>
<tr><td>1</td><td>Instrument identification code</td><td>{ISIN}</td></tr>
<tr><td>2</td><td>Instrument full name</td><td>{ALPHANUM-350}</td></tr>
<tr><td>3</td><td>Instrument classification</td><td>{CFI_CODE}</td></tr>
<tr><td>4</td><td>Commodities derivative indicator</td><td>‘true’ — Yes<br>‘false’ — No</td></tr>
<tr><th colspan="3"><strong>Issuer related fields</strong></th></tr>
<tr><td>5</td><td>Issuer or operator of the trading venue identifier</td><td>{LEI}</td></tr>
<tr><th colspan="3"><strong>Venue related fields</strong></th></tr>
<tr><td>6</td><td>Trading venue</td><td>{MIC}</td></tr>
<tr><td>7</td><td>Financial instrument short name</td><td>{FISN}</td></tr>
<tr><td>8</td><td>Request for admission to trading by issuer</td><td>‘true’ — Yes<br>‘false’ — No</td></tr>
<tr><td>9</td><td>Date of approval of the admission to trading</td><td>{DATE_TIME_FORMAT}</td></tr>
<tr><td>10</td><td>Date of request for admission to trading</td><td>{DATE_TIME_FORMAT}</td></tr>
<tr><td>11</td><td>Date of admission to trading or date of first trade</td><td>{DATE_TIME_FORMAT}</td></tr>
<tr><td>12</td><td>Termination date</td><td>{DATE_TIME_FORMAT}</td></tr>
<tr><th colspan="3"><strong>Notional related fields</strong></th></tr>
<tr><td>13</td><td>Notional currency 1</td><td>{CURRENCYCODE_3}</td></tr>
<tr><th colspan="3"><strong>Bonds or other forms of securitised debt related fields</strong></th></tr>
<tr><td>14</td><td>Total issued nominal amount</td><td>{DECIMAL-18/5}</td></tr>
<tr><td>15</td><td>Maturity date</td><td>{DATEFORMAT}</td></tr>
<tr><td>16</td><td>Currency of nominal value</td><td>{CURRENCYCODE_3}</td></tr>
<tr><td>17</td><td>Nominal value per unit/minimum traded value</td><td>{DECIMAL-18/5}</td></tr>
<tr><td>18</td><td>Fixed rate</td><td>{DECIMAL-11/10}<br>Expressed as a percentage (e.g. 7.0 means 7 % and 0.3 means 0,3 %)</td></tr>
<tr><td>19</td><td>Identifier of the index/benchmark of a floating rate bond</td><td>{ISIN}</td></tr>
<tr><td>20</td><td>Name of the index/benchmark of a floating rate bond</td><td>{INDEX}<br>Or<br>{ALPHANUM-25} — if the index name is not included in the {INDEX} list</td></tr>
<tr><td>21</td><td>Term of the index/benchmark of a floating rate bond.</td><td>{INTEGER-3}+‘DAYS’ — days<br>{INTEGER-3}+‘WEEK’ — weeks<br>{INTEGER-3}+‘MNTH’ — months<br>{INTEGER-3}+‘YEAR’ — years</td></tr>
<tr><td>22</td><td>Base Point Spread of the index/benchmark of a floating rate bond</td><td>{INTEGER-5}</td></tr>
<tr><td>23</td><td>Seniority of the bond</td><td>‘SNDB’ — Senior Debt<br>‘MZZD’ — Mezzanine<br>‘SBOD’ — Subordinated Debt<br>‘JUND’ — Junior Debt</td></tr>
<tr><th colspan="3"><strong>Derivatives and Securitised Derivatives related fields</strong></th></tr>
<tr><td>24</td><td>Expiry date</td><td>{DATEFORMAT}</td></tr>
<tr><td>25</td><td>Price multiplier</td><td>{DECIMAL-18/17}</td></tr>
<tr><td>26</td><td>Underlying instrument code</td><td>{ISIN}</td></tr>
<tr><td>27</td><td>Underlying issuer</td><td>{LEI}</td></tr>
<tr><td>28</td><td>Underlying index name</td><td>{INDEX}<br>Or<br>{ALPHANUM-25} — if the index name is not included in the {INDEX} list</td></tr>
<tr><td>29</td><td>Term of the underlying index</td><td>{INTEGER-3}+‘DAYS’ — days<br>{INTEGER-3}+‘WEEK’ — weeks<br>{INTEGER-3}+‘MNTH’ — months<br>{INTEGER-3}+‘YEAR’ — years</td></tr>
<tr><td>30</td><td>Option type</td><td>‘PUTO’ — Put<br>‘CALL’ — Call<br>‘OTHR’ — where it cannot be determined whether it is a call or a put</td></tr>
<tr><td>31</td><td>Strike price</td><td>{DECIMAL-18/13} in case the price is expressed as monetary value<br>{DECIMAL-11/10} in case the price is expressed as percentage or yield<br>{DECIMAL-18/17} in case the price is expressed as basis points<br>‘PNDG’ in case the price is not available</td></tr>
<tr><td>32</td><td>Strike price currency</td><td>{CURRENCYCODE_3}</td></tr>
<tr><td>33</td><td>Option exercise style</td><td>‘EURO’ — European<br>‘AMER’ — American<br>‘ASIA’ — Asian<br>‘BERM’ — Bermudan<br>‘OTHR’ — Any other type</td></tr>
<tr><td>34</td><td>Delivery type</td><td>‘PHYS’ — Physically Settled<br>‘CASH’ — Cash settled<br>‘OPTN’ — Optional for counterparty or when determined by a third party</td></tr>
<tr><th colspan="3"><strong>Commodity and emission allowances derivatives</strong></th></tr>
<tr><td>35</td><td>Base product</td><td>Only values in the ‘Base product’ column of the classification of commodities and emission allowances derivatives table are allowed.</td></tr>
<tr><td>36</td><td>Sub product</td><td>Only values in the ‘Sub product’ column of the classification of commodities and emission allowances derivatives table are allowed.</td></tr>
<tr><td>37</td><td>Further sub product</td><td>Only values in the ‘Further sub product’ of the classification of commodities and emission allowances derivatives table are allowed.</td></tr>
<tr><td>38</td><td>Transaction type</td><td>‘FUTR’ — Futures<br>‘OPTN’ — Options<br>‘TAPO’ — TAPOS<br>‘SWAP’ — SWAPS<br>‘MINI’ — Minis<br>‘OTCT’ — OTC<br>‘ORIT’ — Outright<br>‘CRCK’ — Crack<br>‘DIFF’ — Differential<br>‘OTHR’ — Other</td></tr>
<tr><td>39</td><td>Final price type</td><td>‘ARGM’ — Argus/McCloskey<br>‘BLTC’ — Baltic<br>‘EXOF’ — Exchange<br>‘GBCL’ — GlobalCOAL<br>‘IHSM’ — IHS McCloskey<br>‘PLAT’ — Platts<br>‘OTHR’ — Other</td></tr>
<tr><th colspan="3"><strong>Interest rate derivatives</strong></th></tr>
<tr><th colspan="3">— The fields in this section should only be populated for instruments that have non-financial instrument of type interest rates as underlying.</th></tr>
<tr><td>40</td><td>Reference rate</td><td>{INDEX}<br>Or<br>{ALPHANUM-25}- if the reference rate is not included in the {INDEX} list</td></tr>
<tr><td>41</td><td>IR Term of contract</td><td>{INTEGER-3}+‘DAYS’ — days<br>{INTEGER-3}+‘WEEK’ — weeks<br>{INTEGER-3}+‘MNTH’ — months<br>{INTEGER-3}+‘YEAR’ — years</td></tr>
<tr><td>42</td><td>Notional currency 2</td><td>{CURRENCYCODE_3}</td></tr>
<tr><td>43</td><td>Fixed rate of leg 1</td><td>{DECIMAL -11/10}<br>Expressed as a percentage (e.g. 7.0 means 7 % and 0.3 means 0,3 %)</td></tr>
<tr><td>44</td><td>Fixed rate of leg 2</td><td>{DECIMAL -11/10}<br>Expressed as a percentage (e.g. 7.0 means 7 % and 0.3 means 0,3 %)</td></tr>
<tr><td>45</td><td>Floating rate of leg 2</td><td>{INDEX}<br>Or<br>{ALPHANUM-25} — if the reference rate is not included in the {INDEX} list</td></tr>
<tr><td>46</td><td>IR Term of contract of leg 2</td><td>{INTEGER-3}+‘DAYS’ — days<br>{INTEGER-3}+‘WEEK’ — weeks<br>{INTEGER-3}+‘MNTH’ — months<br>{INTEGER-3}+‘YEAR’ — years</td></tr>
<tr><th colspan="3"><strong>Foreign exchange derivatives</strong></th></tr>
<tr><th colspan="3">— The fields in this section should only be populated for instruments that have non-financial instrument of type foreign exchange as underlying.</th></tr>
<tr><td>47</td><td>Notional currency 2</td><td>{CURRENCYCODE_3}</td></tr>
<tr><td>48</td><td>FX Type</td><td>‘FXCR’ — FX Cross Rates<br>‘FXEM’ — FX Emerging Markets<br>‘FXMJ’ — FX Majors</td></tr>
</tbody>
</table>

## Annotations

[^c-cfdf77eee7733e7bd5783037596be4a3]: Modification: The “appropriate regulator” has power to make such provision as they consider appropriate by means of an instrument in writing to prevent, remedy or mitigate any failure of the provisions of this Regulation to operate effectively or any other deficiency arising from the withdrawal of the United Kingdom from the EU, see The Financial Regulators' Powers (Technical Standards etc.) (Amendment etc.) (EU Exit) Regulations 2018 (S.I. 2018/1115), [regs. 2](https://www.legislation.gov.uk/uksi/2018/1115/regulation/2), [3](https://www.legislation.gov.uk/uksi/2018/1115/regulation/3), [Sch. Pt. 1](https://www.legislation.gov.uk/uksi/2018/1115/schedule/part/1) (with saving on [I](https://www.legislation.gov.uk/uksi/2018/1115/schedule/part/I)P completion day by S.I. 2019/680, [regs. 1(2)](https://www.legislation.gov.uk/uksi/2019/680/regulation/1/2), [11](https://www.legislation.gov.uk/uksi/2019/680/regulation/11); 2020 c. 1, [Sch. 5 para. 1(1)](https://www.legislation.gov.uk/ukpga/2020/1/schedule/5/paragraph/1/1))

[^c-01b03140f6fc197aff0ccfac151b3c53]: Modification: Regulation: power to modify conferred (11.7.2023) by [Financial Services and Markets Act 2023 (c. 29)](https://www.legislation.gov.uk/ukpga/2023/29), [ss. 3](https://www.legislation.gov.uk/ukpga/2023/29/section/3), [86(3)](https://www.legislation.gov.uk/ukpga/2023/29/section/86/3), [Sch. 1 Pts. 1](https://www.legislation.gov.uk/ukpga/2023/29/schedule/1/part/1), [3](https://www.legislation.gov.uk/ukpga/2023/29/schedule/1/part/3); [S.I. 2023/779](https://www.legislation.gov.uk/uksi/2023/779), [reg. 2(d)](https://www.legislation.gov.uk/uksi/2023/779/regulation/2/d)

[^f00001]: Footnote: [OJ L 173, 12.6.2014, p. 1](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2014.173.01.0001.01.ENG).

[^f00002]: Footnote: Regulation (EU) No 600/2014 of the European Parliament and of the Council of 15 May 2014 on markets in financial instruments and amending Regulation (EU) No 648/2012 ([OJ L 173, 12.6.2014, p. 84](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2014.173.01.0084.01.ENG)).

[^f00003]: Footnote: Regulation (EU) No 1095/2010 of the European Parliament and of the Council of 24 November 2010 establishing a European Supervisory Authority (European Securities and Markets Authority), amending Decision No 716/2009/EC and repealing Commission Decision 2009/77/EC ([OJ L 331, 15.12.2010, p. 84](https://webarchive.nationalarchives.gov.uk/eu-exit/https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv:OJ.L_.2010.331.01.0084.01.ENG)).
