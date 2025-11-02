# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

![Visualization 1- Canadian Violent Crime Severity Index](image-1.png)

    > What software did you use to create your data visualization?

    Python - specifically the Plotly.py graphing library. 

    > Who is your intended audience? 

    Politcians, judicial figures, and high-ranking mebers of federal law enforcment agencies.
    
    > What information or message are you trying to convey with your visualization? 

    Visualizing the change in Violent Crime Severity Index (VCSI) scores over the last six years, comparing both overall VCSI scores and Youth VCSI scores. I was interested to see what, if any, impact the Covid-19 pandemic had on the scores, and if youth violence scores aligned or differed from the general population.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    I provided an annotation at the bottom of the visualization for transparency and context. In the annotation I cite the source of the data used in the visualization, and provide a link to the source as well. I also bring the audience's attention to a specific period of interest (the Covid-19) pandemic which had a global event that likely impacted the data. I outline the time period in which the event would have impacted the results. This allows the audience to take this context into consideration when interepting the data trends.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    In this case because I used python to create the visualization using code, the visualization can be reproduced exactly by anyone using the same data set, provided they use the same graphing library. However, there are some aspects of the code that should be adjusted if the date range of the data set is expanded or reduced. For example the data labels on the first and last markers are based on the years, if the dataset was expanded or shortened they might fall out of scope or will no longer be the oldest or most recent and reduce their value/meaning. 
    
    > How did you ensure that your data visualization is accessible? 

    I made sure that the text is readable via size and color, that labels are properly spaced, that there is a decent amount of contrast between marker colours and the grid, and that marker colors are accessible and distinct enough for those with colour blindness.
    
    > Who are the individuals and communities who might be impacted by your visualization? 

    The individuals and communities who may be impacted by the visualizations are all Canadian citizens, residents, and vistors. High scores might reduce toursim and impact certain economic sectors. Higher scores may drive law enforcment to deploy and focus resources, which may disproportionately affect certain communities. Higher scores may also drive the creation of social initatives.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    I chose to exclude data labels for each marker of the plot lines to reduce clutter and ensure readability. I only added data labels for the first and last markers. The purpose of this is to allow the audience to quickly assess and compare the oldest and most recent index scores. This also helps to easily compare the differences pre and post pandemic.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    The data entry clerks who collected and processed the data at municipal, provincial, and federal policing levels, the Statistics Canada employees who collected, compiled, and processed the data, the creators of python and the Plotly.py graphing library, the designers of the color palettes, the researchers who determined what color palettes are accessible, and all the individuals supporting any of the aforementioned individuals in their work.

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
