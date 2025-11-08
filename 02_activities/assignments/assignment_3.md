# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

For visualization 01:

    > What software did you use to create your data visualization?
        The software used for this visualization was Python, along with the NumPy, Pandas, Seaborn, and Matplotlib libraries.

    > Who is your intended audience? 
        The intended audience for this visualization includes a hypothetical Provincial Government climate policy committee responsible for developing strategic Greenhouse Gas (GHG) emission control policies, and the general public interested in understanding industry-level emission trends.
    
    > What information or message are you trying to convey with your visualization? 
        This visualization illustrates the behavior of the top ten GHG-emitting industries in Ontario across multiple years. By revealing emission trends over time, this visualization can inform policy design, mitigation strategies, and emission control measures at both the governmental and industry levels. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
        A key design focus was readability and accessibility. Since this visualization could appear in public policy and legislative documents, it needed to remain legible in both digital and printed formats. Design choices such as a clean grid style, balanced typography, and distinct color differentiation were applied to maintain clarity even when displaying multiple overlapping industry trendlines.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        Reproducibility was ensured through the use of Python scripting, where all data transformations, calculations, and visual design parameters are explicitly coded. This allows any user to replicate the visualization by running the same code on the source dataset. Additionally, a random seed was set at the beginning of the script to guarantee consistent outputs in cases involving randomization.
    
    > How did you ensure that your data visualization is accessible?  
        To ensure accessibility, a colorblind-friendly palette was applied to provide sufficient contrast and clarity for all viewers. Line weights were carefully adjusted to maintain readability even when multiple trendlines overlap. Font sizes, axis labels, and legends were also selected for high visibility across different screen sizes and resolutions.
    
    > Who are the individuals and communities who might be impacted by your visualization?
        In terms of the visualization’s subject matter, the most directly impacted groups are the industrial sectors identified as major GHG emitters, along with the communities located near these emission sources.
        
        In terms of readership, this visualization impacts the general public, environmental analysts, and policy makers who engage with public reports on emissions and climate initiatives.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        The dataset title "Greenhouse Gas Emissions Reporting by Facility" naturally suggested focusing on the major GHG-emitting industries and their geographic distribution. By concentrating on these features, the visualization highlights which industrial sectors contribute most to emissions, and helps identify regional emission hotspots across Ontario. Less relevant fields, such as individual facility identifiers, were excluded to emphasize the industry-level trends.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
        The primary "underwater labour" involved data cleaning and feature selection. This included isolating key variables, removing null values, and mapping NAICS (North American Industry Classification System) codes to their corresponding industry labels, since these codes were the only identifiers in the raw data. Additional preparation involved converting CO2 tonnes into million tonnes to simplify interpretation and improving axis readability.


For visualization 02:

    > What software did you use to create your data visualization?
        The software utilized for this visualization was Power BI.

    > Who is your intended audience? 
        The intended audience for this visualization is the general public, specifically users accessing a hypothetical climate policy and advocacy webpage that aims to communicate emissions data in an interactive and approachable way.
    
    > What information or message are you trying to convey with your visualization? 
        The purpose of this visualization is to reveal how the locations of the top ten Greenhouse Gas (GHG) emission sources in Ontario have shifted over the past decade. By visualizing these changes across time, the project highlights emerging and persistent emission hotspots and encourages reflection on spatial and temporal emission patterns across the province.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
        The design intent was to maintain a neutral yet visually clear aesthetic while enabling users to explore data interactively across the 2010–2022 timeframe. The layout was structured to let viewers easily navigate between years and identify how the top ten emitting cities or regions change over time, along with their corresponding total annual emissions. The simplicity and clarity of design help emphasize data over decoration, supporting an evidence-based narrative. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        Since this visualization was created in Power BI, it is considered non-reproducible in the strict programming sense, as it relies on a graphical interface rather than executable code. However, reproducibility can still be supported by documenting each transformation step in Power Query and clearly describing how measures were created in DAX. These steps allow others to replicate the same results using the same dataset. 
    
    > How did you ensure that your data visualization is accessible?  
        This visualization employs a neutral, grayscale color palette that maintains clarity and contrast across different display settings. Because it is designed for digital platforms, users can rely on interactive zoom and hover tools to examine details. Additionally, total annual emission values per city per year are displayed directly within the visuals to enhance quick readability without requiring deep navigation.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
        The individuals and communities impacted by this visualization include climate advocacy groups, environmental scientists and professionals, and the general public seeking credible, professionally curated information about Ontario’s emissions landscape. These visual insights can help inform public discourse, support policy advocacy, and encourage community engagement with environmental data.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        Similar to the first visualization, this project focuses on major GHG-emitting industries and their geographic distribution. The dataset was aggregated by city and year, summing total emissions across industries to identify and display the top ten emitting locations. Non-essential columns were excluded to streamline the analysis and emphasize the spatial and temporal dimensions of GHG emissions across Ontario.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
        For this visualization, the underwater labour was relatively minimal but still essential. The main steps included converting CO2 emissions from tonnes to million tonnes to improve readability, and removing null values to ensure data consistency. These refinements were carried out through Power BI’s data modelling features, using measures for unit conversion and filters for data cleaning. 

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
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
