# Software Requirements

## Concepts

- Requirement.
  - Functional.
  - Non-functional.

- Business Rule.
- Use Case.

## Requirement

- Need to be fulfilled.
- Software requirement: Necessary characteristic.
- The course of development.

The definition of the word "requirement" means a need to be fulfilled. When used in the scope of software development, it becomes a software requirement, thus a characteristic to be met in software production. When the requirements of a software are defined, the directions to be followed in the development of this software are being defined.

Development occurs to meet a set of software requirements.

### Types of software requirement

#### Functional

- Something that the program does or executes.
- A functional requirement is always characterized by an infinitive verb.
  - search, define, retrieve...
- Example: enrollment system
  - Display classes
  - Edit enrollment request
  - Evaluate enrollment request

##### Description of functional requirement

- 5W1H
- What? Why? By whom? When? Where? How?
  - When defining a functional requirement, these 6 questions must be answered.
  - The 6 questions must be answered in the context of the requirements specification document.

##### Example: "Evaluate enrollment request"

- What?
  - Search for inconsistencies in a possible enrollment request.
- Why?
  - Ensure the consistency of the enrollment process.
- By whom? (usually we think of users)
  - A student
- When? (temporal issue)
  - During the enrollment process.
- Where? (geographical issue)
  - If it is a registered student, it can be done from anywhere with an internet connection (web system).
  - If it is a new student, they must go to a specific location to register and validate the information by a specific user of the software.
- How? (must be detailed, must consider restrictions... [Business rules])
  - Must obey a set of rules:
    - Minimum and maximum workload.
    - Prerequisites for each subject.

#### Non-functional

- Characteristics that the software must have but are not functionalities.
- It can be a restriction associated with functionalities.
- Example: "The program must be implemented in..."
- Example: "Redundant persistence in..."
- It can be organized into categories: (May vary)
  - Interface.
    - Colors.
    - Position of the logo.
    - Menus.
  - Development support.
    - IDE.
    - DBMS.
    - UML modeling software.
  - Execution platform. (IOS, Windows, Linux...)
  - Robustness, integrity, security.
  - Performance... etc.

##### Description of non-functional requirement

- In a specific section.
- Simpler than functional requirement.

## Business Rule

- Not a software requirement.
- Also called "domain requirement."
- Independent of the computational world.
- Affects functional requirements.

The business rule is something that I must observe but is not classified as a software requirement.
Refers to the domain of the problem that the software deals with.

### Examples of business rule

#### Evaluate enrollment request (Functional requirement)

- Workload (maximum/minimum).
  - The workload must be equal to or greater than the minimum and equal to or less than the maximum. (Business rule)
- Prerequisite.
  - To enroll in the OOPII class, you must have passed OOPI. (Business rule)
- Time conflict.
  - Two subjects cannot have overlapping total or partial schedules. (Business rule)

### Description of business rule

- 1st possibility: Specific section.
  - Rules referenced by functional requirements.
- 2nd possibility: In the body of functional requirements.

## Use Case

- Development concept (UML).
- Software functionality.
- Related to functional requirements.
  - Use case: at least one functional requirement.
  - Functional requirement: at least one use case.
- Correspondence between use case and functional requirement.

### Examples of use case

#### Evaluate enrollment request
