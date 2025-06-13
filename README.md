# Project Healthcare Insurance Analysis

**Project Healthcare Insurance Analysis** is a data analysis project focused on exploring and understanding the factors that influence healthcare insurance charges. Using a real-world dataset, this project investigates how personal attributes (such as age, gender, BMI, family size, and smoking habits) and geographic factors impact insurance costs. The analysis includes data cleaning, visualization, and predictive modeling to provide actionable insights for estimating healthcare expenses.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The dataset used in this project is sourced from [Kaggle: Healthcare Insurance Dataset](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance/data). It contains records of individuals, capturing both personal and geographic attributes that may influence healthcare insurance charges.

**Features include:**
- `age`: Age of the primary beneficiary (numeric)
- `sex`: Gender of the insured individual (`male`, `female`)
- `bmi`: Body Mass Index, providing an indication of body fat (numeric)
- `children`: Number of dependents covered by insurance (numeric)
- `smoker`: Smoking status of the individual (`yes`, `no`)
- `region`: Residential region in the US (`northeast`, `northwest`, `southeast`, `southwest`)
- `charges`: Individual medical insurance costs billed by health insurance (numeric)

This dataset enables analysis of how demographic and lifestyle factors, as well as geographic location, impact insurance costs. It is suitable for statistical analysis, data visualization, and predictive modeling.


## Business Requirements
* I will be focusing on 3 requirements.
* 1. How smoking has an impact on insurance charges.
* 2. Identify how insurance charges vary across different regions
* 3. Explore the relationship between BMI and insurance charges


## Hypothesis and how to validate?
1. **Hypothesis:** Smokers have significantly higher insurance charges than non-smokers.
   - **Validation** Use boxplots to visualise the distribution of charges for smokers vs non-smokers
2. **Hypothesis** Insurance charges vary by geographic region.
   - **Validation:** Calculate and visualize the average charges per region using a bar chart.
3. **Hypothesis:** There is a positive correlation between BMI and insurance charges, especially for smokers.
   - **Validation:** Create a scatter plot of BMI vs. insurance charges, colored by smoking status, and add a regression line to visually assess the trend between BMI and charges.

## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.