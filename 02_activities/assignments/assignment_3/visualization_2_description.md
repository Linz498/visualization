# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

![Visualization 2 - Crime Severity Index Scores Ontario](image-2.png)

    > What software did you use to create your data visualization?

    Microsoft Excel Software

    > Who is your intended audience? 

    Provincial politcians, judicial figures, and high-ranking members of law enforcment agencies in the province of Ontario.
    
    > What information or message are you trying to convey with your visualization? 

    Visualizing the Crime Severity Index scores for Ontario as a whole, as well as the different regions comprising Ontario for the year 2024. The visualization is meant to aid in comparing the scores across Ontario's different regions and against the province as a whole. This should help identify regions of concern that may need focused intervention, and additional resources, as well as regions that have lower scores which may have valuable insights to offer regions with higher scores.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    The prupose of the visualization was to present facts so I tried too keep it as neutral as possible via a simple layout. There were certain design aspects that I would have liked to add that I was unable to based on the constraints in Excel. For example, I would have liked to make the bar chart vertical and ordered from highest to lowest scores for ease of readability, both in terms of the long axis labels, and ranking. However, this is not feasible with combination charts in Excel, which meant I would have had to sacrifice the line series representing the overall CSI score for Ontario. There is also no way for me to add an annotation box to present the audience with the source of data for transparecny purposes (save making a note in the title or creating a text box and linking it to the graph so they can move in tandem). While it is overall quicker to design a graph in Excel, it is much more limited in design capabilities. Even for a simple graph like this, I was unable to make certain changes that would have helped communicate more effectively.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    The visualization cannot be easily reproduced as there was nothing recording what steps I took to create the graph. Unless the audience has access to the original Excel file which shows the dimensions and characteristics of certain features they would have to estimate how to re-create it. 
    
    > How did you ensure that your data visualization is accessible? 

    I made sure that the text is readable via size and color, that labels are properly spaced, that there is a decent amount of contrast between marker colours, bar colours, and the grid, and that selected colours are accessible and have enough for those with colour blindness. Rather than having the x-axis labels on a 45 degree angle, I would have prefered the graph to be horizontal for easier readability, but that was not possible with the combination chart in Excel.
    
    > Who are the individuals and communities who might be impacted by your visualization? 

    The individuals and communities who may be impacted by the visualizations are all Ontario residents, and vistors. High scores might reduce toursim and impact certain economic sectors. Higher scores may drive law enforcment to deploy and focus resources, which may disproportionately affect certain communities. Higher scores may also drive the creation of social initatives.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    I chose to exclude data labels for the bar chart to reduce clutter and ensure readability. The x-axis labels are already adding enough clutter. Realistically, the x-axis labels could have been manually shortened for better readability. I also excluded a full grid and only used horizontal grid lines as only the horizontal gridlines are required to visually link the bars with the scores. The bars themselves visually mimic vertical gridlines.
    
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
