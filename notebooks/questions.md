1.	Why is MLFlow useful?

MLflow is useful because it streamlines and manages the entire machine learning lifecycle, making experimentation, deployment, and collaboration more efficient.

2.	What is the purpose of having automated pipelines in ML production environment? Why can't the data scientist not just run notebooks to train models and produce predictions.

Because it is automating the whole process of training and it helps to handle more problems and be faster to achieve main point of model

3.	What is the difference between A/B testing, Green Blue deployments, Canary deployments and Challenger Champion deployments?

A/B testing is just randomly divining users to two groups to determine which groups with different solutions are better.

Green blue is like production and beta-production environment. Blue is current and stable version but blue is new and verified version pretending to be green. The solution is test blue and achevie green state

Canary deploy is like pilotage version. 

Champion-Challenger deployment is comparing new version to current version which is on production. Winner is going to production

The difference between deployments is the way how developers want to find the best model with consideration of buissiness goals

4.	Why are we hosting artifacts in AWS S3 and metadata in RDS?

Hosting artifacts in AWS S3 and metadata in RDS is a best practice for optimizing scalability, cost, and performance in ML workflows.

5.	What are some security concerns and challenges involved with using secrets and API keys to authenticate our github actions workflow instance?

Conerns:
    Pull Request Attacks from Forks
    Over-privileged Secrets
    Man-in-the-Middle (MITM) Attacks

Challenges:
    Secret Sharing Across Environments
    Hard to Audit Usage
    Limited Secret Management Features in GitHub

6.	What was the biggest challenge for you in completing the assignment?

The bugs and configurations. I really don't get the idea of the process. The last part of instrucion named  Code and codespaces setup is the most NOT clearly part in comparision to whole instruction.
