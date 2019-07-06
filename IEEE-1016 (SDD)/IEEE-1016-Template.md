# *Template Title*
## 1. Overview
### 1.1 Scope
*The developed product is...*

*How is the developed product used?*

*What is the objective of the developed product?*

Each design concern of the stakeholders are topic of at least one design view and these design views are descried with corresponding design elements and modeled with related UML diagrams. The document is prepared in IEEE 1016-2009 standards.
### 1.2 Purpose
*The purpose of this document is...*

The purpose of this document is to provide a description of the design of the software product to allow for software design to proceed with a perceptive of the design that is to be structured and how the process of it develops. The topics of, general description of design elements and their interactions, how the system will be structured, data & functional structure are to e further discussed in order to help producing test cases, and help in maintenance services, and also satisfy requirements, design details indicated in the SRS document.
### 1.3 Intended Audience
*The intended audience of the software design description is...*

This standard is intended for technical and managerial stakeholders who prepare and use SDDs. It guides a designer in the selection, organisation, and presentation of design information. For an organisation developing its own SDD practices, the use of this standard can help to ensure that design descriptions are complete, concise, consistent, interchangeable, appropriate for recording design experiences and lessons learned, well organised, and easy to communicate.
### 1.4 References
[1] IEEE. IEEE Std 1016-2009 IEEE Standard for Information Technology - System Design - Software Design Descriptions. IEEE Computer Society, 2009

[2] StarUML 5.0 User Guide. (2005). Retrived from http://staruml.sourcefource.net/docs/user-guide%20(en)/toc.html
## 2. Definitions, Acronyms and Abbreviations
All the definitions, acronyms and abbreviations which are used in this document are described in the following table.

| Name | Definition |
| --- | -------- |
| Block Diagram | A diagram showing in schematic form the general arrangement of the parts or components of a complex system or process. |
| Class Diagram | A type of static structure diagram in UML that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among the classes |
| IDE | Integrated Development Environment |
| IEEE Standard | International Electric Electronic Engineering Standards 1016-2009 |
| PC | Personal Computer |
| SDD | Software Design Description |
| SDK | Software Development Kit |
| Sprint | A set of period of time during which specific work has to be completed and made ready for review |
| SRS | Software Requirement Specifications |
| Stakeholders | Any person with an interest in the system who is not a developer of the system |
| StarUML | Design tool of diagrams |
| State Transition Diagram | A type of static structure in UML that describes the transition of the system functions |
| USB | Universal Serial Bus |
| Use Case Diagram | A type of static structure diagram in UML that describes user's interaction with the system |
| User | Person who wants to use the system |
| User Interface | An interface that our system contact with the user of the system. It gets all needed information for its running, from user to our system |
## 3. Conceptual model for software design descriptions
This section includes basic *product name* System terms, concepts and context of SDD in which the documentation is prepared. The purpose of conceptual model is to give a better understanding of system terminology and software life cycle that the system resides on. The conceptual model also gives information about stakeholders who will use SDD and how the SDD will be used.

### 3.1 Software design in context
*What is the design paradigm of the product?*

*How/What will the product be implemented using?*

*What will the product try to give?* The system will try to give the most accurate result in a most applicable, proper and correct time with its both software and hardware parts; so it can respond to users' wants correctly and quickly. *How else should it correctly respond?* The speed of software part of the system depends on the computational operations according to processor(s) of computer that runs our system.

*What is the planned application of the product?*

### 3.2 Software design descriptions within the life cycle
This software will be created following IEEE standards. The primary milestones of this system are requirements analysis, design description analysis, implementation and finally verification and validation.

#### 3.2.1 Influences on SDD preparation
The very first influence on software desing process is the *product name* SRS document. In SDD, we considered the product perspective, functional/nonfunctional requirements and interface requirements that were included in the SRS. Given specifications and the possible new requests from the stakeholders will specify the design process of this sytem.

#### 3.2.2 Influences on software life cycle products
*What is the order the product should be designed in?*

*How will changes (such as stakeholder opinions or test) during the design process be implemented into this design?*

Furthermore, the SDD will guide us all the way through the system. According to this document or the first phase some requirements can be added or removed from the software requirements. Consequently, requirements of the stakeholders can be met more precisely after each sprint of our development process.
#### 3.2.3 Design verification and design role in validation
Verification is the process that we will use to test the *product name* system, to determine whether it meets a set of design specifications. In this process, we will look at the SRS and SDD documents for correctness of specifications. We will control that whether all functional and nonfunctional requirements are correctly implemented according to the requirements of the SRS and SDD documents. Furthermore, we will control that whether the design viewpoints of the final *product name* system are met in the viewpoints part of the SDD document.

Validation is the process that the stakeholders and developers decide if the *product name* system is consistent with the main goal, *which is...*.

After the complete implementation of the system, the testing process will be handled with SDD influenced test plans and cases.

## 4. Design description information content
### 4.1 Introduction
Software design description of the *product name* system analyses how the system will be designed and implemented. This section investigates these according to identification of the SDD, identified design stakeholders and design concerns, related design viewpoints, design views, overlays, rationale and languages. Furthermore, this section includes design elements which are design entities, attributes, relationships and constraints.

### 4.2 SDD identification
*When will the product be released?* after validation and verification tests.

*Who is allowed to modify the product?*

*Who is allowed to distribute the product?*

Scope, references, context and summary can be found under the section "Overview". Glossary can be found under the section "Definitions, Acronyms and Abbreviations".

### 4.3 Design stakeholders and their concerns
*Who are the stakeholders, and what are their concerns?*

*What concerns could be associated with the project?*

### 4.4 Design views
Design views help deisgn stakeholders about focusing on design details from a specific perspective and meeting relevant requirements. Each identified design concern must be topic of at least one design view so that SDD is complete. Each design concerns identified in the previous subsection the topic of most of the design views in this document; thus, this SDD is completed. For example, concerns about cost are topic of composition view Moreover, concerns about quality of photo are topic of logical view. In this document, context, composition, logical dependency, information, patterns use, interface, interaction and state dynamics views will be explained in section 4.5 as their corresponding viewpoints. For some views, relevant UML diagrams will be shown in order to clarification.

### 4.5 Design viewpoints
This document describes context, composition, logical, dependency, information patterns use, interface, structure, and interaction and state dynamics viewpoints.

#### 4.5.1 Context Viewpoint
It describes the relationships dependencies and interactions between the system and its environment such as users and other interacting stakeholders. Interactions between the system and its actors are very intense. It includes use case, context and block diagrams showing the system boundary.

#### 4.5.2 Composition viewpoint
It describes how the design subject splits up into its components and which roles these components have. It can be used in estimating cost, staffing and scheduling duties of development teams. It includes deployment and component diagram.
### 4.6 Design elements
#### 4.6.1 Design entities
#### 4.6.2 Design attributes
##### 4.6.2.1 Name attributes
##### 4.6.2.2 Type attributes
##### 4.6.2.3 Purpose attribute
##### 4.6.2.4 Author attribute
#### 4.6.3 Design relationships
#### 4.6.4 Design constraints
### 4.7 Design overlays
### 4.8 Design rationale
### 4.9 Design languages
## 5. Design viewpoints
### 5.1 Introduction
### 5.2 Context viewpoints
#### 5.2.1 Design concerns
#### 5.2.2 Design elements
#### 5.2.3 Example languages
### 5.3 Composition viewpoint
#### 5.3.1 Design concerns
#### 5.3.2 Design elements
##### 5.3.2.1 Function attribute
##### 5.3.2.2 Subordinates attribute
#### 5.3.3 Example languages
### 5.4 Logical viewpoint
#### 5.4.1 Design concerns
#### 5.4.2 Design elements
#### 5.4.3 Example languages
### 5.5 Dependency viewpoint
#### 5.5.1 Design concerns
#### 5.5.2 Design elements
##### 5.5.2.1 Dependencies attribute
#### 5.5.3 Example languages
### 5.6 Information viewpoint
#### 5.6.1 Design concerns
#### 5.6.2 Design elements
##### 5.6.2.1 Data attribute
#### 5.6.3 Example languages
### 5.7 Patterns use viewpoint
#### 5.7.1 Design concerns
#### 5.7.2 Design elements
#### 5.7.3 Example languages
### 5.8 Interface viewpoint
#### 5.8.1 Design concerns
#### 5.8.2 Design elements
##### 5.8.2.1 Interface attribute
#### 5.8.3 Example languages
### 5.9 Structure viewpoint
#### 5.9.1 Design concerns
#### 5.9.2 Design elements
#### 5.9.3 Example languages
### 5.10 Interaction viewpoint
#### 5.10.1 Design concerns
#### 5.10.2 Design elements
#### 5.10.3 Examples
### 5.11 State dynamics viewpoints
#### 5.11.1 Design concerns
#### 5.11.2 Design elements
#### 5.11.3 Example languages
### 5.12 Algorithm viewpoint
#### 5.12.1 Design concerns
#### 5.12.2 Design elements
#### 5.12.3 Processing attribute
#### 5.12.4 Examples
### 5.13 Resource viewpoint
#### 5.13.1 Design concerns
#### 5.13.2 Design elements
##### 5.13.2.1 Resources attribute
#### 5.13.3 Examples
