![](RackMultipart20200806-4-1668bdl_html_bdaaa27124b75e59.jpg)

**Legal Transition Programme**

**Kyrgyz Republic: Implementation of Open Data Standards for Monitoring and Public Access to Public Procurement Information**

_Key Performance Indicator Methodology of Calculated Metrics for Open Data OCDS Analytical Application &quot;Explorer&quot;_

June 2020

**DOCUMENT CHARACTERISTICS**

| **Property** | **Value Proposition** |
| --- | --- |
| Release date | June 2020 |
| Status: | Accepted |
| Version: | V 1.0 |
| Authors: | Anna Soloviova, Iryna Kyrychenko |
| Reviewed by: | EBRD |
| Approved by: | Eliza Niewiadomska, EBRD OL |

**DOCUMENT HISTORY**

| **Version** | **Description** | **Date** |
| --- | --- | --- |
| 1.0 | _Key Performance Indicator Methodology of Calculated Metrics for Open Data OCDS Analytical Application &quot;Explorer&quot;_ | June 2020 |
| 2.0 |
 |
 |
| 3.0 |
 |
 |
| 4.0 |
 |
 |
| 5.0 |
 |
 |

**TABLE OF CONTENTS**

#


Y

**[1Introduction 4](#_Toc47375048)**

[**1.1**** Document objective **** 4**](#_Toc47375049)

[**1.2**** Data sources used for indicator calculation **** 4**](#_Toc47375050)

[**1.3**** Mathematical conventions used in formulas **** 5**](#_Toc47375051)

**[2Quantitative indicators 5](#_Toc47375052)**

**[3Cost indicators 9](#_Toc47375053)**

**[4Time/duration related indicators 11](#_Toc47375054)**

**[5EEC indicators 12](#_Toc47375055)**

**[6Indicators for reporting to the Public Procurement Department 14](#_Toc47375056)**

**[7Data quality indicators 15](#_Toc47375057)**

**LIST OF TABLES**

[Table 1 API endpoints 4](#_Toc47374993)

[Table 2 Number of tenders 5](#_Toc47374994)

[Table 3 Number of lots 5](#_Toc47374995)

[Table 4 Number of contracts 5](#_Toc47374996)

[Table 5 Number of published plans 6](#_Toc47374997)

[Table 6 Number of contracting authorities who published plans 6](#_Toc47374998)

[Table 7 Number of contracting authorities 6](#_Toc47374999)

[Table 8 Number of bidders 6](#_Toc47375000)

[Table 9 Number of bids 6](#_Toc47375001)

[Table 10 Average number of bids per lot 7](#_Toc47375002)

[Table 11 Number of non-competitive procedures 7](#_Toc47375003)

[Table 12 Share of non-competitive procedures 7](#_Toc47375004)

[Table 13 Number of rejected bids 7](#_Toc47375005)

[Table 14 Number of lots with rejected bids 7](#_Toc47375006)

[Table 15 Average number of rejected bids per lot 8](#_Toc47375007)

[Table 16 Number of enquiries 8](#_Toc47375008)

[Table 17 Share of unanswered enquiries 8](#_Toc47375009)

[Table 18 Number of complaints 8](#_Toc47375010)

[Table 19 Number of awards 8](#_Toc47375011)

[Table 20 Number of lots with confirmed awards 9](#_Toc47375012)

[Table 21 Lots&#39; value 9](#_Toc47375013)

[Table 22 Contracts&#39; value 9](#_Toc47375014)

[Table 23 Planned value 9](#_Toc47375015)

[Table 24 Total price reduction 9](#_Toc47375016)

[Table 25 Percentage of price reduction 10](#_Toc47375017)

[Table 26 Contracts&#39; value resulted from non-competitive procedures 10](#_Toc47375018)

[Table 27 Share of contracts&#39; value resulted from non-competitive procedures 10](#_Toc47375019)

[Table 28 Percentage of plan execution 10](#_Toc47375020)

[Table 29 Value of lots with rejected bids 10](#_Toc47375021)

[Table 30 Lots&#39; value with awarded bidders 11](#_Toc47375022)

[Table 31 Average enquiry period duration 11](#_Toc47375023)

[Table 32 Average bidding period duration 11](#_Toc47375024)

[Table 33 Average awarding period duration 11](#_Toc47375025)

[Table 34 Average procedure stage duration (lots) 11](#_Toc47375026)

[Table 35 Average time to answer enquiry 12](#_Toc47375027)

[Table 36 Number of concluded procedures 12](#_Toc47375028)

[Table 37 Number of unsuccessful procedures 12](#_Toc47375029)

[Table 38 Number of bids submitted by potential suppliers 12](#_Toc47375030)

[Table 39 Number of dismissed bids 12](#_Toc47375031)

[Table 40 Number of bids submitted by awarded bidders 13](#_Toc47375032)

[Table 41 Value of signed contracts 13](#_Toc47375033)

[Table 42 Country of bidder/supplier 13](#_Toc47375034)

[Table 43 Number of bids submitted by awarded bidders who refused to sign the contract 13](#_Toc47375035)

[Table 44 Mapping local procurement methods to the ECC form 14](#_Toc47375036)

[Table 45 Number of dismissed bids at the evaluation stage 14](#_Toc47375037)

[Table 46Number of dismissed bids at the qualification stage 14](#_Toc47375038)

[Table 47 Value of the winning bid 14](#_Toc47375039)

[Table 48 Number of bidders 15](#_Toc47375040)

[Table 49 Number of dismissed bids 15](#_Toc47375041)

[Table 50 Contracts&#39; value 15](#_Toc47375042)

[Table 51 Tenders without lots 15](#_Toc47375043)

[Table 52 No information about supplier 16](#_Toc47375044)

[Table 53 No information about bids submitted 16](#_Toc47375045)

[Table 54 Two active awards in one lot 16](#_Toc47375046)

[Table 55 No price proposal for the lot 16](#_Toc47375047)

1.
# Introduction

  1.
## Document objective

This report has been prepared under the contract number C42672/8259/45334, dated 12 August 2019 between the European Bank for Reconstruction and Development (EBRD or the Bank) and Trelisanio Holding Ltd (the Consultant).

This paper aims to present key performance indicators which evaluate public procurement processes in the Kyrgyz Republic and to introduce the methodology for calculating these indicators based on the OCDS.

The provided information for each indicator is as follows:

- Name;
- Short description;
- Calculation formula based on OCDS data.

All indicators presented in this document are divided into the following categories:

- Quantitative indicators;
- Cost indicators;
- Time duration indicators;
- Indicators for EEC forms;
- Data quality indicators

  1.
## Data sources used for indicator calculation

The Kyrgyz open public procurement data which have been used for calculation of key performance indicators can be accessible at the following links:

_ **Table 1 API endpoints** _

| **#** | **Type of data** | **API endpoint** |
| --- | --- | --- |
| 1 | Releases for conducted tenders in the ePS | [http://ocds.zakupki.gov.kg/api/tendering](http://ocds.zakupki.gov.kg/api/tendering) |
| --- | --- | --- |
| 2 | Information about planning | http://ocds.zakupki.gov.kg/api/planning |
| 3 | Published validation results of data completeness | http://ocds.zakupki.gov.kg/api/validation |

To calculate indicators, it is necessary to download from the access points all published OCDS releases which describe public procurement process. The links to the mentioned releases could be found in the array content[] in the field content[].ocid. The specified separate document is accessible at the following link: http://ocds.zakupki.gov.kg/api/tendering/\&lt;content[].ocid\&gt; .

  1.
## Mathematical conventions used in formulas

A combination of [JSONPath](https://github.com/json-path/JsonPath) and SQL-like pseudocode has been used to introduce formulas. A list of keywords and operators used is presented below:

- **count** — equivalent to **count** in SQL
- **count distinct** — equivalent to **count distinct** in SQL
- **sum** — equivalent to **sum** in SQL; used to calculate the sum of a set of values
- **avg** — equivalent to **avg** in SQL; used to return the average KPI value in the specified group
- **where** — equivalent to **where** in SQL; used to specify conditions in a statement
- **group by** — equivalent to **group by** in SQL; used to arrange identical data
- **exists** — an operation which indicates the existence of some data element
- \&lt;\&gt; — operator &quot;not equal&quot;
- **and** , **or** — logical conjunction and disjunction operators
- **not** — logical negation operator
- **in** — equivalent to **in** SQL
- +, -, \*, /, = — addition, subtraction, multiplication, division and equality operators
- **min** — equivalent to **min** in SQL; used to return the lowest value in the selected dataset
- **concat** — string concatenation
- **{name KPI}** — indicator value (applicable when KPI calculation formula uses another KPI as a variable).

1.
# Quantitative indicators

_ **Table 2 Number of tenders** _

|
1. Name of indicator
 | Number of tenders |
| --- | --- |
|
1. Description
 | The total number of tenders which are publicly available on the public procurement electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **count** ($.tender.id) **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 3 Number of lots** _

|
1. Name of indicator
 | Number of lots |
| --- | --- |
|
1. Description
 | The total number of lots in procurement procedures which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **count** ($.tender.lots[].id) **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 4 Number of contracts** _

|
1. Name of indicator
 | Number of contracts |
| --- | --- |
|
1. Description
 | This indicator presents the number of contracts registered in the electronic public procurement system. |
|
1. Formula
 | **count** ($.contract.id) |

_ **Table 5 Number of published plans** _

|
1. Name of indicator
 | Number of published plans |
| --- | --- |
|
1. Description
 | This indicator presents the number of plans on each lot which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **count** ($.planning.plans.id) |

_ **Table 6 Number of contracting authorities who published plans** _

|
1. Name of indicator
 | Number of contracting authorities who published plans |
| --- | --- |
|
1. Description
 | This indicator presents the number of organizations which have placed a plan on a lot in the electronic public procurement system. |
|
1. Formula
 | **count distinct** ([planning API]$.planning.buyer.id) |

_ **Table 7 Number of contracting authorities** _

|
1. Name of indicator
 | Number of contracting authorities |
| --- | --- |
|
1. Description
 | This indicator presents the number of organizations which have placed a procurement procedure which is publicly available on the electronic web portal of the Kyrgyz Republic at least once. |
|
1. Formula
 | **count distinct** ($.parties[].id) **where**&#39;buyer&#39; **in** $.parties[].roles[] **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 8 Number of bidders** _

|
1. Name of indicator
 | Number of bidders |
| --- | --- |
|
1. Description
 | This indicator presents the number of organizations which have participated in public procurement tenders. |
|
1. Formula
 | **count distinct** ($.parties[].id) **where**&#39;tenderer&#39; **in** $.parties[].roles[] |

_ **Table 9 Number of bids** _

|
1. Name of indicator
 | Number of bids |
| --- | --- |
|
1. Description
 | This indicator presents the number of submitted bids on lots which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **count** ( **concat** ($.data.bids.details[].id, &#39;-&#39;, $.data.bids[].details.relatedLot.id)) |

_ **Table10 Average number of bids per lot** _

|
1. Name of indicator
 | Average number of bids per lot |
| --- | --- |
|
1. Description
 | This indicator presents the average number of bids, submitted by bidders per one lot (It is only calculated for completed lots). |
|
1. Formula
 | **{Number of bids} / {Number of lots}**
**where** $.tender.lots[].status = &#39;complete&#39; |

_ **Table 11 Number of non-competitive procedures** _

|
1. Name of indicator
 | Number of non-competitive procedures |
| --- | --- |
|
1. Description
 | This indicator presents the number non-competitive procedures (Single source procurement without an announcement). |
|
1. Formula
 | **count** ($.tender.id) **where** $.tender.procurementMethod = &#39;direct&#39; |

_ **Table 12 Share of non-competitive procedures** _

|
1. Name of indicator
 | Share of non-competitive procedures |
| --- | --- |
|
1. Description
 | This indicator refers to the ratio of the number of non-competitive procedures to the total number of procedures which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **{**** Number **** of non-competitive procedures} / count**($.tender.id)**\* 100%** |

_ **Table 13 Number of rejected bids** _

|
1. Name of indicator
 | Number of rejected bids |
| --- | --- |
|
1. Description
 | This indicator refers to the number of bids which have been rejected during qualification or evaluation processes. |
|
1. Formula
 | **{Number of bids}
 where** $.bids.details[].status = &#39;disqualified&#39;
**or** ($.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;))_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id_ |

_ **Table 14 Number of lots with rejected bids** _

|
1. Name of indicator
 | Number of lots with rejected bids |
| --- | --- |
|
1. Description
 | This indicator presents the number of lots which have at least one rejected bid. |
|
1. Formula
 | **{Number of lots} where** $.bids.details[].status = &#39;disqualified&#39; **or** ($.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;))_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id__Hint: $.bids.details[] associated with the lot object by $.bids.details[].relatedLots[].id = $.tender.lots[].id_ |

_ **Table15 Average number of rejected bids per lot** _

|
1. Name of indicator
 | Average number of rejected bids per lot |
| --- | --- |
|
1. Description
 | This indicator presents the average number of bids rejected by procuring entity within one lot. |
|
1. Formula
 | **{Number of rejected bids} / {Number of lots with rejected bids}** |

_ **Table 16 Number of enquiries** _

|
1. Name of indicator
 | Number of enquires |
| --- | --- |
|
1. Description
 | This indicator presents the number of enquiries about procedures placed in the eProcurement system |
|
1. Formula
 | **count** ($.tender.enquiries[].id) |

_ **Table 17 Share of unanswered enquiries** _

|
1. Name of indicator
 | Share of unanswered enquiries |
| --- | --- |
|
1. Description
 | This indicator presents the share of enquiries which have been left without responds among all enquiries about procedures placed in the eProcurement system |
|
1. Formula
 | **{Number of enquires}**** where not exists** $.tender.enquiries[].answer
**/{Number of enquires}** \*100% |

_ **Table 18 Number of complaints** _

|
1. Name of indicator
 | Number of complaints |
| --- | --- |
|
1. Description
 | This indicator presents the number of complaints placed in the eProcurement system. |
|
1. Formula
 | **count** ($.tender.complaints[].id) |

_ **Table 19 Number of awards** _

|
1. Name of indicator
 | Number of awards |
| --- | --- |
|
1. Description
 | This indicator presents the number of awards made by contracting authorities on bids. |
|
1. Formula
 | **count** ( **distinct** $.awards[].id) **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39;_Hint: $.awards[] associated with the lot object by $.awards[].relatedLots[] = $.tender.lots[].id_ |

_ **Table 20 Number of lots with confirmed awards** _

|
1. Name of indicator
 | Number of lots with confirmed awards |
| --- | --- |
|
1. Description
 | This indicator presents the number of lots in which the bidder was awarded, and this winner confirmed/accepted that award. |
|
1. Formula
 | **{Number of lots} where exists** ($.awards[] **where** $.awards[].status = &#39;active&#39;)_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id__Hint: $.bids.details[] associated with the lot object by $.bids.details[].relatedLots[].id = $.tender.lots[].id_ |

1.
# Cost indicators

_ **Table 21 Lots&#39; value** _

|
1. Name of indicator
 | Lots&#39; value |
| --- | --- |
|
1. Description
 | This indicator presents the total value of lots placed in the electronic public procurement system. |
|
1. Formula
 | **sum** ($.tender.lots[].value.amount) **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 22 Contracts&#39; value** _

|
1. Name of indicator
 | Contracts&#39; value |
| --- | --- |
|
1. Description
 | This indicator presents the total value of contracts registered in the electronic public procurement system. |
|
1. Formula
 | **sum** ($.contracts[].value.amount) |

_ **Table 23 Planned value** _

|
1. Name of indicator
 | Planned value |
| --- | --- |
|
1. Description
 | This indicator presents thetotal value of plans on lots which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **sum** ([planning API]$.planning.plans.value.amount) |

_ **Table 24 Total price reduction** _

|
1. Name of indicator
 | Total price reduction/Savings |
| --- | --- |
|
1. Description
 | This indicator presents the difference between the initial cost of lots and the cost of this lots in the awarded procedures. |
|
1. Formula
 | **{Lots&#39; value} - sum** ($.awards[].value.amount **where** $.awards.status = &#39;active&#39; **and** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39;)_Hint: $.awards[] associated with the lot object by $.awards[].relatedLots[] = $.tender.lots[].id_ |

_ **Table 25 Percentage of price reduction** _

|
1. Name of indicator
 | Percentage of price reduction |
| --- | --- |
|
1. Description
 | This indicator refers to the share of savings to the total lots value. |
|
1. Formula
 | **{Total price reduction} / {Lots&#39; value} \* 100%** |

_ **Table 26 Contracts&#39; value resulted from non-competitive procedures** _

|
1. Name of indicator
 | Contracts&#39; value resulted from non-competitive procedures |
| --- | --- |
|
1. Description
 | This indicator presents the contracts&#39; value resulted from non-competitive procedures. |
|
1. Formula
 | **{Contracts&#39; value} where** $.tender.procurementMethod = &#39;direct&#39; |

_ **Table 27 Share of contracts&#39; value resulted from non-competitive procedures** _

|
1. Name of indicator
 | Share of contracts&#39; value resulted from non-competitive procedures |
| --- | --- |
|
1. Description
 | This indicator presents the ratio of the contracts&#39; value resulted from non-competitive procedures to the total contracts&#39; value. |
|
1. Formula
 | **{Contracts&#39; value resulted from non-competitive} / {Contracts&#39; value}** |

_ **Table 28 Percentage of plan execution** _

|
1. Name of indicator
 | Percentage of plan execution |
| --- | --- |
|
1. Description
 | This indicator presents the share of the value of lots which are published in the electronic public procurement system to thetotal value of plans on lots which are publicly available on the electronic web portal of the Kyrgyz Republic. |
|
1. Formula
 | **{Lots&#39; value} / {Planned value} \* 100%** |

_ **Table 29 Value of lots with rejected bids** _

|
1. Name of indicator
 | Value of lots with rejected bids |
| --- | --- |
|
1. Description
 | This indicator presents the value of lots which have at least one rejected bid. |
|
1. Formula
 | **{Lots&#39; value} where exists** ($.tender.lots[].id
 **             where** $.bids.details[].status = &#39;disqualified&#39;
               **or** ($.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;)))_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id__Hint: $.bids.details[] associated with the lot object by $.bids.details[].relatedLots[].id = $.tender.lots[].id._ |

_ **Table 30 Lots&#39; value with awarded bidders** _

|
1. Name of indicator
 | Lots&#39; value with awarded bidders |
| --- | --- |
|
1. Description
 | This indicator presents the value of lots in which the bidder was awarded, and this winner confirmed/accepted that award. |
|
1. Formula
 | **{Lots&#39; value} where exists** ($.awards[].id **where** $.awards[].status = &#39;active&#39;)_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id__Hint: $.bids.details[] associated with the lot object by $.bids.details[].relatedLots[].id = $.tender.lots[].id.._ |

1.
# Time/duration related indicators

_ **Table 31 Average enquiry period duration** _

|
1. Name of indicator
 | Average enquiry period duration |
| --- | --- |
|
1. Description
 | This indicator presents the average duration in days of enquiry period (calculated for completed lots). |
|
1. Formula
 | **avg** ($.tender.enquiryPeriod.endDate - $.tender.enquiryPeriod.startDate)
**where** $.tender.lots.status = &#39;complete&#39; **and** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 32 Average bidding period duration** _

|
1. Name of indicator
 | Average bidding period duration |
| --- | --- |
|
1. Description
 | This indicator presents the average duration in days of bidding period (calculated for completed lots). |
|
1. Formula
 | **avg** ($.tender.tenderPeriod.endDate - $.tender.tenderPeriod.startDate)
**where** $.tender.lots.status = &#39;complete&#39; **and** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; |

_ **Table 33 Average awarding period duration** _

|
1. Name of indicator
 | Average awarding period duration |
| --- | --- |
|
1. Description
 | This indicator presents the average duration in days for awarding period (calculated for completed lots). This period begins right after the bidding period and ends when the bidder accept the award. |
|
1. Formula
 | **a**** vg**([**min**($.awards[].date)**where**$.awards[].status = &#39;active&#39;**and **$.tender.lots.status = &#39;complete&#39;** and**$.tender.procurementMethod \&lt;\&gt; &#39;direct&#39;
**group by** $.tender.lots[].id**]** - $.tender.tenderPeriod.endDate)_Hint: $.awards[] associated with the lot object by $.awards[].relatedLots[] = $.tender.lots[].id_ |

_**Table 34 Average procedure stage duration (lots)**_

|
1. Name of indicator
 | Average procedure stage duration (lots) |
| --- | --- |
|
1. Description
 | This indicator presents the average duration in days for a period which begins when procedure published on the eProcurement system and ends when bidder accepted the award |
|
1. Formula
 | **{** Average enquiry period duration **} + {** Average bidding period duration**} +
 { **Average awarding period duration** }** |

_ **Table 35 Average time to answer enquiry** _

|
1. Name of indicator
 | Average time to answer enquiry |
| --- | --- |
|
1. Description
 | This indicator presents the average duration in days to answer questions and enquiries submitted by potential bidders. |
|
1. Formula
 | **avg** ($.tender.enquiries[].dateAnswered - $.tender.enquiries[].date) |

1.
# EEC indicators

_ **Table 36 Number of concluded procedures** _

|
1. Name of indicator
 | Number of concluded procedures |
| --- | --- |
|
1. Description
 | This indicator presents the number of procedures/lots which have a terminated status: &#39;complete&#39;, &#39;cancelled&#39;, &#39;unsuccessful&#39;. |
|
1. Formula
 | **count** ($.tender.id) **where** $.tender.status \&lt;\&gt; &#39;active&#39; // **count** ($.tender.lots[].id) **where** $.tender.lots[].status \&lt;\&gt; &#39;active&#39; **or** $.tender.status \&lt;\&gt; &#39;active&#39; |

_ **Table 37 Number of unsuccessful procedures** _

|
1. Name of indicator
 | Number of unsuccessful procedures |
| --- | --- |
|
1. Description
 | This indicator presents the number of procedures(lots) which were completed with the status &#39;unsuccessful&#39; due to the cancelation or lack of submitted bids. |
|
1. Formula
 | **count** ($.tender.lots[].id) **where** $.tender.lots[].status **in** (&#39;unsuccessful&#39;, &#39;cancelled&#39;) **or** $.tender.status **in** (&#39;unsuccessful&#39;, &#39;cancelled&#39;) |

_ **Table 38 Number of bids submitted by potential suppliers** _

|
1. Name of indicator
 | Number of bids submitted by potential suppliers |
| --- | --- |
|
1. Description
 | This indicator presents the number of bids in the procedures in terminated statussubmitted by potential suppliers through the eProcurement system. |
|
1. Formula
 | **count** ( **distinct** $.bids.details.priceProposal.id) **where** $.tender.lots[].status \&lt;\&gt; &#39;active&#39; **or** $.tender.status \&lt;\&gt; &#39;active&#39; |

_ **Table 39 Number of dismissed bids** _

|
1. Name of indicator
 | Number of dismissed bids |
| --- | --- |
|
1. Description
 | This indicator presents the number of dismissed bids at the qualification or evaluation stages of the tendering process. |
|
1. Formula
 | **count** ( **distinct** $.bids.details.priceProposal.id)
**where (**$.bids.details.status = &#39;disqualified&#39; **or (**$.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;))) **and** $.tender.lots[].status \&lt;\&gt; &#39;active&#39; **or** $.tender.status \&lt;\&gt; &#39;active&#39;_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id_ |

_ **Table 40 Number of bids submitted by awarded bidders** _

|
1. Name of indicator
 | Number of bids submitted by awarded bidders |
| --- | --- |
|
1. Description
 | This indicator presents the number of bids which were submitted by awarded bidders. |
|
1. Formula
 | **count** ( **distinct** $.bids.details.priceProposal.id)
**where** $.bids.details.status = &#39;valid&#39; **and**** exists**($.awards[].id**where**$.awards.status = &#39;active&#39;)**and** $.tender.lots[].status = &#39;complete&#39;_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id_ |

_ **Table 41 Value of signed contracts** _

|
1. Name of indicator
 | Value of signed contracts |
| --- | --- |
|
1. Description
 | This indicator presents the value of signed contracts which were registered in the electronic public procurement system. |
|
1. Formula
 | **sum** ($.contracts.value.amountDiscounted) |

_ **Table 42 Country of bidder/supplier** _

|
1. Name of indicator
 | Country of bidder/supplier |
| --- | --- |
|
1. Description
 | Here presented the way the country of bidder/supplier were chosen. |
|
1. Formula
 | $.parties[].address.countryName **where**&#39;tenderer&#39;(&#39;supplier&#39;) **in** $.parties.roles[] |

_ **Table 43 Number of bids submitted by awarded bidders who refused to sign the contract** _

|
1. Name of indicator
 | Number of bids submitted by awarded bidders who refused to sign the contract |
| --- | --- |
|
1. Description
 | This indicator presents the number of bids which were submitted by awarded bidders who rejected the award during the evaluation stage of procurement. |
|
1. Formula
 | **count** ( **distinct** $.bids.details.priceProposal.id)
**where** $.awards.status = &#39;rejected&#39; **and** $.tender.lots[].status \&lt;\&gt; &#39;active&#39; **or** $.tender.status \&lt;\&gt; &#39;active&#39;_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id_ |

The ECC forms consist of distribution of quantitative and cost characteristics of public procurement by procedures types. This distribution, is mostly defined by the field $.tender.procurementMethodDetails. The correspondence of that field to the types of procedures for the ECC form as well as other necessary conditions, are as follows:

_ **Table 44 Mapping local procurement methods to the ECC form** _

| **#** | **Types of procurement methods in ECC form** | **$.tender.procurementMethodDetails** | **Other conditions** |
| --- | --- | --- | --- |
| 1 | Open tender | oneStage, auctionUnlimited, egov, twostage | $.tender.procurementSubMethodDetails **not in** (&#39;centralised&#39;, &#39;personific&#39;, &#39;framework&#39;) |
| --- | --- | --- | --- |
| 2 | Two stage procedures | twostage | $.tender.procurementSubMethodDetails \&lt;\&gt; &#39;twopackage&#39; |
| 3 | Procedures with pre-qualification | oneStage, auctionUnlimited, egov, twostage | $.tender.hasPrequalification **is** TRUE **and** $.tender.procurementSubMethodDetails **not in** ( &#39;centralised&#39;, &#39;personific&#39;, &#39;framework&#39;) |
| 4 | Electronic open tender with an auction | eAuction, downgrade | --- |
| 5 | Request for quotations | requestForQuotation, simplicated | $.tender.procurementSubMethodDetails **not in** (&#39;personific&#39;, &#39;framework&#39;) |
| 6 | Single source procurement | singleSource | $.tender.procurementSubMethodDetails **not in** (&#39;personific&#39;, &#39;framework&#39;) |
| 7 | Other procurement methods | auctionLimited, consultQualityPrice, consultQuality, consultFixedBudget, consultPrice, consultQualification, consultSingleSource, personific | --- |

1.
# Indicators for reporting to the Public Procurement Department

_ **Table 45 Number of dismissed bids at the evaluation stage** _

|
1. Name of indicator
 | Number of dismissed bids at the evaluation stage |
| --- | --- |
|
1. Description
 | This indicator refers to the number of bidders which have been rejected during the evaluation processes |
|
1. Formula
 | **{Number of bidders} where** $.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;) |

_ **Table 46Number of dismissed bids at the qualification stage** _

|
1. Name of indicator
 | Number of dismissed bids at the qualification stage |
| --- | --- |
|
1. Description
 | This indicator refers to the number of bidders which have been rejected during the qualification processes |
|
1. Formula
 | **{Number of bidders} where** $.bids.details.status = &#39;disqualified&#39; |

_ **Table 47 Value of the winning bid** _

|
1. Name of indicator
 | Value of the winning bid |
| --- | --- |
|
1. Description
 | This indicator presents the value of the bid submitted by the supplier selected as the winner |
|
1. Formula
 | $.bids.details.relatedLots.value.amount where $.bids.details.status = &#39;valid&#39; **and exists** ($.awards.id **where** $.awards.status = &#39;active&#39;) |

_ **Table 48 Number of bidders** _

|
1. Name of indicator
 | Number of bidders |
| --- | --- |
|
1. Description
 | This indicator presents the number of organizations which have participated in public procurement tenders. |
|
1. Formula
 | **count distinct** ($.parties[].id) **where**&#39;tenderer&#39; **in** $.parties[].roles[] |

_ **Table 49 Number of dismissed bids** _

|
1. Name of indicator
 | Number of dismissed bids |
| --- | --- |
|
1. Description
 | This indicator presents the number of dismissed bids at the qualification or evaluation stages of the tendering process. |
|
1. Formula
 | **count** ( **distinct** $.bids.details.priceProposal.id)
**where (**$.bids.details.status = &#39;disqualified&#39; **or (**$.bids.details.status = &#39;valid&#39; **and exists** ($.awards[].id **where** $.awards.status = &#39;disqualified&#39;))) **and** $.tender.lots[].status \&lt;\&gt; &#39;active&#39; **or** $.tender.status \&lt;\&gt; &#39;active&#39;_Hint: $.awards[] associated with the bid object by $.awards[].relatedBid = $.bids.details[].id_ |

_ **Table 50 Contracts&#39; value** _

|
1. Name of indicator
 | Contracts&#39; value |
| --- | --- |
|
1. Description
 | This indicator presents the total value of contracts registered in the electronic public procurement system. |
|
1. Formula
 | **sum** ($.contracts[].value.amount) |

1.
# Data quality indicators

_ **Table 51 Tenders without lots** _

|
1. Name of indicator
 | Tenders without lots |
| --- | --- |
|
1. Description
 | This indicator presents the total number of electronic tender notices where no information about lots is available. |
|
1. Formula
 | **count** ($.tender.id) **where** $.tender.procurementMethod \&lt;\&gt; &#39;direct&#39; **and not exists(**$.tender.lots[]) |

_ **Table 52 No information about supplier** _

|
1. Name of indicator
 | No information about supplier |
| --- | --- |
|
1. Description
 | This indicator presents the total number of procedures where contracts were signed but no information about suppliers was provided. |
|
1. Formula
 | **count** ($.tender.id) **where exists(**$.contracts[]) **and not exists** ($.parties.roles[] = &#39;supplier&#39;) |

_ **Table 53 No information about bids submitted** _

|
1. Name of indicator
 | No information about bids submitted |
| --- | --- |
|
1. Description
 | This indicator presents the total number of electronic tender notices where award was made but there is no information about submitted bids. |
|
1. Formula
 | **count** ($.tender.id) **where exists(**$.awards[]) **and not exists** ($.bids.details[]) |

_ **Table 54 Two active awards in one lot** _

|
1. Name of indicator
 | Two active awards in one lot |
| --- | --- |
|
1. Description
 | In tenders which are available in the eProcurement system of the Kyrgyz Republic has to be only one award per lot. This indicator presents the total number of electronic tender notices where exist two awards in one lot. |
|
1. Formula
 | **count** ($.tender.id) **where exists** (( **count** $.awards[].id **where** $.awards[].status = &#39;active&#39; **group by** relatedLots[].id) \&gt; 1) |

_ **Table 55 No price proposal for the lot** _

|
1. Name of indicator
 | No price proposal for the lot |
| --- | --- |
|
1. Description
 | This indicator presents the total number of electronic tender notices in which bids were submitted by potential suppliers but there was no price proposal in the bid. |
|
1. Formula
 | **count** ($.tender.id) **where exists(**$.bids.details[].id **where** $.bids.details[].priceProposal[].id **is null** ) |

_ **Table 56 Bid without reference to the lot** _

|
1. Name of indicator
 | Bid without reference to the lot |
| --- | --- |
|
1. Description
 | This indicator presents the total number of electronic tender notices where exists at least one bid submitted by potential supplier who hasn&#39;t linked his bid to any lot. |
|
1. Formula
 | **count** ($.tender.id) **where exists** ($.bids.details[].id **where not exists(**$.bids.details[].relatedLots[])) |
