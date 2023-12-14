# module_4_assignment

# Explanation of comments in "Custom Portfolio"
There are comments in the beginning of the "Custom Portfolio" section of the assignment. I attempted to extract data into a csv using GOOGLEFINANCE, but everytime the dates would print in this format: '%Y-%m-%d %H:%M:%S.%f' which was an issue when trying to join the dataframes. So ultimately, I decided to leave my original csv files and their code to read them as comments to show my attempt, while I completed the "Custom Portfolio" section with the given back up csv files (goog_historical.csv, aapl_historical.csv, cost_historical.csv). I was then able to complete the assignment.

# Tutor Notes
In line [181] of my notebook, there is a UserWarning that pops up. My tutor and I tried a few different methods to set the date_format so the warning would not pop up, but we were unable to figure it out by the end of our session. The code still works just fine but that warning does pop up. It is just stating that in a future update it will be falling back to 'dateutil' so it would need to be modified in the future.

# Lines [221] and [222] 
I was not sure if the beta trend between my portfolio and S&p 500 needed to be plotted so it is added in line [222] along with the 60 day rolling beta in line [221]. 