# Dockerized-ML-Webapp-Deployed-on-GCP-App-Engine (Serverless deployment)

Google App Engine is a Platform as a service (PaaS) provided by Google that supports the development 
and hosting of different scalable web applications.

Google App Engine Provides an auto-scaling feature that automatically allocates resources, so web application 
can handle more requests.

This project shows how to deploy a machine learning web application on Google App Engine.
 
The steps included for this project are, create an App Engine application deploy application, and finally, 
deleting the project to avoid incurring charges to our Google Cloud account.

## Project Pre-requisites:
1. Google Cloud Account.
2. Enabled Billing.
3. GKE and GCR enabled

## Project Tasks:

1. Create an App Engine application.
2. Deploy application.
3. Take generated Service URL from Cloud Terminal.
4. Testing the Web Application.
5. Deleting the Project.

** Create an App Engine application:**

```bash
gcloud app create
```

<p align="center">
  <img src="images\1.png" alt="workflow"/>
</p>

** Deploy application:**

```bash
gcloud app deploy
```

<p align="center">
  <img src="images\2.png" alt="workflow"/>
</p>

** Take generated Service URL from Cloud Terminal:**

```bash
gcloud app browse
```

<p align="center">
  <img src="images\3.png" alt="workflow"/>
</p>



