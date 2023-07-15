<h1 style="text-align: center;"> SoaML Extension for Diagrams.net </h1>

# About

This extension is a collection of SoaML libraries that enables the user to draw SoaML diagrams within the <a>diagrams.net</a> web application and the <a>draw.io</a> desktop App created by <a>JGraph Ltd</a>. The diagrams in each library are based on the <a href="http://www.omg.org/spec/SoaML/">OMG SoaML specification</a>.

The SoaML extension for diagramas.net was developed as part of my bachelor's thesis at the Vrije Universiteit Amsterdam and is specifically designed to provide students of the <a href="https://studiegids.vu.nl/EN/courses/2022-2023/X_405061#/">Service Oriented Design</a> course taught by <a href="https://research.vu.nl/en/persons/patricia-lago">prof. dr. Patricia Lago</a> as part of the <a href="https://vu.nl/en/education/master/computer-science/curriculum?year=1st-year&specialization=software-engineering-and-green-it">Software Engineering and Green IT</a> track for the Master's in Computer Science at Vrije Universiteit Amsterdam with a lightweight open-source tool to draw SoaML diagrams for their course assignments. However, this extension is also open for use and modification by anyone who is interested in modeling SOA systems using the SoaML notations provided.

This extension provides the user with a colleciton of 5 SoaML libraries, with each library containing the elements for a specific SoaML diagram.

The 5 libraries are:

1. **SoaML-Interface:** For drawing Simple Interface and Service Interface Diagrams.
2. **SoaML-Participant:** For drawing Participant Diagrams.
3. **SoaML-ServiceContract:** For drawing Service Contract Diagrams.
4. **SoaML-ServicesArchitecture:** For drawing Services Architecture Diagrams.
5. **SoaML-Templates:** Examples of the aforementioned diagrams.

These libraries provide the user with the ability to specify services from different points of view, enabling the user to understand how different components provide and use services as well as how they interact with one another within a Services Oriented Architecture (SOA) system in order to to achieve a business goal.

# Table of Contents

- [What is SoaML?](#what-is-soaml)

- [Setting Up the SoaML Extension for Diagrams.net](#setting-up-the-soaml-extension-for-diagramsnet)

- [Drawing SoaML Diagrams in Diagrams.net](#drawing-soaml-diagrams-in-diagramsnet)

  - [What to expect from this tutorial?](#what-to-expect-from-this-tutorial)

  - [Drawing Service Interface Diagrams](#drawing-service-interface-diagrams)

  - [Drawing Participant Diagrams](#drawing-participant-diagrams)

  - [Drawing Service Contract Diagrams](#drawing-service-contract-diagrams)

  - [Drawing Services Architecture Diagrams](#drawing-services-architecture-diagrams)

- [Summary of Notations](#summary-of-notations)

# What is SoaML?

Service Oriented Architecture Modeling Language (SoaML) is a tool specified and maintained by the <a href="https://www.omg.org/">Object Management Group (OMG)</a> that enables us to model services through the use of modified Unified Modeling Language (UML) notations. In order to fully understand the purpose of SoaML let us be reminded of what goes on in a Service Oriented Architecture (SOA) System. In SOA systems, participants exist in a community, or a distributed computing environment and they use and provide services in order to achieve a common goal which are usually tied to a business process. Participants can be defined as people, organizations, or different components of a system. A service is defined as a value that is exchanged. In order for participants to provide or use services, they must play the role of a service provider or a service consumer.

SoaML extends the UML profile to enable the specification of services in three possible approaches as described by the OMG SoaML Specification: The Simple Interface Approach, Service Interface Approach, and Service Contract Approach. Additionally, SoaML allows us to model a service network through the use of the Services Architecture diagram in order to describe how each participants collaborate as a community within a SOA system.

# Setting Up the SoaML Extension for Diagrams.net

### **Method 1 (Recommended): Directly importing the libraries package from the Github Repository to diagrams.net:**

**To import the libraries package directly from the Github Repository to diagrams.net simply click on this <a href="https://app.diagrams.net/?splash=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-General.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Interface.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Participant.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServicesArchitecture.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServiceContract.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Templates.xml">link</a>**, this link will directly import the libraries from the github repository to the diagrams.net web application's library manager. The libraries will be stored in the local storage of your web-browser.

<img src="Images/Tutorial Images/Setting Up Library/1.gif">

**To Update the libraries:** Close the libraries in diagrams.net and click on this link again. This will update the libraries in the local storage of your web-browser.

<img src="Images/Tutorial Images/Setting Up Library/2.gif">

**\*Note:** _This method does not allow the user to modify the libraries and templates and is not available for the offline diagrams.net desktop application._

### **Method 2 (Allows User to Modify Libraries and Templates): Downloading the repository and importing the libraries package to diagrams.net/draw.io desktop:**

1. Click on the link download the library package: <button><a href="https://download-directory.github.io?url=https://github.com/giva16/drawio-custom-lib/tree/main/SOAML%20Library" download>Download Library Package</a></button>

2. Extract the zip file to a folder of your choice.

3. Open the <a href="https://app.diagrams.net/">diagrams.net</a> web application or the draw.io desktop App.

4. Create a new blank diagram by clicking "Create New Diagram" > Select "Blank Diagram" > Click "Create".
   <img src="Images/Tutorial Images/Setting Up Library/3.gif">
5. Give your new diagram a name on the top left corner of the editor.
   <img src="Images/Tutorial Images/Setting Up Library/4.gif">

6.1 **To Load the library one by one** Click on "File" > "Open Library From" > "Device..." > Open the "SOAML Library" folder that you extracted in step 2 > Select the XML file of the library you want to load > Click "Open".

6.2 **To Load multiple or all libraries at once** Open the "SOAML Library" folder that you extracted in step 2 > Select all the XML files of the libraries you want to load > Drag and drop the selected files into the editor.
<img src="Images/Tutorial Images/Setting Up Library/5.gif">

7. You can now view all the SoaML elements in the library panel on the left side of the editor and you have everything you need to start drawing SoaML diagrams.

   <img src="Images/Tutorial Images/Setting Up Library/6.png">

   **Happy Drawing!**

# Drawing SoaML Diagrams in diagrams.net

## What to expect from this Tutorial?

This tutorial will guide the user on how to draw SoaML diagrams using the SoaML libraries provided by this extension. The tutorials will guide the user on how to draw the Service Interface Diagram, Participant Diagram, Service Contract Diagram, and Services Architecture Diagram. Each of the diagrams shown in this tutorial are derived from examples shown in the (2022-2023) edition of the Service Oriented Design (SOD) course at Vrije Universiteit Amsterdam, involving a "CityCar2Go" B2B (Business to Business) Service Network and the participants and services that are involved in the network.

### The tutorials are divided into four sections:

1. How to draw a Service Interface Diagram

2. How to draw a Participant Diagram

3. How to draw a Service Contract Diagram (Video Tutorial Included for the SOD Course)

4. How to draw a Services Architecture Diagram (Video Tutorial Included for the SOD Course)

### Each section will have a similar structure providing the following information in order:

1. Information about the diagram, detailing what the diagram is used for and what it represents.

2. Table of notations involved involved in the drawing of the diagram, detailing the element of that each of the notation represent and what it defines.

3. Step-by-step guide on how to draw the diagram in diagrams.net/draw.io desktop application.

Throughout the tutorials, GIF animations will be used to provide the user with additional visual guidance on how to setup the SoaML extension and draw SoaML diagrams using the SoaML libraries.

**Note:** viewing the GIF animations in full screen by clicking will provide a better quality viewing experience.

## Drawing Service Interface Diagrams

### What is a Service Interface Diagram?

To understand what the SoaML Service Interface Diagram is about, let us be reminded that for a service provider to provide a service to a service consumer, the service provider must implement an interface for the consumer to establish a communication channel with the service provider. For a connection to be established between a service provider and a service consumer, the service provider must define the messages (signals and operations) that it can receive from the consumer by implementing a provided interface for the consumer and define the messages that it expects to be able to send back to the consumer (callbacks in a bi-directional interface) by specifying the provided interface that the consumer is to implement (modeled as a required interface from the perspective of the service provider).

The SoaML Service Interface Diagram specifies the interface that the service provider offers to provide the service logic that it owns to the service consumer and the interface that it expects the consumer to implement to receive callbacks from the provider; this defines a service with a bi-directional protocol. However, the SoaML Service Interface Diagram also allows for modeling a uni-directional interface known as a Simple Interface. In a Simple Interface Diagram, the service provider only specifies its interface to the consumer. It does not perform any callbacks to the consumer, defining a service with a uni-directional protocol.

Additionally, the Service Interface Diagram defines the roles that each participant involved within the service takes. In a bi-directional service, one participant may take the role of a service provider, thus implementing the specified provided interface in its service port. On the other hand, one participant may take the role of a service consumer, thus implementing the specified required interface in its service port.

### SoaML Service Interface Diagram Notations

| Notation                                                                                                           | Name               | Description |
| ------------------------------------------------------------------------------------------------------------------ | :----------------- | :---------- |
| <img src="Images/Notations/Interface/service-interface.png" alt="Service Interface" width="200"/>                  | Service Interface  |             |
| <img src="Images/Notations/Interface/si-interface-cport.png" alt="Interface with Consumer Interface" width="200"/> | Required Interface |             |
| <img src="Images/Notations/Interface/si-interface-pport.png" alt="Provided Interface" width="200"/>                | Provided Interface |             |
| <img src="Images/Notations/Interface/si-participant-cinterface.png" alt="Consumer Role" width="200"/>              | Consumer Role      |             |
| <img src="Images/Notations/Interface/si-participant-pinterface.png" alt="Provider Role " width="200"/>             | Provider Role      |             |
| <img src="Images/Notations/Interface/si-participant-nointerface.png" alt="Participant Role" width="200"/>          | Participant Role   |             |
| <img src="Images/Notations/Interface/service-channel.png" alt="Service Channel " width="200"/>                     | Service Channel    |             |
| <img src="Images/Notations/Interface/realization.png" alt="Realization" width="200"/>                              | Realization        |             |
| <img src="Images/Notations/Interface/usage.png" alt="Usage" width="200"/>                                          | Usage              |             |
| <img src="Images/Notations/Interface/si-signal.png" alt="Signal" width="200"/>                                     | Signal             |             |

### How to draw a Service Interface Diagram in diagrams.net

# Summary of Notations

## Services Architecture Diagram Notations

| Notation                                                                                                       | Name                      | Description                                                                                                                                                                                 |
| -------------------------------------------------------------------------------------------------------------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="Images/Notations/Services Architecture/SA.png" alt="Service Interface" width="200"/>                 | Services Architecture     | ServicesArchitecture describes how a network of participants work together by providing and consuming services to fulfill a purpose. Where each services are expressed as service contracts |
| <img src="Images/Notations/Services Architecture/SC.png" alt="Interface with Consumer Interface" width="200"/> | Internal Service Contract | Service Contract gives a description of how participants should interact in order to enact a service                                                                                        |
| <img src="Images/Notations/Services Architecture/PI.png" alt="Service Interface" width="200"/>                 | Internal Participant      | Internal role within a services architecture, where the role of a participant is typed by the interface that they implement                                                                 |
| <img src="Images/Notations/Services Architecture/PE.png" alt="Service Interface" width="200"/>                 | External Participant      | External role that is involved in the services architecture. Role of participant is typed by the interface that they implement                                                              |
| <img src="Images/Notations/Services Architecture/role-binding.PNG" alt="Service Interface" width="200"/>       | Role Binding              | A role binding attaches a participant with a compatible interface to the service contract within the architecture. Giving the participant its role within the Services Architecture         |

# 1.3 - Service Contract Diagram Notations

| Notation                                                                                                           |     Name      | Description |
| ------------------------------------------------------------------------------------------------------------------ | :-----------: | ----------- |
| <img src="Images/Notations/Interface/service-interface.png" alt="Service Interface" width="200"/>                  | left-aligned  |             |
| <img src="Images/Notations/Interface/si-interface-cport.png" alt="Interface with Consumer Interface" width="200"/> |   centered    |             |
| <img src="Images/Notations/Interface/si-interface-pport.png" alt="Service Interface" width="200"/>                 | right-aligned |             |
| <img src="Images/Notations/Interface/simple-interface-c.png" alt="Service Interface" width="200"/>                 | left-aligned  |             |
| <img src="Images/Notations/Interface/simple-interface-p.png" alt="Service Interface" width="200"/>                 |   centered    |             |
| <img src="Images/Notations/Interface/si-participant-cinterface.png" alt="Service Interface" width="200"/>          | right-aligned |             |
| <img src="Images/Notations/Interface/si-participant-pinterface.png" alt="Service Interface" width="200"/>          | left-aligned  |             |
| <img src="Images/Notations/Interface/si-participant-nointerface.png" alt="Service Interface" width="200"/>         |   centered    |             |
| <img src="Images/Notations/service-channel.png" alt="Service Interface" width="200"/>                              | right-aligned |             |
| <img src="Images/Notations/Interface/realization.png" alt="Service Interface" width="200"/>                        | right-aligned |             |
| <img src="Images/Notations/Interface/usage.png" alt="Service Interface" width="200"/>                              | left-aligned  |             |
| <img src="Images/Notations/Interface/si-signal.png" alt="Service Interface" width="200"/>                          |   centered    |             |
| <img src="Images/Notations/Interface/op-public.png" alt="Service Interface" width="200"/>                          | right-aligned |             |

# 1.4 - Participant Diagram Notations

| Notation                                                                                                           |     Name      | Description |
| ------------------------------------------------------------------------------------------------------------------ | :-----------: | ----------- |
| <img src="Images/Notations/Interface/service-interface.png" alt="Service Interface" width="200"/>                  | left-aligned  |             |
| <img src="Images/Notations/Interface/si-interface-cport.png" alt="Interface with Consumer Interface" width="200"/> |   centered    |             |
| <img src="Images/Notations/Interface/si-interface-pport.png" alt="Service Interface" width="200"/>                 | right-aligned |             |
| <img src="Images/Notations/Interface/simple-interface-c.png" alt="Service Interface" width="200"/>                 | left-aligned  |             |
| <img src="Images/Notations/Interface/simple-interface-p.png" alt="Service Interface" width="200"/>                 |   centered    |             |
| <img src="Images/Notations/Interface/si-participant-cinterface.png" alt="Service Interface" width="200"/>          | right-aligned |             |
| <img src="Images/Notations/Interface/si-participant-pinterface.png" alt="Service Interface" width="200"/>          | left-aligned  |             |
| <img src="Images/Notations/Interface/si-participant-nointerface.png" alt="Service Interface" width="200"/>         |   centered    |             |
| <img src="Images/Notations/service-channel.png" alt="Service Interface" width="200"/>                              | right-aligned |             |
| <img src="Images/Notations/Interface/realization.png" alt="Service Interface" width="200"/>                        | right-aligned |             |
| <img src="Images/Notations/Interface/usage.png" alt="Service Interface" width="200"/>                              | left-aligned  |             |
| <img src="Images/Notations/Interface/si-signal.png" alt="Service Interface" width="200"/>                          |   centered    |             |
| <img src="Images/Notations/Interface/op-public.png" alt="Service Interface" width="200"/>                          | right-aligned |             |

# 1.5 - Miscellaneous Notations

| Notation                                                                                                           |     Name      | Description |
| ------------------------------------------------------------------------------------------------------------------ | :-----------: | ----------- |
| <img src="Images/Notations/Interface/service-interface.png" alt="Service Interface" width="200"/>                  | left-aligned  |             |
| <img src="Images/Notations/Interface/si-interface-cport.png" alt="Interface with Consumer Interface" width="200"/> |   centered    |             |
| <img src="Images/Notations/Interface/si-interface-pport.png" alt="Service Interface" width="200"/>                 | right-aligned |             |
| <img src="Images/Notations/Interface/simple-interface-c.png" alt="Service Interface" width="200"/>                 | left-aligned  |             |
| <img src="Images/Notations/Interface/simple-interface-p.png" alt="Service Interface" width="200"/>                 |   centered    |             |
| <img src="Images/Notations/Interface/si-participant-cinterface.png" alt="Service Interface" width="200"/>          | right-aligned |             |
| <img src="Images/Notations/Interface/si-participant-pinterface.png" alt="Service Interface" width="200"/>          | left-aligned  |             |
| <img src="Images/Notations/Interface/si-participant-nointerface.png" alt="Service Interface" width="200"/>         |   centered    |             |
| <img src="Images/Notations/service-channel.png" alt="Service Interface" width="200"/>                              | right-aligned |             |
| <img src="Images/Notations/Interface/realization.png" alt="Service Interface" width="200"/>                        | right-aligned |             |
| <img src="Images/Notations/Interface/usage.png" alt="Service Interface" width="200"/>                              | left-aligned  |             |
| <img src="Images/Notations/Interface/si-signal.png" alt="Service Interface" width="200"/>                          |   centered    |             |
| <img src="Images/Notations/Interface/op-public.png" alt="Service Interface" width="200"/>                          | right-aligned |             |
