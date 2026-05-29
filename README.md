\# Node.js CI/CD Pipeline



\## Overview

This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions, Docker, and Node.js.



\## Technologies Used

\- Node.js

\- Express.js

\- Docker

\- GitHub Actions

\- Git



\## Workflow

1\. Push code to GitHub

2\. GitHub Actions triggers automatically

3\. Dependencies are installed

4\. Tests are executed

5\. Docker image is built

6\. Docker image is verified



\## Run Locally



```bash

npm install

node app.js

```



\## Run Using Docker



```bash

docker build -t cicd-task1 .

docker run -p 3000:3000 cicd-task1

```

