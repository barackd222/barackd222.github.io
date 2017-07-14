## Hands On Labs

- Oracle Code Sydney July 2017

### Getting Started with the MedRec APIs

- [Pre-Requisite Steps including Required Software Installation](./assets/handsonlabs/prerequisites.md)  

### Downloading the application code and run the APIs locally

- [Fork the MedRec API Git project](./assets/handsonlabs/forkthemedrecapigitrepo.md) 
- [Run the local Node API application](./assets/handsonlabs/runtheapislocally.md)
- [Access the local APIs using SwaggerUI](./assets/handsonlabs/exploretheapis-1.md)
- [Explore the local APIs using Postman Client](./assets/handsonlabs/exploretheapis-3.md)

### Downloading the python client application code 

- [Fork the MedRec Python Git project](./assets/handsonlabs/forkthemedrecpythongitrepo.md) 
- [Access the locally running APIs using Python](./assets/handsonlabs/exploretheapis-2.md)

### Access the APIs hosted on Oracle Cloud protected using API Platform
- [Register as a developer to get an API Key](./assets/handsonlabs/exploretheapis-5a.md)
- [Explore the Secured APIs with your API Key using Swagger](./assets/handsonlabs/exploretheapis-5.md)
- [Explore the Secured APIs with your API Key using Postman](./assets/handsonlabs/exploretheapis-6.md)
- [Explore the Secured APIs with your API Key using an online Python Service](./assets/handsonlabs/exploretheapis-4.md)


Congratulations, you have completed all required labs!

Below you will find a list of optional labs that will teach you how to use Docker-Compose locally, as well as how to provision the MedRec application using Docker containers in the Oracle Public Cloud using Oracle Container Cloud Service, as well as Oracle Application Cloud Service.


### Optional Activities 

#### Build the Docker Image and run up the APIs locally using Docker-Compose

- [Build and Run the Dockerised API application](./assets/handsonlabs/buildthedockerimage.md)

Assuming the docker containers are up and running locally, use Swagger or your preferred client to interact with the REST APIs and prove that it all still works.
Note: You will need to find out the IP address of your Web (Node) container in order to point your browser to the SwaggerUI and / or other clients.

#### Running the APIs on the Oracle Container Cloud Service

Instead of running your Docker containers on your laptop, this time you will login to the Oracle Container Cloud Service (OCCS) and create a stack definition for the MedRec APi (web and mongodb tier) as per the following instructions. 
Note: It is assumed you have already created the OCCS Service using your trial account details.

- [Run and test the Node API and Mongo Stack on the Oracle Container Cloud Service](./assets/handsonlabs/createtheoccsstack.md)

#### Try out the Responsive Web App connecting to the Medrec APIs

Following the micro services architecture pattern, we have decoupled the Web application from the server side API's. In this lab we have provided a sample responsive web application developed using a progressive web framework. The app invokes and performs CRUD operations on the Medrec APIs available.

- [Run and test the web app on your local machine](./assets/handsonlabs/medrecui.md)

#### Provision the application and MongoDB using Oracle Cloud Services

Another options to run up the MedRec APIs is to use other Oracle Cloud Services.
In the following labs you will setup Node.js on Oracle PaaS (Application Container Cloud Service - ACCS) and MongoDB on Oracle IaaS (using a Bitnami MongoDB VM template)

- [Under Development - Provision MongoDB VM on Oracle IaaS](./assets/handsonlabs/mongodboniaas.md)
- [Under Development - Create Application on Application Container Cloud Service](./assets/handsonlabs/medrecapisonaccs.md)

#### Interact with Anki Cozmo

Assuming you have an Anki Cozmo robot, you may want to fork the [barackd222/ankimedrec-cozmo]("https://github.com/barackd222/ankimedrec-cozmo") git repository and start to explore your python skills. 
Note: No additional hands on material is available at this stage.

<hr />
<center>
<a href="index" class="btn" >Go Back Home</a>
</center>
<hr />

