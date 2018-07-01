# SQL Code

This code uses some of my favorite SQL code (eg: CTEs & row_number())

It references generic tables listed below:

**install**
*id*: id for a person
*timestamp*: 'yyyy-mm-dd hh:mm:ss' format of the time of the install
*source*: where the install came from

**app_open**
*id*: id for a person
*timestamp*: 'yyyy-mm-dd hh:mm:ss' format of the time of the app open

**ftue**
*id*: id for a person
*timestamp*: 'yyyy-mm-dd hh:mm:ss' format of the time of the app open
*step*: which step of the ftue the user is in (for this table 1 = started ftue and 10 = finished ftue)

**engagement**
*id*: id for a person
*timestamp*: 'yyyy-mm-dd hh:mm:ss' format of the time of the app open
*activity*: which feature the user is engaging in (for this table: menu, click, use)

**payment**
*id*: id for a person
*timestamp*: 'yyyy-mm-dd hh:mm:ss' format of the time of the payment
*revenue*: $ value of payment in US dollars
