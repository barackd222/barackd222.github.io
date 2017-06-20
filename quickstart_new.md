**Anki-MedRec Platform - Quickstart**
===================


# Medrec Microservices Installation 

MedRec is a project that provides multiple APIs around "Medical Records" use cases. The intention is to generate API consumption for Ideas pursuing Innovation. 

MedRec can be forked/cloned from GitHub and installed locally. The idea to allow a local installation, is to give the opportunity to Developers to fork and extend an independent installation of MedRec.

Additionally, MedRec is also available as a managed service (MedRec aaS), so that API consumers can interact with existing APIs, without requiring to install any software. This aims to  allow a quick and easy API consumption for generating new Innovative Ideas.

## Stand-alone Installation: 

There are 3 different ways developer can quickly install a stand-alone verison of MedRec APIs:

1. Manual Installation in Operating System:
2. Docker containers built and run locally:
3. Docker Containers running in the Oracle Public Cloud: 

### 1. Manual Installation in Operating System:

MedRec project is publicly available in Github, please follow the README file to complete the installation. Go to: [Anki-MedRec-APIs](https://github.com/barackd222/ankimedrec-apis)

### 2. Docker containers built and run locally:

MedRec project can be easily built and run locally using Docker containers. MedRec project is publicly available in Github, please follow the README file to complete the installation. Go to: [Anki-MedRec-APIs](https://github.com/barackd222/ankimedrec-apis)


2.1 Install Git if not currently installed. [Click her for more information](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

2.2 Install Docker and Docker-Compose if not currently installed. [Click her for more information](https://docs.docker.com/compose/install/).

2.3 Clone Github repository:
```bash
$ git clone https://github.com/barackd222/ankimedrec-apis.git
$ cd ankimedrec-apis
```
2.4 Configure properties:

Open and edit file `config.json`set:

"RUNNING_MODE":"**docker**",

`Optionally, you might want to modify the default running Port (i.e. PORT 3000) or other properties as well.`

2.5 Build and Run your local Docker Image:
```bash
$ docker-compose build
$ docker-compose up
```


### 3. Docker Containers running in the Oracle Public Cloud:

MedRec project can be easily built and run in the Oracle Public Cloud using Docker containers. You can deploy your own MedRec Images, or use the default one [publicly available in Dockerhub](https://hub.docker.com/r/barackd222/ankimedrec-apis/). In this section we are going to show you how to run your MedRec APIs in Oracle Container Cloud Service.


3.1 If you currently don't have an Oracle Cloud account, go to [cloud.oracle.com/tryit](https://cloud.oracle.com/tryit).

3.2 Provision a new Oracle Container Cloud Service environment. [Click here to see how](https://redthunder.blog/2017/01/16/occs-provisioning/).

3.3 Using OCCS console, create a new Stack. You can copy/paste the yml definition [from here](http://www.oracle.com)

3.4 Using OCCS console, deploy your Stack. [Click here to see how](https://redthunder.blog/2017/02/02/first-experience-using-the-oracle-container-cloud-service/)

3.5 Once deployed, 2 nodes will be green (up and running). Grab the Public IP Address and go to: [http://IP-ADDRESS:3000](http://IP-ADDRESS:3000). You can also SSH into the new Worker Node(s) and shell into the Docker containers.


## MedRec as a Service: 

TBD



<hr />
<a hr
ef="index" class="btn" >Go Back Home</a>
<hr />

