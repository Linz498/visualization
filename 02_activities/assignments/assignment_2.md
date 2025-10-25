# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.

    BAD VISUALIZATION - Fast Fashion's Enviornmental Wake Up Call #VOTD [https://public.tableau.com/app/profile/fergus.smith/viz/FastFashionsEnvironmentalWakeUpCall/Dashboard1]

    The purpose of this visualization is to communicate the impact of fast fashion on the enviornment. All of the visualizations are set ontop a picture of a pair of blue jeans. There are multiple interactive features where viewers are required to hover over different symbols to obtain context about the visualization, many of the visualizations are made to blend in with the jeans, and the overlayed text lacks contrast against the background. A lot of these features were probably added with the intention of making the visualization pleasing to look at. Unfortuantely the creators focused so much on that aspect that they neglected functionality and effective communication. 
    
    For example, there is a simple line graph on the left jean pocket intended to demonstrate the difference between global population and textile production over time. The lines are coloured to blend in as if the are pocket stitching lines making it easy to miss the graphic entirely and hard to read. There is a lack of axis so it is diffuclt to determine if the graph has been placed on an agle to fit in the pocket, which could lead to an overexaggeration of the data. In graphics where viewers are required to hover over different areas to obtain context about what the visualization is representing, it is near impossible to compare different variables as the viewer can only hover on one at at time. The busyness and effort unecessarily increases cognitive load on the viewer (https://www.europeanbusinessreview.com/keeping-it-simple-the-power-of-minimalist-data-visualizations/).

    Because the visualizations are hard to read, the impact of the visualization is limited and reduces its ability to advocate for the cause it is attempting to higlight (Data Visualization: Introduction and Overview). Additionally, the intended audience for the visualization is unclear. Some visualizations refer to consumer behaviour which would be of interest to businesses, while other visualizations outline the effects of fast fashion and seem to have more purpose galvanizing support amongst politicians and consumers. Also the visualization does not provide any details on the source or preparation of data making it lack both transparency and reproducability (Data Visualization: Reproducible Data Visualization).
    
    Overall rating: Aesthetically pleasing, visually confusing, and bad at communicating. A classic case study of looks trumping substance and functionality.

    GOOD VISUALIZATION - CRM Sales Dashboard #VOTD [https://public.tableau.com/app/profile/fathima.shanavas/viz/CRMSalesDashboard_17405967603400/SalesDashboard]

    The purpose of this visualization is to provide management with information about the company's sales piepeline. The visulaization is simple, making it easy to read and interpret. It also enables interactivity and filtering through clicking on different categories and variables. This allows viewers to easily identify and parse out information of specific relevance to them (ie. different product managers), and shows a good understanding of its intended audience. It also appropriately groups visualizations together for easy complimentary comparaison. There is a section for information about the visualzation on the bottom left. While I cannot acces it, I will assume it provides information about the data such as how recent it is, or the frequecny of ingestion, and where data is being pulled from which provides transparency to the visualization. Additionally, the visualization was prepared using Tableau which has a function called Tableau Prep [https://www.tableau.com/products/prep]. This function allows users to track and store data preparation procedures which allows for reproducability.
    
    The graphs that are the most effective are the two along the bottom "Product Wise", and "Sector Wise". They are simple bar charts, but because they are built vertically, they easily demonstrate rank order. The total numbers of sales are in a condensed format (K instead of zeros) and off to the far side rather than being on the graph, which helpes with readability as well.

    Overall rating: Simple and effective. This demonstrates that complexity does not equal superiority in visualizations (https://www.europeanbusinessreview.com/keeping-it-simple-the-power-of-minimalist-data-visualizations/).


      ```
    - How could this data visualization have been improved?  
      ```
       BAD VISUALIZATION - Fast Fashion's Enviornmental Wake Up Call #VOTD [https://public.tableau.com/app/profile/fergus.smith/viz/FastFashionsEnvironmentalWakeUpCall/Dashboard1]

       To imporve this visualization I would get rid of the background jean picture entirely, it makes it too hard to read the text, see the visualizations, and also constrains the size of the visualizations. Perhaps some smaller images can be used by the title to break up monotony but not distract of the graphics. I would make sure the graphs provide all necessary labels for context rather than requiring the viewer to hover over areas. The hovering function would soley be used for additional supplementary information or definitions. I would also ensure that the source of data is included at the base of the visualization. Additionally, I would focus the purpose and intended audience which would likely reduce the number of graphs and make it easier to communicate the key message.

        GOOD VISUALIZATION - CRM Sales Dashboard #VOTD [https://public.tableau.com/app/profile/fathima.shanavas/viz/CRMSalesDashboard_17405967603400/SalesDashboard]

        To improve this visualization, I would add a bit more depth to the grey colour used in the graphs to create more contrast. The lighter grey does not have as much contrast against the white background as I would like for readability. Contrast can not only affect readability, but also accessibility for viewers with impairments (https://w3c.github.io/wcag21/understanding/21/graphics-contrast.html). I would also maybe include graphs about pricing and order completion. The numbers about sales won and lost are great, but the additional information about pricing and order completion might help the viewers understand why the numbers are the way they are. While we can assume data is sourced from the company's databases, and an information section is provided in the bottom left corner, I would still appreciate a small disclaimer at the top which outlines how recent the data is.
        
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
* Submission Due Date: `23:59 - 10/26/2025`
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

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
