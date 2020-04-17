# covid_risk_score

Dockerized version of shiny app.  Tested on AmazonLinux2. 

- install docker

- run docker

- grab code

- build image (from within root directory)
  - "docker build -t covid-risk-score ."
  
- run container 
  - "docker run -d -p 80:3838 covid-risk-score"

- shiny app should be running on host port 80
