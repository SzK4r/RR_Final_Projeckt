# Reproducing AI Student Perception

The scientific paper which results we chose to reproduce was **"Technical and Humanities Students’ Perspectives on the Development and Sustainability of Artificial Intelligence (AI)l" by Vasile Gherheș and Ciprian Obrad (2018)**. 

## Scientific Paper

This study investigates how the development of artificial intelligence (AI) is perceived by the students enrolled in technical and humanistic specialisations at two universities in Timisoara. It has an emphasis on identifying their attitudes towards the phenomenon, on the connotations associated with it, and on the possible impact of artificial intelligence on certain areas of the social life. Code used to implement this statistical model was not attached to the paper, so we chose to re-implement relevant parts of the procedure described in detail in the scientific article. 

## Data

The dataset utilized in this study encompasses the responses obtained from a survey administered to undergraduate students in their 2nd and 3rd years of study at the Faculty of Cybernetics, Statistics, and Economic Informatics. The survey was conducted online and disseminated through social media groups. Its objective was to acquire insights into students' perceptions regarding the role of artificial intelligence (AI) in the domain of education.

This dataset comprises a total of 96 observations, each representing a unique case or participant. Additionally, the dataset contains 36 variables, which encompass the different characteristics or attributes under investigation.

Dataset available under the link
https://www.kaggle.com/datasets/gianinamariapetrascu/survey-on-students-perceptions-of-ai-in-education 

## Our Workflow

Most important development tools used in the process are listed below:

- We used [R](https://www.r-project.org//) as our language of choice.
- Analysis was performed in a [Markdown](https://www.markdownguide.org/).

## Reproducibility

We set up a custom GitHub action that runs on every pull request to the `main` branch. It runs the sequence of operations described in section Running the Code of this README. 

## Collaboration

In our work we relied heavily on Git:

- We used the **Issues** tab to decide on a project topic and its scope.
- We used the `main` branch as the project master.
- The `main` branch was protected from direct pushes - approval from all team members was required for every pull request, which forced all team members to communicate and comment. Please see our list of [Pull Requests](link_to_pull_requests) here.

## Features / Milestones

The main list of tasks that we wanted to accomplish is outlined below. 
- [x] Potential ideas for the project 
- [x] Finding an interesting dataset 
- [x] Finding research paper
- [x] Loading the data
- [x] Importing R packages relevant for data analysis
- [ ] Forecasting
- [ ] Plotting forecast results
- [ ] Documenting code
- [ ] Were the results replicated?
- [ ] Peper Presentation  
- [ ] Exporting results to a Quarto html report


## Team members

- Antoni Piotrowski
- Szymon Karkoszka
