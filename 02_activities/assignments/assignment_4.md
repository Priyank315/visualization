# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
        Python with libraries: Matplotlib and Seaborn.

        Tableau Public for creating a geographically rich, interactive visualization.

    > Who is your intended audience? 
    Policymakers and program administrators involved in cultural funding.Researchers analyzing cultural investment priorities. --> For Python
        Toronto city council members, community planners, and grant applicants interested in geographic distribution pattern. --> For Tableau

    > What information or message are you trying to convey with your visualization?
        FOR PYTHON - This chart highlights which funding streams received the largest allocations in 2024. It emphasizes the priority given to "Multi-Year Operating" and "Annual Operating" streams compared to "Project" funding.
        FOR TABLEAU - Highlights which wards received the highest/lowest funding, providing insights into spatial equity.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
        FOR PYTHON: Substantive: Focus on a high-level comparison of funding streams.
                    Perceptual: Used distinct colors and clear labels to ensure data is easy to read.
                    Aesthetic: Minimal clutter, with clean axes and an intuitive layout.

        FOR TABLEAU: Substantive: Geographic representation aligns with the theme of ward-level distribution.
                     Perceptual: Used contrasting colors to emphasize disparities.
                     Aesthetic: Simple map layout with a gradient to avoid overwhelming viewers.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        FOR PYTHON: The Python code provided ensures reproducibility. Anyone with access to the dataset can recreate the visualization.
        FOR TABLEAU:Tableau workbooks can be shared. However, they are not fully open-source, which might limit reproducibility. Exported CSV files ensure users can replicate the results. 
    
    > How did you ensure that your data visualization is accessible?  
        FOR PYTHON: Added a descriptive title, labeled axes, and ensured colors are distinguishable for individuals with visual impairments (colorblind-friendly palette).
        FOR TABLEAU:Included clear legends and interactive tooltips to make the visualization informative for diverse audiences. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
        FOR PYTHON: Recipients of funding streams, including cultural organizations and local community groups, may use the visualization to understand funding trends.
        FOR TABLEAU:Community organizations in underfunded wards may use this visualization to advocate for more equitable funding. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        FOR PYTHON: Selected "Stream" and "Grant" columns to focus on grant distribution by funding type. Excluded "Ward" and other details irrelevant to this analysis.
        FOR TABLEAU:Selected "Ward" and "Grant" columns. Excluded other details (e.g., "Project Name") to keep the map focused.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
        FOR PYTHON: Data cleaning and summarization (grouping by streams), ensuring visual clarity, and debugging the code to make the visualization accurate.
        FOR TABLEAU:Exporting data, geocoding wards in Tableau, testing map configurations, and ensuring labels are legible.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
