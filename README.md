# datetime-reference-examples

The following modules are covered:
* datetime
* calendar

The following packagea are covered:
* dateutil
* fiscalyear

##Usecase

The use case we are going to base this walkthrough on is do month to date financial report that is dependant on an external api. Assuming the api will accept date in string formant you could assume you would need to following capabilities:

* accept a string to indicate the year month
* determine the start and end date of the specified month
* determine to fiscal year of the specified month
* determine the start and end date of the fiscal year
* determine number of month between end of specified month and start of financial year to calculate averages
* fill out the future months in the financial year with zeros

