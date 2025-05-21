# Random Retail Data Generator

<div class='tableauPlaceholder' id='viz1747860648814' style='position: relative'><noscript><a href='#'><img alt='Home Page ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fo&#47;FootwearDashboard&#47;HomePage&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FootwearDashboard&#47;HomePage' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fo&#47;FootwearDashboard&#47;HomePage&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> 
**[Click Here to Visit the Tableau Dashboard using this Data](https://public.tableau.com/app/profile/julie.anne.hockensmith/viz/FootwearDashboard/HomePage?publish=yes)** <sup><sub>*Ctrl+Click to open in new tab*</sub></sup>

Use this is a template to create your own Retail Sales data set.

Create a Python dataframe of random Retail Sales data that can be used in Python or exported to CSV for use in Tableau or other analytical platforms.

This code was born of the need for made up data with current dates to use in a Tableau Pulse demo. Pulse requires real-time (or at least recent) timeseries fields in order to provide AI insight and automated visualizations. With the end of continuous updates to the Superstore dataset built into Tableau (data stopped being added in 2024), I decided to create my own dataset with fully customizable dates, distributions, and fields. Since Python random functions often create even distribution, I also included a generator that creates uneven weight distributions that sum to 1 for use in value creation. 

These are the results in Tableau Pulse using this random generator and exporting to csv for use as a data source:


