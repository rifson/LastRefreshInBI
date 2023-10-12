# LastRefreshInBI
Last Refresh for multiple regions in Power BI

Able to make a table showing last dataset refresh time in multiple regions within a report.
In the code it will check for winter and summer time start and end dates to make sure that times changes.
In this code:
- USA will change to winter time first sunday in november
- USA will change to summer time second sunday in march
  
- EU will change to winter time last sunday in october
- EU will change to summer time last sunday in march

- Other zones are just following their UTC timezone all year.

All regions were shown as a tooltip in Power BI thus all users were able to see different timezones that fit them.
