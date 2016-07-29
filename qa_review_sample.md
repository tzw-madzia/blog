# QA PROJECT REVIEW


####DATE: 20.09.2015
####REVIEWER: Dorota Niewęgłowska


## Project documentation (project info, mockups) 
######Project info is a document that contains all the necessary information related to the project e.g. general information about the project, links to all environments, mockups


- is project info available? YES
- is project info up-to-date? YES
- does the project info contain all necessary information? 
- are mockups available? YES

Up-to-date, all credentials are available. Mockups available

## QA Checklist
######We use checklists on a day-to-day basis to make sure that working on new features/bug fixes didn't break anything in the application, causing a regression in already implemented code
- is it available? YES
- is it up-to-date? YES
- is it clear? YES
- are the key features marked in red? NO
- is the checkup done regularly both on staging and after deploy? NO


QA Checklist available and is up to date but it covers only the general app, not the reports for 2 hardcoded apps.
The checklist is thorough and generally clear, but doesn’t cover 2 hardcoded apps. 
The critical features are not marked. 
The checkup is done irregularly, should be done more frequently.

## Project functional notes
######Project functional notes is a document stored in projects folder that contains all information specific to the project. Its purpose is to introduce a new person to the project, specifically a QA who will pop in once in awhile to do QA review.
- is the document available? YES
- does it contain all necessary data? YES
- is it up-to-date?

Yes, the functional notes doc is available and updated regularly.



## Pivotal Tasks/Jira
######It provides bug tracking, issue tracking and project management functions.
- are the bugs properly described? YES
- are the bugs properly labeled? YES
- do the bugs contain screenshots? YES

Tickets submitted by the QA are properly described, labelled and contain screenshots. However, there are tasks submitted by devs and pm and the client that emerge on calls and are not properly described, labelled and don’t contain screenshots or info about the location whatsoever. 

## QA tests automation
######If the project environment allows, QA could write the automated tests to the features. Generally, we use Capybara and Rspec


- does the project environment allow the implementation of tests written by QA?
- are the automated tests implemented by QA? NO
- what framework is used? ----

Not yet covered by the QA.

## Bug Bash
######The idea is to spend some time on testing the project with the whole team and other QAs normally not involved in the project.
- is it made regularly? YES
- are the bugs added to the Pivotal/Jira?

Bug Bash is made regularly.

## Speed
######For checking the speed of the application/web page we use Calibre. Calibre is a tool used to track the front end of an application. It records loading time, pagespeed (for non-authorised pages), performance, files loaded etc. Speedindex is a method of calculating a score that indicates the time it took your page to become visually complete.  Calibre records a "Visually complete" metric to indicate what a end-customer will perceive as the point in time that your site "looked complete". Total transferred data - this value includes the 3 next sections: sum of JS + CSS + Img + 0-500kb for other. Pagespeed is based on google pagespeed insights with the most pressing issues.

- has the project been added to the Calibre app?

- average speedindex from last snapshot:

- average load time (visually complete):

- average page size (total transferred data):

- average pagespeed score: 

Summary - Possible room for improvement: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam





## SUMMARY
**Good things:**
- all docs available and up-to-date (except checklist)


**Room for improvement:**
- checklist doesn’t cover hardcoded apps
- not all tickets are properly described
- total checkups should be done more frequently

**Potential problems for new QA joining the project:**
- ask PM to put more pressure on proper tickets description - to avoid spending time on explaining things. 


**Other observations** (tickets suggestions - UX, design, all other suggestions)
- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam

