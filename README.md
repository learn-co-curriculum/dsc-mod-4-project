## The Deliverables

The goal of this project is to have you complete a very common real-world task in regard to Time-Series Modeling. However, real world problems often come with a significant degree of ambiguity, which requires you to use your knowledge of statistics and data science to think critically about and answer. While the main task in this project is Time-Series Modeling, that isn't the overall goal--it is important to understand that Time-Series Modeling is a tool in your toolbox, and the forecasts it provides you are what you'll use to answer important questions. 

In short, to pass this project, demonstrating the quality and thoughtfulness of your overall recommendation is at least as important as successfully building a Time-Series model!

In order to successfully complete this project, you must have:

* [ ] A well-documented **_Jupyter Notebook_** containing any code you've written for this project<br> (use the notebook in this repo, `mod_4_starter_notebook.ipynb`)
* [ ] A **_Blog post_** detailing your methodology and your findings
* [ ] An **_'Executive Summary' PowerPoint Presentation_** that explains your rationale and methodology for determining the best zipcodes for investment.


### Jupyter Notebook Must-Haves

For this project, you will be provided with a jupyter notebook containing some starter code. If you inspect the zillow dataset file, you'll notice that the datetimes for each sale are the actual column names--this is a format you probably haven't seen before. To ensure that you're not blocked by preprocessing, we've provided some helper functions to help simplify getting the data into the correct format. You're not required to use this notebook or keep it in its current format, but we strongly recommend you consider making use of the helper functions so you can spend your time working on the parts of the project that matter. 

#### Organization/Code Cleanliness

The notebook should be well organized, easy to follow, and code is modularized and commented where appropriate.

* Level Up: The notebook contains well-formatted, professional looking markdown cells explaining any substantial code. All functions have docstrings that act as professional-quality documentation. 
* The notebook is written to technical audiences with a way to both understand your approach and reproduce your results. The target audience for this deliverable is other data scientists looking to validate your findings. 
* Data visualizations you create should be clearly labeled and contextualized--that is, they fit with the surrounding code or problems you're trying to solve. No dropping data visualizations randomly around your notebook without any context!

#### Findings

Your notebook should briefly mention the metrics you have defined as "best", so that any readers understand what technical metrics you are trying to optimize for (for instance, risk vs profitability, ROI yield, etc.). You do **not** need to explain or defend your your choices in the notebook--the blog post and executive summary presentation are both better suited to that sort of content. However, the notebook should provide enough context about your definition for "best investment" so that they understand what the code you are writing is trying to solve. 

#### Visualizations

Time-Series Analysis is an area of data science that lends itself well to intuitive data visualizations. Whereas we may not be able to visualize the best choice in a classification or clustering problem with a high-dimensional dataset, that isn't an issue with Time Series data. As such, **_any findings worth mentioning in this problem are probably also worth visualizing_**. Your notebook should make use of data visualizations as appropriate to make your findings obvious to any readers. 

Also, remember that if a visualization is worth creating, then it's also worth taking the extra few minutes to make sure that it is easily understandable and well-formatted. 

**When creating visualizations, make sure that they have:**
- [ ] A title
- [ ] Clearly labeled X and Y axes, with appropriate scale for each
- [ ] A legend, when necessary
- [ ] No overlapping text that makes it hard to read
- [ ] An intelligent use of color--multiple lines should have different colors and/or symbols to make them easily differentiable to the eye
- [ ] An appropriate amount of information--avoid creating graphs that are "too busy"--for instance, don't create a line graph with 25 different lines on it

<center><img src='images/bad-graph-1.png' height=90% width=80%>
There's just too much going on in this graph for it to be readable--don't make the same mistake! (<a href='http://genywealth.com/wp-content/uploads/2010/03/line-graph.php_.png'>Source</a>)</center>

### Blog Post Must-Haves

Your blog post is where you should dig into your thought process and methodology. As with blog post requirements for other projects, your blog post should strike a balance between writing for technical audiences and non-technical audiences. It should contain code snippets, data visualizations, and a detailed explanation of your methodology and findings. The end goal of this deliverable is to share your findings, but to also leave the reader with a sense of how you found these answers, and why they are correct. 

Of the three deliverables, this is the best one for diving deeply into how you defined what makes for the "best" investment opportunities. Your blog post should definitely take some time to dive into the different options available, and should define why the metrics you picked are the best choice--for example, explaining how riskiness fits into your overall model (if at all), or why ROI is (or isn't) the metric you chose to optimize against. 

**_NOTE:_** This blog post is your way of showcasing the work you've done on this project--chances are it will soon be read by a recruiter or hiring manager! Take the time to make sure that you craft your story well, and clearly explain your process and findings in a way that clearly shows both your technical expertise **and** your ability to communicate your results!

### Executive Summary Must-Haves

**Your presentation should:**

- **Contain between 5 -10 professional quality slides detailing:**<br><br>

    * A high-level overview of your methodology and findings, including the 5 zipcodes you recommend investing in<br><br>
    * A brief explanation of what metrics you defined as "best" in order complete this project<br>
<br>

* **Avoid technical jargon and explain results in a clear, actionable way for non-technical audiences.**<br><br>
* **Take no more than 5 minutes to present**<br><br>