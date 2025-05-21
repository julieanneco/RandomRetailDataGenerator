# Random Retail Data Generator

Use this is a template to create your own Retail Sales data set.

Create a Python dataframe of random Retail Sales data that can be used in Python or exported to CSV for use in Tableau or other analytical platforms.

This code was born of the need for made up data with current dates to use in a Tableau Pulse demo. Pulse requires real-time (or at least recent) timeseries fields in order to provide AI insight and automated visualizations. With the end of continuous updates to the Superstore dataset built into Tableau (data stopped being added in 2024), I decided to create my own dataset with fully customizable dates, distributions, and fields. Since Python random functions often create even distribution, I also included a generator that creates uneven weight distributions that sum to 1 for use in value creation. 

These are the results in Tableau Pulse using this random generator and exporting to csv for use as a data source:

<img src="https://github.com/julieanneco/RandomRetailDataGenerator/blob/main/TableauPulse.png" alt="TableauPulse.key" width="500">


**[Click Here to Visit the Tableau Public Dashboard also using this Data](https://public.tableau.com/app/profile/julie.anne.hockensmith/viz/FootwearDashboard/HomePage?publish=yes)** <sup><sub>*Ctrl+Click to open in new tab*</sub></sup>
