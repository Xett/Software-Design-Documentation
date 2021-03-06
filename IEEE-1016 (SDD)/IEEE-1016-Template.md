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
*Design entities: actors--external active elements interacting with the design subject, including users, other stakeholders and external systems, or other items; services--also called use cases; and directed information flows between the design subject, treated as a black box, and its actors associating actors with services. Flows capture the expected information content exchanged.*

*Design relationships: receive output and provide input (between actors and the design subject).*

*Design constraints: qualities of service; form and medium of interaction (provided to and received from) with environment.*

#### 5.2.3 Example Languages
*Any black-box type diagrams can be used to realise the Context viewpoint. Appropriate languages include Structured Analyys [e.g., IDEF0 (IEEE Std 1320.1-1998 [B18]), Structured Analysis and Design Technique (SADT)(Ross [B32]) or those of the Dearco of Gane-Sarson variety], the Cleanroom's black box diagrams, and UML use cases (OMG [B28]).*

### 5.3 Composition Viewpoint
*The Composition viewpoint describes the way the design subject is (recursively) structured into constituent parts and establishes the roles of those parts.*

#### 5.3.1 Design Concerns
*Software developers and maintainers use this viewpoint to identify the major design constituents of the design subject, to localise and allocate functionality, responsibilities, or other design roles to these constituents. In maintenance, it can be used to conduct impact analysis and localise the efforts of making changes. Reuse, on the level of existing subsystems and large-grained components, can be addressed as well. The information in a Composition view can be used by acquisition management and in project management for specification and assignment of work packages, and for planning, monitoring and control of a software project. This information, together with other project information, can be sued in estimating cost staffing, and schedule for the development effort. Configuration management may use the information to establish the organisation, tracking, and change management of emerging work products (see IEEE Std 12207-2008 [B21]).*

#### 5.3.2 Design Elements
*Design entities: types of constituents of a system: subsystems, components, modules; ports and (provided and required) interfaces; also libraries, frameworks, software repositories, catalogs, and templates.*

*Design relationships: composition, use, and generalisation. The Composition viewpoint supports the recording of the part-whole relationships between design entities using realisation, dependency, aggregation, composition, and generalisation relationships. Additional design relationships are required and provided (interfaces), and the attachment of ports to components.*

*Design attributes: For each design entity, the viewpoint provides a reference to a detailed description via the identification attribute. The attribute descriptions for identification, type, purpose, function, and definition attribute should be utilised.*

##### 5.3.2.1 Function Attribute
*A statement of what the entity does. The function attribute states the transformation applied by the entity to its inputs to produce the output. In the case of a data entity, this attribute states the type of information stored or transmitted by the entity.*

##### 5.3.2.2 Subordinates Attribute
*The identification of all entities composing this entity. The subordinates attribute identifies the "composed of" relationship for an entity. This information is used to trace requirements to design entities and to identify parent/child structural relationships through a design subject.*

#### 5.3.3 Example Languages
*UML component diagrams (see OMG [B28]) cover this viewpoint. The simplest graphical technique used to describe functional system decomposition is a hierarchical decomposition diagram; such diagram can be used together with natural language descriptions of purpose and function for each entity, such as is provided by IDEF0 (IEEE Std 1320.1-1998 [B18]), the Structure Chart (Yourdon and Constantine [B38]), and the HIPO Diagram. Run-time composition can also use structured diagrams (Page-Jones [B29]).*

### 5.4 Logical Viewpoint
*The purpose of the Logical viewpoint is to elaborate existing and designed types and their implementations as classes and interfaces with their structural static relationships. This viewpoint also uses examples of instances of types in outlining design ideas.*

#### 5.4.1 Design Concerns
*The Logical viewpoint is used to address the development and reuse of adequate abstractions and their implementations. For any implementation platform, a set of types is readily available for the domain abstractions of interest in a design subject, and a number of new types is to be designed, some of which may be considered for reuse. The main concern is the proper choice of abstractions and their expression in terms of existing types (some of which may had been specific to the design subject).*

#### 5.4.2 Design Elements
*Design entities: class, interface, power type, data type, object, attribute, method, association class, template, and namespace.*

*Design relationships: association, generalisation, dependency, realisation, implementation, instance of, composition, and aggregation.*

*Design attributes: name, role name, visibility, cardinality, type, stereotype, redefinition, tagged value, parameter, and navigation efficiency.*

*Design constraints: value constraints, relationships exclusivity constraints navigability, generalisation sets, multiplicity, derivation, changeability, initial value qualifier, ordering, static, pre-condition, post-condition, and generalisation set constraints.*

#### 5.4.3 Example Languages
*UML class diagrams and UML object diagrams (showing objects as instances of their respective classes)(OMG [B28]). Lattices of types and references to implemented types are commonly used as supplementary information.*

### 5.5 Dependency Viewpoint
*The Dependency viewpoint specifies the relationships of interconnection and access among entities. These relationships include shared information, order of execution, or parameterisation of interfaces.*

#### 5.5.1 Design Concerns
*A Dependency view provides an overall picture of the design subject in order to assess the impact of requirements or design changes. It can help maintainers to isolate entities causing system failures or resource bottlenecks. It can aid in producing the system integration plan by identifying the entities that are needed by other entities and that must be developed first. This description can also be used by integration testing to aid in the production of integration test cases.*

#### 5.5.2 Design Elements
*Design entities: subsystem, component, and module.*

*Design relationships: uses, provides and requires*

*Design attribute: name (4.6.2.1), type (4.6.2.2), purpose (4.6.2.3), dependencies (5.5.2.1), and resources. These attributes should be provided for all design entities.*

##### 5.5.2.1 Dependencies Attribute
*A description of the relationships of this entity with other entities. The dependencies attribute identifies the uses or requires the presence of relationship of an entity. This attribute is used to describe the nature of each interaction including such characteristics as timing and conditions for interaction. The interactions involve the initiation, order of execution, data sharing, creation, duplicating, usage, storage, or destruction of entities.*

#### 5.5.3 Example Languages
*UML component diagrams and UML package diagrams showing dependencies among subsystems (OMG [B28]).*

### 5.6 Information Viewpoint
*The Information viewpoint is applicable when there is a substantial persistent data content expected with the design subject.*

#### 5.6.1 Design Concerns
*Key concerns include persistent data structure, data content, data management strategies, data access schemes, and definition of metadata.*

#### 5.6.2 Design Elements
*Design entities: data items, data types and classes, data stores, and access mechanisms.*

*Design relationships: association, uses implements. Data attributes, their constraints and static relationships among data entities, aggregates of attributes, and relationships.*

*Design attributes: persistence and quality properties.*

##### 5.6.2.1 Data Attribute
*A description of data elements internal to the entity. The data attribute describes the method of representation, initial values, use, semantics, format, and acceptable values of internal data. The description of data may be in the form of a data dictionary that describes the content, structure, and use of all data elements. Data information should describe everything pertaining to the use of data or internal data structures by this entity. It should include data specifications such as formats, number of elements, and initial values. It should also include the structures to be used for representing data such as file structures arrays, stacks, queues, and memory partitions.*

*The meaning and use of data elements should be specified. This description includes such things as static versus dynamic, whether it is to be shared by transactions, used as a control parameter, or used as a value, loop iteration count, pointer, or link field. In addition, data information should include a description of data validation needed for the process.*

#### 5.6.3 Example Languages
*IDEFIX (IEEE Std 1320.2-1998 [B19]), UML class diagrams (OMG [B28]).*

### 5.7 Patterns use Viewpoint
*The viewpoint addresses design ideas (emergent concepts) as collaboration patterns involving abstracted roles and connectors.*

#### 5.7.1 Design Concerns
*Key concerns include reuse at the level of design ideas (design patterns), architectural styles, and framework templates.*

#### 5.7.2 Design Elements
*Design entities: collaboration, class, connector, role, framework template, and pattern.*

*Design relationships: association, collaboration use, and connector.*

*Design attributes: name.*

*Design constraints: collaboration constraints.*

#### 5.7.3 Example Languages
*UML composite structure diagram and a combination of the UML class diagram and the UML package diagram (OMG [B28]).*

### 5.8 Interface Viewpoint
*The interface viewpoint proides information designers, programmers, and testers the means to know how to correctly use the services provided by a design subject. This description includes the details of external and internal interfaces not provided in the SRS. This viewpoint consists of a set of interface specifications for each entity.*

#### 5.8.1 Design Concerns
*An Interface view description serves as a binding contract among designers, programmers, customers, and testers. It provides them with an agreement needed before proceeding with the detailed design of entities. The interface description is used by technical writers to produce customer documentation or may be used directly by customers. In the latter case, the interface description could result in the production of a human interface view.*

*Designers, programmers, and testers often use design entities that they did not develop. These entities can be reused from earlier projects, contracted from an external source, or produced by other developers. The interface description establishes an agreement among designers, programmers, and testers about how cooperating entities will interact. Each entity interface description should contain everything another designer or programmer needs to know to develop software that interacts with that entity. A clear description of entity interfaces is essential on a multi-person development for smooth integration and ease of maintenance.*

#### 5.8.2 Design Elements
*The attributes for identification (4.6.2.1), function (5.3.2.1), and interface (6.8.2.1) should be provided for all design entities.*

##### 5.8.2.1 Interface Attribute
*A description of how other entities interact with this entity. The interface attribute describes the methods of interaction and the rules governing those interactions. Methods of interaction include the mechanisms for invoking or interrupting the entity, for communicating through parameters, common data areas or messages, and for direct access to internal data. The rules governing the interaction include the communications protocol, data format, acceptable values, and the meaning of each value.*

*This attribute provides a description of the input ranges, the meaning of inputs and outputs, the type and format of each input or output, and output error codes. For information systems, it should include inputs, screen formats, and a complete description of the interactive language.*

#### 5.8.3 Example Languages
*Interface definition languages (IDL), UML component diagram (OMG [B28]). In case of user interfaces the Interface view should include screen formats valid inputs, and resulting outputs. For data-driven entities, a data dictionary should be used to describe the data characteristics. Those entities that are highly visible to a user and involve the details of how the customer should perceive the system should include a functional model, scenarios for use, detailed feature sets and the interaction language.*

### 5.9 Structure Viewpoint
*The Structure viewpoint is used to document the internal constituents and organisation of the design subject in terms of like elements (recursively).*

#### 5.9.1 Design Concerns
*Compositional structure of coarse-grained components and reuse of fine-grained components*

#### 5.9.2 Design Elements
*Design entities: port, connector, interface, part, and class.*

*Design relationships: connected, part of, enclosed, provided, and required.*

*Design attributes: name, type, purpose, and definition.*

*Design constraints: interface constraints, reusability constraints, and dependency constraints.*

#### 5.9.3 Example Languages
*UML composite structure diagram, UML class diagram, and UML package diagram (OMG [B28]).*

### 5.10 Interaction Viewpoint
*The Interaction viewpoint defines strategies for interaction among entities, regarding why, where, how, and at what level actions occur.*

#### 5.10.1 Design Concerns
*For designers. This includes evaluating allocation of responsibilities in collaborations, especially when adapting and applying design patterns; discovery or description of interactions in terms of messages among affected objects in fulfilling required actions; and state transition logic and concurrency for reactive, interactive, distributed, real-time, and similar systems.*

#### 5.10.2 Design Elements
*Classes, methods, states, events, signals, hierarchy, concurrency, timing, and synchronisation.*

#### 5.10.3 Examples
*UML composite structure diagram, UML interaction diagram (OMG [B28]).*

### 5.11 State Dynamics Viewpoints
*Reactive systems and systems whose internal behaviour is of interest use this viewpoint.*

#### 5.11.1 Design Concerns
*System dynamics including modes, states, transitions, and reactions to events.*

#### 5.11.2 Design Elements
*Design entities: event, condition, state, transition, activity, composite state, critical region, and trigger.*

*Design relationships: part-of, internal, effect, entry, exit, and attached to.*

*Design attributes: name, completion, active, initial, and final.*

*Design constraints: guard conditions, concurrency, synchronisation, state invariant, transition constraint, and protocol.*

#### 5.11.3 Example Languages
*UML state machine diagram (OMG [B28]), Harel statechart, state transition table (matrix), automata, Petri net.*

### 5.12 Algorithm Viewpoint
*The detailed design description of operations (such as methods and functions), the internal details and logic of each design entity.*

#### 5.12.1 Design Concerns
*The Algorithm viewpoint provides details needed by programmers, analysts of algorithms in regard to time-space performance and processing logic prior to implementation, and to aid in producing unit test plans.*

#### 5.12.2 Design Elements
*These should include the attribute descriptions for identification, processing (5.12.1), and data for all design entities.*

#### 5.12.3 Processing Attribute
*A description of the rules used by the entity to achieve its function. The processing attribute describes the algorithm used by the entity to perform a specific task and its contingencies. This description is a refinement of the function attribute and is the most detailed level of refinement for the entity.*

*This description should include timing, sequencing of events or processes, prerequisites for process initiation, priority of events, processing level, actual process steps, path conditions, and loop back or loop termination criteria. The handling of contingencies should describe the action to be taken in the case of overflow conditions or in the case of a validation check failure.*

#### 5.12.4 Examples
*Descision tables and flowcharts; program design languages, "pseudo-code", and (actual) programming languages may also be used.*

### 5.13 Resource Viewpoint
*The purpose of the Resource viewpoint is to model the characteristics and utilisation of resources in a design subject.*

#### 5.13.1 Design Concerns
*Key concerns include resource utilisation, resource contention, availability, and performance.*

#### 5.13.2 Design Elements
*Design entities: resources, usage policies.*

*Design relationship: allocation and uses.*

*Design attributes: identification (4.6.2.1), resource (5.13.2.1), performance measures (such as throughput, rate of consumption).*

*Design constraints: priorities, locks, resource constraints.*

##### 5.13.2.1 Resources Attribute
*A description of the elements used by the entity that are external to the design. The resources attribute identifies and describes all of the resources external to the design that are needed by this entity to perform its function. The interaction rules and methods for using the resource are to be specified by this attribute.*

*This attribute provides information about items such as physical devices (printers, disc-partitions, memory banks), software services (math libraries, operating system services), and processing resources (CPU cycles, memory allocation, buffers).*

*The resources attribute should describe usage characteristics such as the processing time at which resources are to be acquired and sizing to include quantity, and physical sizes of buffer usage. It should also include the identification of potential race and deadlock conditions as well as resource management facilities.*

#### 5.13.3 Examples
*Woodside [B37], UML class diagram, UML Object Constraint Langauge (OMG [B28]).*
