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
- Register as a developer to get an API Key by clinking the following link.
<a href="https://apidevelopers-gse00011671.apaas.us2.oraclecloud.com/" target="_blank">Register As A Developer</a>
- [Explore the Secured APIs with your API Key using Swagger](./assets/handsonlabs/exploretheapis-5.md)
- [Explore the Secured APIs with your API Key using Postman](./assets/handsonlabs/exploretheapis-6.md)
- [Explore the Secured APIs with your API Key using an online Python Service](./assets/handsonlabs/exploretheapis-4.md)

### Optional Activities 

#### Build the Docker Image and run up the APIs locally using Docker-Compose

- [Build and Run the Dockerised API application](./assets/handsonlabs/buildthedockerimage.md)

Assuming the docker containers are up and running locally, use Swagger or your preferred client to interact with the REST APIs and prove that it all still works.
Note: You will need to find out the IP address of your Web (Node) container in order to point your browser to the SwaggerUI and / or other clients.

#### Running the APIs on the Oracle Container Cloud Service

Instead of running your Docker containers on your laptop, this time you will login to the Oracle Container Cloud Service (OCCS) and create a stack definition for the MedRec APi (web and mongodb tier) as per the following instructions. 
Note: It is assumed you have already created the OCCS Service using your trial account details.

- [Run and test the Node API and Mongo Stack on the Oracle Container Cloud Service](./assets/handsonlabs/createtheoccsstack.md)

#### Try out the Application User Interface developed in Vue.js

- [TBC - Clone and Run the Vue User Interface to connect to the APIs](./assets/handsonlabs/medrecui.md)

#### Provision the application and MongoDB using Oracle Cloud Services

Setup Node.js/MongoDB on Oracle IaaS and PaaS (ACCS)
- [TBC - Provision MongoDB VM on Oracle IaaS](./assets/handsonlabs/mongodboniaas.md)
- [TBC - Create Application on Application Container Cloud Service](./assets/handsonlabs/medrecapisonaccs.md)

#### Interact with Anki Cozmo

Assuming you have an Anki Cozmo robot, you may want to fork the barackd222/ankimedrec-cozmo git repository and start to play. No additional hands on material is available at this stage.

<hr />
<center>
<a href="index" class="btn" >Go Back Home</a>
</center>
<hr />

