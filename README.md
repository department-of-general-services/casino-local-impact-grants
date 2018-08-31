# Baltimore City Casino Local Impact Grant Funding Analysis
This repository provides the business/government problem, data and other information about the Casino Local Impact Grant funding program, managed by the City of Baltimore. 

## Getting Started
We need analysis visualizations that communicate:
 - Funding level distribution by dollars by program, by target area and by agency by fiscal year
 - Performance measures that consider the timeliness of funds spent and city agencies’ accountability to their projects and the ability to close or complete projects within the funding year
 - The general project readiness of grant-funded projects including when agencies start and finish spending funds, which may indicate their readiness to implement these projects
 - Recipient agencies’ funding-utilization rates, measured by allocation vs. spending amounts and time periods
 - Total spending and spending trends for these grants and how they may impact distribution and outcomes
 - Any other analysis and requests for additional data that can better inform the city in how they:
   - distribute and monitor funding
   - better inform the public on the status of the Casino Local Impact Grant funded programs
   - develop early notification mechanisms for intervention points 
   - effectively communicate any meaningful correlations, relationships, historical and anticipated outcomes that better enable managers and stakeholders to hold agencies accountable for their participation. 
 

## Desired Analysis Outcomes 
The project has the following basic requirements in addition to the above analysis needs laid out in the problem statement. 
 - Providing tools for ease of updating data for quarterly reporting and to compare against historic trends. 
 - Create tools for public viewing and creating dashboard views of key datapoints
 - Creating views that highlight and illustrate key datapoints pertaining to projects’ progress and outcomes
 - Creating views that highlight and illustrate spending over time and in current periods. 
 
## Background
Based on the state enabling legislation, (2012 Special Session 2, SB 1), the City of Baltimore started receiving casino local impact grant funds (“LIG”) derived from a portion (approximately 4.5%) of gaming revenues (i.e., video lottery terminal, or VLT, aka electronic slot machines, only) from Horseshoe Casino starting in 2015 (the old formula). At the end of 2016, Baltimore began also receiving LIG funds from Maryland Live and MGM National Harbor casinos, following the opening of MGM, under the “new formula” in which LIG funds from these three casinos are pooled and divided equally among the three host jurisdictions. 
These funds are to be used for improvements in the neighborhoods surrounding the Horseshoe Casino, designated as the Casino Impact Area or “South Baltimore Gateway.” These include: Barre Circle, Carroll-Camden Industrial Area, Cherry Hill, Federal Hill, Lakeland, Mount Winans, Otterbein, Pigtown, Ridgely’s Delight, Riverside, South Baltimore Neighborhood, Sharp-Leadenhall, Saint Paul, and Westport.
By law, the City is charged with creating a “multi-year spending plan,” created with input from the Casino Local Development Council (“LDC”), an advisory body appointed by the Mayor, which is comprised of community, business and institutional representatives from the neighborhoods above, the Maryland State Senator and two members of the House of Delegates from the impact area. The law requires that programming initiatives from these grants should within the following purposes:

 - infrastructure improvements
 - facilities
 - public safety
 - economic and community development, including housing, and
 - other public services and improvements.
 
The law further requires that the City of Baltimore establish a schedule for the distribution and expenditure of LIG funds and provide quarterly reports to the Legislative Policy Committee of the Maryland General Assembly on the distribution of the funds. 
In preparation for the opening of the Horseshoe Casino and the flow of LIG funds, the City of Baltimore working through the Department of Planning in consultation with the LDC created the South Baltimore Gateway Master Plan. The planning process started in 2013, and the plan was issued at the end of 2015, with the intention of guiding the allocation and leveraging of LIG funds over the next 20 years. The Master Plan contains a wide range of strategies and recommendations grouped under broad goal statements for each of the following nine (9) topics:

1. Transportation Connectivity
2. Environmental Sustainability
3. Safety
4. Community Development & Revitalization
5. Economic Growth
6. Education
7. Health & Wellness
8. Quality of Life
9. Infrastructure

In 2016, the General Assembly, Mayor and City Council established the South Baltimore Gateway Community Impact District Management Authority in order to help manage a portion of LIG funds in fulfillment of the Master Plan. Starting in FY’18, this authority, branded as the South Baltimore Gateway Partnership (SBGP) began receiving one half or 50% of LIG funds provided for South Baltimore. The City through the Mayor’s Office, continues to receive and manage the remaining 50% of LIG funds, which is the basis for the datasets referred to here and the ongoing reporting requirement. 

## Data Dictionary
The dataset outlines the funding distribution, agency spending, and current balance remaining for all Local Impact Grant funded projects. The column headers indicate the following:
__Project or Activity Name:__ 1-10 word description of funded project or targeted initiative

__LDC Ranking FY15:__ Prioritization of activity during first-year spending plan creation

__Lead Agency:__ Baltimore City government agency responsible for the activity or for administering funds on behalf of contractors or sub-grantees.

__Timeframe:__ Expected duration of the project (funding is allocated annually; however agencies can receive funds for the same activity on a recurring or installment basis)

__Fiscal Year__ (Multiple columns and categories):

 - __Budgeted:__ Dollar amounts allocated to project or activity in a given fiscal year
 - __Revised/Final:__ Dollar amounts allocated to the project either through mid-year revisions or at year-end closeout. These amounts may match or differ from budgeted amounts.
 - __Carry Forward:__ Dollar amounts not spent as of year-end closeout, but maintained with the project or activity and “carried forward” to have available in the subsequent budget year.  
 - __FY’16 Tier 1 and Tier 2:__ In FY’15 and FY’16 the Spending Plan included “Tier 1” or low-end and “Tier 2” high-end budgets, as there was no revenue history. In FY’15, the actual revenue fell below the Tier 1 target. In FY’16, there was some amount of surplus over the Tier 1 budget at year-end. This was programmed as “Tier 2” providing additional funding for some activities, which was carried forward for use in FY’17. 
 - __FY’17 Expended:__ Dollar amount spent for that project in fiscal year. 
 - __FY’18 Modification:__ Dollar amount added/subtracted to the budget. This category was used to track budget-cutting measures. Revenue in FY’17 and FY’18 were again below budgeted amounts, after exceeding the budgeted (i.e. Tier 1) amount in FY’16. This occurred after the switch to the new formula, under which revenues did not increase as much as the state’s analysts had predicted they would. 
 - __FY’17 or FY’18 Rev./Final:__ Dollar amount for the total budget for that project in fiscal year XX (Budgeted + Carry Forward +/- Modification). Note may include funds to be carried forward into the next year, i.e. unspent funds that stay with the project.
 
__Q1-4:__ Dollar amount spent in fiscal quarters 1-4 in the current fiscal year.

__Total Spending:__ Dollar amount spent as sum of quarters in the current year.

__Balance Remaining:__ Dollar amount not spent for project in the current fiscal year.

__Remarks:__ Notes on the projects
 

