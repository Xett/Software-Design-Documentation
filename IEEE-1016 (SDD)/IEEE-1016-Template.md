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
## 3. Conceptual Model for Software Design Descriptions
This section includes basic *product name* System terms, concepts and context of SDD in which the documentation is prepared. The purpose of conceptual model is to give a better understanding of system terminology and software life cycle that the system resides on. The conceptual model also gives information about stakeholders who will use SDD and how the SDD will be used.

### 3.1 Software Design in Context
*What is the design paradigm of the product?*

*How/What will the product be implemented using?*

*What will the product try to give?* The system will try to give the most accurate result in a most applicable, proper and correct time with its both software and hardware parts; so it can respond to users' wants correctly and quickly. *How else should it correctly respond?* The speed of software part of the system depends on the computational operations according to processor(s) of computer that runs our system.

*What is the planned application of the product?*

### 3.2 Software Design Descriptions Within the Life Cycle
This software will be created following IEEE standards. The primary milestones of this system are requirements analysis, design description analysis, implementation and finally verification and validation.

#### 3.2.1 Influences on SDD Preparation
The very first influence on software desing process is the *product name* SRS document. In SDD, we considered the product perspective, functional/nonfunctional requirements and interface requirements that were included in the SRS. Given specifications and the possible new requests from the stakeholders will specify the design process of this sytem.

#### 3.2.2 Influences on Software Life Cycle Products
*What is the order the product should be designed in?*

*How will changes (such as stakeholder opinions or test) during the design process be implemented into this design?*

Furthermore, the SDD will guide us all the way through the system. According to this document or the first phase some requirements can be added or removed from the software requirements. Consequently, requirements of the stakeholders can be met more precisely after each sprint of our development process.
#### 3.2.3 Design Verification and Design Role in Validation
Verification is the process that we will use to test the *product name* system, to determine whether it meets a set of design specifications. In this process, we will look at the SRS and SDD documents for correctness of specifications. We will control that whether all functional and nonfunctional requirements are correctly implemented according to the requirements of the SRS and SDD documents. Furthermore, we will control that whether the design viewpoints of the final *product name* system are met in the viewpoints part of the SDD document.

Validation is the process that the stakeholders and developers decide if the *product name* system is consistent with the main goal, *which is...*.

After the complete implementation of the system, the testing process will be handled with SDD influenced test plans and cases.

## 4. Design Description Information Content
### 4.1 Introduction
Software design description of the *product name* system analyses how the system will be designed and implemented. This section investigates these according to identification of the SDD, identified design stakeholders and design concerns, related design viewpoints, design views, overlays, rationale and languages. Furthermore, this section includes design elements which are design entities, attributes, relationships and constraints.

### 4.2 SDD Identification
*When will the product be released?* after validation and verification tests.

*Who is allowed to modify the product?*

*Who is allowed to distribute the product?*

Scope, references, context and summary can be found under the section "Overview". Glossary can be found under the section "Definitions, Acronyms and Abbreviations".

### 4.3 Design Stakeholders and their Concerns
*Who are the stakeholders, and what are their concerns?*

*What concerns could be associated with the project?*

### 4.4 Design Views
Design views help deisgn stakeholders about focusing on design details from a specific perspective and meeting relevant requirements. Each identified design concern must be topic of at least one design view so that SDD is complete. Each design concerns identified in the previous subsection the topic of most of the design views in this document; thus, this SDD is completed. For example, concerns about cost are topic of composition view Moreover, concerns about quality of photo are topic of logical view. In this document, context, composition, logical dependency, information, patterns use, interface, interaction and state dynamics views will be explained in section 4.5 as their corresponding viewpoints. For some views, relevant UML diagrams will be shown in order to clarification.

### 4.5 Design Viewpoints
This document describes context, composition, logical, dependency, information patterns use, interface, structure, and interaction and state dynamics viewpoints.

#### 4.5.1 Context Viewpoint
It describes the relationships dependencies and interactions between the system and its environment such as users and other interacting stakeholders. Interactions between the system and its actors are very intense. It includes use case, context and block diagrams showing the system boundary.

#### 4.5.2 Composition Viewpoint
It describes how the design subject splits up into its components and which roles these components have. It can be used in estimating cost, staffing and scheduling duties of development teams. It includes deployment and component diagram.

#### 4.5.3 Logical Viewpoint
It describes class structures, interactions between them and how they are designed and implemented. Also it supports development and reuse of existing logical components. It includes a class diagram which defines objects and classes, and relationships between them.

#### 4.5.4 Dependency Viewpoint
It describes the components of the system and dependencies between these components. It gives information about shared information and order of execution of these components.

#### 4.5.5 Information Viewpoint
It describes data items, data types and classes data stores and access mechanisms. It gives information about data attributes.

#### 4.5.6 Patterns use Viewpoint
It describes design patterns and usage of design patterns which meet design ideas of the project.

#### 4.5.7 Interface Viewpoint
It describes the details of external and internal interfaces. It provides information to the designers, programmers and testers before proceeding with the detailed design of the system. This also provides designers, programmers and testers to use the system as a random user.

#### 4.5.8 Interaction Viewpoint
It describes the sequence of actions and how, why, where and at what level actions occur in the system. It is preferred to use state dynamics views in detailed for this project.

#### 4.5.9 State Dynamics Viewpoint
It describes the internal behaviour of the system. System dynamics include modes, states, transitions and reactions to events. It gives information step by step about the system operation. It includes state machine diagram which defines conditions, states, transitions and relationships between them.

### 4.6 Design Elements
Any item which appears in a design view is named as a design element. It may be one or some of these subcases; design entity, design relationship, design attribute and design constraints. All design elements are defined with subcases under their corresponding viewpoint in section 5 of the software design description.

#### 4.6.1 Design Entities
*Design entities capture key elements of a software design.*

*Each design entity shall have a name (4.6.2.1), a type (4.6.2.2), and purpose (4.6.2.3).*

*Examples of design entities include, but are not limited to, the following: systems, subsystems, libraries, frameworks, abstract collaboration patterns, generic templates, components, classes, data stores, modules, program units, programs, and processes.*

#### 4.6.2 Design Attributes
A design attribute names a characteristic or property of a design element (which may be a design entity design constraint or a design relationship) and provides a statement of fact about that design element.

All design attributes declared by a design viewpoint shall be specified.

*Design attributes can be thought of as questions about design elements. The answers to those questions are the values of the attributes. All the questions can be answered, but the content of the answer will depend upon the nature of the entity. The collection of answers provides a complete description of an entity. Attribute descriptions should include references and design considerations such as tradeoffs and assumptions when appropriate. In some cases, attribute descriptions may have the value none.*

##### 4.6.2.1 Name Attributes
*The name of the element. Each design element shall have an unambiguous reference name. The names for the element may be selected to characterise their nature. This will simplify referencing and tracking in addition to providing identification*

##### 4.6.2.2 Type Attributes
*A description of the kind of element. The type attribute shall describe the nature of the element. It may simply name the kind of element, such as subsystem, component, framework, library, class, subprogram, module, program unit, function, procedure, process, object, persistent object, class or data store. Alternatively, design elements may be grouped into major classes to assist in locating an element dealing with a particular type of information.*

*Within an SDD, the chosen element types shall be applied consistently.*

##### 4.6.2.3 Purpose Attribute
*A description of why the element exists. The purpose attribute shall provide the rationale for the creation of the element.*

##### 4.6.2.4 Author Attribute
*Identification of designer. The author attribute shall identify the designer of the element.*

#### 4.6.3 Design Relationships
*A design relationship names an association or correspondence among two or more design entities. It provides a statement of fact about those design entities.*

*Each design relationship in an SDD shall have a name (4.6.2.1) and a type (4.6.2.2). A design relationship shall identify the design entities participating in the relationship.*

*There are no design relationships defined in this standard. Most design techniques use design relationships extensively. Normally these design relationships will be defined as part of a design viewpoint. For example, structured design methods are built around design relationships including input (datum I is an input to process A), output (datum O is an output of process A) and decompose (process A decompose into processes A1, A2, and A3) relationships. Object-oriented design methods use design relationships including encapsulation, generalisation, specialisation, composition, aggregation, realisation, and instantiation.*

#### 4.6.4 Design Constraints
*A design constraint is an element of a design view that names a rule or restriction imposed by one design element (the source) upon another design element (the target), which may be a design entity, design attribute, or design relationship.*

*Each design constraint in an SDD shall have a name (4.6.2.1) and a type (4.6.2.2). A design constraint shall identify its source and target design entities.*

*There are no design constraints predefined in this standard. Many design techniques introduce design constraints.*

### 4.7 Design Overlays
Design overlay usually used to add information to the existing views. This concept will be explained clearly when necessary in the design viewpoints section which is 5.

### 4.8 Design Rationale
*How is the program designed? Don't go into detail, just explain the higher level concepts.*

### 4.9 Design Languages
In this document Unified Modeling Language (UML) will be used as the modeling language for the diagrams. The modeling language is used for emphasising the static structure and dynamic behaviour of the system.

*Are there any other languages that will be used to explain the design?*

## 5. Design Viewpoints
### 5.1 Introduction
This section provides several main design viewpoints of *product name* with their corresponding design concerns and appropriate design languages. Respectively, context, composition, logical, dependency, information, patterns, interface structure and interaction viewpoints are defined in the following subsections. Short descriptions relating a minimal set of design entities, design relationships design entity attribute, and design constraints are provided for each viewpoint.

### 5.2 Context Viewpoints
The context viewpoints of *product name* show the functions provided by a design subject with reference to an explicit context. The services are the functions, which describes the relationships, dependencies, and interactions between the system and its environment like users and other stakeholders.

#### 5.2.1 Design Concerns
*The purpose of the Context viewpoint is to identify a design subject's offered services, its actors (users and other interacting stakeholders), to establish the system boundary and to effectively delineate the design subject's scope of use and operation.*

*Drawing a boundary separating a design subject from its environment, determining a set of services to be provided, and the information flows between design subject and its environment, is typically a key design decision. That makes this viewpoint applicable to most design efforts.*

*When the system is portrayed as a black box, with internal decisions hidden, the Context view is often a starting point of design, showing what is to be designed functionally as the only available information about the design subject: a name and an associated set of externally identifiable services. Requirements analysis identifies these services with the specification of quality of service attributes, henceforth invoking many non-functional requirements. Frequently incomplete, a Context view is begun in requirements analysis. Work to complete this view continues during design.*

#### 5.2.2 Design Elements
#### 5.2.3 Example Languages
### 5.3 Composition Viewpoint
#### 5.3.1 Design Concerns
#### 5.3.2 Design Elements
##### 5.3.2.1 Function Attribute
##### 5.3.2.2 Subordinates Attribute
#### 5.3.3 Example Languages
### 5.4 Logical Viewpoint
#### 5.4.1 Design Concerns
#### 5.4.2 Design Elements
#### 5.4.3 Example Languages
### 5.5 Dependency Viewpoint
#### 5.5.1 Design Concerns
#### 5.5.2 Design Elements
##### 5.5.2.1 Dependencies Attribute
#### 5.5.3 Example Languages
### 5.6 Information Viewpoint
#### 5.6.1 Design Concerns
#### 5.6.2 Design Elements
##### 5.6.2.1 Data Attribute
#### 5.6.3 Example Languages
### 5.7 Patterns use Viewpoint
#### 5.7.1 Design Concerns
#### 5.7.2 Design Elements
#### 5.7.3 Example Languages
### 5.8 Interface Viewpoint
#### 5.8.1 Design Concerns
#### 5.8.2 Design Elements
##### 5.8.2.1 Interface Attribute
#### 5.8.3 Example Languages
### 5.9 Structure Viewpoint
#### 5.9.1 Design Concerns
#### 5.9.2 Design Elements
#### 5.9.3 Example Languages
### 5.10 Interaction Viewpoint
#### 5.10.1 Design Concerns
#### 5.10.2 Design Elements
#### 5.10.3 Examples
### 5.11 State Dynamics Viewpoints
#### 5.11.1 Design Concerns
#### 5.11.2 Design Elements
#### 5.11.3 Example Languages
### 5.12 Algorithm Viewpoint
#### 5.12.1 Design Concerns
#### 5.12.2 Design Elements
#### 5.12.3 Processing Attribute
#### 5.12.4 Examples
### 5.13 Resource Viewpoint
#### 5.13.1 Design Concerns
#### 5.13.2 Design Elements
##### 5.13.2.1 Resources Attribute
#### 5.13.3 Examples
