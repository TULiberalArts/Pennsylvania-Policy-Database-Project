---
# global predefined variables
layout: tla_page
permalink: /datasets/
published: true
# meta-data variables
title: Datasets
# custom variables
---
## Available Data
We encourage the free and attributed use of the data collected as part of the Pennsylvania Policy Database Project for publications, instructional use, for policy analysis, and for other non-commercial purposes.

We kindly ask that our data, when used, is cited in one of the following two ways. When included in a reference section:
- J. McLaughlin, P. Wolfgang, J.W. Leckrone, J. Gollob, J. Bossie, J. Jennings, and M. Atherton. 2010.
“The Pennsylvania Policy Database Project: A Model for Comparative Analysis.” _State Politics and Policy Quarterly,_ 10:320-36.

When cited in a note regarding the source of the data, please include the following along with the date the data was accessed:
- Pennsylvania Policy Database Project, Principal Investigator Joseph P. McLaughlin, Temple University.

## Dataset Descriptions
Below is a description of each of our ten datasets. Click on the below links to skip down to a particular dataset.

- [Governing Magazine](#governing-magazine)
- [Newspaper Clips](#newspaper-articles)
- [Bills, Resolutions and Laws](#bills-resolutions-and-laws)
- [Legislative Hearings](#legislative-service-agency-reports)
- [Legislative Service Agency Reports (House and Senate)](#legislative-service-agency-reports)
- [Governor Budget Addresses](#governors-budget-address)
- [Executive Orders](#executive-orders)
- [Supreme Court Decisions](#supreme-court-decisions)
- [Most Important Problem Polls](#most-important-problem-polls)
- [Budget Total Spending All Funds](#budget-total-spending-all-funds)

### Governing Magazine
This dataset includes all articles which appeared in Governing Magazine since 1988. The magazine features articles that examine trends in state and local government. Its inclusion into this database allows researchers to understand the policy debate in Pennsylvania in the context of development in other states. A code and filters have been applied to each record.

**Identifying Variables:**
- ID – These are unique numerical identifiers for each article included in the dataset.
- Year – The year the article was published.
- Month – The month the article was published.
- Title – The actual headline of the article.
- Abstract – A three to five sentence abstract meant to summarize the key points of the article. Researchers avoid abbreviations and jargon while including as many essential figures as possible. Researchers undergo extensive training to ensure a high quality and amount of information contained in each abstract.

**Filter Variables**: For each of the following variables the abstracting researcher examines the original article for mentions of specific actors, events, or topics. For each filter variable, there are three possible values: 
- 0 – no mention
- 1 – significant mention
- 2 – mention

All filters are assigned a 0 by default. In cases where the actor/topic plays a critical role in the article, researchers assign a "1". For example, a story about Governor Rendell giving the State of the State address would receive a "1" for the Executive filter. In cases where the actor/topic is less crucial to the functioning of the article, we assign a "2." In the previous example, a passing mention of the Philadelphia branch of MADD (Mothers Against Drunk Driving) at the end of the article would warrant a "2" for the Interest Group filter.

- Executive – This filter marks the mentioning of the governor, his administration, his staff, and members of the cabinet, the lieutenant governor, and previous governors (when mentioned in reference to their activities as governor).

- Legislative – This filter indicates the mentioning of the Pennsylvania legislature (the General Assembly, House or the Senate), individual state legislators, legislative committees or advisory bodies, and legislative debates or actions. This filter, however, is not marked for mentions of specific legislation in the absence of remarks of the legislature.

- Judicial – This filter marks the mentioning of Pennsylvania state courts or judicial activities. It includes references to the State Supreme Court, Superior Courts, Commonwealth Courts, and any other reference to courts in the state (as PA has a unified judicial system, meaning that all courts are under the direction of the state).

- State Agency – This filter marks the mentioning of Pennsylvania state agencies, department heads, and general references to state advisory committees or state employees. Note that members of the cabinet supervise most agencies, whose mentions warrant the executive filter and not the state agency filter.

- Local Government – This filter marks the mentioning of a specific local government, local officials, and local government bodies (e.g., school boards). Mentions of particular cities or counties also warrant the local government filter when they provide a reference to the actions of governing bodies.

- Federal Government – This filter indicates any mentions of the United States Federal Government including the President, Congress, federal agencies, bureaucracies, officials, and any other reference to national policies, legislation, or actions.

- Interest Groups – This filter marks the mentioning of specific groups engaged in lobbying activity or other efforts to influence the policy process. It can include the larger, more recognizable interest groups like the NRA (National Rifle Association) and the AARP (American Association of Retired Persons), and smaller, less identifiable groups like the State College Chamber of Commerce and the Cambria County Teachers’ Union. Note that this filter marks business organizations, unions, foundations, institutes, and non-profit organizations. However, the lobbying actions of any specific business do not warrant this filter.

- Elections (candidates, campaigns, and parties) – This filter marks any mentions of elections, campaigns (for public office at any level), and mentions of specific inter-party competition. Note that the filter is not used for general non-election references to party competition in the legislature, as that is always constant.

- Tax – This filter marks any mentions of specific taxes or changes in the tax structure. It includes remarks of general taxes such as income taxes, wage taxes, sales taxes, and capital gains taxes. This filter is NOT marked, however, for mentions of “taxpayers” unless the same article also mentions a specific tax.

- Elderly – This filter marks any mentions of senior citizens or any issues related to people who are retired. It includes remarks of pensions and retirement systems, Social Security, the Pennsylvania Department of Aging, and medical care or other assistance programs for the elderly.

- Budget – This filter marks the mentioning of the budget or budgetary process. Specifically, this includes mentions of budget surpluses, budget deficits, budget proposals, hearings related to the budget and any changes to the existing budget.

- Foreign – This filter notes articles that are not about United States policy.

- Pennsylvania – This filter indicates articles that refer specifically to Pennsylvania.

### Newspaper Clips
This dataset provides a measure of the government’s attention to news reporting and opinion on public policy issues in Pennsylvania beginning in 1979. Because there is no dominant news source for the entire state, these data are composed of a random sample of news reports produced by dozens of newspapers and electronic media across Pennsylvania as collected by state Capitol press offices and circulated to key policy makers each weekday in the form of news digests. This is the only dataset that is a random sample as opposed to universal. The governor’s press office has been the source of the news reports during the Thornburgh (1979-1987), Casey (1987-1995),  Rendell (2003-2011), Corbett (2011-2015) administrations. 

**Insert Table**

During the combined Ridge and Schweiker administrations (1995-2003), the project sampled similar news digests produced by the press offices of the House Democratic and Republican caucuses. These reports are collected and circulated by press offices to insure that policy makers and their staffs are aware of what news organizations and opinion writers across Pennsylvania are saying about policy issues. In simple terms, the articles represent the news media’s “agenda” as perceived by key policy makers.

The almost 40 years of articles included in the dataset were collected, abstracted, and then coded by researchers. On average, there are around 1500 articles per year. A random sample was collected by examining articles on every tenth page from the archived news digests. Once collected, the articles were read and then converted into three to five sentence abstracts by undergraduate researchers. During this process, the researchers also coded a variety of filter variables regarding the mention of important actors or topics, which are explained in further detail below. In addition to the filters the articles’ newspaper of origin, date of publication, original headline, and article type were coded to allow for future researchers to locate the original source documents easily and efficiently. The final step in collecting these data involved the application of the Pennsylvania Policy Database Project’s adaptation of the topic coding scheme used by the Policy Agendas Project to the article abstracts. These data are then combined for each individual record such that for every article sampled the following variables are available for analysis.

Because the volume of news stories can fluctuate from year to year and from one press office to another, we recommend using percentage measures to compare attention to various policy topics across  years and legislative sessions. Recognizing that space from news stories can vary from one year to the next due to arbitrary factors such as fluctuations in advertising revenues, the Policy Agendas project also recommends percentage measures with respect to its sample of abstracts from the New York Times index.

In 1988-1992, because the number of articles was especially high, the sample was adjusted to five percent so that stories from every twentieth page (as opposed to every tenth) are included.

**Identifying Variables:**
- ID – These are unique numerical identifiers for each article included in the dataset.
- Newspaper – The original source newspaper in which the article was published. Note: Wire stories were coded according to the publisher. Stories collected directly from the AP wire are recorded as from the Associated Press while AP stories clipped from other papers, e.g. the _Philadelphia Inquirer_, are recorded as being from those papers.
- Day – The numerical day of the month the article was published.
- Month – The month the article was published.
- Year – The year the article was published.
- Headline – The actual headline of the article.
- Abstract – A three - five sentence abstract meant to summarize the key points of the article. Researchers were instructed to avoid abbreviations and jargon while including as many key figures as possible. Researchers underwent extensive training to ensure the quality and amount of information included in each abstract.
- Code – Following the abstracting and filter coding process each article is coded according to the PA Policy Database Project’s adaptation of the Policy Agendas Project’s topic coding scheme. Codes were limited to major topic codes and are based upon the article abstracts, not the full article texts. This coding was completed using the TextTools Automated Text Classification Software.   For a fuller description of what warrants each code, please consult the Topics Codebook section in the codebook.

**Filter Variables:** For each of the following variables the abstracting researcher was asked to examine the original article for mentions of specific actors, events, or topics. For each filter variable there are three possible values: 
- 0 – no mention
- 1 – significant mention
- 2 – mention

† All filters are assigned a 0 by default. In cases where the actor/topic plays a critical role in the article researchers were asked to assign a 1. 

- Executive* – This filter is marked for mentions of the Governor, his administration, his staff, members of the cabinet, the Lieutenant Governor, and previous Governors (when mentioned in reference to their activities as governor.
- Legislative* – This filter is marked for mentions of the Pennsylvania Legislature (either the General Assembly or the Senate), individual state legislators, legislative committees or advisory bodies, and legislative debates or actions. This filter, however, is not marked for mentions of specific legislation in the absence of mentions of the legislature.
- Judicial* – This filter is marked for mentions of Pennsylvania state courts or judicial activities. This includes mentions of the State Supreme Court, Superior Courts, Commonwealth Courts, and any other reference to courts in the state (as PA has a unified judicial system, meaning that all courts are under the direction of the state).
- State Agency* – This filter marked for mentions of Pennsylvania state agencies, department heads, and general references to state advisory committees or state employees. Note that most agencies are supervised by members of the cabinet, whose mentions warrant the executive filter and not the state agency filter.
- Local Government* – This filter is marked for mentions of a specific local government, local officials, and local government bodies (i.e. school boards). Mentions of specific cities or counties also warrant the local government filter when they provide a reference to the actions of governing bodies.
- Federal – This filter is marked for any mentions of the United States Federal Government including the president, Congress, federal agencies, bureaucracies, officials, and any other reference to federal policies, legislation, or actions.
- Elections (Candidates, Campaigns, and Parties) – This filter is marked for any mentions of elections, campaigns (for public office at any level), and mentions of specific inter-party competition. Note that the filter is not used for unspecified non-election references to party competition in the legislature, as that is always constant.
- Elderly – This filter is marked for any mentions of senior citizens or any issues related to people who are retired. This includes mentions of pensions and retirement systems, Social Security, the Pennsylvania Department of Aging, and medical care or other assistance programs for the elderly.
- Tax – This filter is marked for any mentions of specific taxes or changes in the tax structure. This includes mentions of general taxes such as income taxes, wage taxes, sales taxes, and capital gains taxes. This filter is NOT marked, however, for mentions of “taxpayers” unless a specific tax is also mentioned in the same article.
- Budget – This filter is marked for mentions of the budget or budgetary process. Specifically, this includes mentions of budget surpluses, budget deficits, budget proposals, hearings related to the budget and any changes to the existing budget.
- Interest Group – This filter is marked for mentions of specific groups engaged in lobbying activity or other efforts to influence the policy process.This can include the larger, more recognizable interest groups like the NRA (National Rifle Association) and the AARP (American Association of Retired Persons), and smaller, less recognizable groups like the State College Chamber of Commerce and the Cambria County Teachers’ Union.Note that this filter is marked for business organizations, unions, foundations, institutes, and non-profit organizations.However, the lobbying actions of any specific business do not warrant this filter.
- Type – Each clipping has been coded to identify the type of article.The possible codes are as follows:
  - 1 – Article – standard print/broadcast news article
  - 2 – Editorial – article presenting the opinion of an editorial board (indicated by the presence of an opinion and references to “we” in the absence of a by-line)
  - 3 – Opinion – article presenting the opinion of a specific news columnist or policy expert (such as Governor Rendell or the head of the NAACP)
  - 4 – Letter to the Editor – letters expressing opinions written to the newspaper by average citizens.  Note that letters written by policy experts are coded as opinion articles.
  - 5 – Photograph
  - 6 – Newswire Story – articles pulled directly from the newswire. Note that newswire stories published and clipped from other papers are marked as type 1 articles.
  - 7 – Political Cartoon
  - 8 – Other
For a fuller description of the processes discussed please consult the Governors’ News Clips section of the Project Manual.

* Indicates filters that are reserved for mentions within the state of Pennsylvania. This means that mentions of the Governor of California or the legislature in New Jersey do not receive the executive and legislative filters respectively.

† As distinguishing between significant mentions and mentions can be quite subjective, we applied a simple rule of thumb depending on the article length. In articles shorter than 10 paragraphs, if a mention takes place in the first two paragraphs, it is coded as a significant mention (a 1).Anything later is coded as just a mention (a 2).In articles longer than 10 paragraphs a similar cut point is set for the first five paragraphs. Exceptions are made when critical mentions take place later in the article, as often happens in non-traditional news stories (i.e. feature stories). In such cases the application of codes was at the discretion of the researcher.

### Bills, Resolutions and Laws
This dataset includes all bills and resolutions introduced into the Pennsylvania General Assembly beginning with the 1979-80 session through the most recent full session for which coding has been completed. For all regular sessions and Special Sessions beginning in 1979 there is an average of about 5,000 bills and resolutions per session or about 2,500 per year. For each four-digit policy code users can find bill numbers, hyperlinks to the state website providing the full text of the final version of each bill or resolution and all previous versions, and a summary of its legislative history. For some years, the legislative history also provides a link to pages in the legislative journal where verbatim debate and roll calls are available.  Users can filter bills to identify, for example, bills that were referred to particular committees, passed by one chamber but not another, vetoed, enacted by overriding a veto, etc. These are explained in more detail below.Because legislators generally introduce more bills in the first year of a two-year session, the graphs of bills introduced tend to have a zig-zag look when displayed by years. Patterns of legislative attention by policy area are easier to recognize if searches are conducted by legislative sessions (thus smoothing the graphic displays) than by years.

**Legislative History Filters** In addition to enabling researchers to sort legislation by policy category, the Pennsylvania project provides filters to allow researchers to quickly identify and summarize bills and resolutions by their legislative history, a feature not found either on the website of the General Assembly, the Policy Agendas, or Congressional Bills. In using the legislative history tools, researchers should be aware that legislative actions that are logically impossible will produce empty graphs and no downloadable data, users should structure their requests to avoid such results.

**Identifying Variables:**
- Bill Numbers – A number preceded by HB (House Bill), HR (House Resolution), SB (Senate Bill), or SR (Senate Resolution) are included for each record. These are unique identifiers within each session.
- Hyperlink – A link is provided to the record in the PA General Assembly website. From here the final version of the full bill can be viewed.
- Session – Each record has a legislative session indicated by a four digit number, a dash and then a two digit number such as “2005-06,” except with Special Session when a second dash followed by a single digit will indicate Special Session such as “2005-06-1” for the only Special Session of the 1995-96 legislative session or “1995-96-2” for the second Special Session of the 1995-96 legislative session.
- Date Referred to First Committee – A date is given for when the bill or resolution was first assigned to a committee in its primary chamber.
- Sponsor – The name of the sponsor of the bill or resolution is provided for each record.
- Abstract – PA state law dictates that the short title must accurately describe the function of the bill or resolution. This short title has been included as the abstract for each record.
- Last Action – For each chamber there will be a code given to indicate the last action in each chamber. The possible codes are as follows:
  - 0 – Not reported by primary committee
  - 1 – Reported by primary committee
  - 2 – Passed on the floor
  - 3 – Defeated or deferred on the floor
  - 4 – Concurred with Senate/House Amendments
  - 5 – Non-concurred in Senate/House Amendments
  - 6 – Passed Conference Report
  - 7 – Defeated or deferred Conference Report
  - 99 – Never Reached Chamber
  
**Governor’s Action** – For each record a code will be given a binary code to indicate if an action was taken by the governor. If any of the following actions were taken the code will be 1, if this action was not taken or does not apply the code will be 0:  
- Not Sent to Governor
- Vetoed
- Line item Veto
- Overridden by legislature
- Became law without governor’s signature
- Recalled by legislature
- Signed by Governor  

NOTE: Multiple constitutional amendments sometimes are included in one bill, therefore the number of amendments does not equal the number of bills making changes to the Constitution. For more information on amendments to the 1968 PA Constitution, please visit Duquesne University School of Law’s PA Constitution [website](http://law.duq.edu/search/node/pa%20constitution).  

- Appropriations – There are several types of bills that allocate money for programs supported by the state government, the following codes indicate what type of appropriation the record is:
  - 1 – General Appropriation Bill: A bill proposing an annual state budget known as a “GA Bill.”
  - 2 – Supplemental and Special Fund Appropriations: Supplemental bills adjust the spending for the “GA Bills” and appropriate money from special funds.
  - 3 – Non-Preferred Appropriations: Appropriations to institutions not owned or under the total control of the state such as Temple University.
  - 4 – Appropriations attached to non-appropriations bills: appropriations attached to specific portions of a non-appropriation bill.
  - 99 – Not an appropriation bill
  
- Act Number – If a bill has become law (resolutions cannot become law), then the record will have an act number.  If the act is a type 1, 2 or 3 appropriation bill then it will have an “A” after the number such as “Act 12A.”
- Year Enacted – If the bill has been enacted the record will indicate the year it was enacted.
- Primary Committees – Each record will indicate the first committee each bill or resolution was assigned to in each chamber.
- Secondary Committees – Each record will indicate which committees the bill or resolution was re-assigned to after it was assigned to its primary committee.
- Policy Code – Each record will be assigned a 4 digit policy code. Please see the codebook for more information on how each record was coded.  

**Binary Filter Variables:** – There are four binary filters with a 1 indicating that the bill or resolution affected the specific area. The filters are as follows:
- Tax – This filter indicates if a tax was created or altered.
- Elderly – This filter indicates that benefits were provided or changed for older adults.
- Commemorative – This filter indicates that a bill or resolution had a purpose of commemorating an event, person(s) or holiday.
- Petition – This filter indicates that a bill or resolution requests action from another level of government (federal, local or another state), another branch of state government, a foreign government, or a private or non-profit entity.

There were Special Sessions for the following legislative sessions: 1987-88, 1991-92, 2001-02, 2005-06 and there were two in 1995-96.

Because legislators generally introduce more bills in the first year of a two-year session, the graphs of bills introduced tend to have a zig-zag look when displayed by years.  Patterns of legislative attention by policy area are easier to recognize if searches are conducted by legislative sessions (thus smoothing the graphic displays) than by years.

### Legislative Hearings (House and Senate)
**HOUSE HEARINGS**
The **House Hearings** dataset was created with the help of the House Archives. The records have been digitized and an abstract had been written by the staff of the House Archives for each hearing. Unlike the Senate hearings, which we know are incomplete, to our knowledge the House Hearings are a complete dataset of all hearings that took place since 1979. The only filter applied to this dataset is a binary budget filter. This indicates whether or not the hearing is a part of the yearly state budget process. Each record also notes which committee(s) took part in the hearing, which city the hearing took place in, and any specific legislation that was discussed during the hearing.

The following is a brief description of each data column in the downloadable dataset.

**Identifying Variables:**
- ID –These are unique numerical identifiers for each article included in the dataset.
- Day– The day of the month the hearing was held.
- Month– The month the hearing was held.
- Year– The year the hearing was held.
- Committee– The name of the committee holding the hearing.
- Other Committee – The name of a secondary committee that took part in the hearing, if applicable.
- City– This is the city where the hearing was held. Most of the time this will be in Harrisburg, but not always.
- Legislation Number– The number of the piece of legislation the hearing addresses, if applicable.
- 2nd Legislation Number – Same as above, if applicable.
- Legislation Type – Indicating what chamber the legislation originated from and if the legislation is a resolution or bill.
- 2nd Legislation Type – Same as above.
- Abstract– A short description on the subject matter of the hearing.
- Budget– This field indicates whether or not the hearing addressed the budget; 0 indicates it did not, and 1 indicates it did.
- Chamber– Chamber of the General Assembly which hosted the hearing.
- Code– Each hearing is coded according to the PA Policy Database Project’s adaptation of the Policy Agendas Project’s topic coding scheme. For a fuller description of what warrants each code, please consult the Topics Codebook section in the manual.
  
**SENATE HEARINGS**
The **Senate Hearings** dataset was provided to the Pennsylvania Project by the Senate Library. While this dataset is not truly complete, it does represent all of the materials that standing committees have sent to the Senate library for archiving, and therefore could be considered complete in this sense. Not all of the materials in the Senate hearings dataset relate to hearings held by the Senate. Some of the hearings were conducted by the House but lodged in Senate files, and some were conducted jointly by Senate and House committees. Such occasions are indicated in the spreadsheets provided after searches completed with the analysis tool.

Additionally, documents are organized according to how they were grouped in the Senate library, so not all materials related to a single hearing have a single entry, and not all testimony for a hearing is grouped together in one entry. Still, this is more the exception than the rule.

The following is a brief description of each data column in the dataset. Each section explains the coding rules for the data collected.
  
**Identifying Variables:**
- ID –These are unique numerical identifiers for each article included in the dataset.
- Day– The day of the month the hearing was held.
- Month– The month the hearing was held.
- Year– The year the hearing was held.
- Chamber– A 1 indicates the House, 2 indicates the Senate, and 3 indicates joint committees.
- Committee– The name of the committee holding the hearing.
- Subcommittee– The name of the subcommittee holding the hearing, if applicable.
- City– This is the city where the hearing was held.  Most of the time this will be in Harrisburg, but not always.
- Bill– What bill the hearing addresses, if applicable.
- Abstract– A short description on the subject matter of the hearing.
- Budget– This field indicates whether or not the hearing addressed the budget; 0 indicates it did not, and 1 indicates it did.
- Code– Each hearing is coded according to the PA Policy Database Project’s adaptation of the Policy Agendas Project’s topic coding scheme. For a fuller description of what warrants each code, please consult the Topics Codebook section in the manual.  
  
### Legislative Service Agency Reports
This dataset includes over 500 reports collected from legislative service agencies as instructed by the Pennsylvania General Assembly beginning with the 1979-80 session. Reports were collected from the following agencies:
- The Center for Rural Pennsylvania
- The Commission on Sentencing
- The Joint Conservation Committee
- The Joint State Government Commission
- The Legislative Budget and Finance Committee
- The Local Government Commission
- The Independent Fiscal Office

Often, reports are commissioned by bills or resolutions passed by either chamber or the full Pennsylvania General Assembly. In such cases, the appropriate bill or resolution has been noted. Report numbers, hyperlinks, filters, release dates, and a brief abstract have been applied to each record. These will be explained in detail below. For a detailed description of legislative service agencies, the PA General Assembly, and other branches of the PA State government please go to the PA Government section of the manual.  
  
**Identifying Variables:**
- Report Numbers – The number assigned to the report based upon its initial collection.
- Title – The official title of the report as noted on the front page of the legislative report.
- Organization – The official name of the legislative service agency producing the report.
- Year – The year that the legislative service agency report was released.
- Month – The month that the legislative service agency report was released.
- Day – The day that the legislative service agency report was released.
- Hyperlink – For each record, a link is provided to the respective legislative service agency’s website.  From here, the original version of the full report can be viewed.  Note: the link often opens a pdf file containing the report.
- Abstract – Each file contains an abstract briefly summarizing the contents of the report and lists any legislation to which the report was written in response.
- Code – Each record is assigned a four digit policy code. Please see the codebook for more information on how each record was coded.  
  
**Binary Filters** – There are four binary filters with a 1 indicating that the legislative service agency report affected the specific area. The filters are as follows:

- Pursuant to Legislative Request – This filter indicates if the report was undertaken as a result of a legislative act or resolution.
- Tax – This filter indicates whether the report discusses the creation or alteration of a tax.
- Elderly – This filter indicates whether the report discusses the provision of, or changes to, benefits for older adults.
- Contain Policy Recommendations – This filter indicates if the report contains policy recommendations.  
  
### Governors Budget Addresses
The governors’ budget messages dataset follows the coding of the President's _State of the Union_ address dataset in the Policy Agendas Project. Each year in an address to the General Assembly (typically in early February but later during inauguration years), the governor proposes a budget for the fiscal year beginning the following July 1 and identifies policy priorities. Under the Pennsylvania Constitution, the budget must be passed by July 1, though deliberations sometimes extend beyond the legal deadline. In 2003, Governor Rendell presented two budget addresses, and both are included in the dataset.

Researchers have broken each of the budget messages since 1979 into over 8,000 sentences or sentence fragments. _Given differences in the length of the budget address from year to year, the Pennsylvania project recommends using percentages rather than raw counts when comparing messages for policy emphasis._

The following is a brief description of each data column in the dataset. Each section explains the coding rules for the data collected.  
**Identifying Variables:**
- Month – The month listed is the month the Governor delivered the address.
- Day – This is the day the Governor delivered the address.
- Year – This is the year the Governor delivered the address.
- Governor – This column lists the Governor delivering the address.
- Source – This column lists the source of the address transcript used to construct the dataset.
- Sentence- This column displays the sentence or part of the sentence we used to code the dataset. This is a direct transcription of the address delivered by the Governor.
- Code – As with other datasets, the sentence or sentence fragment is coded as to policy impact, if one is discernible. Phrases like “Good Morning” and “Thank you” are given a code of 555, noting no policy impact. This is the same procedure as that followed by the national agendas project.

## Executive Orders
This dataset is a record of every Executive Order (EO) of the Governor of Pennsylvania from the beginning of the Thornburgh Administration (1979). There have been more than two hundred Executive Orders. In addition to new Executive Orders, the dataset includes revisions to existing Orders, and Executive Orders that have been subsequently rescinded.

There is no single online repository providing full-text of all of the Executive Orders for the years covered by the Pennsylvania Policy Database. Our project provides links through the Pennsylvania Office of Administration, the Dick Thornburgh Papers at the University of Pittsburgh and the Pennsylvania Bulletin.

The following is a brief description of each heading in the dataset. Each section explains the purpose of the collected data and how it was coded.
  
**Identifying Variables:**
- ID- This is the unique identifier of the Order.
- Order Number – The Commonwealth assigns a unique number for each Executive Order. Each new Order is labeled sequentially, preceded by the year in which the Executive Order was issued (i.e. 2010-1 would be followed by 2010-2). Revised Executive Orders are labeled by the year that the Order was issued, followed by the number of times the Order has been revised. For example, EO 1980-18 was revised for the third time in 2007. Its official title is 1980-18 Revision No. 3 Amended.
- Year- This is the year of the EO.
- Month- This is the month of the EO.
- Day- This is the day of the EO.
- Session- This contains the two-year legislative session in which the EO was issued or revised. For example an EO issued on March 13, 2003 would be labeled for the 2003-04 legislative session.
- Title – This is the official “Subject” heading that the Commonwealth assigns to each EO.
- Abstract – The Commonwealth does not provide an abstract for Executive Orders. Data collectors read the EO and then constructed a two to three sentence abstract summarizing the purpose of the Executive Order.
- Governor’s Name- This contains the governor’s last name.
- Governor’s Party- This contains the governor’s party. Democrats are labeled “100” and Republicans “200”.
- Beginning of Term- Governors often seek to make significant policy changes early in their administrations.  This filter captures whether the EO was signed within the first 100 days of a governor’s administration.  An Executive Order issued in the first 100 days of a governor’s four year term received a “1.”  Those not issued within the first 100 days were coded “0.”
- Planned Transition- Governors may seek to make significant policy changes as their terms come to a close. This filter captures whether the EO was signed during the final months of a governor’s term.  Executive Orders received a “1” if the EO was signed on or after November 1 of an election year wherein the incumbent loses or is ineligible to run. The Executive Orders were coded with a “0” if it was not in this period of planned transition.
- Gubernatorial Election Year- This captures whether or not the EO was issued or revised during a gubernatorial election year.  The EO received a “1” if it was signed in a gubernatorial election year and a “0” if it was not.
- Legislative Election Year- This captures whether or not the EO was issued or revised during a legislative election year. The EO received a “1” if it was signedin a legislative election year and a “0” if it was not.
- Code- The EO was coded according to policy impact.  For more information on coding decisions and placement, see the codebook.
Descriptive information on the Governor – See Table 1 for information about specific governors and gubernatorial elections.  
  
Policy Filters: A few filters were in used for the Executive Orders.  For a more expansive discussion of the policy filters please see the manual.

- Commemorative- The EO was coded with a “1” if it created a holiday, named a building, designated a special day of remembrance, etc.  It received a “0” if the EO was not commemorative in nature.
- Tax- The EO was coded with a “1” if it discussed the creation, alteration or change of individual taxes or the tax code. It received a “0” if it did not.
- Elderly- The EO was coded with a “1” if it provided or changed benefits for older adults. It received a “0” if it did not.
  
**Information on PA Gubernatorial Administrations 1979-2015**
- **Govenor and Party:** Thornburgh (R)<br>
- **Election Years:** 1978, 1982<br>
- **Period of 1st 100 Days:** January 16-April 25, 1979<br>
- **End of Term Transition Period:** November 1, 1986 - January 20, 1987<br>

- **Govenor and Party:** Casey (D)
- **Election Years:** 1986, 1990
- **Period of 1st 100 Days:** January 20 - April 29, 1987
- **End of Term Transition Period:** November 1, 1994 - January 17, 1995

- **Govenor and Party:** Ridge (R)
- **Election Years:** 1994, 1998
- **Period of 1st 100 Days:** January 17 - April 26, 1995
- **End of Term Transition Period:** N/A*

- **Govenor and Party:** Schweiker (R)
- **Election Years:** N/A**
- **Period of 1st 100 Days:** October 5, 2001 - January 12, 2002
- **End of Term Transition Period:** November 1, 2002 - January 21, 2003

- **Govenor and Party:** Rendell (D)
- **Election Years:** 2002, 2006
- **Period of 1st 100 Days:** January 21 - April 30, 2003
- **End of Term Transition Period:** November 1, 2010 - January 19, 2011

- **Govenor and Party:** Corbett (R)
- **Election Years:** 2010
- **Period of 1st 100 Days:** January 20 - April 29, 2011
- **End of Term Transition Period:** November 5, 2014 – January 19, 2015

- **Govenor and Party:** Wolf (D)
- **Election Years:** 2014
- **Period of 1st 100 Days:** January 20-April 30, 2015

* Ridge left office early to become Secretary of the US Department of Homeland Security
** Schweiker completed Ridge’s second term. He did not seek reelection.

___

## Supreme Court Decisions
The Pennsylvania Supreme Court dataset includes abstracts of opinions issued on cases since 1979. The Pennsylvania Supreme Court consists of seven members initially elected for ten year terms, after which they run on retention ballots. It receives around 2,500 civil and criminal appeals each year but only issues decisions on about 150 cases per year, including appellate, original, exclusive and extraordinary jurisdictions. The dataset does not include cases that were decided without a written opinion.

The abstracts provided were produced by [Westlaw](http://www.westlaw.com) and generously provided to Temple University’s Pennsylvania Policy Database under an exclusive license.  The abstracts themselves are copyrighted by Westlaw and may not be reproduced without its permission.  For each abstract, the tool provides a link to Westlaw for researchers wishing access to the full analysis of the case, either because researchers or their universities are already subscribers to the service or because they wish to order the full analysis with a credit card.  The Temple project is solely responsible for classifying the abstracts by policy topic.

Courts resolve issues that arise from individual cases rather than from the kind of broad political, economic, or social conditions that influence the agendas of the executive and legislative branches. Consequently, in coding a court case, we normally pay more attention to the policy ramifications of a decision than to the legal principle on which it was argued or decided. Essentially, we ask “What policy area is this decision most likely to affect?” For example, the Supreme Court often decides drug cases on procedural grounds.  A drug case decided on a search and seizure issue could be coded 1210 (Criminal Code) or 208 (Right to Privacy) but is more likely to be coded 1203 (Illegal Drug Production, Trafficking, and Control), where we would expect to find news stories about the case and legislative activity generated by the decision.

This approach results in more nuanced data.  By not dumping many of these cases into topics that could apply to almost any court decision, we avoid overpopulating a few minor codes. This does not mean that legal codes are not used – in fact they are still some of the most highly used codes for this dataset. Many are appeals on capital punishment sentences, which are coded in 1210 (Criminal Code). Where a case has no immediately discernable policy implication, it is coded on legal principle. This procedure, however, gives a researcher an accessible dataset that more accurately reflects the policy influence of the Supreme Court.

The following is a brief description of each data column in the dataset. Each section explains the coding rules for the data collected.

**Identifying Variables:**
- Case Citation-  An example of a case citation is 560 Pa. 215, 743 A.2d. 448.The first number refers to the volume where the case is located and the second number, the page. This case would be found in volume 560 of the Pennsylvania Reporter on page 215, or in the - Atlantic Reporter, second edition, volume 743, page 448.Sometimes there is no citation available beyond Westlaw’s.  It will look like this: 2008 WL 2853095.First, the year is provided and the second number is the Westlaw citation number. These are accessible through Westlaw’s links provided within the dataset.
- Case Name- This is the case name, such as Martin Media v. Com. Dept. of Transportation.
- Appellant-  This is the party appealing the decision of a lower court who lost in the previous case. Sometimes both parties appeal a lower court decision and so both will be appellant and appellee. The status as plaintiff or defendant in the lower court is not related to the status of appellant or appellee.
- Appellee- This is the party to whom the appeal is directed having received a favorable judgment in the lower court. Sometimes both parties appeal a lower court decision and so both will be appellant and appellee. The status as plaintiff or defendant in the lower court is not related to the status of appellant or appellee.
- Argued- This is the date the case was argued.
- Decided- This is the date the court decided the case.
- Hyperlink- This link provides instant access to the full Westlaw abstract of the case, including all citations. If you do not have a Westlaw account, you will be asked to pay for access to this information or set up an account with Westlaw.
Background and Holding- Provided here are the background and holding abstracts as provided by Westlaw. The lower court decisions are provided in the background section, though not always. The decision of the Pennsylvania Supreme Court is in the Holding column.
- Majority Opinion Author- The justice who authored the majority opinion is listed here. Sometimes, no majority opinion author is provided in the written opinion, and so it does not appear here. This might occur when the opinion is per curiam, or from the whole of the court. If so, this is indicated in the comments section of the dataset.
- Code- Using the background and holdings of the abstract, the major policy impact area was identified and coded accordingly. Each case is given a 4 digit policy code. As noted above, cases are coded on policy implication and if none is discernible, they are coded on legal principle.

**Filter Variables:** There are nine binary filters for the Supreme Court decisions with a 1 indicating the case affected or involved the specific area. For more detailed descriptions of filters, see the section on filters in the manual. The filters used for this dataset are:

- Executive- Mentions the Governor or his staff, including historical references, the Lieutenant Governor, gubernatorial advisory bodies, and similar examples.
- Legislative- Mentions the legislature and members of the legislature even if not in their official capacity. This filter also includes legislative advisory bodies, and other legislative branch activities, and debates that took place within the legislature.
- Judicial- Mentions the state court or state judicial districts. Because these are cases within the state judicial system, this filter is active for every record.
- State Agency- Mentions a state agency including references to the head of Departments such as the PA Secretary of State, as well as references to any state agency, such as the PA Housing Finance Agency, State Police and the Turnpike Commission.
- Local Government- Mentions a specific local government, individual local government officials or the effects of policy on local governments. Examples would be: the effects of state property tax reform on local governments, the effects of federal mandates on local governments and the effects of an economic downturn on local government budgets.
- Federal- Mention of a federal government agency or official.
- Tax- Mention of new taxes, proposed taxes, elimination of taxes or effects of taxes.
- Elderly- Mention of issues related to people who are retired, includes things such as: pensions and state retirement systems, Social Security, activities of the Department of Aging, use of lottery proceeds aimed at older Pennsylvanians, abuse of the elderly, etc.
- Elections- Discusses candidates for office or elections, including incumbents in election campaigns, political parties, party officials, news coverage of campaigns, legislative redistricting, party platforms, and candidate debates, etc.

Find more information on the [Pennsylvania Supreme Court website](http://www.pacourts.us/courts/supreme-court/).

## Most Important Problems Polls
This dataset codes public opinion from the Franklin and Marshall College Poll’s _Most Important Problem_ question using the major policy codes from the Pennsylvania Policy Database Project that have been reformatted from the National Policy Agendas Project. The Franklin and Marshall College Poll (formerly known as the Keystone Poll) is conducted through the Center for Opinion Research and collects a representative sample of responses from Pennsylvania residents.

The survey asks respondents “What do you think is the most important problem facing you and your family today?” and is similar to the Gallup Poll’s “most important problem facing the nation” question. Unlike the Gallup Poll, it is an open-ended survey with respondents providing their own answer rather than selecting from topics in a list.  The poll aggregates the responses into topical areas like “taxes,” “education,” and “healthcare,” to name a few, in order to ascertain the percentage of “most important problems” facing Pennsylvanians (e.g., 6 percent of respondents said that energy is the most important problem in September of 2008). The dataset contains responses from over 30 polls gathered since 1994 with an average sample size of 500 to 600 respondents per poll.

The following section contains a list of variables for the dataset. Each section explains the coding rules for the data collected.

**Identifying Variables:**
- ID- This provides the unique id assigned to each variable (percentage of the major topic for each poll) in the dataset.
- Year-  This is the year that the poll was conducted.
- Month- This is the month that the poll was conducted.
- Size- This provides the number of respondents who took the poll.
- Major Topic Code- This provides the major topic code assigned to the percentage of respondents stating the “most important problem” at that date in time. The major topic codes are organized into 20 categories and an additional “other/don’t know” category that is coded as “25.”
- Percentage- This provides the percentage of responses within a major topic in a poll. These percentages are sometimes aggregated from smaller categories (e.g., responses of “economy,” “taxes,” and “personal finance” are grouped into a single category called “economy”). See breakdowns below.
- Rankings with 25 (Other/Don’t Know)- This provides the rank assigned for the major category as a result of the percentage breakdown. Categories with the same percentage are given the same tie number, but the next category comes back in order. This rank includes the 25 category of other/don’t know.
- Rankings without 25 (Other/Don’t Know)- This provides the rank assigned for the major category as a result of the percentage breakdown. Categories with the same percentage are given the same tie number, but the next category comes back in order. This rank excludes the 25 category of other/don’t know.
- Breakdowns (Columns 1, 2, 3…)- This provides the percentage of responses that compose the major topic category. For example, the economy (code 1) is often an aggregate of three to four smaller categories that respondents reply. The economy category is usually composed of the economy (column 1), taxes (column 2), personal finances (column 3), and unemployment (column 4).
- Source- This provides the website address on the Keystone Poll website where the raw data can be obtained.

Find more information on the [Franklin and Marshall College Poll website](http://www.fandm.edu/fandmpoll).

The data are collected via telephone survey as a random sample of respondents, and only one response is recorded for each poll.  No normalization of the data is needed.

### Budget (Total Spending All Funds)
Two fiscal datasets shown on the Analysis Tool page are discussed under this topic, which for purposes of paralleling the US Policy Agendas architecture is labeled “Budget.” Both datasets were constructed from well-established and methodologically consistent sources that allow researchers to compare data across many years and across all fifty states.
 
**Total Spending All Funds**
The sources of these data are the annual reports in the  State Government Finances series of the US Bureau of the Census, as adjusted by our researchers to fit major policy topics of the Pennsylvania Policy Database Project.

This dataset captures all expenditures from all funds of the state government — including, but not limited to, the General Fund —measured on a fiscal year basis from 1979 to the present (Pennsylvania’s fiscal year, like that of all but four states, runs from July 1 to June 30). Unlike the Policy Agendas project, which provides federal budget authority (spending authorized by Congress, whether or not the funds have actually been spent in a specific 12-month period), this dataset measures outlies, or dollars actually spent during the months of the relevant fiscal year. It summarizes total outlays for operating and capital purposes and for social insurance payments to recipients, such as retired state employees or injured or unemployed workers. It includes the spending of both state owned sources, revenues and intergovernmental transfers from the federal government or even (in relatively minor instances) from the state’s local governments. In its comprehensive approach to measuring all spending, it parallels the US Policy Agendas project. Because it measures outlays, distortions in long-term spending trends can arise if spending is delayed or accelerated for political or fiscal reasons from one fiscal year to another. Although this occurs infrequently, users spotting implausible variations should check spending trends both by fiscal years and by legislative sessions, which will generally provide a more meaningful pattern. Because the source of these data is the US Census Bureau’s State Government Finances series, the data are consistent from year to year and from state to state. Working with the Census Bureau, the Pennsylvania Policy Database project reorganized the Census data to conform to the project’s major policy topics.

When downloading the total spending spreadsheets, note that only the amounts labeled “R” in the “RE” column should be used to calculate total spending. The number in the “TheValue” column is listed in thousands of dollars and is for the entire Census category and must be multiplied by the percent in “PercentMatch” column to obtain the total for the policy topic code.  For example, if “TheValue” column lists 800 and the “PercentMatch” column lists 20 the total spending for that policy topic code would be $800,000 x .20 = $160,000. All amounts are unadjusted for inflation in the spreadsheet downloads, but can be adjusted for various years within the analysis tool. Information on each of the columns in the download file can be found in the Field Descriptions (**Needs to be migrated into google for new url).
 
**General Fund Balance**
The sources of these data are annual editions of the Fiscal Survey of the States published by the National Governors Association and the National Association of State Budget Officers. This dataset differs from all others in the project in that it is a measure of fiscal condition and not policy attention.  It has no policy content but is relevant in that fiscal condition may be related to shifts in policy attention or decisions, particularly for state governments, which have relatively volatile revenue systems and operate under balanced-budget rules.

This dataset can be used as a rough measure of the fiscal condition of Pennsylvania’s General Fund, which is the largest, most flexible, and most important fund supporting the state’s budget for operations. Under the Pennsylvania Constitution, the General Fund must be balanced on a fiscal year basis, and it cannot be balanced by borrowing. **_The genral assembl has reasonably found another way to use borrowed funds for operations_** If deficits occur, they must be immediately eliminated in the next General Fund budget. State officials and bond-raters argue that a state’s General Fund should aim to achieve a year-end balance of approximately five percent of General Fund expenditures which can be thought of as a sufficient reserve to cover about 18 days of operations, should projected or actual spending exceed projected or actual resources. In addition to planning for small balances, Pennsylvania and a number of other states have established budget-stabilization funds, sometimes called “Rainy Day Funds,” in which they attempt to gradually accumulate larger reserves to cope with looming or actual General Fund deficits.  Pennsylvania’s reserves to deal with unanticipated fiscal problems thus consist of the General Fund balance and the funds available in the Rainy Day Fund.

For insight into the changing fiscal condition of the state government over time, users can graph Pennsylvania’s General Fund balances in inflation-adjusted or unadjusted dollars and as a percentage of General Fund expenditures. Users can also include or exclude in this measure of the state’s fiscal condition the state’s Rainy Day Fund reserves, also measured in inflation-adjusted or unadjusted dollars or as a percentage of General Fund expenditures.

The General Fund includes own-source (e.g., not federal) revenues and expenditures, and it supports most of the operational activities of the state itself and its transfers to local governments, such as counties, municipalities, and school districts. The General Fund does not include funds borrowed to support capital projects or payments from retirement funds. The General Fund accounts for approximately 50 percent of Total Spending All Funds as measured above, and it represents about 85 percent of state own-source spending.  This is the typical pattern in most states. Some spending for operations is from other funds, such as Pennsylvania’s Motor License Fund, which includes revenues earmarked for highway and bridge construction and maintenance activities.

**Additional Background for Total Spending All Funds Dataset**
The creation of the Total Spending All Funds dataset was the most methodologically difficult endeavor undertaken by the Pennsylvania Policy Database Project. As noted above, there is no congruent dataset within the national Policy Agendas scheme because its budget data reflect spending authority authorized by Congress and organized under various functional topics (which are different from the Policy Agendas topics) by the Office of Management and Budget. Consequently, we had to look to other sources for expenditure data.

The Census Bureau’s **_State Government Finances:_** The Pennsylvania Policy Database Project utilizes the Census Bureau’s _State Government Finances_ to provide a consistent longitudinal dataset of Pennsylvania’s expenditures. As noted above, expenditures measure actual outlays of the government, not budget authority. We incorporate two variations of this dataset, both covering the years 1979-2008.  First, we provide Pennsylvania’s expenditures during this period using the Census Bureau’s unique Government Finance classification system, which summarizes spending by function and not by fund. However, this system does not allow for comparison between the budget and other the datasets of the project. Consequently we have a second version of the dataset based on a cross-walk that allows us to shift funds from the Census classifications to the Policy Agendas coding scheme. Additionally, the database can transform expenditures from nominal to inflation adjusted values. The remainder of this section discusses the _State Government Finances_ dataset and the process used to construct the cross-walk between this dataset and the Pennsylvania Policy Database (and Policy Agendas) coding system.

The Utility of _State Government Finances: Through State Government Finances,_ the Census Bureau has already performed the difficult task of interpreting and classifying state expenditures  and combining the outlays of all of the separate funds. In doing so, the bureau has standardized all relevant data and produced reports that are comparable from one year to the next. When Census alters definitions or methodology it provides clear explanations and accounts for such changes. Finally, but perhaps most importantly, the Census Bureau’s need for accurate and consistent data impels it to produce a dataset which is valid across all states. This allows an analyst to easily compare the expenditure patterns of Pennsylvania to Ohio, Alaska, and/or Texas (with its biannual budget) for a given year or over time.

While other datasets provided more detail, they were often unwieldy, complex, ill-defined, and could change methodologically from gubernatorial administration to administration. This would have ultimately led to an inconsistent dataset despite the best efforts of the Pennsylvania project to standardize the data.

Cross-walk Methodology: State government budget data are collected and reported in a manner that is consistent with the Census Bureau coding scheme rather than the Policy Agendas methodology. Consequently, we constructed a cross-walk between the Census Bureau’s Government Finance classification system and the Policy Agendas coding scheme to enable researchers to compare budget expenditures to activity in other project datasets.

Given the inexact nature of building the cross-walk the project only relied on the use of Policy Agendas major topic codes.The number Census codes changed slightly over time, but we were able to effectively condense the approximately sixty codes from the Government Finance classification system into the twenty major topic codes of the Policy Agendas scheme.

The system used to match Government Finance classification codes to Policy Agendas codes relies mostly on the “matchability” of the two codes. This was determined to be the amount that the qualitative definition, description and examples of the Census code fit into the Policy codes.  Matchability was determined to be high if the Census code fit entirely into the policy code with no overlap with any other policy codes. An example of a perfect fit would be the Census code “Air Transportation” which fits entirely into the policy code of “Transportation.” A continuous matchability scale of 1 to 100 was created using a five integer scale. In other words, the system is a 20 point scale counted by fives. The most frequent figures are described as follows:

- 100 – A whole fit. This was not construed as two congruent figures, but rather that one figure fit entirely into the other.
- 95 – A near whole fit. Everything but a minor aspect of the Census code fit into the Policy code. This was given if there was a flaw in the matchability.
- 80 – A strong match between the two codes, but there was a noticeable flaw between the two codes.
- 40 – A 40 was usually given when there was a preponderance of matches, but there were major parts of the codes that didn’t fit together. This was typically considered the lowest level of “significance” for matchability.
- 5 – A 5 was awarded when there was some level of matchability to recognize.

We did not reward any matchability of "1", as it was deemed to be so small that it was insignificant. In a situation where there were numerous (typically an amount more than "5") codes that had very low matchability ratings, a footnote was provided and only the Policy codes which had significant ratings were listed. In no instances did more than two major Policy codes match with the Census codes.

**Additional Background on the General Fund Balance Dataset**
The _Fiscal Survey of the States_ is produced twice annually by the National Governors Association and the National Association of State Budget Officers. The publication produces aggregate and individual state data that compile the own-source revenues, expenditures and reserves from state general funds.  As noted above, the General Fund is essential to determining the fiscal health of states. The Pennsylvania Policy Database collected the fiscal survey data for all fifty of the states from 1979-2008. The standardized format of the data allows researchers to longitudinally compare Pennsylvania’s fiscal health to all other states in the nation.

We used the data from the Fall Fiscal Survey of the States because it is represents the actual data rather than the preliminary information provided in the Spring Fiscal Survey.

The dataset provides the following information. All figures are listed in $millions.

- Beginning Balance – This represents the amount in the general fund at the beginning of the fiscal year.
- Revenues – This represents the total amount of revenue the state brought in during the fiscal year.
- Adjustments – Revenue adjustments are generally one-time sources of revenue for specific states. This includes things such as transfers to the general fund from other funds (such as property tax funds, Tobacco Settlement fund, etc.). Please consult the _Fiscal Survey of the States_ to determine the specific adjustments for each state.
- Total Resources – This is the combination of the Beginning Balance, Revenues and Adjustments. It represents all the resources at the disposal of the state for that fiscal year.
- Expenditures – This represents the expenditures (outlays) for the fiscal year.
- Adjustments – Expenditure adjustments are generally one-time expenditures by a specific state. This includes things such as carry-forwards of appropriations. Please consult the Fiscal Survey of the States to determine the specific adjustments for each state.
- Ending Balance – This represents Total Resources minus Expenditures and Expenditure Adjustments. In some cases the Ending Balance includes the balance of the Budget Stabilization Fund. Please consult the Fiscal Survey of the States to determine which states report in what manner.
- Budget Stabilization Fund – This represents the final dollar figure in the Budget Stabilization Fund (or Rainy Day Fund) at the end of the state’s fiscal year.

### How to Access the Data
- [Download the User Guide (.pdf)](https://drive.google.com/file/d/1JF4HpSlMywVKu1nuuv6sBaYEU3jJKGZX/view?usp=sharing)(You will need Adobe Acrobat, or Acrobat Reader to access this file.)
- Use the [data analysis tool](http://policydb.temple.edu/PAPolicy/analysis.spg)
- Download our datasets

If you would like to download our datasets to perform your own analysis, please follow the instructions below for downloading files into MS Excel.

- Access [‘Data Analysis Tool‘](http://policydb.temple.edu/PAPolicy/analysis.spg) from our Homepage.
- The top part of the tool there is a list of datasets, select the dataset you are interested in downloading. Once selected filter options will appear, but do not change anything if you want the entire dataset.
- Scroll down past the policy topics section, not changing anything (unless you want to limit the policy areas)
- At the bottom you can select the years you are interested in. If you want them all, do not change anything.
- _Click ‘Search’ at the bottom right_
- _Just above the graph that will appear on the next page there will be a link saying “All topic _DatasetSelected”_, click it.
- _An .xlsx file will begin to download, which will open in MS Excel._

For more information on the datasets and how to use the Data Analysis Tool see the [Documents page](http://develop.cla.temple.edu/pennsylvania-policy-database-project/documents/).

**Additional data not incorporated into the Analysis Tool**
- [Speaker’s Journal (Volumes 1-9)](https://drive.google.com/file/d/1ukuPbw6oW9XFXI9rQKpaf90t0Z8XH9k2/view?usp=sharing)
