# Metro Tracker
This is my app to track the metro timing and tell me them according to the now time in ascending order latest to last metro of that day.
- Data of metro timings of different days.
- how to make it for my mobile.
- I can make this in python.

## Steps
1. extract the data from the main site.
2. now i need to find the logic for the app. how should i make it. lets see...
3. first find the data from data frame and give it to me
## Notes
- So i used the pandas.read_html() to get the tabke according the the class attribute. the table i need are last 2 table.
- one is going from sealdah to sector-v
- other is going from sector-v to sealdah
- now i need to make myself clear about what to do with them.
- url = "https://mtp.indianrailways.gov.in/view_section.jsp?fontColor=black&backgroundColor=LIGHTSTEELBLUE&lang=0&id=0,2,630"
- changing the names from saltalke to sectoV(sector five) cause saltlake is in two station.