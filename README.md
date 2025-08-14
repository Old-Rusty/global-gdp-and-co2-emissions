# Global GDP and CO2 Emissions

**Project Summary:** As global industries and economies continue to advance at an unprecedented rate, their impact on the enviornment comes increasingly under scrutiny. This project seeks to better understand the enviornmental impacts of the global economy by analysing and identifying trends between GDP and CO2 emissions.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
The original dataset used in this project can be found in "dataset\raw\gdp_co2_by_country.csv". <br>
This is a precleaned dataset from kaggle
#### Original Dataset
Dataset source: https://www.kaggle.com/datasets/mackness/global-gdp-and-co-emissions-dataset-19602022?resource=download<br>
Author: [Katlyn Goeujon-Mackness](https://www.kaggle.com/mackness)<br>
Licence: [MIT License]

This dataset consists of records of CO2 emissions and various economic indicators of over 180 different countries from 1960 to 2022. 


## Project Objectives
The aim of this project is to:
* Implement data Extraction, Transform and Load pipelines
* Explore the relationship between GDP and CO1 emissions in countries across the globe
* Provide insight on the correlation of GDP and CO2 emissions through Data Visualisation
* Usage of various Python libaries to complete objectives


## Hypothesis and how to validate?
General hypothesis is that GDP is expected to have a positive linear correlation with CO2 emissions. Higher GDP is expected to be linked to higher CO2 emissions, due to the environmental impacts of a rising economy. CO2 emissions can also have a positive correlation to population of a country due to the large demands for industries and transportation.<br><br>

This hypothesis can be tested by creating visualisation using the given dataset. Statistical graphs such as scatter plots and line plots can be used to show existing trends and patterns within the dataset. Analyse correlation between CO2 and GDP as well as their correlation with other features.

## Project Plan
* The dataset was processed and manipulated using the pandas libary.
* During the ETL process, the data was extracted from the CSV file onto a pandas DataFrame.
* The data was then cleaned and processed then saved as a CSV file.
* The processed dataset was then extracted and manipulated for visualisation.
* The visualised data can then be used to draw a final conclusion on the initial hypothesis.

## The rationale to map the business requirements to the Data Visualisations
* Data Visualisations should aim to explore relationship between GDP and CO2.
* Visualised data should highlight relative features (GDP, CO2, Population).
* Visualisations should help drawing conclusions on the data.

## Analysis techniques used
* ETL pipeline was used to clean data and process it into a more usable format.
* Data visualisation was used to identify existing patterns of the data.
* Exploratory Analysis was used to summarise key characteristics oof the data.
* Descriptive Analysis was used to find past trends.
* Generative AI was used to help debug and improve code optimisation.


<!-- ## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues? -->

<!-- ## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences.  -->

## Unfixed Bugs
* Plotly generated graphs not displaying on github

## Development Roadmap
* I faced challenges plotting meaningful data.
* The volume of data from the full dataset was overwhelming
* I struggled to document my work whilst staying on deadlines.

In the future I hope to:
* Improve my ability to handle large datasets.
* Improve data transformation skills to help transform datasets into versions easier to work with.

<!-- ## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file. -->


## Main Data Analysis Libraries
* NumPy
* pandas
* Matplotlib
* Seaborn
* Plotly


## Credits 

* Data source: https://www.kaggle.com/datasets/mackness/global-gdp-and-co-emissions-dataset-19602022?resource=download

<!-- ### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/) -->

<!-- ### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site -->



## Acknowledgements (optional)
Thank you to:
* Dataset Author: [Katlyn Goeujon-Mackness](https://www.kaggle.com/mackness)