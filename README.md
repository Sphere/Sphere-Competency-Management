# Sphere Competency Management
## Introduction
**Sphere Competency Management** is an open-source, modular, and configurable platform built on **[Sunbird](https://www.sunbird.org/product/building-blocks)** building blocks. It is designed for large-scale capacity building of healthcare workers, leveraging the **[FRAC framework](https://clop.cegis.org/what-is-frac)** (Roles, Activities, Competencies) to map competencies across organizational roles.

The platform supports:

 - Role-based competency mapping
 - Competency gap analysis and learning path generation
 - Content curation, onboarding and publishing
 - Web/mobile delivery of e-learning content
 - A plug-and-play mobile app with personalization capability
 - Progress tracking and credentialing of user learning
 - Multi-language support for UI and content
 - User/org management and FRAC administration
 - Scalable architecture for nationwide deployments
 - Web/mobile delivery of e-learning content with in-built Learning Management System

The platform is deployed as [**E-Kshamata**](https://play.google.com/store/apps/details?id=org.aastrika.ekshamata&hl=en-US) in multiple Indian states and can be easily extended or integrated with other systems due to its composable, open-source design.

## Functional Overview

### Framework of Roles, Activities, and Competencies (FRAC)**

The **Framework of Roles, Activities, and Competencies (FRAC)** is a comprehensive competency mapping system to augment capacity building through systematic role-based human resource management. FRAC maps specific competencies to individual positions across government ministries, departments, and organizations, creating a single source of truth for role requirements and performance expectations.

FRAC operates through four interconnected components: **Position** (specific designation), **Roles** (coherent sets of sequential activities), **Activities** (individual actions contributing to objectives), and **Competencies** (knowledge, skills, and attitudes required for successful performance). This framework demystifies job requirements and enables precise competency gap identification.

### Implementation in Healthcare Sector

In healthcare context, FRAC provides exceptional value by standardizing competency requirements across diverse medical positions - from medical officers and nurses to public health administrators.

A system designed to manage a healthcare professional’s competencies based on FRAC definitions can effectively assess individual competency gaps, deliver targeted training and assessments to address those gaps, and record achievements as verifiable credentials. This approach ensures that healthcare professionals gain exactly the competencies required for their specific roles.

Most importantly, implementation of FRAC enhances **citizen-centric healthcare delivery** by ensuring that every healthcare position has clearly defined competencies aligned with patient care objectives, ultimately improving health outcomes and public trust in government healthcare services.

#### For more details please visit this [link](https://clop.cegis.org/what-is-frac) 
#### A sample frac setup can be accessed [here](https://github.com/Sphere/Sphere-Competency-Management/blob/main/SampleFRAC_ANM.xlsx)


## Implementation Showcase

#### Aastrika Sphere Platform along with e-kshamata App
[![IAastrika Sphere Platform](https://img.youtube.com/vi/DAOIrhNaz_8/0.jpg)](https://www.youtube.com/watch?v=DAOIrhNaz_8)

## Technical Overview

### Architecture
The Sphere Competency Management consistes of three main components

 1. The Delivery Channel - Sphere competency reference app to be used by learners
 2. The Core Platform - Platform based upon sunbird-cb; Used to manage content and LMS
 3. Entity Service : Service to implement the FRAC framework

### Installation

Please follow the links to access the installations of respective components.

 - Reference App
	 - [Link to Repository](https://github.com/Sphere/sphere-competency-reference-app)
	 - [Installation Instructions](https://github.com/Sphere/sphere-competency-reference-app/blob/main/README.md)
 - Core Platform
	 - [Knowledge Base](https://www.sunbird.org/product/building-blocks)
	 - [Link to Repository](https://github.com/Sphere/sunbird-devops)
	 - [Installation Instructions](https://ed.sunbird.org/use/getting-started)
	 - [Base Repository](https://github.com/Sphere)
 - Entity Service
	 - [Link to Repository](https://github.com/Sphere/entity-v1)
	 - [Installation Instructions](https://github.com/Sphere/entity-v1/blob/master/README.md)
	 
### Deployment

The Sphere Competency Management System has been tested on AWS Cloud infrastructure using Sunbird-CB/Sunbird version 4.10. Starting from version 5.1, however, Sunbird is cloud-agnostic and supports deployment across various cloud service providers.

## Collaboration
For questions or assistance please open an Issue in this repository

## Contribution
For any contribution, open a PR in the respective source code repository

## References
1. [FRAC](https://clop.cegis.org/what-is-frac)
2. [Sunbird](https://www.sunbird.org/)
3. [Sunbird CB](https://github.com/sunbird-cb)
4. [Sphere Competency Platfrom](https://sphere.aastrika.org/public/home)
5. [Aastrika Foundation](https://www.aastrika.org/)
6. [e-Kshamata](https://play.google.com/store/apps/details?id=org.aastrika.ekshamata&hl=en-US)
