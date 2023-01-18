# Covid-Case-Vicinity-Checker
Given a suburb, radius and timeframe it checks your vicinity to recent covid cases.

It scrapes the NSW Government Covid data to obtain the case dates and suburbs. I then use an open source map web api to obtain the longitude and latitude of each suburb with a 
case. I then use these values to calculate the distance and filter which returns the suburbs within the given radius. The result is then visualised using an interactive heat map.

View it here: https://nbviewer.org/github/sameer-gupta01/Covid-Case-Vicinity-Checker/blob/main/CovidCaseVicinity%20%281%29.ipynb
