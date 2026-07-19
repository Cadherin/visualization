# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Map (Viz 1): I used ArcGIS to create the map view of the visualization. 
    Chart (Viz 2): I used python to generate the chart.
    Table: I used Excel to create a pivot table to summarize the results and complement the map and chart visuals. 

    Please see the this markdown page on github for a compilation of data visualization created on this subject: https://github.com/Cadherin/visualization/blob/main/02_activities/assignments/A3_Viz.md 

    > Who is your intended audience? 
    Both map and chart (Viz 1 & 2): The audience is the general public with an interest in gardening and efforts that the City of Toronto has put towards promoting pollinator gardens.

    > What information or message are you trying to convey with your visualization? 
    Map (Viz 1): The distribution of funded pollinator gardens across the City of Toronto by ward
    Chart (Viz 2): The breakdown of the number of pollinator gardens by type and year funded.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    Map (Viz 1):
    - Type of visualization: A choropleth map was selected to use shades of colours to represent aggregate summary of pollinator gardens funded between 2020 and 2025. The map enables the audience to see where the most and least number of cumulative pollinator garden sites are spatially. The darker the color, the higher the number in the respective ward.

    - Cognitive load: By using map as a familiar object to the audience, it reduces the cognition load required to process the information. Audience would intuitively understand that the map has the intent to convey spatial information. By breaking down the map into wards, the audience can easily see the comparison across smaller areas within the map. 
    
    Chart (Viz 2): 
    - Type of visualization: A horizontal stacked bar chart was selected to illustrate the types of pollinator gardens funded over the years. The stacked format allows comparison of the total number of gardens while also showing the contribution in each funding year. Colour was used to represent garden types and each bar represents one funded year. 

    - Cognitive load: A limited colour palette was used to reduce visual clutter. Data cleanup was performed to group all rain gardens into a single type instead of how breaking it down further as in the raw data to reduce the number of garden types that need to be shown in the chart. Labels and axis titles were added to provide context, including colour legend for the garden types. The plot was also organized so that the most common garden types were easier to identify, creating a clearer visual hierarchy.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    By selecting an open dataset available on a City of Toronto website, I ensure that the dataset is accessible and could be retrieved by all. 
    
    Map (Viz 1): The tool used for making the chart was ArcGIS. There is an online version of this tool that is freely accessible to the public and also through trial. It is a standard mapping software that is widely used.

    Chart (Viz 2): The chart was generated using python. It can be reproduced given access to the dataset and setup of a coding interface that is free. 
    
    > How did you ensure that your data visualization is accessible?  

    By exporting the map and chart (Viz 1 & 2) as images and uploaded them to a web location (i.e. Github) that could be visited by anyone with an internet connection, I ensure that the data visualization is accessible. 
    
    > Who are the individuals and communities who might be impacted by your visualization?

    Individuals and communities that might be impacted by both the map and the chart (Viz 1 & 2) include those who manage the pollinator gardening program and oversee the funding process. Insights on the types of pollinator gardens that have a lower cumulative number could inform targeted promotion efforts to support the respective groups that may not be aware of the program but could benefit. Insights on city wards that have fewer pollinator gardens could also inform changes in outreach efforts. By looking at the number of gardens funded over the years, increasing or decreasing trends could be spotted to inform whether the program is getting consistent traction. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    Map: For a minimalist choropleth to be created, only the aggregate sum of gardens for each ward in the map was displayed. To avoid making the map too cluttered, only the ward names were shown as textual labels. 

    Chart: For a horizontal stacked chart that is not too overwhelming for the audience to process, only the funded year and garden type were features shown in the chart. The garden type categories were also simplified to reduce the number of types and colours that need to be used. The reduction of the number of garden types was achieved by lumping all rain gardens into a single type instead of splitting them into sub-types as in the raw dataset as mentioned above. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    There was not significant underwater labour needed to create both the map and the chart visualization. The only hidden data cleaning work was to group the rain garden related garden types into one. This involved light coding and transformation efforts. 

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
