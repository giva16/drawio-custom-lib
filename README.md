# SoaML Extension for Diagrams.net

## 1- Introduction

### 1.1 - What is SoaML?

Service Oriented Architecture Modeling Language (SoaML) is a modeling language that enables us to architect and model Services Oriented Architecture (SOA) systems.
SoaML extends the Unified Modeling Language (UML) profile to provide the modeling capabilities to describe how people, organizations, and different components of a system provide and use services in order to achieve a common business goal within a community, or a distributed computing environment. The SoaML specification is created and maintained by the <a href="https://www.omg.org/">Object Management Group (OMG)</a>.Furthermore,

### 1.2 - What is the SoaML Extension for Diagrams.net?

This extension is simply a collection of SoaML libraries that enables the user to draw SoaML diagrams within the <a>diagrams.net</a> web application and the <a>draw.io</a> desktop App created by JGraph Ltd. All syntax and semantics of the SoaML diagrams within this extension are based on the <a href="http://www.omg.org/spec/SoaML/">OMG SoaML specification</a>. The extension was developed as part of my bachelor's thesis at the Vrije Universiteit Amsterdam and is specifically designed to provide students of the <a href="https://studiegids.vu.nl/EN/courses/2022-2023/X_405061#/">Service Oriented Design course</a> run by <a href="https://research.vu.nl/en/persons/patricia-lago">prof. dr. Patricia Lago</a> at the Vrije Universiteit Amsterdam, with a lightweight open-source tool to draw SoaML diagrams for their course assignments. However, this extension is open for use and modification by anyone who is interested in modeling SOA systems.

### 1.3 - What are the SoaML Libraries?

This extension provides the user with a colleciton of 5 SoaML libraries, with each library containing the elements for a specific SoaML diagram. The four libraries are:

1. **SoaML-Interface:** For drawing Simple Interface and Service Interface Diagrams.
2. **SoaML-Participant:** For drawing Participant Diagrams.
3. **SoaML-ServiceContract:** For drawing Service Contract Diagrams.
4. **SoaML-ServicesArchitecture:** For drawing Services Architecture Diagrams.
5. **SoaML-Templates:** Examples of the afformentioned diagrams.

These libraries provide the user with the ability to describe SOA systems from different prespectives that enable the user to understand how different components of a SOA System interact with one another to achieve a business goal.

### 1.4 What to expect from the Tutorials?

The tutorials are designed to provide the user with a step-by-step guide on how to draw SoaML diagrams using the SoaML libraries. The tutorials are divided into two parts:

1. **Setting Up the SoaML Extension for Diagrams.net:**

   This part of the tutorial will guide the user on how to set up the SoaML libraries in the <a>diagrams.net</a> web application and the <a>draw.io</a> desktop App.

2. **Drawing SoaML Diagrams:**

   This part of the tutorial will guide the user on how to draw SoaML diagrams using the SoaML libraries. Part 2 of the tutorial will guide the user on how to draw the SoaML diagrams mentioned in section 1.3. The tutorials will also provide the user with a brief explanation of the syntax and semantics of each SoaML diagram, based on the <a>OMG SoaML specification</a>. Moreover, the SoaML diagrams drawn in the tutorial will use examples included in the <a>OMG SoaML specification</a> which involves a Service Network involving 3 "B2B" services comprising of a purchasing service, a shipping service, and a ship status service. **Video tutorials** will on drawing the Service Contract Diagram and the Services Architecture Diagram will also be provided, using the "CityCar2Go" B2B Service Network and its components as an example. The "CityCar2Go" B2B Service Network is an example taken from the "Service Oriented Design" course at the Vrije Universiteit Amsterdam.

Throughout the tutorials, GIF animations will be used to provide the user with additional visual guidance on how to setup the SoaML extension and draw SoaML diagrams using the SoaML libraries.<br>**Note:** the GIF animations in full screen by clicking will provide a better quality viewing experience.

## 2 - Setting Up the SoaML Extension for Diagrams.net

### **Method 1 (Recommended): Directly importing the libraries package from the Github Repository to diagrams.net:**

#### To import the libraries package directly from the Github Repository to diagrams.net simply click on this <a href="https://app.diagrams.net/?splash=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-General.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Interface.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Participant.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServicesArchitecture.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServiceContract.xml">link</a>

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

# 1 - Table of Notations

## 1.1 - Services Architecture Diagram Notations

| Notation                                                                                                       | Name                      | Description                                                                                                                                                                                 |
| -------------------------------------------------------------------------------------------------------------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="Images/Notations/Services Architecture/SA.png" alt="Service Interface" width="200"/>                 | Services Architecture     | ServicesArchitecture describes how a network of participants work together by providing and consuming services to fulfill a purpose. Where each services are expressed as service contracts |
| <img src="Images/Notations/Services Architecture/SC.png" alt="Interface with Consumer Interface" width="200"/> | Internal Service Contract | Service Contract gives a description of how participants should interact in order to enact a service                                                                                        |
| <img src="Images/Notations/Services Architecture/PI.png" alt="Service Interface" width="200"/>                 | Internal Participant      | Internal role within a services architecture, where the role of a participant is typed by the interface that they implement                                                                 |
| <img src="Images/Notations/Services Architecture/PE.png" alt="Service Interface" width="200"/>                 | External Participant      | External role that is involved in the services architecture. Role of participant is typed by the interface that they implement                                                              |
| <img src="Images/Notations/Services Architecture/role-binding.PNG" alt="Service Interface" width="200"/>       | Role Binding              | A role binding attaches a participant with a compatible interface to the service contract within the architecture. Giving the participant its role within the Services Architecture         |

## 1.2 - Service Interface / Simple Interface Diagram Notations

| Notation                                                                                                           | Name                                     | Description |
| ------------------------------------------------------------------------------------------------------------------ | :--------------------------------------- | :---------- |
| <img src="Images/Notations/Interface/service-interface.png" alt="Service Interface" width="200"/>                  | Service Interface                        |             |
| <img src="Images/Notations/Interface/simple-interface-c.png" alt="Service Interface" width="200"/>                 | Simple Interface with Required Interface |             |
| <img src="Images/Notations/Interface/simple-interface-p.png" alt="Service Interface" width="200"/>                 | Simple Interface with Provided Interface |             |
| <img src="Images/Notations/Interface/si-interface-cport.png" alt="Interface with Consumer Interface" width="200"/> | Consumer Interface                       |             |
| <img src="Images/Notations/Interface/si-interface-pport.png" alt="Service Interface" width="200"/>                 | Provider Interface                       |             |
| <img src="Images/Notations/Interface/si-participant-cinterface.png" alt="Service Interface" width="200"/>          | Participant with Required Interface      |             |
| <img src="Images/Notations/Interface/si-participant-pinterface.png" alt="Service Interface" width="200"/>          | Participant with Provided Interface      |             |
| <img src="Images/Notations/Interface/si-participant-nointerface.png" alt="Service Interface" width="200"/>         | Participant                              |             |
| <img src="Images/Notations/service-channel.png" alt="Service Interface" width="200"/>                              | Service Channel                          |             |
| <img src="Images/Notations/Interface/realization.png" alt="Service Interface" width="200"/>                        | Realization                              |             |
| <img src="Images/Notations/Interface/usage.png" alt="Service Interface" width="200"/>                              | Usage                                    |             |
| <img src="Images/Notations/Interface/si-signal.png" alt="Service Interface" width="200"/>                          | Signal                                   |             |
| <img src="Images/Notations/Interface/op-public.png" alt="Service Interface" width="200"/>                          | Operation                                |             |

## 1.3 - Service Contract Diagram Notations

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

## 1.4 - Participant Diagram Notations

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

## 1.5 - Miscellaneous Notations

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

## References

[1]
[2]
[3]
