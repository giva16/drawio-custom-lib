# SoaML Extension to Diagrams.net

## Click<a href="https://app.diagrams.net/?splash=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-General.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Interface.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-Participant.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServicesArchitecture.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgiva16%2Fdrawio-custom-lib%2Fmain%2FSOAML%2520Library%2FSoaML-ServiceContract.xml"> here</a> to load the SoaML Diagrams to diagrams.net

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
