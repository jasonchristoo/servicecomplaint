# Predict complaint from customer
Objectives : Track historical data to predict customer disputed or not

Dataset column consist of :

`Complaint ID` 		: The unique identification number for a complaint <br>
`Date received ` 	: when complaint received <br>
`Product `			   :	The type of product the consumer identified in the complaint <br>
`Sub-product `: The type of sub-product the consumer identified in the complaint <br>
`Issue` : The issue the consumer identified in the complaint <br>
`Sub-issue` :  The sub-issue the consumer identified in the complaint <br>
`Company public response` : The company's optional, public-facing response to a consumer's complaint. Companies can choose to select a response from a pre-set list of options that will be posted on the public database <br>
`Company` : The complaint is about this company <br>
`State` : The state of the mailing address provided by the consumer <br>
`ZIP code `: The mailing ZIP code provided by the consumer <br>
`Consumer consent provided?` : Identifies whether the consumer opted in to publish their complaint narrative. We do not publish the narrative unless the consumer consents and consumers can opt-out at any time. <br>
`Submitted via `: How the complaint was submitted <br>
`Date sent to company` : The date the CFPB sent the complaint to the company <br>
`Timely response?` : Whether the company gave a timely response <br>
`Consumer disputed?` : Whether the consumer disputed the company's response <br>
`Company response to consumer` : This is how the company responded. For example, "Closed with explanation." <br>

## Consumer disputed over product
![image](https://github.com/jasonchristoo/servicecomplaint/assets/123045563/e89efe52-916b-4ce3-b12f-d1c9091661e0)

## Consumer disputed over timely response
![image](https://github.com/jasonchristoo/servicecomplaint/assets/123045563/87e6bea8-3c29-4337-acdd-e195f10c4da2)

Company	Consumer disputed?	count
0	BANK OF AMERICA, NATIONAL ASSOCIATION	Yes	14387
1	WELLS FARGO & COMPANY	Yes	11717
2	EQUIFAX, INC.	Yes	10079
3	JPMORGAN CHASE & CO.	Yes	9523
4	CITIBANK, N.A.	Yes	6697
5	Ocwen Financial Corporation	Yes	5719
6	TRANSUNION INTERMEDIATE HOLDINGS, INC.	Yes	5638
7	Experian Information Solutions Inc.	Yes	5330
8	NATIONSTAR MORTGAGE LLC	Yes	3758
9	CAPITAL ONE FINANCIAL CORPORATION	Yes	3655
10	Navient Solutions, LLC.	Yes	3083
11	U.S. BANCORP	Yes	2652
12	Ditech Financial LLC	Yes	2463
13	AMERICAN EXPRESS COMPANY	Yes	2253
14	SYNCHRONY FINANCIAL	Yes	1965
