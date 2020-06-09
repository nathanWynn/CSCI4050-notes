# Introduction

## Software engineering history

- - Term introduced in the late 60s during a conference held to discuss the software crisis

  - Arian-5 explosion 1996

  - - Caused by software bug (unsigned int overflow)

  - Y2K

  - - Widespread snags in processing dates after the year 2000.
    - Root of the problem: devs shortened the 4 digit data format to a 2 digit date format. They didn’t realize 2000 would be shortened to 00, and 00 < 72

  - Many other examples…

    

## Quality Software Engineering

- - **Characteristics of "quality software"**

  - - Performs precisely as required under all circumstances
    - Fault free (reliable)
    - Maintainable
    - Appropriate ui
    - Efficient
    - Delivered on time
    - Within budget

  - High quality software

  - - **MADE**

    - - **M**aintainable

      - **A**cceptable (usable)

      - **D**ependable

      - - Reliability
        - Security
        - Safety
        - availability

      - **E**fficient



### Why is software development difficult?

- - Problem domain (application domain)

  - Solution domain is difficult

  - Development process is difficult to manage

  - Software --> extreme flexibility

  - Software --> discrete system

  - - **Continuous systems** have no hidden surprises

    - **Discrete systems** can have hidden surprises

    - - David Parnas - pioneer in SWE, developed concepts of modularity and information hiding in systems which are the foundations of Object Oriented Methodologies



### SWE is more than writing code

- #### Facets of Software Engineering

- - - **Problem solving**

    - - Creating a solution
      - Engineering a system based on the solution

    - **Modeling**

    - **Knowledge acquisition**

    - - Knowledge about solution domain

    - **Rationale management**

    - - Capture context in which decisions are made
      - Understand the forces involved and the rationale behind the decisions

 

## Defining Software Engineering

- **Software Engineering** is a discipline that is concerned with all aspects of software production from the early stages of system specification through to maintaining the system after it has gone into use.

- - Engineering discipline

  - - Using appropriate theories and methods

  - All aspects of software production

  - - Not just technical process: project management, development of tools, methods, etc.

      

### Technical phases

- 1. **Requirements engineering**

  2. - Functional vs nonfunctional requirements
     - Documentation
     - Elicitation
     - Analysis
     - Specification (text and diagram)
     - Verification

  3. **Design**

  4. **Implementation**

  5. **Verification and Validation (V&V)**

  6. **Maintenance**

- - Extra: Managerial Activities



### Techniques, methodologies, and tools

- - **Techniques**

  - - Formal procedures for producing results using some well defined notation

  - **Methodologies**

  - - Collection of techniques applied across software dev and unified by a philosophical approach

  - **Tools**

  - - Instruments or automated systems to accomplish a technique
    - CASE: computer aided software engineering



#### Software Systems and Methodologies

- - Systems are usually developed to support a part of the overall mission of the enterprise
  - Many types of systems exist - no universal set of techniques
  - Methods and tools used depend on the type of app, and requirements of the customer/background of the dev team



## Types of systems

- - **Stand alone**

  - - Run on local computer, no need for network

  - **Interactive transaction based systems**

  - - Run on a remote computer, accessed by users from their own local systems - web apps, ecommerce

  - **Embedded control systems**

  - - Control and manage hardware devices - huge chunk of the system ecosystem

  - **Batch processing**

  - - Business systems to process data in batches

  - **Entertainment systems**

  - - Gaming systems

  - **Modelling and simulation**

  - - Used by scientists and engineers to model physical processes

  - **Data collection systems**

  - - Collect data from environment using sensors

    - - GPS, weather station

  - **Systems of systems**

  - - Integration of systems

- - **Web based systems**
    - Web has become a platform for running systems
    - Should be developed and delivered incrementally



### Parties in System Development

- - Parties involved

  - - **Users** (direct/indirect)
    - **Customer/producer**
    - **Producer/developer**

  - *All three are usually different*

  - User centered development

  - - Systems should be

    - - **Specified** based on user needs
      - **Validated** according to user needs
      - **Documented** from the user's perspective

 