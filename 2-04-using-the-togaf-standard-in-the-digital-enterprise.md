# Using the TOGAF® Standard in the Digital Enterprise

## Contents

- [Using the TOGAF® Standard in the Digital Enterprise](#using-the-togaf-standard-in-the-digital-enterprise)
- [Preface](#preface)
  - [The Open Group](#the-open-group)
  - [The TOGAF® Standard, a Standard of The Open Group](#the-togaf-standard-a-standard-of-the-open-group)
  - [This Document](#this-document)
  - [About the TOGAF® Series Guides](#about-the-togaf-series-guides)
- [About the Authors](#about-the-authors)
- [Trademarks](#trademarks)
- [Acknowledgements](#acknowledgements)
- [Referenced Documents](#referenced-documents)
  - [Normative References](#normative-references)
  - [Informative References](#informative-references)
- [1. Introduction](#1-introduction)
  - [1.1. Overview](#11-overview)
  - [1.2. The Digital Practitioner and the Enterprise Architect](#12-the-digital-practitioner-and-the-enterprise-architect)
    - [1.2.1. Context and Background](#121-context-and-background)
  - [1.3. Strategy](#13-strategy)
- [2. Why the TOGAF Standard Supports the Digital Enterprise](#2-why-the-togaf-standard-supports-the-digital-enterprise)
  - [2.1. Introduction](#21-introduction)
  - [2.2. Reactively Managing Technical Debt](#22-reactively-managing-technical-debt)
  - [2.3. Proactively Managing Technical Debt](#23-proactively-managing-technical-debt)
  - [2.4. Mature Digital Products and Operational Excellence](#24-mature-digital-products-and-operational-excellence)
  - [2.5. Simplifying Complexity (The TOGAF ADM)](#25-simplifying-complexity-the-togaf-adm)
- [3. Terminology Alignment](#3-terminology-alignment)
- [4. How the TOGAF Standard Supports the Digital Enterprise](#4-how-the-togaf-standard-supports-the-digital-enterprise)
  - [4.1. Introduction](#41-introduction)
  - [4.2. The DPBoK Standard](#42-the-dpbok-standard)
    - [4.2.1. Context I: Individual/Founder](#421-context-i-individualfounder)
    - [4.2.2. Context II: Team](#422-context-ii-team)
    - [4.2.3. Context III: Team of Teams](#423-context-iii-team-of-teams)
    - [4.2.4. Context IV: Enduring Enterprise](#424-context-iv-enduring-enterprise)
    - [4.2.5. Need More Detail?](#425-need-more-detail)
  - [4.3. How to Apply TOGAF Principles per Context](#43-how-to-apply-togaf-principles-per-context)
    - [4.3.1. Enterprise Architecture Principles: Individual/Founder](#431-enterprise-architecture-principles-individualfounder)
    - [4.3.2. Enterprise Architecture Principles: Team](#432-enterprise-architecture-principles-team)
    - [4.3.3. Enterprise Architecture Principles: Team of Teams](#433-enterprise-architecture-principles-team-of-teams)
    - [4.3.4. Enterprise Architecture Principles: Enduring Enterprise](#434-enterprise-architecture-principles-enduring-enterprise)
  - [4.4. Enterprise Architecture Capabilities and Services](#44-enterprise-architecture-capabilities-and-services)
    - [4.4.1. Enterprise Architecture Capabilities and Services: Individual/Founder](#441-enterprise-architecture-capabilities-and-services-individualfounder)
    - [4.4.2. Enterprise Architecture Capabilities and Services: Team](#442-enterprise-architecture-capabilities-and-services-team)
    - [4.4.3. Enterprise Architecture Capabilities and Services: Team of Teams](#443-enterprise-architecture-capabilities-and-services-team-of-teams)
    - [4.4.4. Enterprise Architecture Capabilities and Services: Enduring Enterprise](#444-enterprise-architecture-capabilities-and-services-enduring-enterprise)
    - [4.4.5. Enterprise Architecture Services Emergence Model](#445-enterprise-architecture-services-emergence-model)
  - [4.5. TOGAF Artifacts and Series Guides](#45-togaf-artifacts-and-series-guides)
    - [4.5.1. Mapping to the Individual/Founder Context](#451-mapping-to-the-individualfounder-context)
    - [4.5.2. Mapping to the Team Context](#452-mapping-to-the-team-context)
    - [4.5.3. Mapping to the Team of Teams Context](#453-mapping-to-the-team-of-teams-context)
    - [4.5.4. Mapping to the Enduring Enterprise Context](#454-mapping-to-the-enduring-enterprise-context)
- [A: Enterprise Architecture Benefits](#a-enterprise-architecture-benefits)
- [B: Principles from the TOGAF Standard](#b-principles-from-the-togaf-standard)
- [C: Services Proposed for the TOGAF Standard](#c-services-proposed-for-the-togaf-standard)
  - [C.1. Requirements and Elicitation](#c1-requirements-and-elicitation)
  - [C.2. Architecture Planning](#c2-architecture-planning)
  - [C.3. Design Support](#c3-design-support)
  - [C.4. Development Support](#c4-development-support)
  - [C.5. Enterprise Support](#c5-enterprise-support)
  - [C.6. Enterprise Architecture Practice Development Support](#c6-enterprise-architecture-practice-development-support)
  - [C.7. Services Mapped to ADM Phases](#c7-services-mapped-to-adm-phases)
- [D: Rationalizing the TOGAF and DPBoK Standards](#d-rationalizing-the-togaf-and-dpbok-standards)
  - [D.1. Organizational Reality, Capabilities, and Dependencies](#d1-organizational-reality-capabilities-and-dependencies)
    - [D.1.1. Aspect: Enterprise Architecture Benefits](#d11-aspect-enterprise-architecture-benefits)
    - [D.1.2. Aspect: Enterprise Architecture Services](#d12-aspect-enterprise-architecture-services)
  - [D.2. Integrating “Outside-In” and “Inside-Out” Views](#d2-integrating-outside-in-and-inside-out-views)
    - [D.2.1. Aspect: Enterprise Architecture Benefits](#d21-aspect-enterprise-architecture-benefits)
    - [D.2.2. Aspect: Enterprise Architecture Services](#d22-aspect-enterprise-architecture-services)
  - [D.3. Strategic Alignment and Synergy](#d3-strategic-alignment-and-synergy)
    - [D.3.1. Aspect: Enterprise Architecture Benefits](#d31-aspect-enterprise-architecture-benefits)
    - [D.3.2. Aspect: Enterprise Architecture Services](#d32-aspect-enterprise-architecture-services)
  - [D.4. Enabling Innovation While Managing Technical Debt](#d4-enabling-innovation-while-managing-technical-debt)
    - [D.4.1. Aspect: Enterprise Architecture Benefits](#d41-aspect-enterprise-architecture-benefits)
    - [D.4.2. Aspect: Enterprise Architecture Services](#d42-aspect-enterprise-architecture-services)

## Using the TOGAF® Standard in

## the Digital Enterprise

## The Open Group TOGAF® Series Guide

## Preface

### The Open Group

The Open Group is a global consortium that enables the achievement of business objectives through technology standards. With more than 870 member organizations, we have a diverse membership that spans all sectors of the technology community – customers, systems and solutions suppliers, tool vendors, integrators and consultants, as well as academics and researchers.

The mission of The Open Group is to drive the creation of Boundaryless Information Flow™ achieved by:

- Working with customers to capture, understand, and address current and emerging requirements, establish policies, and share best practices
- Working with suppliers, consortia, and standards bodies to develop consensus and facilitate interoperability, to evolve and integrate specifications and open source technologies
- Offering a comprehensive set of services to enhance the operational efficiency of consortia
- Developing and operating the industry’s premier certification service and encouraging procurement of certified products

Further information on The Open Group is available at www.opengroup.org.

The Open Group publishes a wide range of technical documentation, most of which is focused on development of Standards and Guides, but which also includes white papers, technical studies, certification and testing documentation, and business titles. Full details and a catalog are available at www.opengroup.org/library.

### The TOGAF® Standard, a Standard of The Open Group

The TOGAF Standard is a proven enterprise methodology and framework used by the world’s leading organizations to improve business efficiency.

### This Document

This document is a TOGAF® Series Guide to Using the TOGAF® Standard in the Digital Enterprise. It has been developed and approved by The Open Group. This document sets out to answer two overarching questions:

1\. How do Enterprise Architecture and the TOGAF Standard enable the digital enterprise? 2. When and how to apply TOGAF methods and best practices to guide a digital enterprise through its stages of development, which the Digital Practitioner Body of Knowledge™ Standard refers to as the emergence mode?

The high-level structure of this document is as follows:

- Chapter 1 provides a high-level introduction to this document in terms of how established Enterprise Architecture practices bring value to digital enterprises at all scales
- Chapter 2 describes how Enterprise Architecture and the TOGAF® Standard bring valuable tools to digital enterprises of all sizes
- Chapter 3 provides an alignment of terminology between the TOGAF Standard and the Digital Practitioner Body of Knowledge
- Chapter 4 provides details on applying Enterprise Architecture and the TOGAF Standard to the contexts described in DPBoK™ Standard
- Appendix A lists Enterprise Architecture benefits
- Appendix B lists principles from the TOGAF Standard
- Appendix C shows how Enterprise Architecture services package TOGAF activities to deliver value on demand in two major categories: internal-centric and customer-centric
- Appendix D further illustrates the connections between the TOGAF Standard and the DPBoK Standard

The audience for this document is those undertaking the roles of both Enterprise Architects and Digital Practitioners. For Digital Practitioners it communicates what architecture practices would help to grow their digital enterprise, and how to interact with the Enterprise Architecture community to get them. For those undertaking an Enterprise Architect role it provides guidance on supporting the digital enterprise.

A side benefit, therefore, of addressing two audiences, each with different cultures and approaches, is sharing information about each community to facilitate cooperation and productive engagements.

### About the TOGAF® Series Guides

The TOGAF® Series Guides contain guidance on how to use the TOGAF Standard and how to adapt it to fulfill specific needs.

The TOGAF® Series Guides are expected to be the most rapidly developing part of the TOGAF Standard and are positioned as the guidance part of the standard. While the TOGAF Fundamental Content is expected to be long-lived and stable, guidance on the use of the TOGAF Standard can be industry, architectural style, purpose, and problem-specific. For example, the stakeholders, concerns, views, and supporting models required to support the transformation of an extended enterprise may be significantly different than those used to support the transition of an in-house IT environment to the cloud; both will use the Architecture Development Method (ADM), start with an Architecture Vision, and develop a Target Architecture on the way to an Implementation and Migration Plan. The TOGAF Fundamental Content remains the essential scaffolding across industry, domain, and style.

## About the Authors

## About the Authors

Terence Blevins

Terence Blevins, a Fellow of The Open Group, is the owner of Enterprise Wise LLC and is a semi-retired Enterprise Architect. He is currently a Director of The Open Group Governing Board. He has been involved with the architecture discipline since the 1980s when he was Director of Strategic Architecture at NCR Corporation. Terence has been involved with The Open Group since 1996 when he first was introduced to the Architecture Forum. He was co-chair of the Architecture Forum and a frequent contributor of TOGAF material, including the Business Scenario Method. Terence was Vice-President and CIO of The Open Group where he contributed to The Open Group Vision of Boundaryless Information Flow™. He holds undergraduate and Masters degrees in Mathematics from Youngstown State University.

Andy Ruth

Andy Ruth started his IT career in the 1970s as a technical expert in both consulting and staff roles. Over the next two decades he rose up through the technical ranks, from the role of architect and through the ranks of management to become a manager of managers. In the mid-1990s, he shifted from delivering IT capability to delivering training; speaking at conferences, and writing books and training for covering the IT space. Toward the end of the 1990s, Andy joined Microsoft to create the Microsoft Certified Architect program and to manage the architect role for the consulting group. In the last few years, Andy has employed his talents to grow standards, training, and tools for the architecture community. In his spare time, he manages an apprenticeship program that helps others to enter the workforce or grow their career.

Heidi Hasz

Heidi Hasz has more than 25 years of experience in IT Architecture, working on initiatives from efficiency improvements and cost takeout to green fields. Heidi began her IT architecture career in California for IBM where she helped Fortune 500 clients to establish an Enterprise Architecture and an Enterprise Architecture practice. In 1998, IBM transferred her to The Netherlands to lead cross-border enterprise infrastructure optimization engagements. During her time at IBM, she was a member of the IBM IT architecture worldwide knowledge center responsible for developing and delivering the IBM architecture methodology and intellectual capital repository. Currently, Heidi is a TOGAF® trainer and architecture course developer working on the initial release of a digitally-enabled accredited TOGAF course.

Sonia Gonzalez

Sonia Gonzalez is The Open Group TOGAF Product Manager. She has more than 25 years of experience as a Business and Enterprise Architecture Consultant in different fields and industry verticals. Sonia’s experience includes Business and Strategy Consultancy as well as Enterprise Architecture and Solutions Consultancy, applying different frameworks, best practices, and tools.

Sonia holds the following certifications issued by The Open Group: TOGAF® 9 Certified and ArchiMate®

3 Practitioner. She also has earned the following Open Badges from The Open Group: TOGAF® Essentials 2018, TOGAF® Standard, Version 9.2, and TOGAF® Enterprise Architecture Modeling Practitioner 9.2. Other certifications include COBIT® 5 Certified, COBIT Certified Trainer, SAFe® 4 Certified, AIPMM Certified Product Manager, and courses in BPM and BPMN™.

## Trademarks

## Trademarks

ArchiMate, DirecNet, Making Standards Work, Open O logo, Open O and Check Certification logo, Platform 3.0, The Open Group, TOGAF, UNIX, UNIXWARE, and the Open Brand X logo are registered trademarks and Boundaryless Information Flow, Build with Integrity Buy with Confidence, Commercial Aviation Reference Architecture, Dependability Through Assuredness, Digital Practitioner Body of Knowledge, DPBoK, EMMM, FACE, the FACE logo, FHIM Profile Builder, the FHIM logo, FPB, Future Airborne Capability Environment, IT4IT, the IT4IT logo, O-AA, O-DEF, O-HERA, O-PAS, Open Agile Architecture, Open FAIR, Open Footprint, Open Process Automation, Open Subsurface Data Universe, Open Trusted Technology Provider, OSDU, Sensor Integration Simplified, SOSA, and the SOSA logo are trademarks of The Open Group.

Scrum.org is a trademark of Scrum.org.

SWIFT is a registered trademark of S.W.I.F.T. SCRL.

Wikipedia is a registered trademark of the Wikimedia Foundation, Inc.

All other brands, company, and product names are used for identification purposes only and may be trademarks that are the sole property of their respective owners.

## Acknowledgements

## Acknowledgements

(Please note affiliations were current at the time of approval.)

The Open Group gratefully acknowledges the contribution of the following people in the development of this document:

- Charlie Betz, University of St. Thomas, Minnesota
- Mark Dickson, The Open Group
- Jim Doss, IT Management and Governance
- Chris Forde, The Open Group
- David Gilmour, Mundo Cognito
- Andrew Josey, The Open Group
- Mike Lambert, Fellow of The Open Group
- Frederic Le, DXC Technology
- David Lounsbury, The Open Group
- Gnana Prakash Ponnusamy, Capgemini
- Vidyasagar Uddagiri, Tata Consultancy Services Ltd.
- Richard Webb, DXC Technology

The Open Group gratefully acknowledges the following reviewers who participated in the Company Review of this document:

- Charles Betz, University of St. Thomas, Minnesota
- Mark Dickson, The Open Group
- David Gilmour, Cognito Mundo
- Sonia Gonzalez, The Open Group
- Andrew Josey, The Open Group
- Mike Lambert, Fellow of the Open Group
- Dave Lounsbury, The Open Group
- William Warrender, Raytheon Technologies

## Referenced Documents

The following documents are referenced in this TOGAF® Series Guide.

(Please note that the links below are good at the time of writing but cannot be guaranteed for the future.)

### Normative References

This document does not contain any normative references at the time of publication. These may be added in a future release.

### Informative References

- ArchiMate® 3.1 Specification, a standard of The Open Group (C197), November 2019, published by The Open Group; refer to: www.opengroup.org/library/c197
- Capability-Based Planning Supporting Project/Portfolio and Digital Capabilities Mapping Using the TOGAF® and ArchiMate® Standards, The Open Group Guide (G193), July 2019, published by The Open Group; refer to: www.opengroup.org/library/g193
- Customer Experience-Driven Enterprise Architecture: How to Revitalize your DSP Business, White Paper (W166), April 2016, published by The Open Group; refer to: www.opengroup.org/library/w166
- Digital Transformation Strategy to Implementation using The Open Group Standards, White Paper (W170), January 2017, published by The Open Group; refer to: www.opengroup.org/library/w170
- How to Use the ArchiMate® Modeling Language to Support TOGAF® Framework Projects, The Open Group Guide (G21E), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g21e
- How to Use the TOGAF® and IT4IT™ Standards Together, White Paper (W185), May 2018, published by The Open Group; refer to: www.opengroup.org/library/w185
- Information Architecture: Business Intelligence & Analytics and Metadata Management Reference Models, The Open Group Guide (G201), January 2020, published by The Open Group; refer to: www.opengroup.org/library/g201
- ISO/IEC/IEEE 42010:2011 Systems and Software Engineering – Architecture Description, December 2011, published by ISO; refer to: www.iso.org/standard/50508.html
- Open Business Architecture (O-BA) – Part II, Preliminary Standard (P171), April 2017, published by The Open Group; refer to: www.opengroup.org/library/p171
- Scrum.org; refer to: scrum.org
- Seamless Service Delivery and the IT4IT™ Standard, White Paper (W183), May 2018, published by The Open Group; refer to: www.opengroup.org/library/w183
- Team Topologies: Organizing Business and Technology Teams for Fast Flow, by Matthew Skelton,

Manuel Pais, and Ruth Malan, September 2019, published by IT Revolution Press

- The Digital Practitioner Body of Knowledge™ Standard, also known as the DPBoK™ Standard, a standard of The Open Group (C196), January 2020, published by The Open Group; refer to: www.opengroup.org/library/c196
- The Open Agile Architecture™ Standard (also known as the O-AA™ Standard), a standard of The Open Group (C208), September 2020, published by The Open Group; refer to: www.opengroup.org/library/c208
- The Open Group IT4IT™ Reference Architecture, Version 2.1, a standard of The Open Group (C171), January 2017, published by The Open Group; refer to: www.opengroup.org/library/c171
- The Seven Levers of Digital Transformation, White Paper (W17D), September 2017, published by The Open Group; refer to: www.opengroup.org/library/w17d
- The TOGAF® Standard, 10th Edition, a standard of The Open Group (C220), April 2022, published by The Open Group; refer to: www.opengroup.org/library/c220
- TOGAF® Series Guide: A Practitioners’ Approach to Developing Enterprise Architecture Following the TOGAF® ADM (G186), April 2022, published by The Open Group; refer to www.opengroup.org/library/g186
- TOGAF® Series Guide: Applying the TOGAF® ADM using Agile Sprints (G210), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g210
- TOGAF® Series Guide: Architecture Maturity Models (G203), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g203
- TOGAF® Series Guide: Architecture Project Management (G188), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g188
- TOGAF® Series Guide: Architecture Skills Framework (G198), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g198
- TOGAF® Series Guide Set: Business Architecture (T190), April 2022, published by The Open Group; refer to: www.opengroup.org/library/t190
- TOGAF® Series Guide: Business Capabilities, Version 2 (G211), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g211
- TOGAF® Series Guide: Digital Technology Adoption: A Guide to Readiness Assessment and Roadmap Development (G212), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g212
- TOGAF® Series Guide: Enabling Enterprise Agility (G20F), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g20f
- TOGAF® Series Guide: Information Mapping (G190), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g190
- TOGAF® Series Guide: The TOGAF® Leader’s Guide to Establishing and Evolving an EA Capability (G184), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g184
- TOGAF® Series Guide: Using the TOGAF® Framework to Define and Govern Service-Oriented

Architectures (G174), September 2017, published by The Open Group; refer to: www.opengroup.org/library/g174

- TOGAF® Series Guide: Value Streams (G178), April 2022, published by The Open Group; refer to: www.opengroup.org/library/g178
- Wikipedia® – Technical Debt; refer to: en.wikipedia.org/wiki/Technical_debt
- Why Business and IT Must Co-Create Strategy for a Digital Enterprise (W203), January 2020, published by The Open Group; refer to: www.opengroup.org/library/w203
- World-Class EA: Governors’ Approach to Developing and Exercising an Enterprise Architecture Governance Capability, White Paper (W178), July 2017, published by The Open Group; refer to: www.opengroup.org/library/w178

## 1. Introduction

This document sets out to answer two overarching questions:

1\. How do Enterprise Architecture and the TOGAF® Standard (see Referenced Documents) enable the digital enterprise? 2. When and how to apply TOGAF methods and best practices to guide a digital enterprise through its stages of development, which the Digital Practitioner Body of Knowledge™ Standard (see Referenced Documents) refers to as the emergence model?

The TOGAF Standard supports strategic decision-making and a sustainable delivery of architecture specifications to support organizations to become a digital enterprise. It can be used in the Individual/Founder, Team, Team of Teams, and Enduring Enterprise contexts in the DPBoK™ Standard to inform and make decisions. The implementation of the TOGAF Standard is always adapted to fit the scale, culture, and operation of the organization in which it is used.

This document provides insight on how to adapt the standard to support the digital enterprise in alignment with the DPBoK Standard concepts and contexts of the emergence model.[1]

### 1.1. Overview

This document describes how and when Enterprise Architecture, using the approach defined in the TOGAF Standard, can be used to enable a digital enterprise. The experience and knowledge collected and cataloged in the TOGAF Standard has come from years of experience by people around the globe who have built and run the IT portions of companies around the world. The lessons learnt can be used to minimize the growing pains from which maturing digital enterprises will likely suffer.

The structure of this document uses the four contexts and descriptions from the DPBoK Standard to describe the different stages or maturity levels through which a digital product and digitally-based company might transition.

Chapter 1 provides an introduction to the Enterprise Architect and the Digital Practitioner along with their perspectives and the strategy to connect them. The document presents guidance using a “peek-ahead” approach so a digital enterprise maturing from one context to the next can appropriately apply the TOGAF Standard and Enterprise Architecture to “look ahead” in preparation for transitioning from context to context. It also describes the importance of delivering Enterprise Architecture through a service delivery model – the Enterprise Architecture as a service strategy.

Chapter 2 describes why Enterprise Architecture using the TOGAF Standard should be applied in a digital enterprise, and describes using each to reactively and proactively manage and avoid technical debt. It also describes how, as digital products mature and operational excellence is needed, both can be used to mature a product and a company.

Chapter 3 provides clarity for the terminology used by the TOGAF Standard and the DPBoK Standard. It also points out definitions commonly used by The Open Group for any terms used in the document that

the reader might want to review.

Chapter 4 comprises the bulk of the content as it reviews the four contexts used by the DPBoK Standard and describes what Enterprise Architecture can contribute during each context. It also describes the Enterprise Architecture principles, capabilities, and services that support each context. Finally, the chapter describes which parts of the TOGAF ADM and TOGAF Series Guides apply to each context to assist with further guidance.

### 1.2. The Digital Practitioner and the Enterprise Architect

The DPBoK Standard describes the skills needed to operate a successful digital enterprise, including digital product delivery.

New business models resulting from a combination of digital technology, combined with digital ways of working, are transforming economies and societies worldwide. Digital investments are critical for modern organizations. Participating in their delivery (i.e., working to create and manage them for value) can provide prosperity for individuals, communities, and public and private enterprises. Learning programs worldwide are under pressure to produce an increasing number of qualified professionals to meet voracious workforce demands. Skill requirements have undergone a seismic shift over the past 20 years; Digital Practitioners require a wide variety of skills and competencies, including cloud architecture and operations, continuous delivery and deployment, collaboration, Agile and Lean methods, product management, and more.

The DPBoK Standard is intended to support the development of the Digital Practitioner. It seeks to provide guidance for both new entrants into the digital workforce as well as experienced practitioners seeking to update their understanding on how all the various themes and components of digital and IT management fit together in the new world. The Enterprise Architect can use the DPBoK Standard to understand culture, leadership practices, and product development. They can use that information to create a rapport with product teams and discover where they can provide an architectural service to product teams. They can also use this standard to better understand what artifacts are created and how to harvest them in the context of the emergence model from the DPBoK Standard.

Every Digital Practitioner wants and expects their company to be a wild success and to grow exponentially from a founder state to an enduring enterprise as described in the DPBoK Standard emergence model. But what happens when, as it grows, they are faced with the complexity of coordination across multiple teams and potentially across multiple lines of business? What happens when every contract with every business or customer needs a legal review, when they face compliance and regulatory concerns, or when they are the target of litigation?

The Digital Practitioner can use this document and the pointers to specific methods defined in the TOGAF Standard as a sort of “peek-ahead” tool. This document provides guidance that helps the Digital Practitioner complete the Enterprise Architecture tasks that are defined in the DPBoK Standard. It indicates/suggests current best practices so that decisions with long-term consequences are well-informed and set for success as they mature to a large enterprise with several hundred or thousand employees. As the company and teams grow and make decisions that impact their product, they can leverage the hard-earned lessons from the generations of practitioners that came before them. By

reviewing where the TOGAF Standard has tools, templates, and processes to complete the tasks discussed in the DPBoK Standard, they will have tools necessary to grow successfully through well-informed decisions.

#### 1.2.1. Context and Background

The perspectives of the Digital Practitioner and the Enterprise Architect are often different. Moreover, they may operate in ways that introduce conflict between them due to goals that are at odds. For instance, the goal of the Digital Practitioner is to deliver customer value as quickly as possible, learning and updating rapidly based on customer feedback, and minimizing effort and attention outside of this learning cycle as much as possible. The goal of the Enterprise Architect is to know and maintain enough information about the ecosystem in which they operate to provide enough of the right information as possible for leadership to make well-informed decisions, and provide correct and informed guidance to product teams.

The TOGAF Standard and the DPBoK Standard each evolved during two different computing eras. That is challenging enough, but we are also in a time of extreme business disruption. One of the drivers of this disruption is the steep fall in price of computing and bandwidth, including in mobile devices. This represents an opportunity to deliver digital value at dramatically lower costs than in the past. Businesses see the value of having digital products to offer to their customers. or, even if they do not see the value, they see the competitive disadvantage they will face if they do not embrace digital products, as their competitors will take advantage of the fall in cost of digital delivery. Would you even consider banking with a bank that did not have a mobile app? Would you ever think of flying with an airline that did not offer online reservation and check in?

Enterprise Architecture and the TOGAF Standard began to evolve at a time when on-premise data centers with large systems were in use and the Internet, virtual machine environments, and cloud-based resources were just evolving. Software and hardware cost money, had long cycles for procurement, and needed to be placed in data centers that had to plan for space, power, and cooling. Everything had to be planned and executed correctly for the intended business outcome to become reality. When available, buying software was preferred to building software so the code base for commodity IT capability was someone else’s problem and the product teams could focus on features that provided a competitive advantage. Experimentation and quick (or any) failure typically meant failure of the initiative. If an initiative was canceled after it was started, there was a very real risk of having purchased assets that never created a revenue stream.

We have now entered an age where digital products and services are a primary way the enterprise goes to market. The DPBoK and TOGAF Standards both support the age of digital products. Founders and product owners have a clear digital value proposition for their market. Their product teams own and focus on smaller microservices that are integrated into larger solutions. These offer the ability to rapidly respond to market feedback through reuse of their components in larger solutions. When a feature is released, it has an Application Programming Interface (API) so that automation and easy integration is possible. Relevant ideas and innovation come primarily from two sources:

- The product team must contain one or more people with a deep knowledge of the systems and the software they work on; what is possible with their current technology deployment, and where the

technical debt inhibits feature release

- The product team must collect insights directly from the end users

These changes are combined with the dominance of the Internet, virtual machines, cloud-based resources for rent, open source software and tools, and innovation occurring at break-neck speed being commonplace in most industries and businesses. Product teams delivering digital capability focus on code output above all else. The code must translate to end-user value. Anything that takes the focus away from developing and delivering code and new features is considered a lost opportunity. Upfront planning and driving product development through end-user feedback are expected. Experimentation and quick failure are not only encouraged, but also expected.

Along with the positives of developing better digital products more quickly, there are some consequences that need attention. Today’s digital products can become tomorrow’s technical debt. Digital products built without consideration of some big picture can result in unintended consequences; for example, privacy and security breaches, and high costs of integration and interoperability.

In this document we provide Enterprise Architecture guidance to anyone shifting from an inside-out view to an “outside-in” view, from a project to product focus, or adopting more Agile and Lean approaches to software delivery. This document provides those practicing Enterprise Architecture with the insights needed to rethink their approach. They should ask themselves if each process and artifact they require is necessary to bring value to the digital enterprise, or if it is a legacy of past organizations and practices. It provides the Digital Practitioner with the guidance needed to leverage Enterprise Architecture to successfully complete the steps and tasks described in the DPBoK Standard while managing risks.

### 1.3. Strategy

In looking at the DPBoK Standard, the subject of building a digital enterprise, and how Enterprise Architecture and the TOGAF Standard specifically support the digital enterprise, it became obvious that a shift in focus would be useful. This resulted in spelling out two specific Enterprise Architecture strategies that are used throughout this document:

- The peek-ahead strategy

The first strategy is to move from a “do it if, and after, the architect says OK” to a “do it with the architecture enablement” approach. Enablement comes in the form of using just enough guidance on risks, standards, and best practices to deliver the minimum viable digital product per context, while looking ahead to ensure that a smooth transition to the next context is enabled. This is not meant to stop progress, but rather to ensure that decisions are taken today with appropriate understanding of potential problems and difficulties. This strategy can be done by someone undertaking the role of an architect. Even in the Individual/Founder Context of the DPBoK Standard, the individual/founder provides the business analysis delivered by an Enterprise Architect, even if it is done in an ad hoc fashion.

- Enterprise Architecture as services strategy

The second strategy further supports enablement by moving from producing architectures, and gating progress, to developing just enough architecture on demand to support the operations tempo of the digital effort. This is accomplished through an Enterprise Architecture services delivery model provided by those undertaking the Enterprise Architect role. This is done in an enabling-consulting fashion. This is especially significant:

  - At the Team of Teams level where the architect can serve to improve cross-team communication and reduce the cognitive load of teams working together
  - In a larger organization that offers consultative services to founders/teams as part of an innovation/incubation strategy

These two strategies along with the guidance contained in this document will improve the probability of success for the digital enterprise in any organization.

## 2. Why the TOGAF Standard Supports the Digital

## Enterprise

### 2.1. Introduction

The TOGAF Standard began to evolve at a time when server hardware and networking equipment needed to be purchased; data center space, power, and cooling needed to be planned for, and product licenses negotiated and purchased. Technology infrastructure had to be well-planned and in place in the early stages of a project to allow for adequate lead time. Now, there are alternatives to purchasing and staging hardware and networking, and many product licenses are open-source licensing.

While the environment has changed, the business functions needed to deliver an IT capability still exist. These functions still require an understanding of the concepts behind the business process, and an approach or methodology to accomplish their associated tasks. The TOGAF Standard and Enterprise Architecture are relevant to understand business functions and the tasks that must be completed by people in order to enable the business functions.

The need for companies to evolve into digital enterprises can be linked to a variety of drivers, least of which is the rapid change in technologies that lend themselves to new ways of working, socializing, and entertaining. The Enterprise Architecture capability and the TOGAF Standard support Agile software delivery environments. An Enterprise Architecture should be seen as supporting and enabling the Agile environment in delivering and enhancing digital products and services quicker and easier by providing insight into various areas; including:

- Reactively managing technical debt as the result of sprints in a cohesive and connected fashion
- Proactively managing technical debt and anticipating Agile development needs by:
  - Identifying standards and reusable standard components that support shortened Agile development cycles
  - Appropriate governance or guardrails to oversee the reuse of components
- Managing matured digital products and delivering operational excellence by:
  - Simplifying complexity in the digital ecosystem using the TOGAF Architecture Development Method (ADM)
  - Establishing an Enterprise Architecture capability that drives operational excellence in the management of digital products and services
  - Institutionalizing Agile development methods by enabling them as another framework used in the organization

Having an Agile culture and using Agile delivery methods does not necessarily lead to products with Agile characteristics. Agile delivery must balance the business value of early delivery to market [2] with the future value of leveraging and connecting to other components in the ecosystem that would add value to the product. As a result, a more appropriate approach to developing an Agile backbone may

be one that looks at the enterprise, particularly in the Team of Teams and Enduring Enterprise contexts of the DPBoK Standard. In other words, the TOGAF Core Concepts and ADM. For more information on Enterprise Architecture supporting Agile delivery using the TOGAF Standard; see the TOGAF® Series Guide: Enabling Enterprise Agility (see Referenced Documents). Often the quickest delivery involves solutions that are not easily adaptable with other features and difficult to connect to other components in the ecosystem that would add value to the product.

It is important to consider that for organizations to become digital they must improve their digital offerings with products and services that offer additional value not considered by competitors. To achieve this, experimentation is important, using iterative test-and-learn approaches to identify new digital products. Enterprise Architecture is well-suited to support this experimentation, providing the alignment of business objectives to the digital vision; for example, by applying techniques like design thinking. The use of architecture alternatives to select different potential implementation roadmaps is also a plus. More details on how to handle architecture alternatives can be found in the TOGAF Standard – ADM Techniques (see Referenced Documents), Chapter 10, “Architecture Alternatives and Trade-Off”.

### 2.2. Reactively Managing Technical Debt

“Technical debt (also known as design debt or code debt) is a concept in software development that reflects the implied cost of additional rework caused by choosing an easy solution now instead of using a better approach that would take longer.” Wikipedia® (see Referenced Documents)

“The issue is that there is not just the typical hack, the technical shortcut that is beneficial today, but expensive tomorrow that creates technical debt. (A not uncommon tactic in feature factories.) There is also a kind of technical debt that is passively created when the Scrum team learns more about the problem it is trying to solve. Today, the product team might prefer a different solution by comparison to the one the team implemented just six months ago. Or, the product team upgrades the definition of “done”, thus introducing rework in former product increments. No matter from what angle you look at the problem, you cannot escape it, and Scrum does not offer a silver bullet either.” Scrum.org™ (see Referenced Documents)

One area of Agile development that can be helped by an Enterprise Architecture approach is the management of technical and architectural debt. Technical debt is not bad, but a debt may bring a short-term benefit at the cost of future delay and inflexibility in bringing new features to market.[3]

Once you incur technical debt, you have to do something with it. This can be considered as reactively managing technical debt. Many technical debt issues can be dealt with in the product backlog by having the principle that technical debt is tracked and continually paid down as part of items in the sprints. However, there are other forms of technical debt that are better dealt with from an enterprise perspective because of their extremely complex or cross-cutting nature, which may be better managed using Enterprise Architecture and/or following the approaches in the TOGAF Standard. Other forms of technical debt that do not require Enterprise Architecture or approaches from the TOGAF Standard are technical debts that can be mitigated by following software or middleware patterns. This approach

might be preferred to simplify maintainability. Technical debt of this nature can also appear in the technology domain.

An approach based on the TOGAF Standard is also well-suited to identifying technical debt incurred due to redundancy. As all products are based in the same digital ecosystem, multiple Scrum teams may have run into the same “architecture roadblocks”. Using the TOGAF ADM as an Enterprise Architecture approach should uncover these overlaps and not only address the issues specific to particular product architectures, but also gain insight into fundamental and systematic deficiencies in the digital ecosystem itself. This can enable teams to develop or acquire solutions to address issues from which multiple products might suffer.

### 2.3. Proactively Managing Technical Debt

In principle, technical debt is avoidable, but in practice it is incurred. However, the amount of debt that an organization takes on can be proactively managed. The TOGAF Standard has a number of features that, when applied at the enterprise level, can help in the proactive management of the infrastructure. In Digital Transformation Strategy to Implementation using The Open Group Standards (see Referenced Documents), debt is described as:

“The gap between desired state and current state is a liability – a debt incurred by the enterprise. When trade-off decisions result in adding to the backlog of work, the architect and the enterprise are wilfully increasing the chasm between current and target state – an increase in debt. Using assessments from maturity and service design, the practitioner constrains and guides the enterprise from tripping up during trade-off decisions. It also provides insights and compels the enterprise to involve all skill verticals

- Human Resources, Finance, Product and Service lines, Strategy, etc.”

When creating a strategy to proactively manage technical debt by using the TOGAF Standard, consider the following:

- Standards include internally agreed upon ways of implementing systems and some of those can help to proactively manage technical debt

Some standards are driven by government regulations and are subject to audit, such as General Data Protection Regulation (GDPR), SWIFT®, BASEL II, and BASEL III. Other standards are adopted as best practices. Regardless of their origin, once adopted as a standard they can cut across product domains and often the entire ecosystem. Identifying standards and managing the lifecycle of the standards removes some of the guess work for Scrum teams. Beyond identifying the standards used, communicating them, and making them visible, the Enterprise Architect stands ready to assist Scrum teams in using the standards. In a rigid culture, a formalized Architecture Board examines the use of standards in architectures and implemented systems. However, in Agile development environments, the architecture board acts more like guardrails to ensure the systems avoid implementation decisions that are difficult and expensive to reverse, or that can lead to integration and operational excellence issues. Components used in solutions that are not internally developed will have standards and a standards lifecycle which will impact the maintainability of digital products.

- An Architecture Repository and Enterprise Continuum are assets to the digital enterprise that Agile delivery teams can use to make more informed design choices and to use proven designs from their own company

While Agile processes do not focus on documentation, a large part of the TOGAF Standard does focus on documenting and analyzing the environment. Product architectures can make use of components that are not developed, managed, or controlled by the environment, and the Enterprise Continuum provides a way to classify and organize components that enhance the sustainability of a digital product.

- Digital Practitioners concern themselves with capabilities to support the digital enterprise as described in The Seven Levers of Digital Transformation (see Referenced Documents), not just the digital products and services, and IT and delivery layers

TOGAF Standard techniques can be applied to product architectures, such as stakeholder management, business transformation readiness assessment, risk management, and several other competency areas described in the DPBoK Standard.

### 2.4. Mature Digital Products and Operational Excellence

Digital products and services have a lifecycle from inception to retirement. The length of the lifecycle is dependent on its viability to its ecosystem. The strength of Agile processes lies in the evidence-based testing of features, which means that some experiments will be a success. For the products that fail for one reason or another the long-term consequence of their viability is not relevant. It is the product that has proven its viability without necessarily being engineered for sustainability or deeply embedded integration, which may require rework to address integration into the larger ecosystem.

A new digital product triggers a chain of events. Products that incorporate any sort of technology are constantly evolving. If they are not evolving, they are becoming obsolete. The evolution of products and services is driven by ever-increasing value to the customer. Value can be measured from many perspectives, but one common perspective is the capability of the product or service to connect to other things.

The TOGAF Standard can be used to manage and mature digital products, and to help deliver operational excellence. However, at times it can feel like quite a challenge as Agile processes focus on delivering code over documentation and the TOGAF Standard centers much of its methodology around artifact collection and management.

Although there can be a feeling amongst agilists that there is no need for architecture, the authors of this document assert that there is. It may be that the architecture is not understood, or written down, or it may be a poorly designed architecture; but as long as there is a system, there is an architecture. Without suggesting a best practice for architecture documentation, each architecture description can be plotted on the matrix described in Figure 1.

![Figure 1: Example of Documentation Matrix](images/04-using-the-togaf-standard-in-the-digital-enterprise-figure-1-p343.png)

*Figure 1: Example of Documentation Matrix*

A system, whether large, small, simple, complex, just invented yesterday, or as old as the punch card mainframes, has an architecture. And that architecture has a description; we can describe it visually, verbally, or in a written form.

The job of the architect is to do just enough architecture, just in time. The TOGAF Standard describes what the architecture description should contain, such as information about stakeholders, concerns, views (for example, the views of stakeholders – to address their concerns), and viewpoints. Separate and apart from the evolutionary state of the architecture is the form of architecture measured by its formality, which is a separate measurement of its completeness, soundness, and robustness. Obvious problem areas are the extremes, when:

- The system (and its architecture) is complex and undocumented (insufficient architecture)
- There is an “architecture mandate” for every potential system, product, or idea before we have even tested its viability (too much architecture)

The architect should have the experience to be able to apply a format of architecture that achieves the best result within the context of the architectural environment.

### 2.5. Simplifying Complexity (The TOGAF ADM)

Digital products must adapt to their evolving ecosystem or they will lose their value. The digital products might become inefficient, obsolete, or too expensive to maintain. A well-constructed ecosystem that is adaptable, scalable, and flexible is the purpose of an architecture.

The TOGAF ADM provides guidance for understanding and describing the larger digital ecosystem in

the form of Enterprise Architecture. The TOGAF Standard can also be used to partition the ecosystem into segment architectures, while digital products can be described as solution architectures.

As digital products and services increase in complexity, more rigorous forms of architecture can and should be applied to maintain the “Agile” aspects of digital products. The question becomes how much rigor to apply? Using guidance available in the TOGAF Standard, the Digital Practitioner can mitigate slow-downs in continuous delivery caused by complexity; for example, by evangelizing the rigorous and structured development of reusable components that are relatively easy to integrate. Conversely, the architect can select TOGAF components that help to address complexity and deselect components that are over-engineered for the context in which they are operating. The TOGAF Standard states that it should be adapted and “right-sized” for smaller or less complex environments.

Most importantly, the TOGAF Standard focuses on business outcomes described as valuable to the customer or end user. This aligns with how the value of digital products and services are measured. However, the Agile approach of “you build it, you operate it” may not be operationally efficient, especially when the digital product begins to embed itself into the core operational model of the technology infrastructure. The TOGAF Standard provides the framework that accommodates not only product architectures but entire capabilities in which the product participates.

## 3. Terminology Alignment

## 3. Terminology Alignment

The terminology used in the TOGAF Standard and the DPBoK Standard does not conflict in definition and usage. However, as you might expect, there are terms that are used in one that are either currently not used or not relevant in the other.

![Table 1: provides a list of some of the key terms focused on the digital enterprise and used in the DPBoK](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-1-p345.png)

*Table 1: provides a list of some of the key terms focused on the digital enterprise and used in the DPBoK*

Standard.

*Table 1: Terminology Alignment between the TOGAF and DPBoK Standards*

Application The term component is used in a more An encapsulation of application Component general way in the DPBoK Standard; functionality aligned to implementation therefore, there is no conflict. structure, which is modular and replaceable. It encapsulates its behavior and data, provides services, and makes them available through interfaces.

An application component usually maintains a data component. It is enabled by technology services provided by technology components.

Architecture Both standards share the same 1. The fundamental concepts or definition. properties of a system in its environment embodied in its elements, relationships, and in the principles of its design and evolution. (Source: ISO/IEC/IEEE 42010:2011; see Referenced

2\. The structure of components, their inter-relationships, and the principles and guidelines governing their design and evolution over time.

Digital Enterprise An enterprise characterized by: There is no specific TOGAF definition for digital enterprise; however, the 1. The creation of digitalized products definition provided in the DPBoK or services that are delivered fully Standard is a special type of enterprise, digitally; e.g., digital media or online as defined in the TOGAF Standard. The banking. TOGAF Standard considers an enterprise to be any collection of 2. Where physical products and services organizations that have common goals, are obtained by the customer by digital operating at all scales. means; e.g., online car-sharing services.

Digital Strategy The DPBoK Standard does not define The term is not defined in the TOGAF digital strategy; however, it implies that Standard; therefore, there is no conflict. a digital strategy is one which aspires to lead to a successful digital enterprise.

Digital Technology IT in the form of a product or service The term is not defined in the TOGAF that is digitally consumable to create or Standard; therefore, there is no conflict. enable business value.

Digital The radical, fundamental change The term is not defined in the TOGAF Transformation toward becoming a digital enterprise. Standard; therefore, there is no conflict. Digitalization The application of digital technology to The term is not defined in the TOGAF create additional business value within Standard; therefore, there is no conflict. the primary value chain of enterprises.

Digitization The conversion of analog information The term is not defined in the TOGAF into digital form. Standard; therefore, there is no conflict.

Process An ordered, countable set of activities; This term is used and there is no an event-driven, value-adding sequence conflict. A process represents a that can be measured and improved. sequence of activities that together achieve a specified outcome, can be decomposed into sub-processes, and can show the operation of a business capability or service (at the next level of detail); see the TOGAF Standard – Applying the ADM (see Referenced Documents). The definitions do not contradict each other.

Service This term is not defined in the DPBoK A repeatable activity; a discrete Standard; therefore, there is no conflict. behavior that a building block may be requested or otherwise triggered to perform.

An element of behavior that provides specific functionality in response to requests from actors or other services.

Technology The term component is used in a more 1. A technology building block: a Component general way in the DPBoK Standard; generic infrastructure technology that therefore, there is no conflict. supports and enables application or data components (directly or indirectly) by providing technology services.

2\. An encapsulation of technology infrastructure that represents a class of technology product or specific technology product.

The following terms are relevant to both the TOGAF Standard and the DPBoK Standard, and definitions are provided that can be used to frame conversations:

- Digital standard (or guide): A publication that helps an enterprise succeed as a digital enterprise; i.e., one that primarily delivers value through digital means (sometimes called a “digital-first” business model)
- Emergence model: An organization of information where topics are related to the organizational complexity or scale of the enterprise (Source: The DPBoK Standard, Scaling Model)
- Principle: A qualitative statement of intent that should be met by the architecture (Source: The TOGAF Standard – ADM Techniques, Section 2.3: “Components of Architecture Principles”)

## 4. How the TOGAF Standard Supports the Digital

## Enterprise

### 4.1. Introduction

This chapter provides a detailed overview of the four contexts of organizational evolution per the DPBoK Standard and their relationship to Enterprise Architecture and the TOGAF Standard. This chapter answers the questions:

- What are the four digital enterprise contexts, at a very high level?
- What can Enterprise Architecture contribute in these contexts?
- Which Enterprise Architecture principles support the digital journey per context?
- Which Enterprise Architecture capabilities and services support Digital Practitioners in each of these contexts?
- Which TOGAF ADM phases, TOGAF artifacts, and TOGAF Series Guides support the DPBoK contexts?
- What is the connection between the TOGAF Standard and the DPBoK Standard?

The strategy for answering this last question is to present a set of Enterprise Architecture services that package the right set of activities within the TOGAF Standard to deliver value to the digital enterprise as needed per context of the emergence model. What is listed is a minimal set of Enterprise Architecture services that deliver Enterprise Architecture capabilities for decision-making in each context to ensure risk is understood, and to “peek-ahead” in preparation for going to the next context.

### 4.2. The DPBoK Standard

The DPBoK Standard identifies four contexts of organizational evolution toward a digital enterprise:

- Context I: Individual/Founder
- Context II: Team
- Context III: Team of Teams
- Context IV: Enduring Enterprise

The DPBoK Standard presents these contexts as levels, where the enterprise moves from an earlier context to the next level of success. This is described as an emergence model where only the knowledge and activity essential to the level is presented, with enough foreshadowing, to prepare for the transition to the next level of emergence. It is our strategy to support this emergence model with Enterprise Architecture through our peek-ahead strategy. So, not only does the Enterprise Architect support the specific context, but also considers the next level and informs the Digital Practitioners of ways to position themselves to evolve. At the higher levels of the emergence model, the Enterprise Architect can play an essential primary role in enabling cross-team communication without adding to

the cognitive load of the individual teams. In addition, the Enterprise Architects can ensure that the risks are clearly identified and communicated so that decisions can be made with an appropriate understanding of potential problems and difficulties.

Each of these contexts is described below in separate sections and for each the role of Enterprise Architecture is summarized along with a list of candidate Enterprise Architect services which might be leveraged by the Digital Practitioner to support their efforts.

#### 4.2.1. Context I: Individual/Founder

The Individual/Founder context addresses “minimum essential concerns they must address to develop and sustain a basic digital product”. This context represents the bare minimum requirements of delivering digital value.

The DPBoK Standard key topics for this context are:

- Conception of digital value

Architecture is often used as a communication medium. Architecture models communicate very well. Also, the Enterprise Architect is a communicator and considered a key enterprise networker.

- Digital infrastructure and related practices (the essential infrastructure and process choices to quickly deliver value to the market)

The Enterprise Architecture provides the necessary descriptions to communicate the infrastructure available and its appropriate use for both development and delivery. The Enterprise Architect can also help to identify existing infrastructure approaches for individuals/founders that may be embedded in larger organizations, and to communicate vetted technical requirements to the infrastructure organization to ensure preparation for new workloads. To clarify: in Context 1 (and Context 2 as well) there are usually not dedicated architects. Instead, architecture is a role, an activity, or the responsibility of the team, to be performed when – and only when – it is needed.

- Agile development and continuous delivery practices

Enterprise Architecture is often used to support and provide answers to questions about Agile development and continuous delivery. Enterprise Architects, if available to individuals/founders, are often approached to provide guidance in these areas on demand, based on their practical experience.

In this context it is expected that Enterprise Architecture efforts must support the project to deliver digital products/solutions effectively and efficiently. To support this context, the person acting as the Enterprise Architect has a role to assure that risk is understood and that decisions are made with an understanding of risk.

For example, when an individual/founder proceeds with the development and deployment of a new digital product they must be informed of risks associated with the inadvertent release of

information that is either sensitive or classified. Also the individual/founder may need guidance on ease of use, assistance with timely delivery, and guidance on technologies that can assist or deter.

More details about the TOGAF Standard supporting enterprise agility can be found in the TOGAF® Series Guide: Enabling Enterprise Agility (see Referenced Documents) and in the TOGAF® Series Guide: Applying the TOGAF® ADM using Agile Sprints (see Referenced Documents).

Enterprise Architects need to deliver this support in an on-demand, service-oriented manner to meet the operating tempo of the individual/founder. Some areas where the Enterprise Architecture and the TOGAF Standard could support the creation of a digital strategy include:

- Identifying digital offerings or digital value using an outside-in view that focuses on the customer or end user first
- Distinguishing strategy from the business model, and communicating the strategy to support a corporate brand identity
- Helping to distinguish between the problem space and the solution space
- Helping to shift from requirements to outcome-oriented and outcome-centered thinking in product delivery and value delivery to customers through value streams and capabilities identification
- Increasing or enhancing operational excellence by supporting and providing guidance for operational improvements

This includes modeling operations and defining a realistic improvement roadmap; collaborating on models to ensure a complete picture of the company from supplier to end-user support, product ideation through retirement, and throughout the value stream with demarcations for cost and revenue. Examples of this type of output or outcome include a business model canvas, business scenarios, value stream and business capabilities mapping, product and service modeling, use cases, and business cases, specifically around requirements management:

  - Digital security, security architecture, risk management, and Enterprise Architecture governance to provide the company protection from harmful events
  - Creating a digital stack by identifying the supporting capabilities for the digital offering, as well as the digital stack and associated interdependencies
  - Defining the digital lifecycle through the service, application portfolio, and security infrastructure lifecycle viewpoints

#### 4.2.2. Context II: Team

The team has a single mission and a cohesive identity, but does not need a lot of overhead to get the job done. The Team context covers the basic elements necessary for a collaborative product team to achieve success while remaining at a manageable human scale. Establishing team collaboration as a fundamental guiding value is essential to successful digital product development. Even with a few new people comes the need to establish product direction more clearly, so people are building the right thing. The team is all in the same location, and can still communicate informally, but there is enough

going on that it needs a more organized approach to getting work done.

The collaboration level represents the critical Team-level experience. Establishing team collaboration as a fundamental guiding value is essential to successful digital product development. The insights of the Agile movement and related themes such as Lean are primary in this context.

The DPBoK Standard highlights the following areas of interest within the Team context:

- Product Management
  - Product architecture has been a staple for assisting product management decisions

Enterprise Architecture can provide architecture models that map to a given digital product profile. Additionally, Enterprise Architecture makes interdependencies explicit, assuring an holistic view of the digital product.

- Work Execution Management
  - Enterprise Architecture is often used to depict processes and workflows in very simple to very complex levels of detail

In the Team context very simple models can be constructed to help communicate workflows and processes; not the entire answer for work management, but a good way to communicate within a small team.

- Operations Management
  - Enterprise Architects have been significant contributors to those managing operations

Indeed, whenever you see a control board you are seeing a visual depiction of the connection between the operations architecture and real-time data about operations. In the Teams context a single digital product may need an architecture model to depict how operations are expected to run while the actual digital product is running and while the team is working on the continuous delivery of improvements to that product.

In the Team context the Enterprise Architecture efforts must support the project to deliver digital products/solutions effectively and efficiently in an environment where there are more people involved

- communication is essential. In the Team context the Enterprise Architect has an even greater role to assure that risk is understood and that decisions are made with an understanding of risk. And, given the greater number of people involved in the Team context, the Enterprise Architect has an additional role to ensure efficacy of communication and collaboration. So, modeling and documenting become more important to have a common shared understanding to support product management, work execution, and operations understanding.

For example, when a team proceeds with the development and deployment of a new digital product they must not only be informed of data risks, they must also have a shared understanding of those risks among team members. Also critical in a team environment is to ensure a common and shared approach to requirements understanding to avoid different team members moving on different

priorities. For the small teams typically working in this context, the approach should be lightweight communication in full support of the team’s tempo.

Enterprise Architects help to communicate risks and mitigations when dealing with data security, guidance on ease-of-use, assisting with requirements understanding, assisting with timely delivery, and providing guidance on technologies that can assist or deter. Enterprise Architects should deliver this support in an on-demand, service-oriented manner to meet the operating tempo of the team.

#### 4.2.3. Context III: Team of Teams

Coordinating across a team of teams is the main concern that people in an Enterprise Architect role need to address using Enterprise Architecture and the TOGAF Standard. Too often, coordination mechanisms (such as overly process-centric operating models) degrade team cohesion and performance. It is important to balance overcomplex coordination with the need to ensure the success of a family of digital products.

The Team of Teams context is a natural evolution of the Teams context, but one where the number of people and digital products involved generates complexity. Coordinating across a team of teams is the main concern and, too often, coordination mechanisms degrade team cohesion and performance. Communication is again key to ensure successful collaboration and value delivery.

The Team of Teams context is where the traditional strengths of Enterprise Architecture increase significantly in value through identifying and enabling essential interactions between teams while minimizing the cognitive load of those interactions for the team members.

The DPBoK Standard key topics for this context are:

- Organization and cultural factors

Organizational, and especially cultural, issues are often significant drivers in shaping process design, especially in international or multi-jurisdictional enterprises. In certain cases, it might be necessary to respect cultural differences through different means. The means might include altering basic processes, different approaches to stakeholder interaction and management, or altering designs. When an organization is described in terms of value generation, many cultural issues can be managed simply by respecting the constituent parts of the organization. Enterprise Architecture helps to resolve all of these concerns.

- Coordination and process mechanisms

Enterprise Architecture is used to depict processes and control mechanisms. It is used to identify and eliminate choke points and for continuous process improvement.

- Investment and portfolio consequences of a multi-team structure

Enterprise Architectures that depict portfolios of products are critical resources in portfolio management. The holistic depiction of interdependencies, value generation, and cost, etc. support portfolio management decision-making.

Other areas where Enterprise Architecture and TOGAF Standard expertise can be used to remove friction from company operations and growth include:

- Identifying key drivers for the transition from a unitary team to a team of teams
- Identifying the basics of coordination problems and providing a solution that solves it, which includes spotlighting the pros and cons of traditional process management
- Identifying the basic product/function spectrum of organizational forms
- Identifying important cultural factors and concepts for measuring and changing culture

In the Team of Teams context, Enterprise Architecture and the person in the Enterprise Architect role continues to ensure that risk is understood and communication is effective. Yet, given the greater number of digital products involved in a Team of Teams context, the Enterprise Architect has the additional role of ensuring that the digital products work together, leverage each other, and are appropriately coupled; thus, modeling and documenting the move from a specific digital product to portfolios of digital products that require interoperability.

Additional areas where Enterprise Architecture and the TOGAF Standard provide support include where Enterprise Architecture:

- Can be applied to support cross-activities and interdependencies between teams following a portfolio view
- Supports cross-activities and interdependencies between teams following a portfolio view in alignment with, and supported by, the IT4IT™ Standard
- Delivers the high-level view and landscape, and identifying the current and target organization maturity level for the digital enterprise
- Supports digital product and service catalog definition
- Provides capability-based planning and process management guidance

#### 4.2.4. Context IV: Enduring Enterprise

The Enduring Enterprise context is about how to manage an enterprise that has been successful and is now faced with the realities of operating a sustainable business over periods of time longer than the next product cycle; see the DPBoK Standard (see Referenced Documents), Section 6.4: “However, what may be less obvious is that scaling up in size also means scaling out in terms of timeframes: concern for the past and the future extend further and further in each direction. Organizational history is an increasing factor, and the need to manage this knowledge base can’t be ignored. The organization is fulfilling responsibilities set in place by those no longer present and is building product and signing service contracts to be fulfilled by those who will come after”.

The DPBoK Standard highlights the following areas of interest within the Enduring Enterprise context:

- Governance, risk, security, and compliance
  - Managing risk, including security risk, is often accomplished through governance and

compliance

Compliance criteria can be derived from internal (to the company) sources, and external sources (such as laws and regulation). Good Enterprise Architectures provide compliance criteria that must be used to assess compliance of business processes, information technology, and human resources (though admittedly little is done in Enterprise Architecture on the human resource side today other than specific certifications). The assessments should guide information governance decisions.

- Information management
  - A critical domain in any Enterprise Architecture is the Information Systems domain, which covers data and application architecture; this domain is here to guide information management issues
- Architecture and portfolio management
  - Enterprise Architectures that depict portfolios of product are critical resources in portfolio management

The holistic depiction of interdependencies – value generation, cost, etc. – supports portfolio management decision-making. Given the costs of Enterprise Architecture, this activity itself represents something within a portfolio that should be managed in the Enduring Enterprise context.

To support enduring enterprises, the Enterprise Architecture expands its role into overall strategy and governance. It must support what was presented immediately above, as well as support other enterprise issues such as handling third parties, impact analysis on mergers and acquisitions, etc.

Specific areas of enabling an enduring enterprise that the DPBoK Standard may or may not address but are relevant and can be leveraged from Enterprise Architecture and TOGAF Standard guidance and experience include:

- Establishing additional feedback mechanisms for steering, managing risk, and assuring performance at scale and ever-increasing time horizons and increasingly complex ecosystems; for example, governance, risk, security, and compliance
- Founding and maturing information management across the company
- Fostering an architecture-driven and portfolio management culture

Specific areas of supporting strategy/portfolio/projects/solution delivery that the DPBoK Standard may or may not address but are relevant and can be leveraged from Enterprise Architecture and the TOGAF Standard guidance and experience include:

- Defining architecture as a competency area
- Defining concepts, quality levels, and implementation guidance for architecture, digital strategy, and portfolio creation and management
- Defining and establishing Agile Enterprise Architecture
- Implementing Enterprise Architecture and the TOGAF Standard governance framework to support digital governance
- Providing architectural guidance that evolves data from information into knowledge that provides value to the company and adapting the trio to fulfill digital enterprise needs
- Providing portfolio support in the creation and connectedness between portfolios
- Adapting an existing or new Enterprise Architecture capability to support an Agile and digital organization
- Adapting Enterprise Architecture and the TOGAF Standard to fit its delivery style into Agile approaches and digital product creation and offerings
- Adapting Enterprise Architecture to support business strategies that are digital, and providing the required capabilities to deliver the digital offering, as well as supporting product and service digitalization

#### 4.2.5. Need More Detail?

The following subsections provide further detail:

- Section 4.3 summarizes the relevant Enterprise Architecture and TOGAF principles per context
- Section 4.4 summarizes the relevant Enterprise Architecture capabilities and Enterprise Architecture services per context
- Section 4.5 summarizes the relevant TOGAF ADM and TOGAF Series Guides per context

And Appendix D further rationalizes the positive connections between the TOGAF Standard and the DPBoK Standard.

### 4.3. How to Apply TOGAF Principles per Context

This section answers the questions:

- What principles from Enterprise Architecture and the TOGAF Standard support the approach of the DPBoK Standard toward a digital enterprise?
- How are these concepts applied in a digital enterprise context in general?

The following subsection identifies the TOGAF principles that directly support the intent of the DPBoK Standard and, in general, how and where they are applied in various emergence levels (contexts) of a digital enterprise. This is called the “principles aspect” of looking at the digital enterprise and the TOGAF Standard. Consideration was given to each of the principles from the TOGAF Standard, as listed in Appendix B.

*Figure 2: identifies which of the TOGAF principles are most applicable to each of the contexts of the*

DPBoK Standard. Descriptions of the principles and how they apply to the DPBoK contexts follow the

matrix. If a principle is assessed as applicable to an earlier context it applies to all other later contexts.

![Figure 2: TOGAF Principles Mapped to DPBoK Standard Contexts](images/04-using-the-togaf-standard-in-the-digital-enterprise-figure-2-p356.png)

*Figure 2: TOGAF Principles Mapped to DPBoK Standard Contexts*

This mapping should be used as a reference and for general guidance. What principles NOTE are finally selected will depend on the specific situation.

The following principles from the TOGAF Standard that support the DPBoK Standard are presented per digital enterprise context.

#### 4.3.1. Enterprise Architecture Principles: Individual/Founder

For each of the TOGAF principles, rationales, and implications given here, the individual/founder should assess the specific scenario for the following subjects and seek out Enterprise Architecture support when a particular subject is in play.

Principle 2: Maximize Benefit to the Enterprise

Decisions are made to provide maximum benefit to the enterprise as a whole.

- Rationale

This principle embodies “service above self”. Decisions made from an enterprise-wide perspective have greater long-term value than decisions made from any particular organizational perspective.

Maximum Return on Investment (ROI) requires information management decisions to adhere to enterprise-wide drivers and priorities. No group will detract from the benefit of the whole. However, this principle will not preclude any group from getting its job done.

Principle 2 should be written on the heart of every founder – “How do I maximize the value of my enterprise?”, whether this is someone working on an incubator “enterprise” in a larger organization, the head of a digital team that has just been spun out of a parent, or the classic two people in a garage.

- Implications for the Digital Enterprise

To support this principle in this context the Enterprise Architect and Enterprise Architecture must become enablers for decision-making, giving consideration to the following:

  - Supporting planning and information management decisions with an analysis of quality enterprise information
  - Communication of the greater benefit to the entire enterprise in contrast to local benefits when needed
  - Supporting application development priority-setting from an enterprise perspective
  - Applications component sharing across organizational boundaries
  - Governance

Principle 15: Data Security

Data is protected from unauthorized use and disclosure. In addition to the traditional aspects of national security classification, this includes, but is not limited to, the protection of pre-decisional, sensitive, source selection-sensitive, and proprietary information.

- Rationale

Open sharing of information and the release of information via relevant legislation must be balanced against the need to restrict the availability of classified, proprietary, and sensitive information. Existing laws and regulations require the safeguarding of national security and the privacy of data, while permitting free and open access. Pre-decisional (work-in-progress, not yet authorized for release) information must be protected to avoid unwarranted speculation, misinterpretation, and inappropriate use.

- Implications for the Digital Enterprise

The Enterprise Architect can support the assessment of this scenario and help with mitigation. The Enterprise Architect can also support decisions regarding the digital product architecture to avoid issues.

  - The aggregation of data may generate data security issues

The aggregation of unclassified or insensitive data can result in classified or sensitive data that may put the organization at risk.

  - The storage-use of classified or sensitive data requires special consideration of the digital product

Principle 17: Ease-of-Use

Applications are easy to use. The underlying technology is transparent to users, so they can concentrate on tasks at hand.

- Rationale

The more a user has to understand the underlying technology, the less productive that user is. Ease-of-use is a positive incentive for the use of applications. It encourages users to work within the integrated information environment instead of developing isolated systems to accomplish the task outside of the enterprise’s integrated information environment. Most of the knowledge required to operate one system will be similar to others. Training is kept to a minimum, and the risk of using a system improperly is low. Using an application should be as intuitive as driving a different car.

- Implications for the Digital Enterprise

The Enterprise Architect should have a good understanding of the requirements for and best practices to meet common look-and-feel requirements.

  - Common look-and-feel requirements

Applications may be required to have a common “look-and-feel” and support ergonomic requirements; hence, the common look-and-feel standard must be designed and usability test criteria must be developed.

  - User interface complexity

Guidelines for user interfaces should not be constrained by narrow assumptions about user location, language, systems training, or physical capability. Factors such as linguistics, customer physical infirmities (visual acuity, ability to use keyboard/mouse), and proficiency in the use of technology have broad ramifications in determining the ease-of-use of an application.

Principle 19: Responsive Change Management

Changes to the enterprise information environment are implemented in a timely manner.

- Rationale

If people are to be expected to work within the enterprise information environment, that information environment must be responsive to their needs.

- Implications for the Digital Enterprise

In the digital environment the Enterprise Architect can be an invaluable asset in helping to ensure that pitfalls to change can be addressed up front. The Enterprise Architect has a more holistic view and knowledge base so can be consulted on many of these issues to ensure responsive change management if needed.

  - Processes for managing and implementing change must be developed that do not create delays

#### 4.3.2. Enterprise Architecture Principles: Team

For each of the TOGAF principles, rationales, and implications given here, the team leader should assess the specific scenario for the following subjects and seek out Enterprise Architecture support when a particular subject is in play.

Principle 6: Service Orientation

Digital products should follow a service-oriented design which mirrors real-world business activities comprising the enterprise (or inter-enterprise) business processes.

- Rationale

Service orientation delivers enterprise agility and enables Boundaryless Information Flow™.

- Implications for the Digital Enterprise

The Enterprise Architect should be prepared to assess the appropriateness of using service orientation for the digital product(s) and provide guidance on implementing them if chosen. The Enterprise Architect should consider the following:

  - Service and microservice representation utilizes business descriptions to provide context; the information provides guidance used for service orchestration
  - Service orientation places unique requirements on the infrastructure, and implementations should use open standards to realize interoperability and location transparency
  - Implementations are environment-specific; they are constrained or enabled by context and must be described within that context
  - Consider if governance of service representation and implementation is required in this context

Principle 18: Requirements-Based Change

Only in response to business needs are changes to applications and technology made.

- Rationale

This principle will foster an atmosphere where organizational changes (business and business support environment) should happen in response to customer and market needs (outside-in view). This is to ensure that business value is the basis for any proposed change. However, a change in technology may provide an opportunity to improve the business process and, hence, improve the value delivered to customers.

- Implications for the Digital Enterprise

In digital enterprises requirements are handled somewhat differently than traditional methods. This principle is embodied in the digital enterprise and Agile development concepts of the "outside-in" view where customer experience trumps technology-driven decision-making. The Enterprise Architecture should consider:

  - Whether funding a specific effort based on response to customer and market needs should be governed based on risk to the enterprise
  - Whether change management has been considered

#### 4.3.3. Enterprise Architecture Principles: Team of Teams

In addition to the principles from the prior contexts, the following are relevant TOGAF Standard principles, their rationale, and implications in the digital enterprise context.

Principle 5: Common Use Applications

The development of applications used across the enterprise is preferred over the development of similar or duplicative applications that are only provided to a particular organization.

- Rationale

Duplicative capability is expensive and proliferates conflicting data.

- Implications for the Digital Enterprise

When an enterprise is in a Team of Teams context great care must be taken to balance the quick delivery of new digital products with the risk of increasing technical debt and the cost of integration and interoperation. Judicious consideration of the following should result in advice to the digital teams based on risks:

  - Organizations which depend on a capability that does not serve the entire enterprise should consider changing over to the replacement enterprise-wide capability, if it exists
  - Organizations should not develop or acquire capabilities for their own use which are

similar/duplicative of enterprise-wide capabilities; in this way, expenditures of scarce resources to develop essentially the same capability in marginally different ways will be reduced

Principle 10: Data is an Asset

Data is an asset that has value to the enterprise and is managed accordingly.

- Rationale

Data is a valuable corporate resource; it has a real, measurable value. In simple terms, the purpose of data is to aid decision-making. Accurate, timely data is critical to accurate, timely decisions. Most corporate assets are carefully managed, and data is no exception. Data is the foundation of our decision-making, so we must also carefully manage data to ensure that we know where it is, can rely upon its accuracy, and can obtain it when and where we need it.

- Implications for the Digital Enterprise

In the Team of Teams context this principle is recommended. This is one of three closely-related principles regarding data: data is an asset; data is shared; and data is easily accessible. The Enterprise Architect can help ensure that data and information are leveraged throughout the enterprise and/or that artificial boundaries are not put in place which deter enterprise leverage. The Enterprise Architect also takes on an education task to ensure that all teams within the enterprise understand the relationship between value of data, sharing of data, and accessibility to data. Data management is key for the digital enterprise in this context. Data discovery, consistent quality, data supporting new product and services design, data protection, self-service access, and scalable solutions are some of the key considerations. Data analytics is key to defining customer profiling for a better understanding of customer needs, supporting the definition of the digital offering. Consideration is given to the following:

  - Organizational capabilities which produced new data (not shared among other organizations) should assess the utility of this data to the enterprise
  - Cultural transition from “data ownership” thinking to “data stewardship” thinking
  - Data-information stewardship is important because obsolete, incorrect, or inconsistent data could be passed to enterprise personnel and could adversely affect decisions across the enterprise

Principle 11: Data is Shared

Users have access to the data necessary to perform their duties; therefore, data is shared across enterprise functions and organizations.

- Rationale

Timely access to accurate data is essential to improving the quality and efficiency of enterprise decision-making. It is less costly to maintain timely, accurate data in a single application, and then share it, than it is to maintain duplicative data in multiple applications. The enterprise holds a

wealth of data, but it is stored in hundreds of incompatible stovepipe databases. The speed of data collection, creation, transfer, and assimilation is driven by the ability of the organization to efficiently share these islands of data across the organization.

Shared data will result in improved decisions since we will rely on fewer (ultimately one virtual) sources of more accurate and timely-managed data for all of our decision-making. Electronically-shared data will result in increased efficiency when existing data entities can be used, without re-keying, to create new entities.

- Implications for the Digital Enterprise

As stated, this principle as well as the principles that data is both an asset and is easily accessible are closely related, hence the implications are basically the same. For this principle, consideration should be given to the following, again balancing value and risk:

  - A common set of policies, procedures, and standards governing data management and access for both the short and the long term:
  - In the short term: standard data models, data elements, and other metadata that define this shared environment and develop a repository system for storing this metadata to make it accessible
  - In the long term: common data access policies and guidelines for new application developers ensure that data in new digital products remains available to the shared environment and that data in the shared environment can continue to be used by the new digital products
  - For both the short term and the long term: common methods and tools for creating, maintaining, and accessing the data shared across the enterprise are useful
  - Trade-off with data security – under no circumstances will the data sharing principle cause confidential data to be compromised

Principle 12: Data is Accessible

Data is accessible for users to perform their functions.

- Rationale

Wide access to data leads to efficiency and effectivenes in decision-making, and affords a timely response to information requests and service delivery. Using information must be considered from an enterprise perspective to allow access by a wide variety of users. Staff time is saved and the consistency of data is improved.

- Implications for the Digital Enterprise

The implications of this principle are basically the same as for the above; data is an asset and data is shared. For this principle, consideration should be given to the following, balancing value and risk:

  - The ease with which users obtain information
  - The way information is accessed and displayed must be sufficiently adaptable to meet a wide range of enterprise users and their corresponding methods of access
  - Limiting the misinterpretation of information

Principle 16: Technology Independence

Applications are independent of specific technology choices and therefore can operate on a variety of technology platforms.

- Rationale

The independence of applications from the underlying technology allows applications to be developed, upgraded, and operated in the most cost-effective and timely way. Otherwise, technology, which is subject to continual obsolescence and vendor-dependence, becomes the driver rather than the user requirements themselves. Realizing that every decision made with respect to IT makes us dependent on that technology, the intent of this principle is to ensure that digital products are not dependent on specific hardware and operating systems software.

- Implications for the Digital Enterprise

When an enterprise is in a Team of Teams context, great care must be taken to balance the quick delivery of new digital products with the risk of increasing technical debt and the cost of integration and interoperation. Technology independence helps to manage the risk of technical debt. Judicious consideration of the following should result in advice to the digital teams based on risks:

  - Digital product portability
  - Commercial Off-The-Shelf (COTS) and Government Off-The-Shelf (GOTS) offerings may be technology and platform-dependent
  - Enablement of legacy applications to interoperate
  - Middleware to decouple applications from the underlying platform

Principle 20: Control (Manage) Technical Diversity

A key driver of the overall reorientation to digital has been that things like cloud and infrastructure as code frameworks drive down the acquisition and deployment cost of infrastructure. The emergence of the concept of “Infrastructure as Code” has reduced management complexity and the costs of deploying infrastructure. However, as the enterprise scales to larger contexts, there is a real, non-trivial cost required to manage multiple processing environments. Limiting the number of supported components may simplify maintainability and reduce costs as the enterprise reaches the Team of Teams and Enduring Enterprise contexts, where budgeting and management issues start to overlay product time-to-market considerations.

- Rationale

The business advantages of minimum technical diversity include the standard packaging of components, predictable implementation impact, predictable valuations and returns, redefined testing, utility status, and increased flexibility to accommodate technological advancements. Common technology across the enterprise brings the benefits of economies of scale to the enterprise. Technical administration and support costs are better controlled when limited resources can focus on this shared set of technology.

On the other hand, there is value to be exploited by digital enterprises in new technologies that specifically assist the digital enterprise. Using new technologies may, or may not, improve schedules. The trade-offs need to be considered.[6]

- Implications for the Digital Enterprise

Managing technical debt is an important job to ease growing larger contexts, particularly to the Team of Teams context where coordination and resource allocation across teams becomes critical. The Enterprise Architect can again apply their broad knowledge of the various technologies in play and help make better decisions early on. So if controlling technical debt is a desire while considering the cost of delay, then getting the Enterprise Architect to help address the following will be beneficial:

  - Technology choices could be constrained by the choices available within the technology blueprint or the technology blueprint can be enhanced with new digital technologies
  - Procedures for augmenting the acceptable technology set to meet evolving requirements will be supported by the Enterprise Architect.

Principle 21: Interoperability

Software and hardware should conform to defined standards that promote interoperability for data, applications, and technology.

- Rationale

Standards help to ensure consistency, thus improving the ability to manage systems, improve user satisfaction, and protect existing IT investments, thus maximizing ROI and cost reduction. Standards for interoperability additionally help to ensure support from multiple vendors for their products, and facilitate supply chain integration.

- Implications for the Digital Enterprise:

A team of teams creates many digital products leading to an increase in probability of need for interoperation. To facilitate this the Enterprise Architect can help digital teams in the following areas:

  - Interoperability standards and industry standards
  - Governance for setting standards, reviewing and revising them, and granting exceptions on use

#### 4.3.4. Enterprise Architecture Principles: Enduring Enterprise

The following are the related TOGAF Standard principles, their rationale, and implications in the digital enterprise context.

Principle 3: Information Management is Everybody’s Business

All organizations in the enterprise participate in the information management decisions needed to accomplish business objectives.

- Rationale

Information users are the key stakeholders, or customers, in the application of technology to address a business need. In order to ensure information management is aligned with business, all organizations in the enterprise must be involved in aspects of the information environment. The business experts from across the enterprise and the technical staff responsible for developing and sustaining the information environment need to come together as a team to jointly define the goals and objectives of IT.

- Implications for the Digital Enterprise

In this context the Enterprise Architect can perform the valued role of bringing different stakeholders together and coordinating the necessary collaboration to manage the digital enterprise from an holistic perspective. The Enterprise Architect must enable:

  - Operation as an enterprise team where stakeholders, including customers, need to accept responsibility for managing the information environment
  - Identification of the right resources to implement this principle

Principle 4: Business Continuity

Enterprise operations are maintained in spite of system interruptions.

- Rationale:

As system operations become more pervasive, we become more dependent on them; therefore, we must consider the reliability of such systems throughout their design and use. Business premises throughout the enterprise must be provided with the capability to continue their business functions regardless of external events. Hardware failure, natural disasters, and data corruption should not be allowed to disrupt or stop enterprise activities. The enterprise business functions must be capable of operating on alternative information delivery mechanisms.

- Implications for the Digital Enterprise:

In the Enduring Enterprise context business continuity is a priority. Supporting risk management is

therefore a priority of the Enterprise Architect, supported by a high-quality Enterprise Architecture. The areas of consideration include:

  - Dependence on shared-system applications mandates that the risks of business interruption be established and managed:
  - Management includes but is not limited to periodic reviews, testing for vulnerability and exposure, or designing mission-critical services to ensure business function continuity through redundant or alternative capabilities
  - Recoverability, redundancy, and maintainability within the Enterprise Architecture to support timely design
  - Digital products must be assessed for criticality and impact on the enterprise mission in order to determine the level of continuity required, and what corresponding recovery plan is necessary

### 4.4. Enterprise Architecture Capabilities and Services

Enterprise Architecture capabilities can be described as the ability to realize something within certain constraints and under certain conditions. Enterprise Architecture services are the delivery mechanism for Enterprise Architecture capabilities. In this section, we list the Enterprise Architecture capabilities supported by the TOGAF Standard that could be of use in each of the contexts of the DPBoK Standard, and then describe the Enterprise Architecture services that deliver those capabilities. The capabilities identified here were honed by analyzing both the implications of the principles in the prior section and the content from the DPBoK Standard – fundamentally by asking the question: “What Enterprise Architecture capabilities would be useful here?”.

Enterprise Architecture capabilities can be written in a manner such as: the Enterprise Architecting ability (skilled people, repeatable process, and material) to {do x} under circumstances {y} within time window {z}. Of course an Enterprise Architecture service can be engaged to deliver an Enterprise Architecture capability in any of the contexts, however it is understood that the emergence model does not need all services in all contexts.

![Figure 3: Enterprise Architecture Services to DPBoK Standard Emergence Model](images/04-using-the-togaf-standard-in-the-digital-enterprise-figure-3-p367.png)

*Figure 3: Enterprise Architecture Services to DPBoK Standard Emergence Model*

*Figure 3: summarizes the Enterprise Architecture services that should be considered per context to*

deliver Enterprise Architecture capabilities. The following sections elaborate on the Enterprise Architecture services and Enterprise Architecture capabilities most pertinent for each context. The Digital Practitioner would be wise to consider using the Enterprise Architecture services listed per context. The Enterprise Architecture service provider must consider the context and deliver in a timely manner, in line with the operation tempo of the given context.

#### 4.4.1. Enterprise Architecture Capabilities and Services: Individual/Founder

Enterprise Architecture capabilities that would be useful in this context include:

- The ability to assess and communicate the digital value of a proposed digital product
- The ability to communicate available and appropriate digital infrastructure for Agile development and the delivery of a proposed digital product (aka the digital infrastructure architecture and accompanying application architecture, addressing common look-and-feel, ease-of-use)
- The ability to communicate technical requirements to digital infrastructure managers
- The ability to respond to questions concerning risk on demand; e.g., change, privacy, and security risk
- The ability to communicate minimum business and technical standards for the digital product (covering security, human factors, technology, etc.)

To support the Individual/Founder context, the following Enterprise Architecture services should be considered:

- Business Value Assessment and Analysis Service
  - Provides on-demand assessment and analysis of business value based on the current state of the landscape

This service delivers:

  - Competitive assessment report
  - Capability assessment report
  - Value versus risk matrix
- Stakeholders Management Services
  - Provides capabilities to identify, understand, decide upon, and engage stakeholders based on the scope of a given effort

This service delivers:

  - Stakeholder identification report
  - Stakeholder engagement strategy and plan
  - Stakeholder needs report
- Sustainability Management Support Services
  - Provides on-demand analysis and recommendations for ensuring that sustainability is being addressed throughout programs required to meet the business goals of an organization over a time horizon based on the current state of the enterprise

This service delivers:

  - Sustainability assessment report
  - Sustainability recommendations
- Architecture and Standards Guidance Service (for digital infrastructure; Agile development, deployment, and delivery)
  - Provides guidance to developing organizations on using the architecture, standards, and how they are implemented

This service delivers:

  - Business recommendations
  - Policy recommendations
  - Technical recommendations
- Risk Management Services (specifically change management, data privacy, and security)
  - Provides analysis, assessments, and recommendations for risk mitigation based on the goals of the organization

This service delivers:

  - Risk identification report
  - Risk assessment report
  - Risk mitigation report

Each of these, and subsequent services must be provided in a timely manner to support NOTE the operational tempo of the effort. The limited context of the effort must be used to scope the depth of any analysis that would support execution of the service.

#### 4.4.2. Enterprise Architecture Capabilities and Services: Team

In addition to the Enterprise Architecture capabilities in the prior context, the following Enterprise Architecture capabilities would be useful in the Team context:

- The ability to assess interoperability and transparency needs (stakeholder needs)
- The ability to understand the impact of changes in digital product implementation
- The ability to understand all interdependencies
- The ability to understand the operational view of the business and development

Of the Enterprise Architecture capabilities identified in previous contexts, the following Enterprise Architecture capabilities would be taken to a greater level of precision:

- The ability to communicate available and appropriate digital infrastructure for Agile development and the delivery of a proposed digital product (aka the digital infrastructure architecture and accompanying application architecture, addressing common look-and-feel, ease-of-use, service orientation – including orchestration)
- The ability to respond, on demand, to questions concerning risk; e.g., change, privacy and security risk (no service governance and/or no change management)

In addition to the services from the Founder context, the following additional Enterprise Architecture service should be considered:

- Change Management
  - Provides recommendations for developing holistic change management plans
  - People impact recommendations
  - Processes impact recommendations
  - Technologies impact recommendations

The following are Enterprise Architecture services previously identified, but will be done with increased precision and granularity in this context:

- Stakeholders Management Services
  - Provides capabilities to identify, understand, decide upon, and engage stakeholders based on the scope of a given effort

This service delivers:

  - Stakeholder identification report
  - Stakeholder engagement strategy and plan
  - Stakeholder needs report (deeper focus on interoperation and integration)
- Sustainability Management Support Services
  - Provides on-demand analysis and recommendations for ensuring that sustainability is being addressed throughout programs required to meet the business goals of an organizational over a time horizon based on the current state of the enterprise

This service delivers:

  - Sustainability assessment report
  - Sustainability recommendations (deeper focus on reuse)
- Architecture and Standards Guidance Service (for digital infrastructure; Agile development, deployment, and delivery)
  - Provides guidance to developing organizations on using the architecture and implementing standards

This service delivers:

  - Business (model) recommendations (deeper focus on operational view)
  - Policy recommendations
  - Technical (model) recommendations (deeper focus on service orientation and interdependencies)
- Risk Management Services
  - Provides analysis, assessments, and recommendations for risk mitigation based on the goals of the organization

This service delivers:

  - Risk identification report (deeper focus on governance and change management)
  - Risk assessment report (deeper focus on governance and change management)
  - Risk mitigation report (deeper focus on governance and change management)

#### 4.4.3. Enterprise Architecture Capabilities and Services: Team of Teams

In addition to the Enterprise Architecture capabilities in the prior context, the following Enterprise Architecture capabilities would be useful in the Team of Teams context:

- Prior capabilities that could be deeper:
  - The ability to respond to questions concerning risk on demand; e.g., data governance, standards compliance governance
  - The ability to communicate minimum business and technical standards for the digital product, especially data access and sharing standards, application portability, interoperation, middleware
- New capabilities in this context:
  - The ability to understand the various parts of the organization and their part in the organization’s value stream
  - The ability to understand sourcing opportunities
  - The ability to understand processes in place
  - The ability to understand the bigger operational picture of the digital portfolio
  - The ability to understand reusable assets (processes, services, components, data) for a particular digital product

In addition to the Enterprise Architecture services from the Team context, the following additional Enterprise Architecture services should be considered:

- Architecture Project Planning Services
  - Provides a resourced project plan and statement of architecture work at the appropriate level of detail that matches the organization’s change process

This service delivers:

  - Statement of Architecture Work, including scope
  - Resources and tools
  - Expected activities to support and enable
- Architecting Tailoring Services
  - Maps out how Enterprise Architects provide value and evolve the architecture data in lockstep with an organization’s processes

This service delivers:

  - Course of action, covering:
  - Iteration
  - How to address the landscape with various levels (strategic, segment, capability, etc.)
  - Tailoring for frameworks, styles, and/or constraints to produce the right deliverables at the right time
- Architecture Vision and Strategy Services
  - Documents the vision that drives the architecting efforts including articulating the value proposition and Key Performance Indicators (KPIs)

This service delivers:

  - Expected business value
  - Expected performance improvements
  - Intent to support
  - Intended uses of the architecture and value
- Architecture Modeling and Documentation Services (MVA)
  - Provides modeling of architectures (Minimum Viable Architecture (MVA)) whether Enterprise, Business, Information, Application, Technology, Infrastructure, Systems, or Solution Architecture

This service delivers:

  - Baseline, Target, or Transition Architectures
- Architecture Integration Services
  - Provides analysis (across landscape, dependencies, gaps, and solutions) of relevant architectures that pertain to a particular project based on a given update to a particular architecture; for example, to ensure that all the interrelated architectures work together

This service delivers:

  - Updates to all relevant architectures
- Digital Product Release Support Services
  - Provides on-demand guidance on release issues based on the current state of the enterprise

This service delivers:

  - Release guidance
- Portfolio Management Support Services (including Asset Management, Acquisitions)
  - Provides on-demand analysis and recommendations for the portfolio of investments required to meet the business goals of an organization over a time horizon based on the current state of the enterprise:
  - Prioritization of portfolio items report
  - Acquisition recommendation and rationale
- Enterprise Analysis and Assessment Service
  - Provides support to various enterprise processes such as portfolio management, program management, project management, change management, risk management (impact), etc. honed for specific subjects such as readiness, concepts, risks, capabilities, governance, impact, process optimization, security, laws and regulations

This service delivers:

  - Assessment report
  - Recommendations
  - Supporting information

The following are Enterprise Architecture services previously identified, but will be done in more depth in the Team of Teams context:

- Architecture and Standards Guidance Service
  - Provides guidance to developing organizations on using the architecture and implementing standards.

This service delivers:

  - Business recommendations
  - Policy recommendations (especially data access and sharing standards)
  - Technical recommendations (especially data access and sharing standards, application portability, interoperation, middleware)
- Risk Management Services
  - Provides analysis, assessments, and recommendations for risk mitigation based on the goals of the organization

This service delivers:

  - Risk identification report (focusing on data governance, standards compliance governance)
  - Risk assessment report (focusing on data governance, standards compliance governance)
  - Risk mitigation report (focusing on data governance, standards compliance governance)

#### 4.4.4. Enterprise Architecture Capabilities and Services: Enduring Enterprise

In addition to the Enterprise Architecture capabilities in the prior context, the following Enterprise Architecture capabilities would be useful in the Enduring Enterprise context:

- The ability to understand mergers and acquisitions
- The ability to understand the bigger operational picture of the enterprise
- The ability to understand the components of the enterprise; services, interdependencies, costs, data usage
- The ability to understand enterprise impact; e.g., optimize for the enterprise, trade-offs
- The ability to identify mission-critical people, processes, and systems
- The ability to understand what it takes to maintain the business when stressed
- The ability to identify and rationalize stakeholder needs across the enterprise

Of the Enterprise Architecture capabilities identified in previous contexts, the following Enterprise Architecture capabilities would be deeper:

- The ability to respond to questions concerning risk on demand (deeper)
- The ability to assess interoperability and transparency needs (deeper)
- The ability to understand all interdependencies (integrating people, process, and technology)
- The ability to understand the various parts of the organization and their part in the organizations value stream (across the enterprise)

In addition to the services from the Team of Teams context, the following Enterprise Architecture services should be considered:

- Architecture Compliance Development Services (Business, Information, Application, Infrastructure, Systems, etc.)
  - Provides specific and actionable compliance criteria for an architecture whether Enterprise, Business, Information, Application, Technology, Infrastructure, Systems, or Solution Architecture

This service delivers:

  - Compliance criteria
  - Guidance for compliance
  - Recommendations for evidence
- Compliance Assessment and Analysis Service
  - Provides assessments and analysis of how standards identified in the pertinent architectures are being implemented

This service delivers:

  - Solutions assessment reports
  - Interoperability assessment report
- Capability Planning Service
  - Provides an holistic view of all it takes to improve and/or to provide specific capabilities

This service delivers:

  - Capability report detailing steps to improve or develop a new capability (people, process, technology, etc.) with roadmaps
- Enterprise Architecture Development Process Improvement Service
  - This service provides an assessment of, and recommendations for improving, the delivery process of an Enterprise Architecture service provider

This service delivers:

  - Assessment report
  - Recommendations for improvement

The following are Enterprise Architecture services previously identified, but will be done in more depth in the Enduring Enterprise context:

- Business Value Assessment and Analysis Service
  - Provides on-demand assessment and analysis of business value based on the current state of the landscape

This service delivers:

  - Competitive assessment report
  - Capability assessment report
  - Value versus risk matrix
- Stakeholders Management Services
  - Provides capabilities to identify, understand, decide upon, and engage stakeholders based on the scope of a given effort

This service delivers:

  - Stakeholder identification report
  - Stakeholder engagement strategy and plan
  - Stakeholder needs report (deeper focus on interoperation and integration)
- Architecture Integration Services
  - Provides analysis (across landscape, dependencies, gaps, and solutions) of relevant architectures that pertain to a particular project based on a given update to a particular architecture; for example, to ensure that all the interrelated architectures work together

This service delivers:

  - Updates to all relevant architectures
- Enterprise Analysis and Assessment Service
  - Provides support to various enterprise processes such as portfolio management, program management, project management, change management, risk management (impact), etc. honed for specific subjects such as readiness, concepts, risks, capabilities, governance, impact, process optimization, security, laws and regulations, etc.

This service delivers:

  - Assessment report
  - Recommendations
  - Supporting information
- Risk Management Services
  - Provides analysis, assessments, and recommendations for risk mitigation based on the goals of the organization

This service delivers:

  - Risk identification report (focusing on data governance, standards compliance governance)
  - Risk assessment report (focusing on data governance, standards compliance governance)
  - Risk mitigation report (focusing on data governance, standards compliance governance)

#### 4.4.5. Enterprise Architecture Services Emergence Model

The matrix in Figure 4 summarizes the Enterprise Architecture services per context. It constitutes the Enterprise Architecture Service Emergence Model.

![Figure 4: The Enterprise Architecture Service Emergence Model](images/04-using-the-togaf-standard-in-the-digital-enterprise-figure-4-p377.png)

*Figure 4: The Enterprise Architecture Service Emergence Model*

### 4.5. TOGAF Artifacts and Series Guides

#### 4.5.1. Mapping to the Individual/Founder Context

For modeling, the TOGAF viewpoints can also be delivered using the ArchiMate NOTE modeling notation in the ArchiMate® 3.1 Specification; see Referenced Documents.

![Table 2: Mapping to the Individual/Founder Context](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-2-p378.png)

*Table 2: Mapping to the Individual/Founder Context*

Enterprise Preliminary Phase and Phase A: Open Business Architecture (O-BA) – Architecture and strategic and motivation models Part II the TOGAF Standard Strategy and business entities from the TOGAF® Series Guide: Business supporting the TOGAF content metamodel used at this Capabilities definition of a level are: goal, objective, measure, digital strategy driver, course of action, value stream, TOGAF® Series Guide: Value Streams and business capabilities TOGAF® Series Guide Business Architecture Set

Why Business and IT Must Co-Create Strategy for a Digital Enterprise

Enterprise Phases B, C, and D: high-level landscape TOGAF® Series Guide Business Architecture view Architecture Set providing the organizational High-level models to understand and The TOGAF Series Guide applied at landscape to provide a systemic view for the area of solution level aimed to scale to cover a understand context concern at the Individual/Founder level more general landscape: and support the specially to identify dependencies with digital products other related areas TOGAF® Series Guide: A Practitioners’ positioning / digital Approach to Developing Enterprise product definition Base for an intentional architecture – Architecture Following the TOGAF® scale to cover just a segment of the ADM organization or the whole landscape – apply the minimum needed in the model (MVA)

Entities that can be applied from the TOGAF content metamodel can be found in Figures 2-1 and 2-2 in the TOGAF Standard – Architecture

Entities grouped in Business Architecture, Information Systems Architecture, and Technology Architecture.

Identify key Phases B, C, and D: more detailed views TOGAF® Series Guide Business capabilities needed – applied per segment, aimed to scale Architecture Set – Business Capabilities, to support the from solution level to a portfolio or Value Streams, Organization Mapping, digital offerings program level Information Mapping, Business Models (platforms and leverage latest Entities that can be applied from the Information Architecture: Business trends) TOGAF content metamodel can be Intelligence & Analytics and Metadata found in Figures 2-1 and 2-2 in the Management Reference Models TOGAF Standard – Architecture Content. Entities grouped in Business TOGAF® Series Guides applied at Architecture, Information Systems solution level aimed to scale to cover a Architecture, and Technology more general landscape: Architecture. TOGAF® Series Guide: A Practitioners’ Value streams, capabilities map, Approach to Developing Enterprise information mapping, technology Architecture Following the TOGAF® landscape, information systems ADM landscape TOGAF® Series Guide: Digital Artifacts and tools to address digital Technology Adoption: A Guide to technology adoption Readiness Assessment and Roadmap Development

Open Agile Architecture™ Standard, see Chapter 10: “Building Blocks Overview”

Digital services Phases B, C, and D TOGAF® Series Guide Business identification and Architecture Set design at different Business, information, and technology levels, customer- services identification TOGAF® Series Guide: A Practitioners’ facing, digital Approach to Developing Enterprise platforms, and Applied per segment or domain aimed Architecture Following the TOGAF® backend systems – to scale to cover portfolios, programs, ADM service portfolio and the overall organization definition How to Use the TOGAF® and IT4IT™ Entities that can be applied from the Standards Together TOGAF content metamodel can be found in Figures 2-1 and 2-2 in the TOGAF® Series Guide: Using the TOGAF® TOGAF Standard – Architecture Framework to Define and Govern Content. Entities grouped in Business Service-Oriented Architectures Architecture, Information Systems Architecture, and Technology Open Agile Architecture™ Standard, see Architecture. Chapter 4: “Architecture Development”

Customer focus: Phases B, C, and D: applied to map and TOGAF® Series Guide Business customer support Architecture Set information/data management and Customer journey definition Customer Experience-Driven Enterprise profiling, value Architecture: How to Revitalize your chain, and value Customer profiling DSP Business stream Customer data management Open Agile Architecture™ Standard, see Chapter 4: “Architecture Development” Value stream and capability mapping for customer journey support Open Agile Architecture™ Standard, see Chapter 10: “Building Blocks Overview” Entities that can be applied from the TOGAF content metamodel can be found in Figures 2-1 and 2-2 in the TOGAF Standard – Architecture Content. Entities grouped in Business Architecture, Information Systems Architecture, and Technology Architecture, especially the following: value streams, business capabilities, course of action, business information service, business services, contracts, events, products, actors, roles, function, and organization unit.

Product leadership: Phases B, C, and D applied to deliver a Open Agile Architecture™ Standard, see product design – product architecture; refer to the Chapter 4: “Architecture Development” the TOGAF ADM artifacts in the previous rows applied to applied to define a the product architecture Open Agile Architecture™ Standard, see product Chapter 10: “Building Blocks Overview” architecture from Entities that can be applied from the project to product TOGAF content metamodel can be TOGAF® Series Guide Business focus found in Figures 2-1 and 2-2 in the Architecture Set TOGAF Standard – Architecture Operational Content. Entities grouped in Business TOGAF® Series Guide: Enabling excellence: Architecture, Information Systems Enterprise Agility, see Chapter 5 Enterprise Architecture, and Technology Architecture Architecture. supporting operational improvements (operational model definition and improvement)

#### 4.5.2. Mapping to the Team Context

For modeling, the TOGAF viewpoints can also be delivered using the ArchiMate NOTE modeling notation in the ArchiMate® 3.1 Specification.

It is important to note that the recommendations provided in Section 4.5.1 are also applicable at the Team level since the approach and models are suitable to scale.

So in this mapping, the emphasis is on how to support coordination across teams.

![Table 3: Mapping to the Team Context](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-3-p383.png)

*Table 3: Mapping to the Team Context*

Enterprise The TOGAF ADM applied in an Agile TOGAF® Series Guide: Enabling Architecture way Enterprise Agility supporting projects/Agile Preliminary Phase and Phase A to TOGAF® Series Guide: Applying the delivery teams support user stories and epics – TOGAF® ADM using Agile Sprints intentional architecture – Enterprise Enterprise Architecture supporting Agile teams How to Use the ArchiMate® Modeling Architecture Language to Support TOGAF® supporting work Framework Projects execution applying Agile Open Agile Architecture™ Standard methodologies and DevOps

Enterprise Phases A and B applied to support TOGAF® Series Guide Business Architecture strategy definition and business Architecture Set – Business Capabilities, capabilities applied landscape to support teams Value Streams, Organization Mapping, to support product Information Mapping, Business Models management and Value streams – business capabilities operations: mapping The TOGAF Series Guide applied at Business solution level aimed to scale to cover a Architecture value Organizational maps more general landscape: stream and capabilities Business process improvements TOGAF® Series Guide: A Practitioners’ offered/managed Approach to Developing Enterprise by business unit(s) Platform structure analysis Architecture Following the TOGAF® ADM Capability-based planning Capability-Based Planning Supporting Project/Portfolio and Digital Capabilities Enterprise Mapping Using the TOGAF® and Architecture/the ArchiMate® Standards TOGAF ADM and project TOGAF® Series Guide: Architecture management Project Management

Organizational maps – information maps

Value streams and business capabilities

Product Phases A and B for product definition Open Agile Architecture™ Standard, see Management – Chapter 4: “Architecture Development” Enterprise Phases C and D to identify capabilities Architecture to support product delivery Open Agile Architecture™ Standard, see supporting product Chapter 10: “Building Blocks Overview” definition and Project to product shift to support and Chapter 14: “Product Architecture” architecture – product management reflected in product definition Phases E and F for product planning TOGAF® Series Guide Business and discovery and Phases G and H for product Architecture Set applied to define a governance and change management Product Architecture

Product – process – services and TOGAF® Series Guide: Enabling platform models as supporting artifacts Enterprise Agility, see Chapter 5

#### 4.5.3. Mapping to the Team of Teams Context

For modeling, the TOGAF viewpoints can also be delivered using the ArchiMate NOTE modeling notation in the ArchiMate® 3.1 Specification.

It is important to note that the recommendations provided in Section 4.5.1 are also applicable at the Team level since the approach and models are suitable to scale.

So in this mapping, the emphasis is on how to support coordination across different teams.

![Table 4: Mapping to the Team of Teams Context](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-4-p386.png)

*Table 4: Mapping to the Team of Teams Context*

Enterprise Preliminary Phase and Phase A to TOGAF® Series Guides applied at the Architecture support user stories and epics – program and portfolio level: applied to support intentional architecture – Enterprise cross-activities and Architecture supporting Agile teams TOGAF® Series Guide: A Practitioners’ interdependencies and Agile team of teams at portfolio Approach to Developing Enterprise between teams level Architecture Following the TOGAF® following a ADM portfolio view High-level iteration Phases B to D to provide the high-level landscape to Open Agile Architecture™ Standard, see support team of teams and address Chapter 4: “Architecture Development” interoperability issues. Open Agile Architecture™ Standard, see Governance support – architecture Chapter 10: “Building Blocks Overview” guardrails definition TOGAF® Series Guide: Enabling Entities that can be applied from the Enterprise Agility, see Chapter 5 TOGAF content metamodel can be found in Figures 2-1 and 2-2 in the World-Class EA: Governors’ Approach TOGAF Standard - Architecture Content. to Developing and Exercising an Entities grouped in Business Enterprise Architecture Governance Architecture, Information Systems Capability Architecture, and Technology Architecture and also in architecture realization (Content framework).

Enterprise High-level iterations Phases B-D to TOGAF® Series Guides applied at the Architecture provide the portfolio and service program and portfolio and project level: supporting landscape for every team and for the programs / set of teams – supported by the high- TOGAF® Series Guide: A Practitioners’ portfolios – service level general view of the landscape Approach to Developing Enterprise management described above Architecture Following the TOGAF® delivery aligned ADM Entities that can be applied from the with the IT4IT TOGAF content metamodel can be Standard TOGAF and IT4IT guides: found in Figures 2-1 and 2-2 in the TOGAF Standard – Architecture Seamless Service Delivery and the Content. Entities grouped in Business IT4IT™ Standard Architecture, Information Systems Architecture, and Technology How to Use the TOGAF® and IT4IT™ Architecture. Standards Together

Enterprise Preliminary Phase applied to address TOGAF Series Guide applied to define Architecture to maturity level for the digital enterprise the Enterprise Architecture capability deliver the high- to address the digital enterprise: level view and TOGAF® Series Guide: The TOGAF® landscape and to Leader’s Guide to Establishing and identify the Evolving an EA Capability organization maturity level for TOGAF maturity models and skills the digital management guides applied – adapted enterprise to address the digital enterprise:

TOGAF® Series Guide: Architecture Maturity Models

TOGAF® Series Guide: Architecture Skills Framework

TOGAF® Series Guide: Digital Technology Adoption: A Guide to Readiness Assessment and Roadmap Development

Enterprise Phases B, C, and D TOGAF Series Guide applied at the Architecture program / portfolio level: supporting digital Artifacts and views supporting portfolio product and definition for digital products TOGAF® Series Guide: A Practitioners’ service catalog Approach to Developing Enterprise definition Architecture Following the TOGAF® ADM - Application portfolio Capability-Based Planning Supporting management Project/Portfolio and Digital Capabilities - Service portfolio Mapping Using the TOGAF® and management ArchiMate® Standards - Digital portfolio management Open Agile Architecture™ Standard, see - Capability-based Chapter 4: “Architecture Development” planning - Process Open Agile Architecture™ Standard, see management Chapter 10: “Building Blocks Overview” and Chapter 14: “Product Architecture”

TOGAF® Series Guide Business Architecture Set applied to define a Product Architecture

TOGAF® Series Guide: Enabling Enterprise Agility, see Chapter 5

#### 4.5.4. Mapping to the Enduring Enterprise Context

For modeling, the TOGAF viewpoints can also be delivered using the ArchiMate NOTE modeling notation in the ArchiMate® 3.1 Specification.

It is important to note that the recommendations provided in Section 4.5.1 are also applicable at the team level since the approach and models are suitable to scale.

So in this mapping, the emphasis is on how to support coordination across different teams.

![Table 5: Mapping to the Enduring Enterprise Context](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-5-p389.png)

*Table 5: Mapping to the Enduring Enterprise Context*

Enterprise The TOGAF ADM applied in an Agile Open Business Architecture (O-BA) Architecture and way Standard the TOGAF Standard Preliminary Phase and Phase A to The TOGAF ADM applied at the strategy supporting support user stories and epics – and program level strategy/portfolio/p intentional architecture – Enterprise rojects and Architecture supporting Agile teams TOGAF® Series Guide Business solution delivery Architecture Set – Business Capabilities, Preliminary Phase and Phase A: Value Streams, Organization Mapping, - Architecture as a Strategic and motivation Information Mapping, Business Models competency area – the DPBoK Phases B, C, D: high-level landscape The TOGAF Series Guide applied at Standard, Section view – MVA solution level aimed to scale to cover a 6.4.3 more general landscape - Architecture, Base for an intentional architecture – Digital Strategy, scale to cover the enduring enterprise TOGAF® Series Guide: A Practitioners’ and Portfolio Approach to Developing Enterprise Phases B, C, D: more detailed – applied Architecture Following the TOGAF® Agile Enterprise per segment aimed to scale from ADM Architecture solution level to a portfolio or program level TOGAF® Series Guide: Enabling - Enterprise Enterprise Agility Architecture Value streams, capabilities map, capabilities information mapping, technology How to Use the ArchiMate® Modeling adapted to support landscape, information systems Language to Support TOGAF® the Agile and landscape Framework Projects digital organization The TOGAF content metamodel applied Open Agile Architecture™ Standard, see - Enterprise depending on the views needed Chapter 10: “Building Blocks Overview” Architecture and and Chapter 14: “Product Architecture” the TOGAF Standard – new delivery style following an Agile approach and supporting digital product offerings

Information / Data Phases B and C to identify business Information Architecture: Business / Information information capabilities and data Intelligence & Analytics and Metadata Architecture capabilities Management Reference Models guidance in progress – TOGAF® Series Guide: Information adapted/used to Mapping fulfil digital enterprise needs Open Agile Architecture™ Standard, see Chapter 18: Data Information and Artificial Intelligence

Enterprise Phases G and H applied following an TOGAF Standard governance content: Architecture and Agile approach the TOGAF World-Class EA: Governors’ Approach Digital metrics definition governance to Developing and Exercising an framework Enterprise Architecture Governance supporting digital Capability governance Open Agile Architecture™ Standard, see Chapter 8: “Agile Governance”

Enterprise Phases B, C, and D to define the Open Business Architecture (O-BA) – Architecture portfolios, values streams, and Part II supporting the capabilities business strategy TOGAF® Series Guide Business (digital) and Adaptation needed to cover digital Architecture Set – Business Capabilities, providing the product portfolio definition Value Streams, Organization Mapping, required Information Mapping, Business Models capabilities to deliver the digital TOGAF® Series Guide: A Practitioners’ offering – Approach to Developing Enterprise supporting Architecture Following the TOGAF® products/services ADM digitalization Open Agile Architecture™ Standard

## A: Enterprise Architecture Benefits

## A: Enterprise Architecture Benefits

- More effective and efficient business operations:
  - Lower business operation costs
  - More Agile organization
  - Business capabilities shared across the organization
  - Lower change management costs
  - More flexible workforce
  - Improved business productivity
- More effective and efficient digital enterprise and IT operations:
  - Extending effective reach of the enterprise through digital capability
  - Bringing all components of the enterprise into a harmonized environment
  - Lower software development, support, and maintenance costs
  - Increased portability of applications
  - Improved interoperability and easier system and network management
  - Improved ability to address critical enterprise-wide issues like security
  - Easier upgrade and exchange of system components
- Better return on existing investment, reduced risk for future investment:
  - Simplify the business ability to deliver value through technology
  - Maximum ROI in existing business and IT infrastructure
  - The flexibility to make, buy, or out-source business and IT solutions
  - Reduced risk overall in new investments and their cost of ownership
- Faster, simpler, and cheaper procurement:
  - Buying decisions are simpler, because the information governing procurement is readily available in a coherent plan
  - The procurement process is faster – maximizing procurement speed and flexibility without sacrificing architectural coherence
  - The ability to procure heterogeneous, multi-vendor open systems
  - The ability to secure more economic capabilities

## B: Principles from the TOGAF Standard

## B: Principles from the TOGAF Standard

- Principle 1: Primacy of Principles

Statement: These principles of information management apply to all organizations within the enterprise.

- Principle 2: Maximize Benefit to the Enterprise

Statement: Information management decisions are made to provide maximum benefit to the enterprise as a whole.

- Principle 3: Information Management is Everybody’s Business

Statement: All organizations in the enterprise participate in information management decisions needed to accomplish business objectives.

- Principle 4: Business Continuity

Statement: Enterprise operations are maintained in spite of system interruptions.

- Principle 5: Common Use Applications

Statement: Development of applications used across the enterprise is preferred over the development of similar or duplicative applications which are only provided to a particular organization.

- Principle 6: Service Orientation

Statement: The architecture is based on a design of services which mirror real-world business activities comprising the enterprise (or inter-enterprise) business processes.

- Principle 7: Compliance with Law

Statement: Enterprise information management processes comply with all relevant laws, policies, and regulations.

- Principle 8: IT Responsibility

Statement: The IT organization is responsible for owning and implementing IT processes and infrastructure that enable solutions to meet user-defined requirements for functionality, service levels, cost, and delivery timing.

- Principle 9: Protection of Intellectual Property

Statement: The enterprise’s Intellectual Property (IP) must be protected. This protection must be reflected in the IT architecture, implementation, and governance processes.

- Principle 10: Data is an Asset

Statement: Data is an asset that has value to the enterprise and is managed accordingly.

- Principle 11: Data is Shared

Statement: Users have access to the data necessary to perform their duties; therefore, data is shared across enterprise functions and organizations.

- Principle 12: Data is Accessible

Statement: Data is accessible for users to perform their functions.

- Principle 13: Data Trustee

Statement: Each data element has a trustee accountable for data quality.

- Principle 14: Common Vocabulary and Data Definitions

Statement: Data is defined consistently throughout the enterprise, and the definitions are understandable and available to all users.

- Principle 15: Data Security

Statement: Data is protected from unauthorized use and disclosure. In addition to the traditional aspects of national security classification, this includes, but is not limited to, protection of pre-decisional, sensitive, source selection-sensitive, and proprietary information.

- Principle 16: Technology Independence

Statement: Applications are independent of specific technology choices and therefore can operate on a variety of technology platforms.

- Principle 17: Ease-of-Use

Statement: Applications are easy to use. The underlying technology is transparent to users, so they can concentrate on tasks at hand.

- Principle 18: Requirements-Based Change

Statement: Only in response to business needs are changes to applications and technology made.

- Principle 19: Responsive Change Management

Statement: Changes to the enterprise information environment are implemented in a timely manner.

- Principle 20: Control Technical Diversity

Statement: Technological diversity is controlled to minimize the non-trivial cost of maintaining expertise in and connectivity between multiple processing environments.

- Principle 21: Interoperability

Statement: Software and hardware should conform to defined standards that promote interoperability for data, applications, and technology.

## C: Services Proposed for the TOGAF Standard

## C: Services Proposed for the TOGAF Standard

The following are Enterprise Architecture services that package TOGAF activities to deliver value on demand. There are two major categories: one is customer-centric and the other is more internal to the architecting community. This document focuses on customer-centric Enterprise Architecture services.

![Table 6: Enterprise Architecture Service Categories and Descriptors](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-6-p395.png)

*Table 6: Enterprise Architecture Service Categories and Descriptors*

Customer-Centric REQUIREMENTS Product managers Enterprise Stakeholder Solid outside-in ELICITATION AND Architect with concerns view of UNDERSTANDING requirements requirements and SERVICES understanding Requirements value for solutions specialty balanced among Assessments stakeholders (value, ability, etc.)

DESIGN SUPPORT Program-level Enterprise MVA (including Better design SERVICES decision-makers Architect standards and decisions builder/modeler compliance criteria, roadmaps) Successful for programs programs and projects Compliance guidance

Compliance reports

DEVELOPMENT Project-level Enterprise MVA (including Better product SUPPORT SERVICES decision-makers Architect standards and decisions builder/modeler compliance criteria) for Successful projects/products products

Compliance guidance

Compliance reports

ENTERPRISE C-level Enterprise analysts Answers to Better enterprise SUPPORT SERVICES management using Enterprise questions decisions Architecture as a tool Assessment reports Lower risk

Recommendations

Internal-Centric ARCHITECTURE Architecture team Experienced Architecture Resourced PLANNING leaders Enterprise project plans architecture team SERVICES Architect ENTERPRISE Architecture Enterprise Enterprise Highly skilled and ARCHITECTURE organization Architecture Architecture organized PRACTICE decision-makers practice experts capability Enterprise DEVELOPMENT assessments Architecture SUPPORT SERVICES practice Enterprise organization Architecture (internal or capability external) improvement recommendations

### C.1. Requirements and Elicitation

This service category contains candidate services that enable requirements understanding – taking a step beyond requirements management, these services help get closer to real needs, which will deliver greater business value.

![Table 7: Requirements Elicitation and Understanding Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-7-p396.png)

*Table 7: Requirements Elicitation and Understanding Services*

Business Value Assessment and Provides on-demand assessment Competitive assessment report Analysis and analysis of business value based on the current state of the Capability assessment report landscape Value versus risk matrix

Stakeholders Management Provides capabilities to identify, Stakeholder identification report understand, decide upon, and engage stakeholders based on Stakeholder engagement strategy the scope of a given effort and plan

Stakeholder needs report

### C.2. Architecture Planning

This service category contains candidate services that enable well-planned and executed architecture projects in support of organization change. These services would typically be provided in the beginning of a “project”, whether large or small, waterfall, or Agile.

![Table 8: Architecture Planning Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-8-p397.png)

*Table 8: Architecture Planning Services*

ADM Tailoring Maps out how Enterprise Course of action, covering: Architects provide value and

  - Iteration evolve the architecture data in lockstep with an organization’s
  - How to address the processes landscape with various levels (strategic, segment, capability, etc.)
  - Tailoring for frameworks, styles, and/or constraints to produce the right deliverables at the right time

Architecture Project Planning Provides a resourced project Statement Of Architecture Work, plan and statement of including scope architecture work at the Resources and tools appropriate level of detail that matches the organization’s Expected activities to support change process and enable

### C.3. Design Support

This service category contains candidate services that enable good design decisions in support of organization change. These services would typically be provided after a project has been funded, whether large or small, waterfall, or Agile. These services include the development of MVAs and associated analysis to support the design decisions.

![Table 9: Design Support Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-9-p398.png)

*Table 9: Design Support Services*

Architecture Compliance Provides specific and actionable Compliance criteria Development compliance criteria for an Guidance for compliance architecture, whether Enterprise, Business, Recommendations for evidence Information, Application, Technology, Infrastructure, Systems, or Solution Architecture

Architecture Integration Provides analysis (across Updates to all relevant landscape, dependencies, gaps, architectures and solutions) of relevant architectures that pertain to a particular project based on a given update to a particular architecture; for example, to ensure that all the interrelated architectures work together

Architecture Modeling Provides modeling of Baseline, Target, or Transition architectures (MVA), whether Architectures Enterprise, Business, Information, Application, Technology, Infrastructure, Systems, or Solution Architecture

Architecture Vision and Strategy Documents the vision that drives Expected business value Definition the architecting efforts including articulating the value Expected performance proposition and KPIs improvements

Intent to support

Intended uses of the architecture and value

### C.4. Development Support

This service category contains candidate services that enable good development decisions in support of organization change. These services would typically be provided during the development phase of a project, whether large or small, waterfall, or Agile. These services focus on answering questions and providing enterprise analysis in support of development decisions.

![Table 10: Development Support Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-10-p399.png)

*Table 10: Development Support Services*

Architecture and Standards Provides guidance to developing Business recommendations Guidance organizations on using the Policy recommendations architecture and implementing standards Technical recommendations

Change Management Provides recommendations for People impact recommendations developing holistic change management plans Processes impact recommendations

Technologies impact recommendations

Compliance Assessment and Provides assessments and Solutions assessment reports Analysis analysis of how standards identified in the pertinent Interoperability assessment architectures are being report implemented

Release Support Provides on-demand guidance Release guidance on release issues based on the current state of the enterprise

### C.5. Enterprise Support

This service category contains services that enable good enterprise decisions in support of organization change. These services could be provided independent of any individual project. These services focus on answering questions and providing enterprise analysis in support of more strategic decisions.

![Table 11: Enterprise Support Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-11-p399.png)

*Table 11: Enterprise Support Services*

Capability Planning Support Provides an holistic view of all it Capability report detailing steps takes to improve and/or to to improve or develop a new provide specific capabilities capability (people, process, technology, etc.) with roadmaps

Portfolio Management Support Provides on-demand analysis Prioritization of portfolio items and recommendations for the report portfolio of investments required to meet the business goals of an Acquisition recommendation organization over a time horizon and rationale based on the current state of the enterprise

Risk Management Provides analysis, assessments, Risk identification report and recommendations for risk mitigation based on goals of the Risk assessment report organization Risk mitigation report

Sustainability Management Provides on-demand analysis Sustainability assessment report Support and recommendations for ensuring that sustainability is Sustainability recommendations being addressed throughout programs required to meet the business goals of an organization over a time horizon based on the current state of the enterprise

Enterprise Analysis and Provides support to various Assessment report Assessment enterprise processes such as portfolio management, program Recommendations management, project management, change Supporting information management, risk management (impact), etc. honed for specific subjects such as readiness, concepts, risks, capabilities, governance, impact, process optimization, security, laws and regulations, etc.

### C.6. Enterprise Architecture Practice Development Support

This service category contains candidate services that enable the development and management of an Enterprise Architecture practice. These services are focused on improving the Enterprise Architecture capability.

![Table 12: Enterprise Architecture Practice Development Support Services](images/04-using-the-togaf-standard-in-the-digital-enterprise-table-12-p401.png)

*Table 12: Enterprise Architecture Practice Development Support Services*

Enterprise Architecture This service provides an Assessment report Development Process assessment of, and Improvement recommendations for improving, Recommendations for the delivery process of an improvement Enterprise Architecture Service Provider

### C.7. Services Mapped to ADM Phases

![Figure 5: Enterprise Architecture Service to ADM Phase](images/04-using-the-togaf-standard-in-the-digital-enterprise-figure-5-p401.png)

*Figure 5: Enterprise Architecture Service to ADM Phase*

## D: Rationalizing the TOGAF and DPBoK Standards

## D: Rationalizing the TOGAF and DPBoK

## Standards

This appendix provides another view that might further clarify the answer to the question: “Is there a conceptual alignment of the TOGAF and DPBoK Standards?”

The DPBoK Standard, Section 4.9: “Compatibility with Enterprise Architecture”, describes the connection between the digital enterprise and Enterprise Architecture as:

As part of the paradigm shift to digital, it is important to have a clear understanding of which existing capabilities can be retired, and which new ones will be needed. In some cases, organizations may need to deal with all these changes while keeping their current legacy platform and supporting applications. Integrating new capabilities with existing ones in an effective and efficient way requires a clear landscape and overall view of the organization context. This is provided by Enterprise Architecture.

- The DPBoK Standard

The DPBoK Standard further identifies the following topic areas that can be used for aligning a digital enterprise and Enterprise Architecture concepts and practices:

- DPBoK alignment area: A systemic view of organizational reality, capabilities, and dependencies
- DPBoK alignment area: Recognizing and communicating internal and external context, integrating the “outside-in” and “inside-out” views
- DPBoK alignment area: Driving strategic alignment and synergy among organizational components
- DPBoK alignment area: Enabling innovation while also managing technical debt

The following subsections summarize the concepts in the TOGAF Standard that supports these alignment areas between the digital enterprise and Enterprise Architecture/the TOGAF Standard. Within the subsections we consider two aspects:

- Benefits aspect – considers the general benefits of Enterprise Architecture which support the digital enterprise since the TOGAF Standard has evolved specifically to realize them

This is accomplished by listing the benefits of Enterprise Architecture that guide the content of the TOGAF Standard and highlighting the specific benefits that relate to the digital enterprise. Having said that, it isn’t a stretch to notice that all the benefits of Enterprise Architecture relate to the digital enterprise, at least indirectly. Consideration was given to Enterprise Architecture benefits listed in Appendix A.

- Enterprise Architecture services aspect – where proposed Enterprise Architecture services, if deployed, would support the subject DPBoK Standard alignment area

Consideration was given to the candidate Enterprise Architecture services proposed for the TOGAF Standard listed in Appendix C.

Enterprise Architecture services are delivered by architects (or someone in the role of architect) to provide Enterprise Architecture capabilities. Careful consideration should be given to the matter of whether a skilled architect is on a team to deliver those capabilities. Especially in Contexts I and II, team dynamics work best with skilled experts being on the team in contrast to being engaged from an outside source. As the enterprise grows in complexity to the Team of Teams and Enduring Enterprise levels, the value of engaging external Enterprise Architecture services increases.[7]

In looking at these aspects and their support for the DPBoK Standard alignment areas, we observe the following:

- Each of the following aspects lists benefits and proposed Enterprise Architecture services for each of the DPBoK Standard alignment areas
- The elements in the lists support the notion of Enterprise Architecture being a valuable asset for the digital enterprise, with slight changes in the delivery of the Enterprise Architecture capability needed
- It is recommended that the person in the role of Enterprise Architect utilizes a service delivery model to provide Enterprise Architecture services that help the company to realize the benefits in a timely manner, one where delivery is done in support of the digital enterprise tempo

### D.1. Organizational Reality, Capabilities, and Dependencies

Each of the following aspects lists benefits and proposed Enterprise Architecture services that support the DPBoK Standard alignment area.

#### D.1.1. Aspect: Enterprise Architecture Benefits

- More effective and efficient business operations – business capabilities are shared across the organization
- More effective and efficient digital enterprise and IT operations – to extend the effective reach of the enterprise through digital capability, and to bring all components of the enterprise into a harmonized environment
- Faster, simpler, and cheaper procurement – create an environment where buying decisions are simpler, because the information governing procurement is readily available in a coherent plan

#### D.1.2. Aspect: Enterprise Architecture Services

- Requirements Elicitation and Understanding Services – Stakeholders Management Services
- Design Support Services – Architecture Integration Services, Architecture Modeling, and Documentation Services (MVA)
- Enterprise Support Services – Portfolio Management Support Services (including Asset

Management, Acquisitions), Risk Management Services, Sustainability Management Support Services, Enterprise Analysis and Assessment Services, Capability Planning Support Service

### D.2. Integrating “Outside-In” and “Inside-Out” Views

#### D.2.1. Aspect: Enterprise Architecture Benefits

- More effective and efficient digital enterprise and IT operations – extending the effective reach of the enterprise through digital capability, and bringing all components of the enterprise into a harmonized environment

#### D.2.2. Aspect: Enterprise Architecture Services

- Requirements Elicitation and Understanding Services – Stakeholders Management Services
- Design Support Services – Architecture Vision and Strategy Services, Architecture Modeling and Documentation Services (MVA)
- Enterprise Support Services – Enterprise Analysis and Assessment Services, Capability Planning Support Service

### D.3. Strategic Alignment and Synergy

#### D.3.1. Aspect: Enterprise Architecture Benefits

- More effective and efficient business operations – business capabilities shared across the organization, more flexible workforce, and improved business productivity
- More effective and efficient digital enterprise and IT operations – extending effective reach of the enterprise through digital capability, bringing all components of the enterprise into a harmonized environment, and improved interoperability and easier system and network management
- Better return on existing investment, reduced risk for future investment – reduced complexity in the business and IT

#### D.3.2. Aspect: Enterprise Architecture Services

- Requirements Elicitation and Understanding Services – Business Value Assessment and Analysis Service
- Development Support Services – Architecture and Standards Guidance Service, Change Management, Release Support Services
- Enterprise Support Services – Portfolio Management Support Services (including Asset Management, Acquisitions), Sustainability Management Support Services, Enterprise Analysis and Assessment Services, Capability Planning Support Service

### D.4. Enabling Innovation While Managing Technical Debt

#### D.4.1. Aspect: Enterprise Architecture Benefits

- More effective and efficient digital enterprise and IT operations – bringing all components of the enterprise into a harmonized environment, increased portability of applications, improved ability to address critical enterprise-wide issues like security
- Better return on existing investment, reduced risk for future investment – reduced complexity in the business and IT, maximum ROI in existing business and IT infrastructure, reduced risk overall in new investments and their cost of ownership

#### D.4.2. Aspect: Enterprise Architecture Services

- Design Support Services – Architecture Compliance Development Services (Business, Info, Application, Infrastructure, Systems, etc.)
- Development Support Services – Compliance Assessment and Analysis Service
- Enterprise Support Services – Enterprise Analysis and Assessment Services, Risk Management Services

---

## Footnotes

- [2] The DPBoK Standard, Section 6.6.2.2.9, “Cost of Delay”. [3] The DPBoK Standard, Section 6.2.2.2.3, “Front Load the Development Process”: “Poor decisions made early in the development process have negative consequences that increase exponentially over time because reversing them later in the [4] Terms taken from the DPBoK Standard, Chapter 2: “Definitions” unless otherwise stated. [5] Terms taken from the TOGAF Standard – Introduction and Core Concepts, Chapter 4: “Definitions” unless otherwise [6] More details about the factors and consideration for the adoption of new technologies can be found in the TOGAF® Series Guide: Digital Technology Adoption: A Guide to Readiness Assessment and Roadmap Development; see Referenced
