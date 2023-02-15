# Requirement Generation Tool

The Requirement Generation Tool is a critical component of the OpenATO ecosystem. It will help agencies simplify the ATO process by providing a suite of tools for generating and assessing system requirements, managing existing profiles, building security plans, and creating agency profiles needed for secure technology implementation.

## Need Statement

The Requirement Generation Tool is needed to address the complexity and inefficiencies in the ATO process. By providing a suite of tools for generating and assessing system requirements, building and maintaining security plans, and creating up-to-date agency profiles, the tool will help agencies shift compliance left, so that security compliance is built into systems from the start, and development teams can build systems more efficiently. With the increasing complexity and frequency of updates in the technology landscape, it becomes imperative to have a tool that can effectively manage the requirements and keep them up to date. The tool will also help improve the accuracy of ATO documents, ensuring that government technology is more secure and that the public can confidently access the benefits and services they need.

## Roadmap

The Requirement Manager is designed to streamline the creation and management of agency and impact level requirements. The product roadmap is focused on providing a clear workflow for various teams involved in the creation of the agency profile, impact profiles, and ensuring changes are made efficiently.

### Features

#### Agency Profile Builder

The Agency Profile Builder provides a clear workflow for the creation and management of the agency profile. Teams involved in the creation of the agency profile are guided through the process with questions and pre-filled content to help streamline the creation process.

#### Impact Profile(s) Builder

The Impact Profile Builder builds on the foundation of the Agency Profile. Once the agency profile is complete, users answer questions to generate their Impact Profiles. These profiles are then used to populate the Agency Knowledge Base and Component Library with applicable components and implementation tasks.

#### Agency Profile Manager

The Agency Profile Manager allows users to manage and update their agency profile. Any changes made to the profile will cascade to all relevant resources, ensuring that updates are reflected accurately throughout the system.

#### Impact Profile Manager

The Impact Profile Manager is responsible for managing updates and changes to the impact profiles. Changes made to the impact profiles are reflected in controls and components, ensuring that the system remains up-to-date and secure.

```mermaid
graph TD
subgraph Now
A[Agency Profile Builder]
end
subgraph Next
B[Impact Profile(s) Builder]
end
subgraph Later
C[Agency Profile Manager]
D[Impact Profile Manager]
end

Now --> Next
Next --> Later
```
