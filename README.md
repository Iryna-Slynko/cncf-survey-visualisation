# Patterns and Challenges among Kubernetes users (based on World 2020 Cloud Native Computing Foundation Survey data)

## Summary

This work has been done for the for the Interactive Media Design and Data Visualisation course. [The original report](./Report.md) is cleaned up and attached to the repository.

The data for this report is collected from [CNCF 2020 survey](https://github.com/cncf/surveys/blob/main/cloudnative/Cloud_Native_Survey_1H_2020.csv).

The data was converted to a more parseable format using Excel and imported in Tableau. [The result Excel file](CNCFSurvey.xlsx), [CSV file](CNCFSurveyParsed.csv) and [Tableau file](Book3.twbx) are attached. Tableau file is also available [online](https://public.tableau.com/views/PatternsandChallengesamongK8susers/PatternsandChallengesamongKubernetesusers?:language=en-GB&:display_count=n&:origin=viz_share_link).

We discovered several correlations from the data obtained.

* Using CI/CD is slightly higher for companies based in Europe rather than in the USA. 
* Developers in small companies (10-50 people) spend more time writing code and, thus, can commit the code more often. People in large companies (500-999 people) take the second place in that regard.
* The majority of the companies surveyed have only several production clusters except for large (100-499 people) and enormous companies(>5000) where people work on tools supporting multiple clusters.
* The companies based in Asia do not see the culture challenges as important as they do in North America and Europe.
* One more difference for the Asian companies is the release cycle. They release new version more often, once a month, than on other continents.
* The deployment time is the main benefit for using Kubernetes. Only the companies with 100-499 head count and less than 10 people in North America have it in the same place as scalability.

Fun fact that revealed from the data is that if the company does not use CI/CD, then they do not know how many clusters are there in production. This might be due to the strict role separation and manual deployments.

See more information in dashboard
![Screenshot of dashboard](images/k8s-users-dashboard.jpg)
