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


## Highest company with disputed customer 
| Company | Consumer disputed?  | count |
| :------------ |:---------------:| -----:|
| 	BANK OF AMERICA, NATIONAL ASSOCIATION	| Yes	| 14387
|	WELLS FARGO & COMPANY	| Yes	| 11717
|	EQUIFAX, INC.	| Yes	| 10079
|	JPMORGAN CHASE & CO.	| Yes	| 9523
|	CITIBANK, N.A.	|Yes	|6697|
|	Ocwen Financial Corporation	| Yes	| 5719|
|	TRANSUNION INTERMEDIATE HOLDINGS, INC.	| Yes	| 5638
|	Experian Information Solutions Inc.	| Yes	| 5330
|	NATIONSTAR MORTGAGE LLC	| Yes	| 3758
|	CAPITAL ONE FINANCIAL CORPORATION	| Yes	| 3655
|	Navient Solutions, LLC.	| Yes	| 3083
|	U.S. BANCORP	| Yes |	2652
|	Ditech Financial LLC	| Yes	| 2463
|	AMERICAN EXPRESS COMPANY	| Yes	| 2253
|	SYNCHRONY FINANCIAL	| Yes	|1965

