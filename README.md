# Automation with Tableau
| Project   | Topic   |Description                                                    | Tools |
|----------|--------|------------------------------------------------------------|-------------|
|[Automation with Tableau](https://public.tableau.com/views/MyFirstViz_16526990619590/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)|Data pipelines and Automation|Building adashboard and a presentation about trending videos on YouTube |Tableau, Canva|

Description:

In this project we work as a video ad analysts at the Sterling & Draper advertising agency. We devote a lot of time to analyzing trending videos on YouTube to determine what content deserves marketing attention.
Each video has a specific category (Entertainment, Music, News & Politics, etc.), region, and trending date.
A video can be in the trending section for several days in a row.


Every week, the new employees asked the same questions:
- What video categories were trending last week?
- How were they distributed among various regions?
- What categories were especially popular in the United States?

We decide that it's high time the process were automated. We're going to make a dashboard for the new employees.
After talking to the managers and database administrators, you've drawn up brief technical requirements:

**Business goal:** analyze trending-video history on YouTube

**How often the dashboard will be used:** at least once a day

**Target dashboard user:** video ads planning managers

**Dashboard data content:**
 - Trending videos from the past, broken down by day and category
 - Trending videos, broken down by countries
 - A table of correspondence between categories and countries

**Parameters according to which the data is to be grouped:**
 - Trending date and time
 - Video category
 - Country

**The data:**

*Trending history* — absolute values with a breakdown by day (two graphs: absolute numbers and percentage ratio)

*Events, broken down by countries* — relative values (% of events)

*The correspondence between the categories and countries* — absolute values (a table)

**Importance:** all graphs are equally important

**Data sources for the dashboard:** the data engineers promised to create an aggregate table called `trending_by_time` (.csv file in the repository) 

**Data update interval:** once every 24 hours

**[Link to dashboard availiable here](https://public.tableau.com/views/MyFirstViz_16526990619590/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) and in addition is stored in the repository .txt file.


