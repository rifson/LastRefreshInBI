# LastRefresh In BI Report
Last Refresh for multiple timezones in Power BI

Able to make a table showing last dataset refresh time in multiple regions within a Power BI report.
In the code it will check for winter and summer time start and end dates to make sure that times changes.
In this code:
- USA will change to winter time first sunday in november
- USA will change to summer time second sunday in march
  
- EU will change to winter time last sunday in october
- EU will change to summer time last sunday in march

- Other zones are just following their UTC timezone all year.

All regions can be shown as a tooltip in Power BI thus all users are able to see different timezones that fit them.

![image](https://github.com/rifson/LastRefreshInBI/assets/10552516/88cff642-b76c-412b-91cc-4f4cc1bb8d14)

# How to add
In order to add this table to Power BI simply just add a blank query to Power BI and paste in LastRefreshInBI code:

Get data and then Blank query

![image](https://github.com/rifson/LastRefreshInBI/assets/10552516/3ca24ab0-aec2-4429-acfc-3a1111c23b0d)
<br />
<br />
In Advanced Editor remove all code and paste in code from here

![image](https://github.com/rifson/LastRefreshInBI/assets/10552516/914c5911-839d-48ab-9ea8-23638f0776cc)
<br />
<br />
Now after closing Advanced Editor a table of the different timezone should be shown

![image](https://github.com/rifson/LastRefreshInBI/assets/10552516/5d7e75e2-fda4-40e2-95a3-53a63e6238e8)
<br />
<br />
Close and apply changes.<br />
Thereafter change the time format to the desired format in each column.<br />
I have used 14 Mar 2001 13.30 (d mmm yyyy hh.nn)

![image](https://github.com/rifson/LastRefreshInBI/assets/10552516/da9b33d6-aa10-4eef-aac3-44f2dbe351a9)

Now its ready to use and will change each time the Power BI report is set to do a scheduled refresh or is being refreshed manually



