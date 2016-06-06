
|  Project documentation |  |  |
|  :------: | ------ | ------ |
|   | is project info available? | yes |
|   | is up-to-date? | NO |
|   | does the project info contain all necessary information? <br/> | yes |
|   | are mockups available?  | yes |
|   | **SUMMARY** | Project info contains all necessary data and new template is used. <br/>Pivotal Tracker is linked instead of JIRA.<br/>Password for staging should be kept in 1pass vault, not in the project info. |
|  QA Checklist |  |  |
|   | is it available?  | yes |
|   | is it up-to-date?  | yes |
|   | Is it clear?  | yes |
|   | are the key features marked in red?  | yes |
|   | is the checkup done regularly both on staging and after deploy?  | checklist is quite new, there are only 2 checkups for now |
|   | **SUMMARY** | There is 2 month gap between checkups, but last one was made a week ago, so quite recently. |
|  Project functional notes | is the document available?  | yes |
|   | does it contain all necessary data?  | yes |
|   | is it up-to-date? | yes (last edit May 20th) |
|   | **SUMMARY** | Pretty impressive functional notes - great job! |
|  Pivotal Tasks/Jira | are the bugs properly described? do they contain commits/PRs? | generally yes, but some tickets (mainly from PM) don't have any description at all |
|   | are the bugs properly labeled?  | not all of them |
|   | do the bugs contain screenshots?  | yes |
|   | **SUMMARY** | Tickets added by QA are very well described, using AS/TO BE pattern and contain screenshots/screencasts. Tickets added by the client/PM are mostly properly described as well. However there are some tickets without any description - like these two: https://www.pivotaltracker.com/story/show/118578823, https://www.pivotaltracker.com/story/show/118578783. <br/>Some bugs don't have priority labels.<br/> |
|  QA Automation tests | does the project environment allow the implementation of tests written by QA? | yes |
|   | are the automated tests implemented by QA?  | no |
|   | what framework is used? | rspec, capybara, site-prism |
|   | **SUMMARY** | Project environment allows the implementation of tests written by QA - Rspec and Capybara gems are used. Feature specs are written by the developer for now. Michal is a junior QA so he is not writing any specs for now, but he will probably have the abbility to do that in the future :) |
|  Bug Bash | is it made regularly?  | yes |
|   | are the bugs added to the Pivotal/Jira? | yes |
|   | **SUMMARY** | all good |
|  1password | is the file available? | yes |
|   | does the file contain all the needed data? | yes |
|   | do all credentials work? | not all of them - staging credentials have wrong url (url of homepage instead of login page) |
|   | **SUMMARY** | Credentials for all important accounts are added to 1pass and are up to date, but some accounts have incorrect url address. |
|  Speed | has the project been added to the Calibre app? | yes |
|   | average speedindex from last snapshot: | 4458 |
|   | average load time (visually complete): | 7,77sec |
|   | average page size (total transferred data): | 2,37MB |
|   | average pagespeed score: | 52/100 |
|   | **SUMMARY/possible room for improvement:** | Average page size and pagespeed score are ok. Speedindex need to be looked at (it's not tragic, but results below 3000 are desirable). Average load time require some work since acceptable values start at 5 sec.  |
|   |  |  |
|   |  |  |
|  **SUMMARY** | **Good things** | - great functional notes!<br/>- really clear checklist - good job. just keep up with regular checkups.<br/>- regular bugbashes<br/>- tickets are very well described - good QA work<br/>- looks like it's a good project for writing feature specs - stick with it it for the future! ;) |
|   | **Room for improvement** | - please update project info doc. I checked Pivotal Tracker instead of Jira because info was outdated. There are 3 Carnival related projects in JIRA (are all of those needed?) so without help from Michał I wouldn't know where too look. <br/>- Because I checked Pivotal some of my suggestions may no longer be relevant (like missing labels). However, please remember about proper descriptions for tickets that are not added by QA. Tickets without description/screenshots may be confusing for new team members.<br/><br/>Small things:<br/>- please change URLs for staging credentials in 1pass vault - they're redirecting to incorrect page<br/>- take a look at the Calibre results - some improvements in speedindex and average load time would be nice.<br/> |
|   | **Potential problems for new QA joining the project** | Nothing comes to my mind - great functional notes, very clear checklist and pretty well described tickets should be enough to introduce new QA to the project smoothly. |
|   | **Other observations** | - |