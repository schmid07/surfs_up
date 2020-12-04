# Surf Shop

# Ride Sharing Data by City Type -- Overview
We've been tasked with analyzing June and December temperature trends to help determine whether it makes sense to keep the surf shop opened year-round.  

## Resources
- Software: Python 3.7.6, Jupyter Notebook
- SQLite, SQLAlchemy, and Flask

## Summary
As shown in the table below, among our sample collected, both the average fare per ride and average fare per driver were less in Urban areas and most in Rural areas.  There is no adjustment for miles traveled in the data, so one possible explanation is that trip distance is lower in Urban areas, which would lead to a lower fare per ride.  

![png](June_temps.png)

![png](December_temps.png)

## Recommendations
To address disparities in fares between rides, one recommendation is to charge different rates between Urban, Suburban, and Rural areas.  Another recommendation is to add an upfront fee that is contigent on the type of area.  A final recommendation is to tie rates to miles traveled so that the first mile is the most expensive, and gradually declines as vehicle miles increase.    
