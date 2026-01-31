# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    The softwares used were Python and R.

    > Who is your intended audience? 

    The intended audience is the general public.
    
    > What information or message are you trying to convey with your visualization? 

    The visualization is meant to convey that intimate partner violence remains an important public safety concern often involving intimate partners.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

    The visualizations incorporated a simple figure design featuring two axes and colour coded categories to reduce cognitive load.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    In both cases, the figures were generated programmatically. The code used to generate both the Python and R figures was provided with comments explaining general steps.
    
    > How did you ensure that your data visualization is accessible?

    The data visualization utilized a color blind friendly palette (i.e. viridis) with an associated legend to label categories. In addition, a sans-serif family typeface was used to make it more accessible for people with cognitive disabilities. Lastly, default font size and spacing were thought to be sufficient. In the R version, a subtitle was included to provide additional description for the reader.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    This visualization is expected to impact members of the general public, but also the following stakeholder groups: victims of intimate partner violence, law enforcement organizations and policymakers.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

    The dataset was transformed to aggregate count information by year, collapsing smaller time units and locality information. This was done to make the trend more accessible to the public.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    In this case, the preparation of the dataset can be considered the main underwater labour. Specifically, the dataset is comprised of verified Intimate Partner Violence occurrences investigated by the Toronto Police Service (TPS) reported since 2014. Therefore, the staff at the TPS can be said to have made significant contributions towards this data visualization product.

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
