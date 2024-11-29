# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      
BAD EXAMPLE:  1st Public data visualization: THE FOODIE FINDS in BENGALURU [source: https://public.tableau.com/app/profile/pradeepkumar.g/viz/FoodieFindsinBengaluru/Home]

    
The "Foodie Finds in Bengaluru" visualization is classified as a *partially effective dashboard*. 
It employs geographic maps, bar charts, and filters, demonstrating an attempt to provide users with interactive insights about restaurants in Bengaluru. 
This aligns with principles of exploratory data analysis, enabling users to investigate data based on their preferences.

However, while the dashboard succeeds in offering multiple data views, it falters in its accessibility and clarity. 
For example, it overuses elements that require user interaction to reveal information (e.g., hover features), which may not be intuitive for all users. 
Additionally, the visualization appears to prioritize aesthetics over usability, as some design choices complicate data interpretation.

According to Tufte’s guidelines on data presentation, an effective visualization should reduce the "data-to-ink" ratio, ensuring every design element serves a purpose. 
In this case, clutter and inconsistent visual elements detract from the core narrative, which is a critical evaluation criterion.


GOOD EXAMPLE: 2nd Public Data Visualization: ANOTHER 10 HACKS FOR BETTER USER EXPERIENCE [source: https://public.tableau.com/app/profile/louisyu/viz/Another10hacksforBETTERuserexperience/Dashboard ]


The "Another 10 Hacks for Better User Experience" dashboard is classified as a *highly effective data visualization*. 
It provides actionable insights into enhancing user experience through design practices while employing a clear, visually appealing, and interactive layout. 
The dashboard’s use of simple bar charts, informative tooltips, and strategic use of whitespace makes it intuitive and engaging.

Each chart in this dashboard has a clear title, context, and actionable takeaways. 

The dashboard also leverages interactivity effectively by allowing users to focus on specific data points of interest without overwhelming them with unnecessary information.
This visualization excels in its ability to guide users through its narrative structure, with each "hack" explained clearly. 
This storytelling aligns with McCandless’s approach to visual data communication, making it a practical example of turning data into a compelling narrative.







      ```
    - How could this data visualization have been improved?  
      ```
      
      1st Public data visualization: THE FOODIE FINDS in BENGALURU [source: https://public.tableau.com/app/profile/pradeepkumar.g/viz/FoodieFindsinBengaluru/Home]


1. **Simplify the Layout:**
   The dashboard's layout is visually busy, which may overwhelm users. Reducing the number of visual elements per view and consolidating related metrics into simpler charts would enhance usability. For example, merging location-based insights with restaurant ratings in one map or chart could streamline the user experience.

2. **Improve Labeling and Legends:**
   Many users may struggle to interpret the dashboard due to limited labeling. For example, some metrics on bar charts are unlabeled, requiring additional effort to understand. Clear and concise axis titles, as well as a consistent legend placement, would improve comprehension.

3. **Enhance Geographic Insights:**
   The geographic map is visually appealing but lacks analytical depth. Using heat maps or clustering can provide a more intuitive view of restaurant density. Additionally, incorporating region-based filters or highlighting neighborhoods with key metrics (like highly rated restaurants) could make the insights actionable.

4. **Add Narrative Context:**
   The visualization fails to establish a clear narrative. For instance, users are not immediately informed of the dashboard's purpose or the insights it aims to deliver. A text box summarizing key findings, trends, or use cases (e.g., "The top-rated restaurants are concentrated in XYZ neighborhoods") would provide a much-needed guide.

5. **Enhance Interactivity:**
   Interactive elements like filters and hover-over details could be more intuitive. For example:
   - Providing an overview button to reset all filters ensures better navigation.
   - Adding interactive explanations or tooltips for new users would increase accessibility.

6. **Incorporate Comparative Metrics:**
   Users could benefit from comparative insights, such as a chart showing how restaurant ratings vary by cuisine or location. For instance, a stacked bar chart comparing ratings across different cuisines might reveal patterns hidden in the current dashboard.

By addressing these areas, the visualization would better adhere to principles outlined by Few (*Information Dashboard Design*), who emphasizes prioritizing user needs and simplifying data representation to enhance decision-making. Additionally, following Norman's usability heuristics (e.g., visibility, error prevention) would help make the dashboard more effective for a broader audience.



2nd Public Data Visualization: ANOTHER 10 HACKS FOR BETTER USER EXPERIENCE [source: https://public.tableau.com/app/profile/louisyu/viz/Another10hacksforBETTERuserexperience/Dashboard ]
Your answer...

While the dashboard is highly effective, several enhancements could further elevate its usability and accessibility:

1. **Enhance Contrast for Better Accessibility:**
   - The color palette, though visually appealing, lacks strong contrast in some areas, which may not meet Web Content Accessibility Guidelines (WCAG). 
   Using colors with higher contrast or providing alternative textures would ensure the dashboard is accessible to users with visual impairments.

2. **Refine the Navigation Flow:**
   - While the dashboard organizes its sections logically, adding a clickable navigation menu or an overview summary would make it easier for users to jump to specific hacks. 
   This aligns with Jakob Nielsen’s usability heuristic of supporting "user control and freedom."

3. **Provide Deeper Contextual Information:**
   - Each "hack" is supported by concise descriptions, but adding real-world examples or linking to resources for further reading could provide greater depth. 
   Users would then not only understand the recommendations but also see their practical applications.

4. **Optimize for Different Screen Sizes:**
   - The dashboard may lose readability on smaller screens due to the density of content. 
   Designing a responsive version or including a mobile-friendly layout would increase its accessibility.



      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
