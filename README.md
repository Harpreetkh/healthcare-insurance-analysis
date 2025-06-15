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

## Business Requirements
* I will be focusing on 3 requirements.
* 1. Does smoking effect insurance charges?
* 2. Identify how insurance charges vary across different regions
* 3. Explore the relationship between BMI and insurance charges


## Hypothesis and how to validate?
1. **Hypothesis:** Smokers have significantly higher insurance charges than non-smokers.
   - **Validation** Use boxplots to visualise the distribution of charges for smokers vs non-smokers
2. **Hypothesis** Insurance charges vary by geographic region.
   - **Validation:** Calculate and visualize the average charges per region using a bar chart.
3. **Hypothesis:** There is a positive correlation between BMI and insurance charges, especially for smokers.
   - **Validation:** Create a scatter plot of BMI vs. insurance charges, coloured by smoking status, and add a regression line to visually assess the trend between BMI and charges.

## Project Plan
* The pokect followed these steps:
* 1. Data Extraction: Load the CSV dataset using pandas.
* 2. Data Cleaning and Trnaformation: Checked for missing values, duplicates and ensured correct data types.
* 3. Data visualisation: Used matplotlib, seaborn and plotly to explore relationships and patterns
* 4. Analysis and Interpretation: Each visualisation answered a business questions and helped confirm or reject the hypothesis

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

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits 
### Content 
- I used chat gpt to help me in several parts when I wasn't sure what to do. For example, I didn't realise that I had to manually download the libraries that I needed, so I asked chat gpt what to do. Chat gpt also helped me ass the box around the legend in the scatterplot.
- https://www.kaggle.com/code/chandradeepnarra3/insurance-data-insights - I had a look at other people's analysis of the dataset that I was using. I used the code from this person at the beginning of my code where i was eztracting the data. 
- I used github copilot 

## Acknowledgements (optional)
* Thank the people who provided support through this project.