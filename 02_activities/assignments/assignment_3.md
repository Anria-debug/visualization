# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

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
* Submission Due Date: `23:59 - 13/07/2025`
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

Answer:I chose Dataset on Occupancy and Average Daily Rates by Region, August 2025.
https://www.ontario.ca/page/tourism-research-statistics#section-0

Data visualization #1. Python Line chart.
What software did you use to create your data visualization?
I used Python, specifically the Matplotlib library, to create this line chart. Matplotlib allows for detailed control over design, color, labels, and overall layout, while ensuring full reproducibility through code.
> Who is your intended audience? 
    
    The intended audience includes tourism researchers, hospitality analysts, and policy-makers in Ontario’s tourism sector. It may also interest hotel owners and marketing teams who want to compare their region’s performance against provincial trends.
> What information or message are you trying to convey with your visualization? 
    The visualization communicates the variation in Average Daily Rate (ADR) across Ontario’s tourism regions in August 2025. It highlights which regions (such as Muskoka and Niagara Canada) have significantly higher average hotel prices, suggesting stronger demand or more premium accommodations compared with others.

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I considered clarity, consistency, and readability:
    Used a line with markers to clearly show changes between regions.
    Chose a neutral blue tone that is accessible for most viewers, including those with color-vision deficiencies.
    Rotated and aligned x-axis labels to improve legibility of long regional names.
    Added grid lines and appropriate scaling for better comparison across data points.
    Kept the design minimalist to emphasize data rather than decoration.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?   
    The visualization is fully reproducible because it was created entirely in Python.
    All code, data, and libraries used are included and can be re-run by anyone. This guarantees transparency and consistency, allowing future users to verify or update the results with new data.

> How did you ensure that your data visualization is accessible?  
     I ensured accessibility by:
     Using high-contrast colors for the line and background.
     Avoiding reliance on color alone to convey meaning (points and grid lines add structure).
     Using clear fonts, descriptive titles, and labeled axes for context.
     Saving the figure in a high-resolution format that screen readers and magnifiers can handle.
    
> Who are the individuals and communities who might be impacted by your visualization?  
     This visualization impacts tourism boards, hotel operators, and local governments. It may influence resource allocation, marketing strategies, or pricing decisions based on regional performance.
     It could also inform travelers looking for more affordable destinations in Ontario.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I selected only the “Average Daily Rate” column for August 2025, as it directly represents pricing trends.
    Other metrics such as occupancy rates or revenue per available room were excluded to maintain a focused message and avoid clutter.
    This choice supports a clear comparison of regional hotel costs without mixing multiple performance indicators.

> What ‘underwater labour’ contributed to your final data visualization product?
      The underlying work involved:
      Extracting and cleaning the data from the Ontario tourism Excel file.
      Verifying region names and values to ensure accuracy.
      Writing, debugging, and commenting Python code for reproducibility.
      Testing different visualization types (bar, line, pie) before selecting the one that best communicated the data trend.
      

Data visualization #2. Excel Bar chart.

>What software did you use to create your data visualization?
    I used Microsoft Excel to create this horizontal bar chart. Excel offers an accessible and user-friendly interface for data visualization, especially useful for quickly formatting and comparing numerical data across multiple categories.
> Who is your intended audience? 
    The intended audience is tourism professionals, regional hotel managers, and analysts working in Ontario’s hospitality sector. The visualization helps them quickly compare hotel price levels across various regions and identify where average daily rates are highest or lowest.
> What information or message are you trying to convey with your visualization? 
    This chart highlights how average hotel rates differ across Ontario regions in August 2025. It emphasizes that areas like Muskoka, Parry Sound and Algonquin Park and Niagara Canada have notably higher average daily rates, possibly reflecting their popularity as tourist destinations during the summer season.
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I focused on clarity, hierarchy, and aesthetics to make the chart readable and professional:
    Used horizontal bars to fit longer regional names neatly on the y-axis.
    Applied consistent blue tones for visual harmony and simplicity.
    Added data labels to each bar to provide exact dollar amounts without requiring viewers to estimate values.
    Included a clear title and subtle background gradient to make the visualization engaging but not distracting.
    Ordered bars logically to show regional variation clearly and avoid clutter.
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    While Excel allows visual replication through the same dataset and formatting steps, it is less reproducible than code-based tools like Python. Reproducing the chart relies on following manual steps rather than automated scripts. This means small visual differences may appear if recreated by another person. To enhance reproducibility, I saved both the Excel file and the chart formatting instructions.
> How did you ensure that your data visualization is accessible?  
    I ensured accessibility by:
    Using high-contrast colors for the bars and text.
    Including labels directly on bars so values can be read without relying on color interpretation.
    Using large, readable fonts for region names and numeric values.
    Keeping the background subtle to maintain strong text and color visibility.
> Who are the individuals and communities who might be impacted by your visualization?  
    This visualization can impact regional tourism boards, hotel associations, and business investors. It helps them make data-driven decisions about pricing, marketing, and tourism promotion. Additionally, travelers could use this data to compare lodging affordability across destinations.
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    I focused on the Average Daily Rate for August 2025 to isolate seasonal pricing trends. Occupancy data was excluded in this visualization to maintain focus on price differences rather than hotel demand. This selective approach allows a clearer interpretation of how hotel prices vary geographically.
> What ‘underwater labour’ contributed to your final data visualization product?
   The behind-the-scenes work included:
   Extracting, cleaning, and verifying data from the CBRE custom report.
   Organizing the dataset in Excel to match region names with corresponding rates.
   Testing different chart types (column, bar, pie) before selecting a bar chart as the clearest option.
   Formatting and labeling the chart for clarity and professional presentation.
   Cross-checking numeric accuracy between Excel calculations and the original dataset to ensure consistency.



