# LabSIM
Health System-Laboratory Sample Inventory Management System


# Challenge:
This application is meant to assist Laboratories in effectively managing their data samples exclusively from the hospital’s overall patient system. This will assist the technicians to redistribute labor based on incoming patient’s disease type and accumulative data can be used for laboratory research to determine epidemic, disease season and disease mutations. The applications aim to assist laboratory technicians to be more effective in their work and give them adequate data effectively organized for their research. This project is dependent on the medical sector more specifically Laboratory technicians.
 
 
# Risks
Technical: the application is dependent on an infrastructure that allows it to be accessible over the internet. If the laboratory is in a remote area or the facility does not have hardware infrastructure such as network cables implemented then accessing the application may be challenging. A solution to resolve this is to recreate the application into a mobile application which will utilize IPS service to access the internet that will load the application for use.
Non-technical: This application is a new tool in the laboratory which will require training on the lab technicians to understand how to effectively use it in their day to day. This might create a pause in the normal operations of the hospital. A way to resolve this is to have self-paced courses online to assist the lab technicians to access the learning materials in their free time while also performing grouped training which will ensure the lab always has a technician in hand to perform lab duties.
 
# Infrastructure
A repository for the project will be made. Additional collaborators will be added during the development phase of the project.
Deployment: the project will undertake both server and cloud deployment strategies. For the prototype, it will undertake a localhost service deployment strategy.
I will populate the application with test data dating back three years from the MoH DHIS
Testing tools will be a java compiler which will assist to detect bugs during development of the application.
 
# Existing Solution
There is already a web application on OpenMRS for the laboratory. However, with this application the only difference with it is that it links up with other hospital services. What my application aims to do is to provide an exclusive application meant for the laboratory which aims to assist them in performing and expounding their roles and research. The reasons as to why I choose to create an exclusive app is because of the Covid-19 experience where in my country there was a lot of debate that samples being shared to news outlets were cumulative and not day by day collected. As such the Covid experience just showed there need to have an effective way to manage samples from labeling to testing. In addition, during the entire experience there was no contribution from the country in regards to research of the disease and I felt that in an all-hands situation testing and research should have been done simultaneously, which if were done some preventive measure could have been discovered…maybe.

# APIs
The types of APIs used will be:

Private APIs: The laboratory deals with sensitive data that must adhere to the patient confidentiality clause thus the need to implement a private API.

Database APIs: this will assist the client side of architecture the ability to communicate with the database enabling data collection, storage and retrieval.

# User Stories

During the 2019 Covid epidemic there was a lot of misconception about how many vials of samples were being collected and how they were being tested. In addition, most of the samples were stated to be repetitive and despite samples being collected the sample size always remained the same. The project aims to address this issue giving laboratory substantial evidence to back up their claim.

A biotechnician stated in his line of work, they use paperwork in the health facility. So, you end up finding sample labeling is done manually and after tests are concluded the sample along with the ID is destroyed for health reasons. In addition, once the lab tests are received they are stored in the patient file. This limits the potential of the laboratory identifying epidemics when they arise while also not being able to identify and locate samples collected. 

A personal experience is when I went to the hospital and asked for a sample but was unable to give it due to my current medical predicament. I was notified to go with the sample bottle and came back to seek medical services when I came back. I never went back. So how can the health facility identify such cases of data collections where a sample bottle with a unique ID just disappeared from the hospital and it is not in the lab. Such cases are ignored but the data provided can assist the hospital in understanding the why and resolving them or even finding alternative ways to sample collection.

