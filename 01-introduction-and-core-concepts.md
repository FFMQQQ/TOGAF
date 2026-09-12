# Introduction and Core Concepts

## Contents

- [TOGAF Enterprise Architecture Practitioner Body of Knowledge Set 1](#togaf-enterprise-architecture-practitioner-body-of-knowledge-set-1)
- [Introduction and Core Concepts](#introduction-and-core-concepts)
- [1 Introduction](#1-introduction)
  - [1.1 Executive Overview](#11-executive-overview)
  - [1.2 Structure of this Document](#12-structure-of-this-document)
  - [1.3 Information on Using the TOGAF Standard](#13-information-on-using-the-togaf-standard)
    - [1.3.1 Conditions of Use](#131-conditions-of-use)
    - [1.3.2 How Much Does the TOGAF Standard Cost?](#132-how-much-does-the-togaf-standard-cost)
    - [1.3.3 Downloads](#133-downloads)
  - [1.4 Why Join The Open Group?](#14-why-join-the-open-group)
- [2 The TOGAF Documentation Set](#2-the-togaf-documentation-set)
  - [2.1 Structure of the TOGAF Documentation Set](#21-structure-of-the-togaf-documentation-set)
  - [2.2 The TOGAF Standard](#22-the-togaf-standard)
  - [2.3 The TOGAF Library](#23-the-togaf-library)
- [3 Core Concepts](#3-core-concepts)
  - [3.1 What is the TOGAF Standard?](#31-what-is-the-togaf-standard)
  - [3.2 What is Architecture in the Context of the TOGAF Standard?](#32-what-is-architecture-in-the-context-of-the-togaf-standard)
  - [3.3 What Kind of Architecture Does the TOGAF Standard Deal With?](#33-what-kind-of-architecture-does-the-togaf-standard-deal-with)
  - [3.4 Architecture Development Method](#34-architecture-development-method)
  - [3.5 Enterprise Architecture Services](#35-enterprise-architecture-services)
    - [3.5.1 Enterprise Support Services](#351-enterprise-support-services)
    - [3.5.2 Design Support Services](#352-design-support-services)
    - [3.5.3 Development Support Services](#353-development-support-services)
    - [3.5.4 Requirements Elicitation and Understanding Services](#354-requirements-elicitation-and-understanding-services)
    - [3.5.5 Architecture Planning Services](#355-architecture-planning-services)
    - [3.5.6 Enterprise Architecture Practice Development Support Services](#356-enterprise-architecture-practice-development-support-services)
  - [3.6 Deliverables, Artifacts, and Building Blocks](#36-deliverables-artifacts-and-building-blocks)
  - [3.7 Architecture Abstraction](#37-architecture-abstraction)
    - [3.7.1 Contextual Abstraction Level](#371-contextual-abstraction-level)
    - [3.7.2 Conceptual Abstraction Level](#372-conceptual-abstraction-level)
    - [3.7.3 Logical Abstraction Level](#373-logical-abstraction-level)
    - [3.7.4 Physical Abstraction Level](#374-physical-abstraction-level)
  - [3.8 Architecture Principles](#38-architecture-principles)
  - [3.9 Interoperability](#39-interoperability)
  - [3.10 Enterprise Continuum](#310-enterprise-continuum)
  - [3.11 Architecture Repository](#311-architecture-repository)
  - [3.12 TOGAF Content Framework and Enterprise Metamodel](#312-togaf-content-framework-and-enterprise-metamodel)
    - [3.12.1 Overview](#3121-overview)
    - [3.12.2 Content Framework](#3122-content-framework)
    - [3.12.3 Enterprise Metamodel](#3123-enterprise-metamodel)
    - [3.12.4 Developing the Enterprise Metamodel](#3124-developing-the-enterprise-metamodel)
  - [3.13 Establishing and Maintaining an Enterprise Architecture Capability](#313-establishing-and-maintaining-an-enterprise-architecture-capability)
  - [3.14 Establishing the Architecture Capability as an Operational Entity](#314-establishing-the-architecture-capability-as-an-operational-entity)
  - [3.15 Using the TOGAF Standard with Other Frameworks](#315-using-the-togaf-standard-with-other-frameworks)
  - [3.16 Using the TOGAF Framework with Different Architecture Styles](#316-using-the-togaf-framework-with-different-architecture-styles)
  - [3.17 Architecture Views and Viewpoints](#317-architecture-views-and-viewpoints)
  - [3.18 Enterprise Agility](#318-enterprise-agility)
  - [3.19 Risk Management](#319-risk-management)
- [4 Definitions](#4-definitions)
  - [4.1 Abstraction](#41-abstraction)
  - [4.2 Actor](#42-actor)
  - [4.3 Application Architecture](#43-application-architecture)
  - [4.4 Application Component](#44-application-component)
  - [4.5 Application Platform](#45-application-platform)
  - [4.6 Application Service](#46-application-service)
  - [4.7 Architectural Style](#47-architectural-style)
  - [4.8 Architecture](#48-architecture)
  - [4.9 Architecture Building Block (ABB)](#49-architecture-building-block-abb)
  - [4.10 Architecture Continuum](#410-architecture-continuum)
  - [4.11 Architecture Development Method (ADM)](#411-architecture-development-method-adm)
  - [4.12 Architecture Domain](#412-architecture-domain)
  - [4.13 Architecture Framework](#413-architecture-framework)
  - [4.14 Architecture Governance](#414-architecture-governance)
  - [4.15 Architecture Landscape](#415-architecture-landscape)
  - [4.16 Architecture Level](#416-architecture-level)
  - [4.17 Architecture Model](#417-architecture-model)
  - [4.18 Architecture Partition](#418-architecture-partition)
  - [4.19 Architecture Principle](#419-architecture-principle)
  - [4.20 Architecture View](#420-architecture-view)
  - [4.21 Architecture Viewpoint](#421-architecture-viewpoint)
  - [4.22 Architecture Vision](#422-architecture-vision)
  - [4.23 Artifact](#423-artifact)
  - [4.24 Baseline](#424-baseline)
  - [4.25 Boundaryless Information Flow](#425-boundaryless-information-flow)
  - [4.26 Building Block](#426-building-block)
  - [4.27 Business Architecture](#427-business-architecture)
  - [4.28 Business Capability](#428-business-capability)
  - [4.29 Business Function](#429-business-function)
  - [4.30 Business Governance](#430-business-governance)
  - [4.31 Business Model](#431-business-model)
  - [4.32 Business Service](#432-business-service)
  - [4.33 Capability](#433-capability)
  - [4.34 Capability Architecture](#434-capability-architecture)
  - [4.35 Capability Increment](#435-capability-increment)
  - [4.36 Communications and Stakeholder Management](#436-communications-and-stakeholder-management)
  - [4.37 Concern](#437-concern)
  - [4.38 Course of Action](#438-course-of-action)
  - [4.39 Data Architecture](#439-data-architecture)
  - [4.40 Deliverable](#440-deliverable)
  - [4.41 Digital Architecture](#441-digital-architecture)
  - [4.42 Enterprise](#442-enterprise)
  - [4.43 Enterprise Architecture Service](#443-enterprise-architecture-service)
  - [4.44 Enterprise Continuum](#444-enterprise-continuum)
  - [4.45 Foundation Architecture](#445-foundation-architecture)
  - [4.46 Framework](#446-framework)
  - [4.47 Gap](#447-gap)
  - [4.48 Governance](#448-governance)
  - [4.49 Information](#449-information)
  - [4.50 Information Technology (IT)](#450-information-technology-it)
  - [4.51 Interoperability](#451-interoperability)
  - [4.52 Logical](#452-logical)
  - [4.53 Metadata](#453-metadata)
  - [4.54 Metamodel](#454-metamodel)
  - [4.55 Method](#455-method)
  - [4.56 Modeling](#456-modeling)
  - [4.57 Model Kind](#457-model-kind)
  - [4.58 Objective](#458-objective)
  - [4.59 Pattern](#459-pattern)
  - [4.60 Physical](#460-physical)
  - [4.61 Principle](#461-principle)
  - [4.62 Product](#462-product)
  - [4.63 Reference Model (RM)](#463-reference-model-rm)
  - [4.64 Requirement](#464-requirement)
  - [4.65 Roadmap](#465-roadmap)
  - [4.66 Role](#466-role)
  - [4.67 Segment Architecture](#467-segment-architecture)
  - [4.68 Service](#468-service)
  - [4.69 Service Orientation](#469-service-orientation)
  - [4.70 Service-Oriented Architecture (SOA)](#470-service-oriented-architecture-soa)
  - [4.71 Service Portfolio](#471-service-portfolio)
  - [4.72 Solution Architecture](#472-solution-architecture)
  - [4.73 Solution Building Block (SBB)](#473-solution-building-block-sbb)
  - [4.74 Solutions Continuum](#474-solutions-continuum)
  - [4.75 Stakeholder](#475-stakeholder)
  - [4.76 Standards Library](#476-standards-library)
  - [4.77 Strategic Architecture](#477-strategic-architecture)
  - [4.78 Target Architecture](#478-target-architecture)
  - [4.79 Taxonomy of Architecture Views](#479-taxonomy-of-architecture-views)
  - [4.80 Technology Architecture](#480-technology-architecture)
  - [4.81 Technology Component](#481-technology-component)
  - [4.82 Technology Service](#482-technology-service)
  - [4.83 Transition Architecture](#483-transition-architecture)
  - [4.84 Value Stream](#484-value-stream)
  - [4.85 View](#485-view)
  - [4.86 Viewpoint](#486-viewpoint)
  - [4.87 Viewpoint Library](#487-viewpoint-library)
  - [4.88 Work Package](#488-work-package)
- [A Referenced Documents](#a-referenced-documents)
- [B Glossary of Supplementary Definitions](#b-glossary-of-supplementary-definitions)
  - [B.1 Application Software](#b1-application-software)
  - [B.2 Availability](#b2-availability)
  - [B.3 Business System](#b3-business-system)
  - [B.4 Catalog](#b4-catalog)
  - [B.5 Client](#b5-client)
  - [B.6 COBIT](#b6-cobit)
  - [B.7 Configuration Management](#b7-configuration-management)
  - [B.8 CxO](#b8-cxo)
  - [B.9 Data Dictionary](#b9-data-dictionary)
  - [B.10 Data Element](#b10-data-element)
  - [B.11 Database](#b11-database)
  - [B.12 Database Management System](#b12-database-management-system)
  - [B.13 End User](#b13-end-user)
  - [B.14 Enterprise Resource Planning (ERP) System](#b14-enterprise-resource-planning-erp-system)
  - [B.15 Hardware](#b15-hardware)
  - [B.16 Information Domain](#b16-information-domain)
  - [B.17 Information System (IS)](#b17-information-system-is)
  - [B.18 Interaction](#b18-interaction)
  - [B.19 Interaction Model](#b19-interaction-model)
  - [B.20 Interface](#b20-interface)
  - [B.21 Key Performance Indicator (KPI)](#b21-key-performance-indicator-kpi)
  - [B.22 Lifecycle](#b22-lifecycle)
  - [B.23 Managing Successful Programs (MSP)](#b23-managing-successful-programs-msp)
  - [B.24 Matrix](#b24-matrix)
  - [B.25 Metaview](#b25-metaview)
  - [B.26 Open System](#b26-open-system)
  - [B.27 Operational Governance](#b27-operational-governance)
  - [B.28 Packaged Services](#b28-packaged-services)
  - [B.29 Portability](#b29-portability)
  - [B.30 Portfolio](#b30-portfolio)
  - [B.31 PRINCE2](#b31-prince2)
  - [B.32 Program](#b32-program)
  - [B.33 Project](#b33-project)
  - [B.34 Risk Management](#b34-risk-management)
  - [B.35 Scalability](#b35-scalability)
  - [B.36 Security](#b36-security)
  - [B.37 Server](#b37-server)
  - [B.38 Service Quality](#b38-service-quality)
  - [B.39 SMART](#b39-smart)
  - [B.40 Supplier Management](#b40-supplier-management)
  - [B.41 System](#b41-system)
  - [B.42 Time Period](#b42-time-period)
  - [B.43 Use-Case](#b43-use-case)
  - [B.44 User](#b44-user)
- [C Abbreviations](#c-abbreviations)

## The Open Group Standard

## TOGAF® Standard — Introduction and Core Concepts

The Open Group

Copyright © 2005-2022, The Open Group

All rights reserved.

No part of this publication may be reproduced, stored in a retrieval system, or transmitted, in any form or by any means, electronic, mechanical, photocopying, recording or otherwise, without the prior permission of the copyright owners.

Any use of this publication for commercial purposes is subject to the terms of the Annual Commercial License relating to it. For further information, see www.opengroup.org/legal/licensing.

The Open Group Standard TOGAF® Standard — Introduction and Core Concepts

ISBN: 1-947754-90-4 Document Number: C220

Published by The Open Group, 2005-2022.

Any comments relating to the material contained in this document may be submitted by email to:

OGspecs@opengroup.org

## Preface

## The Open Group

The Open Group is a global consortium that enables the achievement of business objectives through technology standards. With more than 870 member organizations, we have a diverse membership that spans all sectors of the technology community — customers, systems and solutions suppliers, tool vendors, integrators and consultants, as well as academics and researchers.

The mission of The Open Group is to drive the creation of Boundaryless Information Flow™ achieved by:

- Working with customers to capture, understand, and address current and emerging requirements, establish policies, and share best practices
- Working with suppliers, consortia, and standards bodies to develop consensus and facilitate interoperability, to evolve and integrate specifications and open source technologies
- Offering a comprehensive set of services to enhance the operational efficiency of consortia
- Developing and operating the industry’s premier certification service and encouraging procurement of certified products

Further information on The Open Group is available at www.opengroup.org.

The Open Group publishes a wide range of technical documentation, most of which is focused on development of Standards and Guides, but which also includes white papers, technical studies, certification and testing documentation, and business titles. Full details and a catalog are available at www.opengroup.org/library.

## This Document

This is the TOGAF Standard — Introduction and Core Concepts.

This document is part of the TOGAF Standard, and provides an introduction to the standard, including an executive overview of Enterprise Architecture, a description of how the standard is organized, and a summary of core concepts. It also contains the material common to the individual documents that comprise the standard, such as the definitions, as well as document references and abbreviations.

## The TOGAF Documentation

The TOGAF documentation set comprises a portfolio of documents, built around the TOGAF Standard.

## The TOGAF® Standard

The TOGAF® Standard is an open, industry consensus framework for Enterprise Architecture.

It is a foundational framework, which means that it is applicable to the development of any kind of architecture in any context. This foundational framework is supplemented by The Open Group TOGAF Library,1 an extensive and growing portfolio of guidance material, providing

practical guidance in the application of the TOGAF framework in specific contexts.

The TOGAF Standard is presented as a series of free-standing, but closely linked documents and is supplemented by an extensive and growing portfolio of guidance material, providing practical guidance in the application of the TOGAF Standard in specific contexts.

The TOGAF Standard is a standard of The Open Group. The Open Group works with customers and suppliers of technology products and services, and with consortia and other standards organizations to capture, clarify, and integrate current and emerging requirements, establish standards and policies, and share best practices. Standards ensure openness, interoperability, and consensus.

At the time of publication, the TOGAF Standard comprises the following documents:

- TOGAF Standard — Introduction and Core Concepts
- TOGAF Standard — Architecture Development Method
- TOGAF Standard — ADM Techniques
- TOGAF Standard — Applying the ADM
- TOGAF Standard — Architecture Content
- TOGAF Standard — Enterprise Architecture Capability and Governance
- TOGAF Standard — TOGAF Series Guides (set of documents)

## Intended Audience

The TOGAF Standard is intended for Enterprise Architects, Business Architects, IT Architects, Data Architects, Systems Architects, Solution Architects, and anyone responsible for the architecture function within an organization.

Other audiences are Digital and Agile Practitioners, Product Managers, and C-Suite. These audiences will find more detailed guidance on how to apply the standard to fulfill specific needs in the TOGAF Series Guides set of documents.

1\. The TOGAF Library is a publicly-accessible resource located at www.opengroup.org/togaf-library.

## Keywords

architecture, architecture framework, architecture development method, architect, architecting, enterprise architecture, enterprise architecture framework, enterprise architecture method, method, methods, open, group, technical reference model, standards library

## Trademarks

ArchiMate, DirecNet, Making Standards Work, Open O logo, Open O and Check Certification logo, The Open Group, TOGAF, UNIX, UNIXWARE, and the Open Brand X logo are registered trademarks and Boundaryless Information Flow, Build with Integrity Buy with Confidence, Commercial Aviation Reference Architecture, Dependability Through Assuredness, Digital Practitioner Body of Knowledge, DPBoK, EMMM, FACE, the FACE logo, FHIM Profile Builder, the FHIM logo, FPB, Future Airborne Capability Environment, IT4IT, the IT4IT logo, O-AA, O-DEF, O-HERA, O-PAS, Open Agile Architecture, Open FAIR, Open Footprint, Open Process Automation, Open Subsurface Data Universe, Open Trusted Technology Provider, OSDU, Sensor Integration Simplified, SOSA, and the SOSA logo are trademarks of The Open Group.

CMMI is a registered trademark of CMMI Institute.

COBIT is a registered trademark of the Information Systems Audit and Control Association (ISACA) and the IT Governance Institute.

FICO is a registered trademark of Fair Isaac Corporation in the United States and other countries.

IEEE is a registered trademark of the Institute of Electrical and Electronics Engineers, Inc.

ITIL, MSP, and PRINCE2 are registered trademarks of AXELOS Limited.

Java is a registered trademark of Oracle and/or its affiliates.

MDA, Model-Driven Architecture, Object Management Group, OMG, SysML, and UML are registered trademarks and BMM, BPMN, Business Motivation Model, Business Process Modeling Notation, ITPMF, IT Portfolio Management Facility, SPEM, Systems Modeling Language, and Unified Modeling Language are trademarks of the Object Management Group.

Merriam-Webster Collegiate Dictionary is a registered trademark of Merriam-Webster, Incorporated.

OASIS is a registered trademark of OASIS, the open standards consortium.

PMBOK is a registered trademark of the Project Management Institute, Inc. which is registered in the United States and other nations.

Zachman is a registered trademark of Zachman International, Inc.

The Open Group acknowledges that there may be other company names and products that might be covered by trademark protection and advises the reader to verify them independently.

## Participants

The TOGAF Standard, 10th Edition was prepared by The Open Group Architecture Forum. When The Open Group approved this standard for publication in April 2022, the Architecture Forum Officers were as follows:

## Mick Adams, EY, Co-Chair

## Paul Homan, IBM, Co-Chair (2018-2021)

## Céline Lescop, AXA, Co-Chair (from March 2021)

## Sonia Gonzalez, The Open Group, TOGAF Product Manager

## Mark Dickson, The Open Group, Architecture Forum Director

## Daniel Hutley, The Open Group, Architecture Forum Director

## Architecture Forum Technical Reviewers

Technical reviewers are those individuals who have submitted comments during the Company Review, or participated in an issue resolution meeting during the development of the TOGAF Standard, 10th Edition (arranged in alphabetical order).

(Please note affiliations were current at the time of approval.)

- Adam Art, Raytheon Technologies
- Graham Berrisford, Avancier
- Terence Blevins, Enterprise Wise LLC & Fellow of The Open Group
- Ken Block, Raytheon Technologies
- Steve Dupont, Boeing
- Ivan Eikenberry, Raytheon Technologies
- Chris Forde, Vice-President Enterprise Architecture, The Open Group
- Mats Gejnevall, Biner Consulting
- David Gilmour, Mundo Cognito
- Susan Gottschlich, Raytheon Technologies
- Heidi Hasz, Global Knowledge Training LLC
- Judith Jones, ATE Enterprises
- Andrew Josey, VP Standards & Certification, The Open Group
- Rolf Knoll, Novatec Consulting GmbH
- Bryan Lail, Raytheon Technologies
- Mike Lambert, Fellow of The Open Group
- Frédéric Lé, DXC
- Seshu Madabhushi, Tata Consultancy
- Stephen Marshal, IBM
- Terence McKiernan, Raytheon Technologies
- Jon McLeod, EA Learning Pty Ltd.
- Marc Perna, Raytheon Technologies
- David Pham, Raytheon Technologies
- Luke Ranck, Raytheon Technologies
- James Renfro, Raytheon Technologies
- G. Edward Roberts, Elparazim
- Naveen Sharma, HCL Technologies
- Ralph Shaw, Raytheon Technologies
- Dirk Vollmerhaus, Scape Consulting GmbH
- Robert Weisman, Build the Vision
- Mark Whitbread, Raytheon Technologies

## Architecture Forum Members

An up-to-date list of Forum members can be found at: www.opengroup.org/architecture.

## Acknowledgements

The Open Group gratefully acknowledges The Open Group Architecture Forum for developing the TOGAF Standard.

The Open Group gratefully acknowledges the significant contribution to the evolution of this release of the TOGAF Standard by Mike Lambert, Fellow of The Open Group and Paul Homan, IBM.

The Open Group gratefully acknowledges those past and present members of the Architecture Forum who have served as its Officers (Chairs and Vice-Chairs) since its inception. In alphabetical order:

Mick Adams Céline Lescop Christer Askerfjord Stuart Macgregor Terence Blevins Ian McCall Bill Estrem Tara Paider Hugh Fisher Barry Smith Chris Forde Walter Stahlecker Chris Greenslade Sheena Thompson Ed Harrington Paul van der Merwe Peter Haviland Dave Van Gelder Paul Homan Jane Varnus Dave Hornford Vish Viswanathan David Jackson Robert Weisman Mike Lambert Hal Wilson

## Chapter 1: Introduction

The TOGAF Standard is a framework for Enterprise Architecture. It may be used freely by any organization wishing to develop an Enterprise Architecture for use within that organization (see Section 1.3.1).

The TOGAF Standard is developed and maintained by members of The Open Group, working within the Architecture Forum (refer to www.opengroup.org/architecture). The original development of TOGAF Version 1 in 1995 was based on the Technical Architecture Framework for Information Management (TAFIM), developed by the US Department of Defense (DoD). The DoD gave The Open Group explicit permission and encouragement to create Version 1 of the TOGAF Standard by building on the TAFIM, which itself was the result of many years of development effort and many millions of dollars of US Government investment.

Starting from this sound foundation, the members of The Open Group Architecture Forum have developed successive versions of the TOGAF Standard and published each one on The Open Group public website.

This version builds on previous versions of the TOGAF Standard and updates the material available to architecture practitioners to assist them in building a sustainable Enterprise Architecture. Work on White Papers and Guides describing how to integrate and use this standard with other frameworks and architectural styles has highlighted the universal framework parts of the standard, as well as industry, architecture style, and purpose-specific tools, techniques, and guidance. This work is embodied in the TOGAF Library.1

Although all of the TOGAF documentation works together as a whole, it is expected that organizations will customize it during adoption, and deliberately choose some elements, customize some, exclude some, and create others. For example, an organization may wish to adopt the TOGAF metamodel, but elect not to use any of the guidance on how to develop an in-house Technology Architecture because they are heavy consumers of cloud services.

You are recommended to first read the Executive Overview (see Section 1.1), which includes an outline of The Open Group understanding of Enterprise Architecture and answers to fundamental questions, such as:

- Why is an Enterprise Architecture needed?
- Why use the TOGAF Standard as a framework for Enterprise Architecture?

### 1.1 Executive Overview

This section provides an executive overview of Enterprise Architecture, the basic concepts of what it is (not just another name for IT Architecture), and why it is needed. It provides a summary of the benefits of establishing an Enterprise Architecture and adopting the TOGAF approach to achieve that.

What is an enterprise?

The TOGAF Standard considers an "enterprise" to be any collection of organizations that have common goals.

For example, an enterprise could be:

- A whole corporation or a division of a corporation
- A government agency or a single government department
- A chain of geographically distant organizations linked together by common ownership
- Groups of countries, governments, or governmental organizations (such as militaries) working together to create common or shareable deliverables or infrastructures
- Partnerships and alliances of businesses working together, such as a consortium or supply chain

The term "Enterprise" in the context of "Enterprise Architecture" can be applied to either an entire enterprise, encompassing all of its business activities and capabilities, information, and technology that make up the entire infrastructure and governance of the enterprise, or to one or more specific areas of interest within the enterprise. An enterprise may include partners, suppliers, and customers as well as internal business units. In all cases, the architecture crosses multiple systems, and multiple functional groups within the enterprise.

The enterprise operating model concept is useful to determine the nature and scope of the Enterprise Architecture within an organization. Many organizations may comprise multiple enterprises, and may develop and maintain a number of independent Enterprise Architectures to address each one. These enterprises often have much in common with each other including processes, functions, and their information systems, and there is often great potential for wider gain in the use of a common architecture framework. For example, a common framework can provide a basis for the development of common building blocks and solutions, and a shareable Architecture Repository for the integration and re-use of business models, designs, information, and data.

Why is an Enterprise Architecture needed?

The purpose of Enterprise Architecture is to optimize across the enterprise the often fragmented legacy of processes (both manual and automated) into an integrated environment that is responsive to change and supportive of the delivery of the business strategy.

The effective management and exploitation of information and Digital Transformation are key factors to business success, and indispensable means to achieving competitive advantage. An Enterprise Architecture addresses this need, by providing a strategic context for the evolution and reach of digital capability in response to the constantly changing needs of the business environment.

Furthermore, a good Enterprise Architecture enables you to achieve the right balance between business transformation and continuous operational efficiency. It allows individual business units

to innovate safely in their pursuit of evolving business goals and competitive advantage. At the same time, the Enterprise Architecture enables the needs of the organization to be met with an integrated strategy which permits the closest possible synergies across the enterprise and beyond.

And lastly, much of the global privacy legislation demands that processes around personal data are fully documented in a way that can be easily understood by untrained readers — such as the data subjects and judges and lawyers. The penalties for failing to have this can be very significant. Clearly the creation of this basic documentation arises from the changed fundamental considerations and this is now crucial.

What are the benefits of an Enterprise Architecture?

An effective Enterprise Architecture can bring important benefits to the organization. Potential benefits of an Enterprise Architecture include:

- More effective strategic decision-making by C-Level executives and business leaders:
  - Quick response to change and support for enterprise agility aligned with the organization strategy
  - Organizational transformation, adopting new trends in business and technology
  - Organizational change to support Digital Transformation
  - Organizational and operating model changes to improve efficiency and effectiveness
- More effective and efficient business operations:
  - Lower business operation costs
  - More agile organization
  - Business capabilities shared across the organization
  - Lower change management costs
  - More flexible workforce
  - Improved business productivity
  - Improved organization integration in support of mergers and acquisitions
- More effective and efficient Digital Transformation and operations:
  - Extending effective reach of the enterprise (e.g., through digital capability)
  - Bringing all components of the enterprise into a harmonized environment
  - Lower development, deployment, operations, support, and maintenance costs
  - Improved interoperability
  - Improved system management
  - Improved ability to address critical enterprise-wide issues (e.g., security)
  - Easier upgrade and exchange of system components
- Better return on existing investment, reduced risk for future investment:
  - Reduced complexity in the business and IT
  - Maximized return on investment in existing business and IT
  - The flexibility to make, buy, or outsource business and IT solutions
  - Understanding how return on investment changes over time
- Faster, simpler, and cheaper procurement:
  - Buying decisions are simpler, because the information governing procurement is readily available in a coherent plan
  - The procurement process is faster — maximizing procurement speed and flexibility without sacrificing architectural coherence
  - The ability to procure heterogeneous, multi-vendor open systems
  - The ability to secure more economic capabilities

What specifically would prompt the development of an Enterprise Architecture?

The reasons for embarking on an Enterprise Architecture review or development are varied, including:

- Business-driven initiatives to enable business transformation; for example, to leverage digital services and products as revenue generating assets
- Technology-driven initiatives for efficiency and cost reduction; for example, technology consolidation initiatives, where the consolidation destination can be physical, virtual, or a combination
- Merger or acquisition, where the return on investment is only realized after technology efficiencies are realized
- Management of technical debt accrued by agile development initiatives

In all of these situations, Enterprise Architecture review or development is needed to manage complexity when change involves multiple systems with multiple inter-dependencies.

Often key people identify areas of change required in order for new business goals to be met. Such people are commonly referred to as the "stakeholders" in the change. The role of the architect is to address their concerns by:

- Identifying and refining the requirements of the stakeholders
- Developing views of the architecture that show how the concerns and requirements are going to be addressed
- Showing the trade-offs that are going to be made in reconciling the potentially conflicting concerns of different stakeholders

Without the Enterprise Architecture, it is highly unlikely that all the concerns and requirements will be considered and met.

What is an architecture framework?

An architecture framework is a foundational structure, or set of structures, which can be used for developing a broad range of different architectures. It should include a method for describing both a baseline and target state of the enterprise, in terms of a set of building blocks for showing how the building blocks fit together and planning the evolution from baseline to target states.

A framework is typically tailored to meet the specific needs of the organization. Tailoring of the framework should establish a set of tools and a common vocabulary.

Why use the TOGAF Standard as a framework for Enterprise Architecture?

The TOGAF Standard has been developed through the collaborative efforts of the whole community. Using the TOGAF Standard results in Enterprise Architecture that is consistent, reflects the needs of stakeholders, employs best practice, and gives due consideration both to current requirements and the perceived future needs of the business.

Developing and sustaining an Enterprise Architecture is a technically complex process which involves many stakeholders and decision processes in the organization. The TOGAF Standard plays an important role in standardizing and de-risks the architecture development process. The TOGAF Standard provides a best practice framework for adding value, and enables the organization to build workable and economic solutions which address their business issues and needs.

The TOGAF Standard value proposition is to enable organizations to operate in an efficient and effective way using a proven and recognized set of best practices, across the enterprise and in different sectors to address specific business and technology trends.

A key consideration is that guidance provided by the standard is intended to be adapted to address different needs and particular use-cases. That means it can be used to create a sustainable Enterprise Architecture for a broad range of use-cases, including agile enterprises and Digital Transformation.

Who would benefit from using the TOGAF Standard?

Any organization undertaking, or planning to undertake, the development and implementation of an Enterprise Architecture for the support of business transformation will benefit from use of the TOGAF Standard.

Organizations seeking Boundaryless Information Flow™can use the TOGAF Standard to define and implement the structures and processes to enable access to integrated information within and between enterprises.

Organizations that design and implement Enterprise Architectures using the TOGAF Standard are assured of a design and a procurement specification that can facilitate an open systems implementation, thus enabling the benefits of open systems with reduced risk.

Organizations that need to adapt to face new business and market challenges, to improve value propositions to their customers as part of Digital Transformation.

When should Enterprise Architecture be done?

To get the greatest benefit from Enterprise Architecture it should be done early and throughout the change process to help decision-makers understand the implications of their decisions. Without this understanding, costly mistakes can be made and Enterprise Architecture is not serving it fullest potential. Enterprise Architecture done after decisions are made is merely documentation of those decisions or at best enforcement of those decisions. No insight is gained as to the effect of those decisions which could be far-reaching and perhaps detrimental.

### 1.2 Structure of this Document

This document introduces the TOGAF Standard and the TOGAF Library, and includes definitions and referenced materials relevant to the individual elements of the Standard.

- This chapter provides a general introduction to Enterprise Architecture and the TOGAF Standard
- Chapter 2 describes:
  - The scope and structure of the materials that make up the TOGAF Standard
  - The scope and structure of the TOGAF Library
- Chapter 3 describes the core concepts that are used across the components of the TOGAF Standard
- Chapter 4 contains definitions of terms that are used consistently across the components of the TOGAF Standard
- Appendix A contains a list of documents referenced in the TOGAF Standard
- Appendix B contains a supplementary list of definitions of terms that may be encountered when reading the materials that make up the TOGAF Standard
- Appendix C contains a list of commonly used abbreviations

### 1.3 Information on Using the TOGAF Standard

#### 1.3.1 Conditions of Use

The TOGAF Standard is freely available for viewing online without a license. Alternatively, it can be downloaded and stored under license, as explained on the TOGAF information website.

In either case, the TOGAF Standard can be used freely by any organization wishing to do so to develop an architecture for use within that organization. No part of it may be reproduced, stored in a retrieval system, or transmitted, in any form or by any means, electronic, mechanical, photocopying, recording, or otherwise, for any other purpose including, but not by way of limitation, any use for commercial gain, without the prior permission of the copyright owners.

#### 1.3.2 How Much Does the TOGAF Standard Cost?

The Open Group is committed to delivering greater business efficiency by bringing together buyers and suppliers of information systems to lower the barriers of integrating new technology across the enterprise. Its goal is to realize the vision of Boundaryless Information Flow.

The TOGAF Standard is a key part of its strategy for achieving this goal, and The Open Group wants it to be taken up and used in practical architecture projects, and the experience from its use fed back to help improve it.

The Open Group therefore publishes it on its public web server, and allows and encourages its reproduction and use free-of-charge by any organization wishing to use it internally to develop an Enterprise Architecture. (There are restrictions on its commercial use, however; see Section 1.3.1.)

#### 1.3.3 Downloads

Downloads of the TOGAF Standard, including printable PDF files, are available under license from the TOGAF information website (refer to www.opengroup.org/togaf/downloads). The license is free to any organization wishing to use the standard entirely for internal purposes (for example, to develop an Enterprise Architecture for use within that organization).

### 1.4 Why Join The Open Group?

Organizations wishing to reduce the time, cost, and risk of implementing multi-vendor solutions that integrate within and between enterprises need The Open Group as their key partner.

The Open Group brings together the buyers and suppliers of information systems worldwide, and enables them to work together, both to ensure that IT solutions meet the needs of customers, and to make it easier to integrate IT across the enterprise. The TOGAF Standard is a key enabler in this task.

Yes, the TOGAF Standard itself is freely available. But how much will you spend on developing or updating your Enterprise Architecture? And how much will you spend on procurements based on that architecture? The price of membership of The Open Group is insignificant in comparison with these amounts.

In addition to the general benefits of membership, as a member of The Open Group you will be eligible to participate in The Open Group Architecture Forum, which is the development program within which the TOGAF Standard is evolved, and in which TOGAF users come together to exchange information and feedback. Members of the Architecture Forum gain:

- Immediate access to the fruits of the current TOGAF work program (not publicly available until publication of the next edition of the TOGAF Standard) — in effect, the latest information on the standard
- Exchange of experience with other customer and vendor organizations involved in Enterprise Architecture in general, and networking with architects using the TOGAF Standard in significant architecture development projects around the world
- Peer review of specific architecture case study material

## Chapter 2: The TOGAF Documentation Set

### 2.1 Structure of the TOGAF Documentation Set

The TOGAF documentation set consists of a portfolio of documents illustrated in Figure 2-1.

![Figure 2-1: The TOGAF Documentation Set](images/01-introduction-and-core-concepts-figure-2-1-p21.png)

*Figure 2-1: The TOGAF Documentation Set*

The TOGAF Standard

The TOGAF Standard describes the generally applicable approach to Enterprise and IT Architecture. It is presented as a series of free-standing, but closely linked documents, as shown in Figure 2-1.

The TOGAF Standard is a standard of The Open Group. The Open Group works with customers and suppliers of technology products and services, and with consortia and other standards organizations to capture, clarify, and integrate current and emerging requirements, establish standards and policies, and share best practices. Standards ensure openness, interoperability, and consensus.

The TOGAF Library

The TOGAF Library is a portfolio of additional guidance material, which supports the practical application of the TOGAF approach.

### 2.2 The TOGAF Standard

The TOGAF Standard is an open, industry consensus framework for Enterprise Architecture.

It is a foundational framework, which means that it is applicable to the development of any kind of architecture in any context. This foundational framework is supplemented by The Open Group TOGAF Library, an extensive and growing portfolio of guidance material, providing practical guidance in the application of the TOGAF framework in specific contexts.

The structure of the TOGAF Standard reflects the structure and content of an Architecture Capability within an enterprise, as shown in Figure 2-2.

![Figure 2-2: Structure of the TOGAF Standard](images/01-introduction-and-core-concepts-figure-2-2-p23.png)

*Figure 2-2: Structure of the TOGAF Standard*

The TOGAF Standard Fundamental Content is presented as six free-standing documents:

- The TOGAF Standard — Introduction and Core Concepts (this document)
- The TOGAF Standard — Architecture Development Method

This document describes the TOGAF Architecture Development Method (ADM) — an iterative approach to developing an Enterprise Architecture.

- The TOGAF Standard — ADM Techniques

This document contains a collection of techniques available for use in applying the TOGAF approach and the TOGAF ADM.

- The TOGAF Standard — Applying the ADM

This document contains guidelines for adapting the TOGAF ADM to address the specific style of architecture required in a practical context.

- The TOGAF Standard — Architecture Content

This document describes the TOGAF Content Framework and a structured metamodel for architectural artifacts, the use of re-usable Architecture Building Blocks (ABBs), and an overview of typical architecture deliverables.

- The TOGAF Standard — Enterprise Architecture Capability and Governance

This document discusses the organization, processes, skills, roles, and responsibilities required to establish and operate an architecture function within an enterprise and describes an Enterprise Architecture governance framework.

The intention of dividing the TOGAF Standard into these independent documents is to allow for different areas of specialization to be considered in detail and potentially addressed in isolation. Although all the constituent documents work together as a whole, it is also feasible to select particular documents for adoption while excluding others. For example, an organization may wish to adopt the ADM process, but elect not to use any of the materials relating to Architecture Capability. As an open framework, such use is encouraged, particularly in the following situations:

- Organizations that are new to the TOGAF approach and wish to incrementally adopt TOGAF concepts are expected to focus on particular constituent documents of the standard for initial adoption, with other areas tabled for later consideration
- Organizations that have already deployed architecture frameworks may choose to merge these frameworks with aspects of the TOGAF Standard

The TOGAF Standard comprises the TOGAF Fundamental Content and a collection of TOGAF Series Guides, which provide the practical guidance in the application of the TOGAF Standard.

![Figure 2-3: depicts the structure and scope of the TOGAF Standard.](images/01-introduction-and-core-concepts-figure-2-3-p24.png)

*Figure 2-3: depicts the structure and scope of the TOGAF Standard.*

*Figure 2-3: The TOGAF Standard*

Besides the core framework content covered by the six documents explained above, the standard provides guidance to address specific concerns and use-cases through the TOGAF Series Guides.

The TOGAF Series Guides are designed to support more specific needs from practitioners who need further explanation or more detail than that provided in the core content.

Not all the TOGAF Series Guides will be relevant in every situation. However, Enterprise

Architects who are planning the deployment of the TOGAF Standard should be aware of the guidance available.

This content will evolve more rapidly than the core content to cover new needs as they emerge from market trends and the needs of the industry. There is a set of activities running continuously in The Open Group Architecture Forum to deliver this content following a continuous and incremental delivery pipeline.

Examples of the areas covered by this guidance material are:

- Strategy decision-making and business value-oriented decisions
- Business Architecture and operating model description
- Information and data management
- Information system guidance
- Information reference models and data integration models
- Technology Architecture: how Enterprise Architecture as a practice can be applied to adopt new technology trends to assess if the organization owns the right capabilities to support the new technology adoption
- Security Architecture: how the TOGAF Standard can be applied to deliver and support Security Architecture and risk management
- How Enterprise Architecture as a practice and the TOGAF Standard can be applied to support the agile enterprise, to be delivered following an agile style, and how the standard can support organizations using agile methodologies
- How Enterprise Architecture as a practice and the TOGAF Standard support the digital enterprise so that organizations can deliver digital products, and improve their digital offering and digital value proposition
- How the standard can be applied with other standards and methodologies of The Open Group such as the O-AA™Standard, the DPBoK™Standard, the IT4IT™Reference Architecture, the ArchiMate® Specification, Microservices Architecture (MSA), security standards, and also with other standards bodies’ standards and best practices

The complete set of TOGAF Series Guides can be found at www.opengroup.org/library/guides/togaf/togaf-series-guides.

### 2.3 The TOGAF Library

Accompanying the TOGAF Standard is a broad portfolio of guidance material, known as the TOGAF Library,2 to support the practical application of the TOGAF approach. The TOGAF Library is a reference library containing guidelines, templates, patterns, and other forms of reference material to accelerate the creation of new architectures for the enterprise.

The TOGAF Library is maintained under the governance of The Open Group Architecture Forum.

The TOGAF Library supports one of the classes of information in the TOGAF Enterprise Architecture Repository, the Reference Library.

The Reference Library provides guidelines, templates, patterns, and other forms of reference material that can be leveraged in order to accelerate the creation of new architectures for the enterprise.

The TOGAF Library is a Reference Library of potentially useful resources. The TOGAF Library follows a categorization model based on capabilities and features that can be delivered into the market through different sets of documents and resources, as depicted in Figure 2-4.

![Figure 2-4: The TOGAF Library Continuum](images/01-introduction-and-core-concepts-figure-2-4-p26.png)

*Figure 2-4: The TOGAF Library Continuum*

## Chapter 3: Core Concepts

For the purposes of the TOGAF Standard, the core concepts provided in this chapter apply.

### 3.1 What is the TOGAF Standard?

The TOGAF Standard is an architecture framework. It provides the methods and tools for assisting in the acceptance, production, use, and maintenance of an Enterprise Architecture. It is based on an iterative process model supported by best practices and a re-usable set of existing architecture assets. See Section 2.2.

### 3.2 What is Architecture in the Context of the TOGAF Standard?

ISO/IEC/IEEE 42010: 2011 defines "architecture" as:

"The fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution."

The TOGAF Standard embraces but does not strictly adhere to ISO/IEC/IEEE 42010: 2011 terminology. In addition to the ISO/IEC/IEEE 42010: 2011 definition of "architecture", the TOGAF Standard defines a second meaning depending upon the context:

"The structure of components, their inter-relationships, and the principles and guidelines governing their design and evolution over time."

The TOGAF Standard considers the enterprise as a system and endeavors to strike a balance between promoting the concepts and terminology drawn from relevant standards, and commonly accepted terminology that is familiar to the majority of the TOGAF readership. For more on terminology, refer to Chapter 4 and the TOGAF Standard — Architecture Content.

### 3.3 What Kind of Architecture Does the TOGAF Standard Deal With?

There are four architecture domains that are commonly accepted as subsets of an overall Enterprise Architecture, all of which the TOGAF Standard is designed to support:

- The Business Architecture defines the business strategy, governance, organization, and key business processes
- The Data Architecture describes the structure of an organization’s logical and physical data assets and data management resources
- The Application Architecture provides a blueprint for the individual applications to be deployed, their interactions, and their relationships to the core business processes of the organization
- The Technology Architecture describes the digital architecture and the logical software and hardware infrastructure capabilities and standards that are required to support the deployment of business, data, and applications services. This includes digital services, Internet of Things (IoT), social media infrastructure, cloud services, IT infrastructure, middleware, networks, communications, processing, standards, etc.

There are many other domains that could be defined by combining appropriate views of the Business, Data, Application, and Technology domains. For example:

- Information Architecture
- Risk and Security Architectures
- Digital Architecture

The TOGAF framework enables the creation of these multi-dimensional views and categorizes them to create specific domains that enable an enterprise to consider the wider scope of their enterprise and capabilities.

### 3.4 Architecture Development Method

The TOGAF Architecture Development Method (ADM) provides a tested and repeatable process for developing architectures. The ADM includes establishing an architecture framework, developing architecture content, transitioning, and governing the realization of architectures.

All of these activities are carried out within an iterative cycle of continuous architecture definition and realization that allows organizations to transform their enterprises in a controlled manner in response to business goals and opportunities. This is illustrated in Figure 3-1.

![Figure 3-1: Architecture Development Cycle](images/01-introduction-and-core-concepts-figure-3-1-p29.png)

*Figure 3-1: Architecture Development Cycle*

Phases within the ADM are as follows:

- The Preliminary Phase describes the preparation and initiation activities required to create an Architecture Capability including customization of the TOGAF framework and definition of Architecture Principles
- Phase A: Architecture Vision describes the initial phase of an architecture development cycle

It includes information about defining the scope of the architecture development initiative, identifying the stakeholders, creating the Architecture Vision, and obtaining approval to proceed with the architecture development.

- Phase B: Business Architecture describes the development of a Business Architecture to support the agreed Architecture Vision
- Phase C: Information Systems Architectures describes the development of Information Systems Architectures to support the agreed Architecture Vision
- Phase D: Technology Architecture describes the development of the Technology Architecture to support the agreed Architecture Vision
- Phase E: Opportunities & Solutions conducts initial implementation planning and the identification of delivery vehicles for the architecture defined in the previous phases
- Phase F: Migration Planning addresses how to move from the Baseline to the Target Architectures by finalizing a detailed Implementation and Migration Plan
- Phase G: Implementation Governance provides an architectural oversight of the implementation
- Phase H: Architecture Change Management establishes procedures for managing change to the new architecture
- Requirements Management operates the process of managing architecture requirements throughout the ADM

The description of the phases of the ADM in the TOGAF Standard — Architecture Development Method focuses on recommendations on what may be done to define and deploy an Enterprise Architecture.

Guidance on how to do what is specified can be found in the TOGAF Series Guides (see Section 2.2). A full list of referenced TOGAF Series Guides is included in Appendix A.

The TOGAF framework recommends that the ADM be adapted to meet the needs of the enterprise and to support different architecture styles (see Section 3.16).

In particular, the ADM does not:

- Mandate that the phases must be performed in any specific sequence
- Mandate a "waterfall" method

The TOGAF Standard describes how the ADM can be used iteratively to develop a comprehensive Enterprise Architecture landscape. Rather than viewing the ADM graphic as a process model, it is helpful to view it as a reference model defining what has to be done in order to deliver solutions in an architected way and identifying interacting components across the enterprise and the relationships between them.

### 3.5 Enterprise Architecture Services

Activities described in the ADM are often provided through a service delivery model. The services are organized and presented in service categories. These services address specific needs independent of an organization’s specific operation model. Any given service described utilizes the appropriate activities in the ADM to address a given need.

*Table 3-1: summarizes the proposed service categories and provides some context. The first*

four categories are customer-centric and the others are more internally centered on architects. Each service category is briefly described in the following subsections.

*Table 3-1: Service Categories and Descriptors*

Descriptor

Typical Typical Categories Customer Provider Deliverable(s) Desired Result Customer-centric Enterprise C-level Enterprise Answers to Better enterprise Support Services management analysts using questions decisions Enterprise Assessment Lower risk Architecture as a reports tool Recommendations

Design Support Program-level Enterprise MVAs (including Better design Services decision-makers Architect standards and decisions builder/modeler compliance Successful criteria, programs and roadmaps) for projects programs

Compliance guidance

Compliance reports

Development Project-level Enterprise MVAs (including Better product Support Services decision-makers Architect standards and decisions builder/modeler compliance Successful criteria) for products projects/products

Compliance guidance

Compliance reports

Requirements Product Enterprise Stakeholder Solid outside-in Elicitation and managers Architect with concerns view of Understanding requirements requirements and Requirements Services understanding value for specialty Assessments solutions (value, ability, etc.) balanced among stakeholders

Internal-centric Architecture Architecture Experienced Architecture Resourced Planning team leaders Enterprise project plans architecture team Services Architect

Descriptor

Typical Typical Categories Customer Provider Deliverable(s) Desired Result Enterprise Architecture Enterprise Enterprise Highly skilled and Architecture organization Architecture Architecture organized Practice decision-makers practice experts Capability Enterprise Development assessments Architecture Support Services practice Enterprise organization Architecture (internal or Capability external) improvement recommendations

#### 3.5.1 Enterprise Support Services

This service category contains candidate services that enable informed enterprise decisions in support of organization change. These services could be provided independent of any individual project. These services focus on answering questions and providing enterprise analysis in support of strategic decisions.

#### 3.5.2 Design Support Services

This service category contains candidate services that enable informed design decisions in support of organization change. These services would typically be provided after a project has been funded, whether large or small, waterfall or agile. These services include the development of Minimum Viable Architectures (MVAs) and associated analysis to support the design decisions.

#### 3.5.3 Development Support Services

This service category contains candidate services that enable informed development decisions in support of organization change. These services would typically be provided during the development phase of a project, whether large or small, waterfall or agile. These services focus on answering questions and providing enterprise analysis in support of development decisions.

#### 3.5.4 Requirements Elicitation and Understanding Services

This service category contains candidate services that enable requirements understanding. Taking a step beyond requirements management, these services help get closer to real need that will deliver greater business value.

#### 3.5.5 Architecture Planning Services

This service category contains candidate services that enable well-planned and executed architecture projects in support of organization change. These services would typically be provided at the beginning of a "project" whether large or small, waterfall or agile.

#### 3.5.6 Enterprise Architecture Practice Development Support Services

This service category contains candidate services that enable the development and management of an Enterprise Architecture practice. These services are focused on improving Enterprise Architecture Capability.

### 3.6 Deliverables, Artifacts, and Building Blocks

Architects executing the ADM will produce a number of outputs as a result of their efforts, such as process flows, architectural requirements, project plans, project compliance assessments, etc. The TOGAF Architecture Content Framework (see the TOGAF Standard — Architecture Content) provides a structural model for architectural content that allows major work products to be consistently defined, structured, and presented.

The Architecture Content Framework uses the following three categories to describe the type of architectural work product within the context of use:

- A deliverable is a work product that is contractually specified and in turn formally reviewed, approved, and signed off by the stakeholders

Deliverables represent the output of projects and those deliverables that are in documentation form will typically be archived at completion of a project, or transitioned into an Architecture Repository as a reference model, standard, or snapshot of the Architecture Landscape at a point in time.

- An artifact is an architectural work product that describes an aspect of the architecture

Artifacts are generally classified as catalogs (lists of things), matrices (showing relationships between things), and diagrams (pictures of things). Examples include a requirements catalog, application interaction matrix, and a value chain diagram. An architectural deliverable may contain one or more artifacts and artifacts will form the content of the Architecture Repository. An artifact may or may not be considered a deliverable based on the contractual specification.

- A building block represents a potentially re-usable component that can be combined with other building blocks to deliver architectures and solutions

Building blocks can be defined at various levels of detail, depending on what stage of architecture development has been reached. For instance, at an early stage, a building block can simply consist of a name or an outline description. Later on, a building block may be decomposed into multiple supporting building blocks and may be accompanied by a full specification. Building blocks can relate to "architectures" or "solutions".

  - Architecture Building Blocks (ABBs) typically describe required capability and shape the specification of Solution Building Blocks (SBBs); for example, a customer services capability may be required within an enterprise, supported by many SBBs, such as processes, data, and application software
  - Solution Building Blocks (SBBs) represent components that will be used to implement the required capability; for example, a network is a building block that can be described through complementary artifacts and then put to use to realize solutions for the enterprise

The relationships between deliverables, artifacts, and building blocks are shown in Figure 3-2.

![Figure 3-2: Relationships between Deliverables, Artifacts, and Building Blocks](images/01-introduction-and-core-concepts-figure-3-2-p34.png)

*Figure 3-2: Relationships between Deliverables, Artifacts, and Building Blocks*

For example, an Architecture Definition Document is a deliverable that documents an Architecture Description. This document will contain a number of complementary artifacts that are views of the building blocks relevant to the architecture. For example, a process flow diagram (an artifact) may be created to describe the target call handling process (a building block). This artifact may also describe other building blocks, such as the actors involved in the process (e.g., a Customer Services Representative). An example of the relationships between deliverables, artifacts, and building blocks is illustrated in Figure 3-3.

![Figure 3-3: Example — Architecture Definition Document](images/01-introduction-and-core-concepts-figure-3-3-p35.png)

*Figure 3-3: Example — Architecture Definition Document*

The concepts of Deliverables, Artifacts, and Building Blocks are described in more detail in the TOGAF Standard — Architecture Content.

The TOGAF Standard — ADM Techniques describes the Architecture Development Method and includes summary lists of Deliverables and Artifacts that may be created in each phase. The TOGAF Standard — Architecture Content contains detailed descriptions of these.

### 3.7 Architecture Abstraction

An architectural technique for dividing a problem area into smaller problem areas that are easier to model and therefore easier to solve.

Abstraction levels are layered in nature, moving from high-level models to more detailed models.

Architecture effort can be divided into four distinct abstraction levels that cross the Business, Data, Application, and Technology domains to answer fundamental questions about an architecture:

- Why — why is the architecture needed?
- What — what functionality and other requirements need to be met by the architecture?
- How — how do we structure the functionality?
- With what — with what assets shall we implement this structure? Note that why, what, and how have no connection to their use in the Zachman® Enterprise Architecture Framework.

#### 3.7.1 Contextual Abstraction Level

This abstraction level is focused on understanding the environment in which an enterprise operates and the context in which architecture work is planned and executed. It answers why an enterprise undertakes architecture work, what is the scope of work, and the motivation in terms of goals, drivers, and objectives.

#### 3.7.2 Conceptual Abstraction Level

This abstraction level is centered on decomposing the requirements to understand the problem, and what is needed to address the problem, without unduly focusing on how the architecture will be realized. It answers what is necessary to realize the requirements and is usually modeled using service models (business service, application service, technology service) that represent desired behavior.

Note this abstraction level can also be referred to as either service abstraction or behavior abstraction.

#### 3.7.3 Logical Abstraction Level

This abstraction level is focused on identifying the kinds of business, data, application, and technology components needed to achieve the services identified in the conceptual level. It is about identifying how an architecture can be organized and structured, in an implementation-independent fashion. There will potentially be several ways to group services into logical components, based on principles and other grouping criteria, providing different logical solution alternatives.

#### 3.7.4 Physical Abstraction Level

This abstraction level manages the allocation and implementation of physical components to meet the identified logical components. It is about determining with what physical components the logical-level components can be realized. There will potentially be many ways to use physical components to realize logical components, based on principles and other grouping criteria, providing different physical solution alternatives.

### 3.8 Architecture Principles

Principles are general rules and guidelines, intended to be enduring and seldom amended, that inform and support the way in which an organization sets about fulfilling its mission.

Depending on the organization, principles may be established within different domains and at different levels. Two key domains inform the development and utilization of architecture:

- Enterprise Principles provide a basis for decision-making throughout an enterprise, and inform how the organization sets about fulfilling its mission

Such principles are commonly found as a means of harmonizing decision-making across an organization. In particular, they are a key element in a successful Architecture Governance strategy (see TOGAF Standard — Enterprise Architecture Capability and Governance).

Within the broad domain of Enterprise Principles, it is common to have subsidiary principles within a business or organizational unit; for example, principles specific to IT, HR, domestic operations, or overseas operations. These principles provide a basis for decision-making within the subsidiary domain and will inform architecture development within the domain. Care must be taken to ensure that the principles used to inform architecture development align to the organizational context of the Architecture Capability.

- Architecture Principles are a set of principles that relate to architecture work

They reflect a level of consensus across the enterprise and embody the spirit and thinking of existing Enterprise Principles. Architecture Principles govern the architecture process, affecting the development, maintenance, and use of the Enterprise Architecture.

Within an enterprise the hierarchy of principles starts with the Enterprise Principles. The subsidiary segment principles must exist within the bounds of these Enterprise Principles which are overarching. Consequently, at each hierarchical level the set of principles will be informed by and elaborate on the principles inherited from the level above and cannot overstep their boundaries.

Architecture Principles may restate other enterprise guidance in terms and form that effectively guide architecture development.

Architecture Principles define the underlying general rules and guidelines for the use and deployment of all resources and assets across the enterprise. They reflect a level of consensus among the various elements of the enterprise and form the basis for making future architecture decisions.

Each Architecture Principle should be clearly related back to the business objectives and key architecture drivers.

Architecture Principles are further explained in the TOGAF Standard — ADM Techniques.

### 3.9 Interoperability

A definition of interoperability is "the ability to share information and services". Defining the degree to which the information and services are or are not to be shared is a very useful architectural requirement, especially in a complex organization and/or extended enterprise.

The determination of interoperability is present throughout the Architecture Development Method (ADM) as follows:

- In the Architecture Vision (Phase A), the nature and security considerations of the information and service exchanges are first revealed within the business scenarios
- In the Business Architecture (Phase B), the information and service exchanges are further defined in business terms
- In the Data Architecture (Phase C), the content of the information exchanges is detailed using the corporate data and/or information exchange model
- In the Application Architecture (Phase C), the way that the various applications are to share the information and services is specified
- In the Technology Architecture (Phase D), the appropriate technical mechanisms to permit the information and service exchanges are specified
- In Opportunities & Solutions (Phase E), the actual solutions (e.g., Commercial Off-The-Shelf (COTS) packages) are selected
- In Migration Planning (Phase F), the interoperability is logically implemented

There are many ways to define interoperability and the aim is to define one that is consistently applied within the enterprise and extended enterprise. It is best that both the enterprise and the extended enterprise use the same definitions.

Many organizations find it useful to categorize interoperability as follows:

- Operational or Business Interoperability defines how different parts of the enterprise work together at the business level
- Information Interoperability defines how information is to be shared
- Technical Interoperability defines how technical resources are to be shared or at least connect to one another

From an IT perspective, it is also useful to consider interoperability in a similar vein to Enterprise Application Integration (EAI); specifically:

- Presentation Integration/Interoperability is where a common look-and-feel approach through a common portal-like solution guides the user to the underlying functionality of the set of systems
- Information Integration/Interoperability is where the corporate information is seamlessly shared between the various corporate applications to achieve, for example, a common set of client information

Normally this is based upon a commonly accepted corporate ontology and shared services for the structure, quality, access, and security/privacy for the information.

- Application Integration/Interoperability is where the corporate functionality is integrated and shareable so that the applications are not duplicated (e.g., one change of address service/component; not one for every application) and are seamlessly linked together through functionality such as workflow

This impacts the business and infrastructure applications and is very closely linked to corporate business process unification/interoperability.

- Technical Integration/Interoperability includes common methods and shared services for the communication, storage, processing, and access to data primarily in the application platform and communications infrastructure domains

Interoperability and Interoperability Requirements are addressed in detail in the TOGAF Standard — ADM Techniques.

### 3.10 Enterprise Continuum

The TOGAF Standard includes the concept of the Enterprise Continuum, which sets the broader context for an architect and explains how generic solutions can be leveraged and specialized in order to support the requirements of an individual organization.

The Enterprise Continuum is a categorization for assets held in the Enterprise Repositories that provides methods for classifying assets, including architecture and solution artifacts as they evolve from generic Foundation Architectures to Organization-Specific Architectures. The

Enterprise Continuum comprises two complementary concepts: the Architecture Continuum and the Solutions Continuum.

The Enterprise Continuum is described in detail in the TOGAF Standard — Architecture Content.

An overview of the structure and context for the Enterprise Continuum is shown in Figure 3-4.

External factors

![Figure 3-4: Enterprise Continuum](images/01-introduction-and-core-concepts-figure-3-4-p39.png)

*Figure 3-4: Enterprise Continuum*

### 3.11 Architecture Repository

Supporting the Enterprise Continuum is the concept of an Architecture Repository which can be used to store different classes of architectural output at different levels of abstraction, created by the ADM. In this way, the TOGAF Standard facilitates understanding and co-operation between stakeholders and practitioners at different levels.

By means of the Enterprise Continuum and Architecture Repository, architects are encouraged to leverage all other relevant architectural resources and assets in developing an Organization-Specific Architecture. In this context, the TOGAF ADM can be regarded as describing a process lifecycle that operates at multiple levels within the organization, operating within a holistic governance framework and producing aligned outputs that reside in an Architecture Repository. The Enterprise Continuum provides a valuable context for understanding architectural models: it shows building blocks and their relationships to each other, and the constraints and requirements on a cycle of architecture development.

The structure of the TOGAF Architecture Repository is shown in Figure 3-5.

![Figure 3-5: TOGAF Architecture Repository Structure](images/01-introduction-and-core-concepts-figure-3-5-p40.png)

*Figure 3-5: TOGAF Architecture Repository Structure*

The major components within an Architecture Repository are as follows:

- The Architecture Metamodel describes the organizationally tailored application of an architecture framework, including a metamodel for architecture content
- The Architecture Capability defines the parameters, structures, and processes that support governance of the Architecture Repository
- The Architecture Landscape is the architectural representation of assets deployed within the operating enterprise at a particular point in time — the landscape is likely to exist at multiple levels of abstraction to suit different architecture objectives
- The Standards Library captures the standards with which new architectures must comply, which may include industry standards, selected products and services from suppliers, or shared services already deployed within the organization
- The Reference Library provides guidelines, templates, patterns, and other forms of reference material that can be leveraged in order to accelerate the creation of new architectures for the enterprise
- The Governance Repository provides a record of governance activity across the enterprise
- The Architecture Requirements Repository provides a view of all authorized architecture requirements which have been agreed with the Architecture Board
- The Solutions Landscape presents an architectural representation of the SBBs supporting the Architecture Landscape which have been planned or deployed by the enterprise

The TOGAF Architecture Repository is described in the TOGAF Standard — Architecture Content.

### 3.12 TOGAF Content Framework and Enterprise Metamodel

#### 3.12.1 Overview

The TOGAF ADM provides lifecycle management to create and manage architectures within an enterprise. At each phase within the ADM, a discussion of inputs, outputs, and steps describes a number of architectural work products.

An essential task when establishing the enterprise-specific Enterprise Architecture Capability in the Preliminary Phase of the ADM is to define:

- A categorization framework to be used to structure the Architecture Descriptions, the work products used to express an architecture, and the collection of models that describe the architecture; this is referred to as the Content Framework
- An understanding of the types of entities within the enterprise and the relationships between them that need to be captured, stored, and analyzed in order to create the Architecture Description; this Enterprise Metamodel depicts this information in the form of a formal model
- The specific artifacts to be developed (see Section 3.6)

The Content Framework chosen is likely to be influenced by:

- The Architecture Framework selected as the basis for the Enterprise Architecture Capability
- The chosen software tool used to support the Enterprise Architecture Capability

#### 3.12.2 Content Framework

The Content Framework defines a categorization framework to be used to describe the building blocks and artifacts reflecting decisions taken in creating the overall architecture deliverables.

The Architecture Repository, which is explained in Section 3.11, is structured to store the artifacts and work products identified in the Content Framework. The Content Framework is one element of the Enterprise-Specific Architecture Framework.

There are many alternative Content Frameworks (e.g., the TOGAF Content Framework, the Zachman Framework, DoDAF, NAF, etc.). Selecting a Content Framework is essential even though the choice of Content Framework is less important. The final Content Framework is usually adapted to fit specific organization needs.

The TOGAF Content Framework is intended to:

- Provide a detailed model of architectural work products
- Drive consistency in the outputs created when following the ADM
- Provide a comprehensive checklist of architecture output that could be created
- Reduce the risk of gaps within the final architecture deliverable set
- Help an enterprise mandate standard architecture concepts, terms, and deliverables

At the highest level, the TOGAF Content Framework (see Figure 3-6) is structured in line with the phases of the ADM.

![Figure 3-6: Content Framework by ADM Phase](images/01-introduction-and-core-concepts-figure-3-6-p42.png)

*Figure 3-6: Content Framework by ADM Phase*

capture the surrounding context of formal architecture models, including general Architecture Principles, strategic context that forms input for architecture modeling, and requirements generated from the architecture

The relevant aspects of the business context that have given rise to the Request for Architecture work are typically investigated, refined, validated, and recorded in the Preliminary and Architecture Vision phases.

- Business Architecture captures architecture models of the business, looking specifically at factors that motivate the enterprise, its structure, and its capabilities
- Information Systems Architecture models capture architecture models of IT systems, looking at applications and data in line with the TOGAF ADM phases
- Technology Architecture models capture technology assets that are used to implement and realize information system solutions
- Architecture Realization/Transformation models capture change roadmaps showing transition between architecture states and binding statements that are used to steer and govern an implementation of the architecture
- Architecture Change Management models capture value realization management events, internal and external, that impact the Enterprise Architecture and the generation of requirements for action

The TOGAF Content Framework is described in detail in the TOGAF Standard — Architecture Content.

#### 3.12.3 Enterprise Metamodel

The TOGAF Standard encourages development of an Enterprise Metamodel, which defines the types of entity to appear in the models that describe the enterprise, together with the relationships between these entities.

For example, one type in an Enterprise Metamodel might be Role. Then the enterprise’s Business Architecture models might include such instances of Role as Teller, Pilot, Manager, Volunteer, Customer, or Firefighter. Of course it would be an unusual enterprise that had all of these roles.

An Enterprise Metamodel provides value in several ways:

- It gives architects a starter set of the types of thing to investigate and to cover in their models
- It provides a form of completeness-check for any architecture modeling language, or architecture metamodel, that is proposed for use in an enterprise

Namely, how completely does it handle the types of entity in the Enterprise Metamodel, and manage required facts about them such as their attributes and relationships?

- It can help ensure:
  - Consistency
  - Completeness
  - Traceability

Note that the TOGAF Standard does not aim to constrain an enterprise’s:

- Selection of artifacts
- Modeling notation The TOGAF Standard may use a variety of modeling languages, such as the ArchiMate® modeling language, Business Process Modeling Notation™(BPMN™), Unified Modeling Language™(UML®), entity relationship diagramming, flowcharting, or any other notation that can express some TOGAF ideas.

The types of entity within an enterprise and the relationships between them are specific to the individual enterprise. Developing a high-quality metamodel is an important aspect of establishing the Enterprise Architecture Capability.

#### 3.12.4 Developing the Enterprise Metamodel

The Enterprise Metamodel is an important part of the Organization-Specific Architecture Framework, as highlighted here. Figure 3-7 shows how the Enterprise Continuum (see Section 3.10) provides a way to consider resources on a scale ranging from the most general ("Foundation") to most specific ("Organization-Specific"):

© The Open Group

Foundation Common Industry Organization-specific

![Figure 3-7: Applying the Enterprise Continuum](images/01-introduction-and-core-concepts-figure-3-7-p44.png)

*Figure 3-7: Applying the Enterprise Continuum*

To support development of the enterprise’s metamodel, the TOGAF Library includes a Foundation-level Core Enterprise Metamodel, detailed in the TOGAF Standard — Architecture Content. It shows types of entity, and relationships between them, that are likely to be required in modeling most enterprises and provides a context for the artifacts suggested in the ADM.

The Foundation Enterprise Metamodel is illustrated in Figure 3-8.

![Figure 3-8: The TOGAF Core Enterprise Metamodel](images/01-introduction-and-core-concepts-figure-3-8-p45.png)

*Figure 3-8: The TOGAF Core Enterprise Metamodel*

### 3.13 Establishing and Maintaining an Enterprise Architecture Capability

In order to carry out architectural activity effectively within an enterprise, it is necessary to put in place an appropriate business capability for architecture, through organization structures, roles, responsibilities, skills, and processes. An overview of the TOGAF Architecture Capability is shown in Figure 3-9.

![Figure 3-9: TOGAF Architecture Capability Overview](images/01-introduction-and-core-concepts-figure-3-9-p46.png)

*Figure 3-9: TOGAF Architecture Capability Overview*

### 3.14 Establishing the Architecture Capability as an Operational Entity

Barring Architecture Capabilities set up to purely support change delivery programs, it is increasingly recognized that a successful Enterprise Architecture practice must sit on a firm operational footing. In effect, an Enterprise Architecture practice must be run like any other operational unit within a business; i.e., it should be treated like a business. To this end, and over and above the core processes defined within the ADM, an Enterprise Architecture practice should establish capabilities in the following areas:

- Financial Management
- Performance Management
- Service Management
- Risk and Opportunity Management (see Section B.34)
- Resource Management
- Communications and Stakeholder Management (see Section 4.36)
- Quality Management
- Supplier Management (see Section B.40)
- Configuration Management (see Section B.7)
- Environment Management

Central to the notion of operating an ongoing architecture is the execution of well-defined and effective governance, whereby all architecturally significant activity is controlled and aligned within a single framework.

As governance has become an increasingly visible requirement for organizational management, the inclusion of governance within the TOGAF Standard aligns the framework with current business best practice and also ensures a level of visibility, guidance, and control that will support all architecture stakeholder requirements and obligations.

The benefits of Architecture Governance include:

- Increased transparency of accountability, and informed delegation of authority
- Proactive risk and opportunity management
- Protection of the existing asset base through maximizing re-use of existing architectural components
- Proactive control, monitoring, and management mechanisms
- Process, concept, and component re-use across all organizational business units
- Value creation through monitoring, measuring, evaluation, and feedback
- Increased visibility supporting internal processes and external parties’ requirements; in particular, increased visibility of decision-making at lower levels ensures oversight at an appropriate level within the enterprise of decisions that may have far-reaching strategic consequences for the organization
- Greater shareholder value; in particular, Enterprise Architecture increasingly represents the core intellectual property of the enterprise — studies have demonstrated a correlation between increased shareholder value and well-governed enterprises
- Integrates with existing processes and methodologies and complements functionality by adding control capabilities

Further detail on establishing an Enterprise Architecture Capability is given in the TOGAF Standard — Enterprise Architecture Capability and Governance.

### 3.15 Using the TOGAF Standard with Other Frameworks

Two of the key elements of any Enterprise Architecture framework are:

- A definition of the deliverables that the architecting activity should produce
- A description of the method by which this should be done

With some exceptions, the majority of Enterprise Architecture frameworks focus on the first of these — the specific set of deliverables — and are relatively silent about the methods to be used to generate them (intentionally so, in some cases).

Because the TOGAF Standard is a generic framework and intended to be used in a wide variety

of environments, it provides a flexible and extensible content framework that underpins a set of generic architecture deliverables.

As a result, the TOGAF framework may be used either in its own right, with the generic deliverables that it describes; or else these deliverables may be replaced or extended by a more specific set, defined in any other framework that the architect considers relevant.

In all cases, it is expected that the architect will adapt and build on the TOGAF framework in order to define a tailored method that is integrated into the processes and organization structures of the enterprise. This architecture tailoring may include adopting elements from other architecture frameworks, or integrating TOGAF methods with other standard frameworks or best practices, such as ITIL®, CMMI®, COBIT®, PRINCE2, PMBOK, and MSP®. It may also include adopting reference materials from the TOGAF Library, such as the IT4IT™Reference Architecture. Guidelines for adapting the TOGAF ADM in such a way are given in the TOGAF Standard — ADM Techniques.

As a generic framework and method for Enterprise Architecture, the TOGAF Standard provides the capability and the collaborative environment to integrate with other frameworks. Organizations are able to fully utilize vertical business domains, horizontal technology areas (such as security or manageability), or application areas (such as e-Commerce) to produce a competitive Enterprise Architecture framework which maximizes their business opportunities.

### 3.16 Using the TOGAF Framework with Different Architecture Styles

The TOGAF framework is designed to be flexible and is used with various architectural styles.

Architectural styles differ in terms of focus, form, techniques, materials, subject, and time period. The TOGAF Standard is a generic framework intended to be used in a wide variety of environments. It is a flexible and extensible framework that can be readily adapted to a number of architectural styles.

An organization’s Architecture Landscape can be expected to contain architecture work that is developed in many architectural styles. The TOGAF Standard ensures that the needs of each stakeholder are appropriately addressed in the context of other stakeholders and the Baseline Architecture.

When using the TOGAF Standard to support a specific architectural style the practitioner must take into account the combination of distinctive features in which architecture is performed or expressed. As a first step, the distinctive features of a style must be identified.

The second step is determining how these distinctive features will be addressed. Addressing a distinctive style should not call for significant changes to the TOGAF framework; instead it should adjust the models, viewpoints, and tools used by the practitioner.

In Phase B, Phase C, and Phase D the practitioner is expected to select the relevant architecture resources, including models, viewpoints, and tools, to properly describe the architecture domain and demonstrate that stakeholder concerns are addressed (see the TOGAF Standard — ADM Techniques). Depending upon the distinctive features, different architectural styles will add new elements that must be described, highlight existing elements, adjust the notation used to describe the architecture, and focus the architect on some stakeholders or stakeholder concerns.

Addressing the distinctive features will usually include extensions to the Architecture Content Metamodel and the use of specific notation or modeling techniques and the identification of

viewpoints. Dominance of a particular architectural style can direct the practitioner to revisit the Preliminary Phase to make changes to the Architecture Capability or to address a distinctive feature in the expected scope of a single ADM cycle.

Style-specific reference models and maturity models are commonly used tools that support a practitioner.

During the lifetime of the TOGAF framework many architectural styles have been developed to address key problems facing practitioners and to demonstrate how the TOGAF framework can be made more relevant within defined contexts.

Some of these have been developed by The Open Group Forums and Work Groups working in specific areas and have been published in Guides, White Papers, and Standards. Examples include:

- TOGAF® Series Guide: Using the TOGAF® Framework to Define and Govern Service-Oriented Architectures
- TOGAF® Series Guide: Integrating Risk and Security within a TOGAF® Enterprise Architecture

Some of these have been developed collaboratively between The Open Group and other bodies. Examples include:

- TOGAF® and SABSA® Integration
- Archi Banking Group: Combining the BIAN Reference Model, ArchiMate® Modeling Notation, and the TOGAF® Framework
- Exploring Synergies between TOGAF® and Frameworx
- TOGAF® 9 and DoDAF 2.0

The TOGAF Library (see www.opengroup.org/togaf-library) is a structured library of resources that support the TOGAF Standard.

### 3.17 Architecture Views and Viewpoints

The ability to create specific "views" of parts of a complex architecture is fundamental in being able to communicate with and allay concerns of stakeholders or groups of stakeholders. To gain full understanding and support from stakeholders it is necessary to present information in a form that each stakeholder will relate to and understand.

The role of architecture views is shown in Figure 3-10, adapted from more formal definitions contained in ISO/IEC/IEEE 42010: 2011 and ISO/IEC/IEEE 15288: 2015.

![Figure 3-10: Basic Architectural Concepts](images/01-introduction-and-core-concepts-figure-3-10-p50.png)

*Figure 3-10: Basic Architectural Concepts*

### 3.18 Enterprise Agility

Enterprise agility is a commonly used term, but the exact definition differs among practitioners. Regardless of how the term is defined, it is important because it enables an enterprise to better react to change by being more customer and product-centric, more efficient, and better able to ensure regulatory compliance.

The term "agile" is frequently associated with agile software development processes associated with the Manifesto for Agile Software Development.

While these "agile" principles and techniques can be applied to adapt the TOGAF framework, enterprise agility is a broader context than agile software development. Therefore, additional techniques are employed in adapting the TOGAF framework to an agile enterprise.

Enterprise Architecture provides a framework for change, linked to both strategic direction and business value. It provides a sufficient view of the organization to manage complexity, support

continuous change, and manage the risk of unanticipated consequences.

The TOGAF framework has embraced the call to respond to the needs of the enterprise in a timely manner, through the concepts of "partitions" and "levels". Partitions define how the work is broken down into multiple architecture initiatives. Levels define how the overall architecture can be developed at different levels of granularity and detail.

In addition, the TOGAF ADM supports a number of concepts that are characterized as iteration.

More detailed descriptions of how to adapt the TOGAF ADM to support enterprise agility can be found in:

- TOGAF® Series Guide: Applying the ADM Using Agile Sprints
- TOGAF® Series Guide: Enabling Enterprise Agility
- The Open Agile Architecture™Standard

### 3.19 Risk Management

There will always be risk with any architecture/business transformation effort. It is important to identify, classify, and mitigate these risks before starting so that they can be tracked throughout the transformation effort.

Mitigation is an ongoing effort and often the risk triggers may be outside the scope of the transformation planners (e.g., merger, acquisition) so planners must monitor the transformation context constantly.

It is also important to note that the Enterprise Architect may identify the risks and mitigate certain ones, but it is within the governance framework that risks have to be first accepted and then managed.

There are two levels of risk that should be considered, namely:

- Initial level of risk: risk categorization prior to determining and implementing mitigating actions
- Residual level of risk: risk categorization after implementation of mitigating actions (if any)

The process for risk management consists of the following activities:

- Risk classification
- Risk identification
- Initial risk assessment
- Risk mitigation and residual risk assessment
- Risk monitoring

A qualitative approach to risk management is described in the TOGAF Standard — ADM Techniques. Risk concepts are included in the Enterprise Security Architecture described in the TOGAF® Series Guide: Integrating Risk and Security within a TOGAF® Enterprise Architecture.

A more rigorous quantitative approach is described in the Open FAIR™Body of Knowledge which comprises two standards from The Open Group: Open Risk Taxonomy (O-RT) and Open Risk Analysis (O-RA).

## Chapter 4: Definitions

For the purposes of the TOGAF Standard, the following terms and definitions apply. Appendix B should be referenced for supplementary definitions not defined in this chapter. The Merriam-Webster® Collegiate Dictionary should be referenced for terms not defined in this section or Appendix B.

### 4.1 Abstraction

The technique of providing summarized or generalized descriptions of detailed and complex content.

Note: Abstraction, as in "level of abstraction", can also mean providing a focus for analysis that is concerned with a consistent and common level of detail or abstraction. Abstraction in this sense is typically used in architecture to allow a consistent level of definition and understanding to be achieved in each area of the architecture in order to support effective communication and decision-making. It is especially useful when dealing with large and complex architectures as it allows relevant issues to be identified before further detail is attempted.

### 4.2 Actor

A person, organization, or system that has one or more roles that initiates or interacts with activities; for example, a sales representative who travels to visit customers. Actors may be internal or external to an organization.

Note: In the automotive industry, an original equipment manufacturer would be considered an actor by an automotive dealership that interacts with its supply chain activities.

### 4.3 Application Architecture

A description of the structure and interaction of the applications that provide key business capabilities and manage the data assets.

Note: Application Architecture is described in the TOGAF Standard — Architecture Development Method.

### 4.4 Application Component

An encapsulation of application functionality aligned to implementation structure, which is modular and replaceable. It encapsulates its behavior and data, provides services, and makes them available through interfaces.

Note: For example, a business application such as an accounting, payroll, or CRM system.

An application component usually maintains a data component. It is enabled by technology services provided by technology components.

### 4.5 Application Platform

The collection of technology components of hardware and software that provide the services used to support applications.

### 4.6 Application Service

A discrete behavior requestable from an application; an automated element supporting or delivering part or all of one or more business services.

### 4.7 Architectural Style

The combination of distinctive features related to the specific context within which architecture is performed or expressed; a collection of principles and characteristics that steer or constrain how an architecture is formed.

### 4.8 Architecture

1\. The fundamental concepts or properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution. (Source: ISO/IEC/IEEE 42010: 2011)

2\. The structure of components, their inter-relationships, and the principles and guidelines governing their design and evolution over time.

### 4.9 Architecture Building Block (ABB)

An architectural component that specifies the required Solution Building Blocks (SBBs) at a more logical (or supplier-independent) level.

See also Section 4.26.

### 4.10 Architecture Continuum

A categorization mechanism, with increasing detail and specialization, for the components and artifacts stored in the Architecture Landscape or Reference Library (part of the Architecture Repository).

Note: This Continuum begins with foundational definitions like reference models, core strategies, and basic building blocks. From there it spans to Industry Architectures and all the way to an Organization-Specific Architecture.

See also Section 4.44.

### 4.11 Architecture Development Method (ADM)

The core of the TOGAF framework. A multi-phase, iterative approach to develop and use an Enterprise Architecture to shape and govern business transformation.

Note: The ADM is described in the TOGAF Standard — ADM Techniques.

### 4.12 Architecture Domain

The architectural area being considered. The TOGAF framework follows the tradition of dividing Enterprise Architecture into four primary architecture domains: business, data, application, and technology. Other domains (motivation, security, governance, etc.) may span those four primary domains.

### 4.13 Architecture Framework

A conceptual structure used to plan, develop, implement, govern, and sustain an architecture.

### 4.14 Architecture Governance

The practice of monitoring and directing architecture-related work. The goal is to deliver desired outcomes and adhere to relevant principles, standards, and roadmaps.

See also Section 4.48.

### 4.15 Architecture Landscape

The architectural representation of assets in use, or planned, by the enterprise at particular points in time.

### 4.16 Architecture Level

Levels provide a framework for dividing the Architecture Landscape into levels of granularity.

Note: Architecture levels are distinct from architecture partitions.

### 4.17 Architecture Model

A representation of a subject of interest.

Note: An architecture model provides a smaller scale, simplified, and/or abstract representation of the subject matter.

See also Section 4.75, Section 4.20, and Section 4.21.

### 4.18 Architecture Partition

A subset of architecture resulting from dividing that architecture to facilitate its development and management.

### 4.19 Architecture Principle

A qualitative statement of intent that should be met by the architecture.

Note: A sample set of Architecture Principles is defined in the TOGAF Standard — ADM Techniques.

### 4.20 Architecture View

A representation of a system from the perspective of a related set of concerns.

Note: In some sections of this standard, the term "view" is used as a synonym for "architecture view".

See also Section 4.75 and Section 4.21.

### 4.21 Architecture Viewpoint

A specification of the conventions for a particular kind of architecture view.

Note: An architecture viewpoint can also be seen as the definition or schema for that kind of architecture view. It establishes the conventions for constructing, interpreting, and using an architecture view to address a specific concern (or set of concerns) about a system-of-interest. In some sections of this standard, the term "viewpoint" is used as a synonym for "architecture viewpoint".

See also Section B.25.

### 4.22 Architecture Vision

A succinct description of the Target Architecture that describes its business value and the changes to the enterprise that will result from its successful deployment. It serves as an aspirational vision and a boundary for detailed architecture development.

Note: Phase A (Architecture Vision) is described in the TOGAF Standard — Architecture Development Method.

### 4.23 Artifact

An architectural work product that describes an aspect of the architecture.

See also Section 4.26.

### 4.24 Baseline

A specification that has been formally reviewed and agreed upon, that thereafter serves as the basis for further development or change and that can be changed only through formal change control procedures or a type of procedure such as configuration management.

### 4.25 Boundaryless Information Flow™

A shorthand representation of "access to integrated information to support business process improvements" representing a desired state of an enterprise’s infrastructure specific to the business needs of the organization.

Note: The need for Boundaryless Information Flow — a trademark of The Open Group — is described in the TOGAF® Series Guide: The TOGAF Integrated Information Infrastructure Reference Model (III-RM).

### 4.26 Building Block

A potentially re-usable component that can be combined with other building blocks to deliver architectures and solutions.

Note: Building blocks can be defined at various levels of detail, depending on what stage of architecture development has been reached. For instance, at an early stage, a building block can simply consist of a name or an outline description. Later on, a building block may be decomposed into multiple supporting building blocks and may be accompanied by a full specification. Building blocks can relate to "architectures" or "solutions". Building blocks are described in the TOGAF Standard — Architecture Content.

See also Section 4.23.

### 4.27 Business Architecture

A representation of holistic, multi-dimensional business views of: capabilities, end-to-end value delivery, information, and organizational structure; and the relationships among these business views and strategies, products, policies, processes, initiatives, and stakeholders.

Note: Business Architecture relates business elements to business goals and elements of other domains. Business Architecture is described in the TOGAF Standard — Architecture Development Method.

### 4.28 Business Capability

A particular ability that a business may possess or exchange to achieve a specific purpose.

### 4.29 Business Function

A collection of business behavior based on a chosen set of criteria, closely aligned to an organization.

### 4.30 Business Governance

Concerned with ensuring that the business processes and policies (and their operation) deliver the business outcomes and adhere to relevant business regulation.

### 4.31 Business Model

A model describing the rationale for how an enterprise creates, delivers, and captures value.

### 4.32 Business Service

Supports the business by encapsulating a unique "element of business behavior".

Note: A service offered external to the enterprise may be supported by business services.

### 4.33 Capability

An ability that an organization, person, or system possesses.

Note: This a general-purpose definition. See Section 4.28 for how this concept is refined for usage in Business Architecture.

### 4.34 Capability Architecture

An architecture that describes the abilities that an enterprise possesses. See also the TOGAF® Series Guide: A Practitioners’ Approach to Developing Enterprise Architecture Following the TOGAF ADM.

### 4.35 Capability Increment

A discrete portion of a capability architecture that delivers specific value. When all increments have been completed, the capability has been realized.

### 4.36 Communications and Stakeholder Management

The management of needs of stakeholders of the Enterprise Architecture practice. It also manages the execution of communication between the practice and the stakeholders and the practice and the consumers of its services.

Note: Architecture stakeholder management is described in the TOGAF Standard — ADM Techniques.

### 4.37 Concern

An interest in a system relevant to one or more of its stakeholders.

Note: Concerns may pertain to any aspect of the system’s functioning, development, or operation, including considerations such as performance, reliability, security, distribution, and evolvability and may determine the acceptability of the system.

See also Section 4.75.

### 4.38 Course of Action

Direction and focus provided by strategic goals and objectives, often to deliver the value proposition characterized in the business model.

### 4.39 Data Architecture

A description of the structure of the enterprise’s major types and sources of data, logical data assets, physical data assets, and data management resources.

Note: Data Architecture is described in the TOGAF Standard — Architecture Development Method.

### 4.40 Deliverable

An architectural work product that is contractually specified and in turn formally reviewed, agreed, and signed off by the stakeholders.

Note: Deliverables represent the output of projects and those deliverables that are in documentation form will typically be archived at completion of a project, or transitioned into an Architecture Repository as a reference model, standard, or snapshot of the Architecture Landscape at a point in time.

### 4.41 Digital Architecture

The inclusive architecture focused on a combination of Enterprise Architecture, data science, telecommunications and IoT, security, artificial intelligence, cognitive science, neuroscience, robotics, and social medias to deliver operational services.

### 4.42 Enterprise

The highest level (typically) of description of an organization and typically covers all missions and functions. An enterprise will often span multiple organizations.

### 4.43 Enterprise Architecture Service

An encapsulated element of Enterprise Architecture capability that delivers specific Enterprise Architecture functionality.

### 4.44 Enterprise Continuum

A categorization mechanism for classifying architecture and Solution Building Blocks (SBBs) as they evolve from generic to specific applicability (or vice versa).

See also Section 4.10 and Section 4.74.

### 4.45 Foundation Architecture

Generic building blocks, their inter-relationships with other building blocks, combined with the principles and guidelines that provide a foundation on which more specific architectures can be built.

### 4.46 Framework

A structure for content or process that can be used as a tool to structure thinking, ensuring consistency and completeness.

### 4.47 Gap

A statement of difference between two states. Used in the context of gap analysis, where the difference between the Baseline and Target Architecture is identified.

Note: Gap analysis is described in the TOGAF Standard — ADM Techniques.

### 4.48 Governance

The discipline of monitoring and guiding the management of a business (or IS/IT landscape) to deliver the business outcomes required.

See also Section 4.14, Section 4.30, and Section B.27 in Appendix B.

### 4.49 Information

Any communication or representation of facts, data, or opinions, in any medium or form, including textual, numerical, graphic, cartographic, narrative, or audio-visual forms.

### 4.50 Information Technology (IT)

The lifecycle management of information and related technology used by an organization.

### 4.51 Interoperability

1\. The ability to share information and services.

2\. The ability of two or more systems or components to exchange and use information.

3\. The ability of systems to provide and receive services from other systems and to use the services so interchanged to enable them to operate effectively together.

### 4.52 Logical

Implementation-independent.

Note: A logical architecture is an implementation-independent definition of the architecture.

### 4.53 Metadata

Data about data, of any sort in any media, that describes the characteristics of an entity.

### 4.54 Metamodel

A model that describes the entities used in building an Architecture Description, their characteristics, and the key relationships between those entities.

### 4.55 Method

A defined, repeatable approach to address a particular type of problem.

### 4.56 Modeling

A technique through construction of models which enables a subject to be represented in a form that enables reasoning, insight, and clarity concerning the essence of the subject matter.

### 4.57 Model Kind

Conventions for a type of modeling.

Note: An architecture viewpoint references one or more model kinds; an architecture view incorporates one or more models.

### 4.58 Objective

An organizational aim that is declared in a Specific, Measurable, Actionable, Realistic, and Timebound (SMART) way. For example, "Increase capacity utilization by 30% by the end of the year, to support the planned increase in market share".

### 4.59 Pattern

A technique for putting building blocks into context; for example, to describe a re-usable solution to a problem.

Note: Building blocks are what you use: (architecture) patterns can tell you how you use them, when, why, and what trade-offs you have to make in doing so.

See also Section 4.26.

### 4.60 Physical

Real-world, tangible.

Note: A logical architecture is realized through a physical architecture.

### 4.61 Principle

See Section 4.19.

### 4.62 Product

An outcome generated by the business to be offered to customers. Products include materials and/or services.

### 4.63 Reference Model (RM)

An abstract framework for understanding significant relationships among the entities of [an] environment, and for the development of consistent standards or specifications supporting that environment.

Note: A reference model is based on a small number of unifying concepts and may be used as a basis for education and explaining standards to a non-specialist. A reference model is not directly tied to any standards, technologies, or other concrete implementation details, but it does seek to provide common semantics that can be used unambiguously across and between different implementations. Source: OASIS®; refer to www.oasis-open.org/committees/tc_home.php?wg_abbrev=soa-rm.

### 4.64 Requirement

A statement of need, which is unambiguous, testable or measurable, and necessary for acceptability.

### 4.65 Roadmap

An abstracted plan for business or technology change, typically operating across multiple disciplines over multiple years. Normally used in the phrases Technology Roadmap, Architecture Roadmap, etc.

### 4.66 Role

1\. The usual or expected behavior of an actor, or the part somebody or something plays in a particular process or event. An actor may have a number of roles.

2\. The part an individual plays in an organization and the contribution they make through the application of their skills, knowledge, experience, and abilities.

See also Section 4.2.

### 4.67 Segment Architecture

A detailed, formal description of areas within an enterprise, used at the program or portfolio level to organize and align change activity.

See also Section 4.77.

### 4.68 Service

An encapsulated element of behavior that provides specific functionality in response to requests from actors or other services.

Note: A service has an interface and description.

### 4.69 Service Orientation

Viewing an enterprise, system, or building block in terms of services provided and consumed.

See also Section 4.70.

### 4.70 Service-Oriented Architecture (SOA)

An architectural style that supports service orientation.

See also Section 4.7 and Section 4.69.

### 4.71 Service Portfolio

A collection of services, potentially an interface definition.

Note: It is used in the TOGAF framework to define the requirement for a building block or system.

### 4.72 Solution Architecture

A description of a discrete and focused business operation or activity and how IS/IT supports that operation.

### 4.73 Solution Building Block (SBB)

A physical or implementation-specific component that realizes part or all of one or more logical Architecture Building Blocks (ABBs).

Note: There are business, application, and technology SBBs.

### 4.74 Solutions Continuum

A categorization mechanism, with increasing detail and specialization, for the components and artifacts stored in the Solutions Landscape or Reference Library (part of the Architecture Repository).

See also Section 4.44 and Section 4.10.

### 4.75 Stakeholder

An individual, team, organization, or class thereof, having an interest in a system.

### 4.76 Standards Library

A library of standards that can be used to define the particular services and other components of an Organization-Specific Architecture.

Note: The Standards Library is described in the TOGAF Standard — Architecture Content: Architecture Repository.

### 4.77 Strategic Architecture

A summary formal description of the enterprise, providing an organizing framework for operational and change activity, and an executive-level, long-term view for direction setting.

### 4.78 Target Architecture

The description of a future state of the architecture being developed for an organization.

Note: There may be several future states developed as a roadmap to show the evolution of the architecture to a target state.

### 4.79 Taxonomy of Architecture Views

The organized collection of all architecture views pertinent to an architecture.

### 4.80 Technology Architecture

A description of the structure and interaction of the technology services and technology components.

Note: Technology Architecture is described in the TOGAF Standard — Architecture Development Method.

### 4.81 Technology Component

1\. A technology building block. A generic infrastructure technology that supports and enables application or data components (directly or indirectly) by providing technology services.

2\. An encapsulation of technology infrastructure that represents a class of technology product or specific technology product.

### 4.82 Technology Service

A technical capability required to provide enabling infrastructure that supports the delivery of applications.

### 4.83 Transition Architecture

A formal description of one state of the architecture at an architecturally significant point in time.

Note: One or more Transition Architectures may be used to describe the progression in time from the Baseline to the Target Architecture. Transition Architecture is described in the TOGAF Standard — Architecture Content: Architecture Definition Document.

### 4.84 Value Stream

A representation of an end-to-end collection of activities that create an overall result for a customer, stakeholder, or end user.

### 4.85 View

See Section 4.20.

### 4.86 Viewpoint

See Section 4.21.

### 4.87 Viewpoint Library

A collection of the specifications of architecture viewpoints contained in the Reference Library portion of the Architecture Repository.

### 4.88 Work Package

A set of actions identified to achieve one or more objectives for the business. A work package can be a part of a project, a complete project, or a program.

## Appendix A: Referenced Documents

The Open Group TOGAF Series Guides

- TOGAF® Series Guide: Applying the ADM Using Agile Sprints, April 2022 (G210), published by The Open Group; refer to www.opengroup.org/library/g210
- TOGAF® Series Guide: A Practitioners’ Approach to Developing Enterprise Architecture Following the TOGAF ADM, April 2022 (G186), published by The Open Group; refer to www.opengroup.org/library/g186
- TOGAF® Series Guide: Architecture Maturity Models, April 2022 (G203), published by The Open Group; refer to www.opengroup.org/library/g203
- TOGAF® Series Guide: Architecture Project Management, April 2022 (G188), published by The Open Group; refer to www.opengroup.org/library/g188
- TOGAF® Series Guide: Architecture Skills Framework, April 2022 (G198), published by The Open Group; refer to www.opengroup.org/library/g198
- TOGAF® Series Guide: Business Capabilities, Version 2, April 2022 (G211), published by The Open Group; refer to www.opengroup.org/library/g211
- TOGAF® Series Guide: Business Models, April 2022 (G18A), published by The Open Group; refer to www.opengroup.org/library/g18a
- TOGAF® Series Guide: Business Scenarios, April 2022 (G176), published by The Open Group; refer to www.opengroup.org/library/g176
- TOGAF® Series Guide: Digital Technology Adoption — A Guide to Readiness Assessment and Roadmap Development, April 2022 (G212), published by The Open Group; refer to www.opengroup.org/library/g212
- TOGAF® Series Guide: Information Architecture — Customer Master Data Management, April 2022 (G21B), published by The Open Group; refer to www.opengroup.org/library/g21b
- TOGAF® Series Guide: Information Mapping, April 2022 (G190), published by The Open Group; refer to www.opengroup.org/library/g190
- TOGAF® Series Guide: Integrating Risk and Security within a TOGAF® Enterprise Architecture, April 2022 (G152), published by The Open Group; refer to www.opengroup.org/library/g152
- TOGAF® Series Guide: Organization Mapping, April 2022 (G206), published by The Open Group; refer to www.opengroup.org/library/g206
- TOGAF® Series Guide: Enabling Enterprise Agility, April 2022 (G20F), published by The Open Group; refer to www.opengroup.org/library/g20f
- TOGAF® Series Guide: The TOGAF Integrated Information Infrastructure Reference Model (III-RM): An Architected Approach to Boundaryless Information Flow™, November 2017 (G179), published by The Open Group; refer to www.opengroup.org/library/g179
- TOGAF® Series Guide: The TOGAF Leader’s Guide to Establishing and Evolving an EA Capability, April 2022 (G184), published by The Open Group; refer to www.opengroup.org/library/g184
- TOGAF® Series Guide: The TOGAF Technical Reference Model (TRM), September 2017 (G175), published by The Open Group; refer to www.opengroup.org/library/g175
- TOGAF® Series Guide: Using the TOGAF® Framework to Define and Govern Service-Oriented Architectures, September 2017 (G174), published by The Open Group; refer to www.opengroup.org/library/g174
- TOGAF® Series Guide: Value Streams, April 2022 (G178), published by The Open Group; refer to www.opengroup.org/library/g178

Other Publications from The Open Group

- A Practical Approach to Application Portfolio Consolidation using the TOGAF® Standard, The Open Group Guide, July 2018 (G18B), published by The Open Group; refer to www.opengroup.org/library/g18b
- Archi Banking Group: Combining the BIAN Reference Model, ArchiMate® Modeling Notation, and the TOGAF® Framework, Case Study, March 2020 (Y201), published by The Open Group; refer to www.opengroup.org/library/y201
- ArchiMate® 3.1 Specification, The Open Group Standard, November 2019 (C197), published by The Open Group; refer to www.opengroup.org/library/c197
- Digital Practitioner Body of Knowledge™Standard (also known as the DPBoK™Standard), The Open Group Standard, January 2020 (C196), published by The Open Group; refer to www.opengroup.org/library/c196
- Exploring Synergies between TOGAF® and Frameworx, White Paper, May 2011 (W114), published by The Open Group; refer to www.opengroup.org/library/w114
- Information Architecture: Business Intelligence & Analytics and Metadata Management Reference Models, The Open Group Guide, January 2020 (G201), published by The Open Group; refer to www.opengroup.org/library/g201
- Open Risk Analysis (O-RA), Version 2.0, The Open Group Standard, November 2020 (C20A), published by The Open Group; refer to www.opengroup.org/library/c20a
- Open Risk Taxonomy (O-RT), Version 3.0, The Open Group Standard, November 2020 (C20B), published by The Open Group; refer to www.opengroup.org/library/c20b
- The Open Agile Architecture™Standard, The Open Group Standard, September 2020 (C208), published by The Open Group; refer to www.opengroup.org/library/c208
- The Open Group IT4IT™Reference Architecture, Version 2.1, The Open Group Standard, January 2017 (C171), published by The Open Group; refer to www.opengroup.org/library/c171
- TOGAF® 9 and DoDAF 2.0, White Paper, July 2010 (W105), published by The Open Group; refer to www.opengroup.org/library/w105
- TOGAF® and SABSA® Integration, White Paper, October 2011 (W117), published by The Open Group; refer to www.opengroup.org/library/w117

Other Referenced Documents

- A Guide to the Project Management Body of Knowledge (PMBOK®) Guide), Project Management Institute; refer to www.pmi.org/pmbok-guide-standards
- A Method for Identifying Process Re-Use Opportunities to Enhance the Operating Model, M. de Vries, A. van der Merwe, P. Kotze, A. Gerber, in proceedings of the 2011 IEEE International Conference on Industrial Engineering and Engineering Management (IEEM)
- Analysis Patterns — Reusable Object Models, M. Fowler, ISBN: 0-201-89542-0, Addison-Wesley
- ANSI/IEEE Std 1471-2000: Systems and Software Engineering — Recommended Practice for Architectural Description of Software-intensive Systems
- A Pattern Language: Towns, Buildings, Construction, Christopher Alexander, ISBN: 0-19-501919-9, Oxford University Press, 1979
- Business Motivation Model™(BMM™), Object Management Group (OMG); refer to www.omg.org/spec/BMM/About-BMM
- Business Process Modeling Notation™(BPMN™) Specification, Object Management Group (OMG); refer to www.bpmn.org
- Business Transformation Enablement Program (BTEP), Canadian Government; refer to https://purl.org/theopengroup/btep
- Control Objectives for Information and related Technology (COBIT®), Version 4.0, IT Governance Institute, 2005
- Corporate Governance, Ranami Naidoo, ISBN: 1-919-903-0086, Double Storey, 2002
- Design Patterns: Elements of Reusable Object-Oriented Software, Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides, ISBN: 0-201-63361-2, Addison-Wesley, October 1994
- Enterprise Architecture as Strategy, Jeanne Ross, Peter Weill, David C. Robertson, ISBN: 1-59139-839-8, Harvard Business School Press, 2006
- Enterprise Architecture Capability Maturity Model (ACMM), Version 1.2, United States Department of Commerce, December 2007
- Enterprise Architecture Maturity Model, Version 1.3, National Association of State CIOs (NASCIO), December 2003
- Enterprise Architecture Planning (EAP): Developing a Blueprint for Data, Applications, and Technology, Steven H. Spewak, Steven C. Hill, ISBN: 0-47-159985-9, John Wiley & Sons, 1993
- Headquarters Air Force Principles for Information Management, US Air Force, June 29, 1998
- ISO/IEC 20000: 2011, Information Technology — Service Management
- ISO/IEC/IEEE 15288: 2015, Systems and Software Engineering — System Life Cycle Processes
- ISO/IEC/IEEE 42010: 2011, Systems and Software Engineering — Architecture Description
- IT Portfolio Management Facility™(ITPMF™) Specification, Object Management Group (OMG); refer to www.omg.org/spec/ITPMF
- Manifesto for Agile Software Development, 2001; refer to www.agilemanifesto.org
- Merriam-Webster Collegiate Dictionary, Merriam-Webster, English Language, 11th Edition, April 2008, ISBN-10: 0877798095, ISBN-13: 978-0877798095; refer to www.merriam-webster.com
- Model-Driven Architecture® (MDA®) Specification, Object Management (OMG); refer to www.omg.org/mda
- OECD Principles of Corporate Governance, Organization for Economic Co-operation and Development, December 2001; refer to www.oecd.org
- Organigraphs: Drawing How Companies Really Work, H. Mintzberg and L. Van der Heyden, Harvard Business Review, October 1999; refer to https://hbr.org/1999/09/organigraphs-drawing-how-companies-really-work
- Pattern-Oriented Software Architecture: A System of Patterns, F. Buschmann, R. Meunier, H. Rohnert, P. Sommerlad, M. Stal, ISBN: 0-471-95869-7, John Wiley & Sons, 1996
- Patterns and Software: Essential Concepts and Terminology, Brad Appleton, 2000; refer to www.bradapp.com/docs/patterns-intro.html
- Re-usable Asset Specification (RAS), Version 2.2, Object Management Group (OMG), November 2005; refer to www.omg.org/spec/RAS
- Service Component Architecture (SCA) Specification, developed by the Open Service Oriented Architecture (OSOA) collaboration; refer to www.oasis-opencsa.org/sca
- Service Data Objects (SDO) Specification, developed by the Open Service Oriented Architecture (OSOA) collaboration; refer to www.oasis-opencsa.org/sdo
- Software Processing Engineering Metamodel (SPEM™) Specification, Version 2.0, Object Management Group (OMG), April 2008; refer to www.omg.org/spec/SPEM
- Systems Modeling Language™(SysML®), Object Management Group (OMG); refer to www.sysml.org
- The Art of Systems Architecting, Eberhardt Rechtin, Mark W. Maier, 2000
- The Oregon Experiment, Christopher Alexander, ISBN: 0-19-501824-9, Oxford University Press, 1975
- The Timeless Way of Building, Christopher Alexander, ISBN: 0-19-502402-8, Oxford University Press, 1979
- The Zachman® Framework, Zachman International; refer to www.zachman.com
- UML Profile and Metamodel for Services (UPMS) RFP (OMG soa/2006-09-09), Object Management Group (OMG), June 2007
- Unified Modeling Language™(UML®) Specification, Object Management Group (OMG); refer to www.uml.org

The following websites provide useful reference material:

- The Cloud Computing Design Patterns community website (refer to www.cloudpatterns.org)
- The Information Technology Governance Institute: www.isaca.org/About-ISACA/IT-Governance-Institute

This website has many resources that can help with corporate assessment of both IT and governance in general.

- The Patterns-Discussion FAQ: http://purl.org/theopengroup/pd-FAQ

This website is maintained by Doug Lea and provides a thorough and highly readable FAQ about patterns.

- The Patterns Home Page: hillside.net/patterns

This website is hosted by The Hillside Group and provides information about patterns, links to online patterns, papers, and books dealing with patterns, and patterns-related mailing lists.

- The SOA Patterns community website (refer to www.soapatterns.org/), dedicated to the ongoing development and expansion of the SOA design pattern catalog

## Appendix B: Glossary of Supplementary Definitions

This appendix contains additional definitions to supplement the definitions contained in Chapter 4.

### B.1 Application Software

Software entities which have a specific business purpose.

### B.2 Availability

In the context of IT systems, the probability that system functional capabilities are ready for use by a user at any time, where all time is considered, including operations, repair, administration, and logistic time. Availability is further defined by system category for both routine and priority operations.

### B.3 Business System

Hardware, software, policy statements, processes, activities, standards, and people which together implement a business capability.

### B.4 Catalog

A structured list of architectural outputs of a similar kind, used for reference. For example, a technology standards catalog or an application portfolio.

### B.5 Client

An application component which requests services from a server.

### B.6 COBIT

An acronym for Control OBjectives for Information and related Technology, created by the Information Systems Audit and Control Association (ISACA) and the IT Governance Institute (ITGI), which provides a set of recommended best practices for the governance/management of information systems and technology.

### B.7 Configuration Management

A discipline applying technical and administrative direction and surveillance to:

- Identify and document the functional and physical characteristics of a configuration item
- Control changes to those characteristics
- Record and report changes to processing and implementation status

Also, the management of the configuration of Enterprise Architecture practice (intellectual property) assets and baselines and the control of change over of those assets.

### B.8 CxO

The chief officer within a particular function of the business; e.g., Chief Executive Officer, Chief Financial Officer, Chief Information Officer, Chief Technology Officer.

### B.9 Data Dictionary

A specialized type of database containing metadata; a repository of information describing the characteristics of data used to design, monitor, document, protect, and control data in information systems and databases; an application system supporting the definition and management of database metadata.

### B.10 Data Element

A basic unit of information having a meaning and that may have subcategories (data items) of distinct units and values.

### B.11 Database

A structured or organized collection of data entities, which is to be accessed by a computer.

### B.12 Database Management System

A computer application program that accesses or manipulates the database.

### B.13 End User

Person who ultimately uses the computer application or output.

### B.14 Enterprise Resource Planning (ERP) System

A complete suite of integrated applications that support the major business support functions of an organization; e.g., Financial (AP/AR/GL), HR, Payroll, Stock, Order Processing and Invoicing, Purchasing, Logistics, Manufacturing, etc.

### B.15 Hardware

The physical infrastructure needed to run software; e.g., servers, workstations, network equipment, etc.

### B.16 Information Domain

Grouping of information (or data entities) by a set of criteria such as security classification, ownership, location, etc. In the context of security, information domains are defined as a set of users, their information objects, and a security policy.

### B.17 Information System (IS)

The computer (or IT)-based portion of a business system.

### B.18 Interaction

A relationship between architectural building blocks (i.e., services or components) that embodies communication or usage.

### B.19 Interaction Model

An architectural view, catalog, or matrix that shows a particular type of interaction. For example, a diagram showing application integration.

### B.20 Interface

Interconnection and inter-relationships between, for example, people, systems, devices, applications, or the user and an application or device.

### B.21 Key Performance Indicator (KPI)

A way of quantifying the performance of the business or project.

### B.22 Lifecycle

The period of time that begins when a system is conceived and ends when the system is no longer available for use.

### B.23 Managing Successful Programs (MSP)

A best practice methodology for program management, developed by the UK Office of Government Commerce (OGC).

### B.24 Matrix

A format for showing the relationship between two (or more) architectural elements in a grid format.

### B.25 Metaview

A pattern or template of the view, from which to develop individual views. Establishes the purposes and audience for a view, the ways in which the view is documented (e.g., for visual modeling), and the ways in which it is used (e.g., for analysis).

See also Section 4.21 in Chapter 4.

### B.26 Open System

A system that implements sufficient open specifications for interfaces, services, and supporting formats to enable properly engineered application software:

- To be ported with minimal changes across a wide range of systems
- To interoperate with other applications on local and remote systems
- To interact with users in a style that facilitates user portability

### B.27 Operational Governance

The operational performance of systems against contracted performance levels, the definition of operational performance levels, and the implementation of systems that ensure effective operation of systems.

See also Section 4.48 in Chapter 4.

### B.28 Packaged Services

Services that are acquired from the market from a Commercial Off-The-Shelf (COTS) vendor, rather than being constructed via code build.

### B.29 Portability

1\. The ease with which a system, component, data, or user can be transferred from one hardware or software environment to another.

2\. A quality metric that can be used to measure the relative effort to transport the software for use in another environment or to convert software for use in another operating environment, hardware configuration, or software system environment.

### B.30 Portfolio

A collection of programs, projects, and/or operations managed as a group to achieve strategic objectives. For example, project portfolio, application portfolio, technology portfolio, or service portfolio.

Note: Portfolio management is the act of managing portfolios.

### B.31 PRINCE2

An acronym for PRojects IN Controlled Environments, which is a standard project management method.

### B.32 Program

A co-ordinated set of change projects that deliver business benefit to the organization.

### B.33 Project

A single change project which delivers business benefit to the organization.

### B.34 Risk Management

The management of risks and issues that may threaten the success of the Enterprise Architecture practice and its ability to meet its vision, goals, and objectives, and, importantly, its service provision.

Note: Risk management is described in the TOGAF Standard — Architecture Content.

### B.35 Scalability

The ability to use the same application software on many different classes of hardware/software platforms from PCs to super-computers (extends the portability concept). The capability to grow to accommodate increased work loads.

### B.36 Security

Services which protect data, ensuring its confidentiality, availability, and integrity.

### B.37 Server

An application component which responds to requests from a client.

### B.38 Service Quality

A preset configuration of non-functional attributes that may be assigned to a service or service contract.

### B.39 SMART

An acronym for Specific, Measurable, Actionable, Realistic, and Timebound, which is an approach to ensure that targets and objectives are set in a way that can be achieved and measured.

### B.40 Supplier Management

The management of suppliers of products and services to the Enterprise Architecture practice in concert with larger corporate procurement activities.

### B.41 System

A combination of interacting elements organized to achieve one or more stated purposes. (Source: ISO/IEC/IEEE 15288: 2015)

### B.42 Time Period

The timeframe over which the potential impact is to be measured.

### B.43 Use-Case

A view of organization, application, or product functionality that illustrates capabilities in context with the user of that capability.

### B.44 User

1\. Any person, organization, or functional unit that uses the services of an information processing system.

2\. In a conceptual schema language, any person or any thing that may issue or receive commands and messages to or from the information system.

## Appendix C: Abbreviations

ABB Architecture Building Block

ACMM Architecture Capability Maturity Model

ADM Architecture Development Method

ANSI American National Standards Institute

API Application Platform Interface

ARTS Association for Retail Technology Standards

BMM Business Motivation Model

BPM Business Process Management

BPMN Business Process Modeling Notation

BTEP The Canadian Government Business Transformation Enablement Program

CMM Capability Maturity Models

CMMI Capability Maturity Model Integration

COBIT Control OBjectives for Information and related Technology

COTS Commercial Off-The-Shelf applications

CRM Customer Relationship Management

CRUD Create/Read/Update/Delete

CSF Critical Success Factor

DBA Database Administrator

DBMS Database Management System

DoC US Department of Commerce

DoD US Department of Defense

DoDAF Department of Defense Architecture Framework

EAI Enterprise Application Integration

EDIFACT (United Nations) Electronic Data Interchange For Administration, Commerce, and Transport

ERP Enterprise Resource Planning

ETL Extract, Transform, Load

FICO Fair Isaac Corporation

FTE Full-Time Equivalent

GOTS Government Off-The-Shelf applications

HIPAA Health Insurance Portability and Accountability Act

ICAM Integrated Computer Aided Manufacturing

ICOM Inputs, Controls, Outputs, and Mechanisms/Resources

IDEF Integrated Computer Aided Manufacturing (ICAM) DEFinition

IEC International Electrotechnical Commission

IEEE Institute of Electrical and Electronic Engineers

III-RM Integrated Information Infrastructure Reference Model

IoT Internet of Things

ISACA Information Systems Audit and Control Association

ISACF Information Systems Audit and Control Foundation

ISO International Standards Organization

IT Information Technology

ITGI IT Governance Institute

ITIL Information Technology Infrastructure Library

ITPMF IT Portfolio Management Facility

J2EE Java 2 Platform, Enterprise Edition

KPI Key Performance Indicator

LAN Local Area Network

MDA Model-Driven Architecture

MSA Microservices Architecture

MSP Managing Successful Programs

MVA Minimum Viable Architecture

NAF NATO Architecture Framework

NASCIO National Association of State Chief Information Officers

OECD Organization for Economic Co-operation and Development

OGC UK Office of Government Commerce

OLA Operational-Level Agreement

OMB Office of Management and Budget

OMG Object Management Group

ORB Object Request Broker

OSI Open Systems Interconnection

OSOA Open Service-Oriented Architecture

PDF Portable Document Format

PMBOK Project Management Body of Knowledge

PRINCE PRojects in Controlled Environments

QoS Quality of Service

RAS Remote Access Services

RFC Request For Change

RFI Request for Information

RFP Request for Proposal

RM Reference Model

SBB Solution Building Block

SCA Service Component Architecture

SDO Service Data Objects

SEI Software Engineering Institute

SGML Standard Generalized Markup Language

SLA Service-Level Agreement

SMART Specific, Measurable, Actionable, Realistic, and Timebound

SOA Service-Oriented Architecture

SPEM Software Processing Engineering Metamodel

SysML Systems Modeling Language

TAFIM Technical Architecture Framework for Information Management

TRM Technical Reference Model

UML Unified Modeling Language

WAN Wide Area Network

XML Extensible Markup Language

---

## Footnotes

- 1\. The TOGAF Library provides an online publicly available structured list of Guides, White Papers, and other resources. Refer to TOGAF Library at www.opengroup.org/togaf-library. 2. The TOGAF Library is a publicly accessible resource located at www.opengroup.org/togaf-library.
