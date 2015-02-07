---
published: true
permalink: /
layout: hero
filename: index.md
title: Common Profile Framework
---

IMPORTANT: THIS IS A DRAFT AND STILL UNDER CONSTRUCTION.

##1. Introduction

The ISE Common Profile Framework description (Common Profile) is a means to standardize the way a modular component profile or an information interoperability profile is documented.  The Common Profile is an important aid that provides a template for consistently documenting the contents of a profile for inter- and intra-organization information documentation and discovery.  A profile characterizes a base set of standards, for example, an exchange profile with options necessary to accomplish (a) the desired purpose of interoperability and (b) a common methodology for referencing standards across multiple component solutions.    The standards themselves are often configuration managed and listed in online available registries.  For example, the DoD and IC managed their standards jointly via the DoD-IC Joint Enterprise Standards Committee (JESC); and they register decisions such as mandated use in the DoD Information Technology Standards Registry (DISR).  Producers of a Common Profile aim to add value to the list of standards by providing further context on standards usage to the prospective Consumers.
   Additionally, the profile provides a packaging construct that links detailed reference information to an instance within the enterprise.  The profile is not intended to replace or duplicate detailed information describing a standard or technical component.  Profiles may be published and maintained in a Profile Repository within an organization or a similar domain-specific repository across organizations.     
Common Profiles may be written entirely by individual acquisition programs or partially by authoritative standards bodies that will use them to guide and lighten the load for those individual programs.  For example, the Geospatial Intelligence Working Group (GWG), a Technical Working group for DoD and the Intelligence Community (IC), could write the Reference and Technical Views to provide a given capability; then, an acquisition program would need to provide the details of how they physically implement their guidance in the Implementation Instance View.    
The Common Profile is further defined by three views that are used to identify the characteristics of the managed components within the enterprise: a Reference View, Technical Guidance View, and Implementation Instance View. These three Common Profile views are defined as follows:    

* **Reference View**:  Serves as the high-level abstract example or reference for the profiled enterprise component. It includes basic attributes, enterprise entities, and guidance information. The Reference View is implementation independent, vendor independent, and sometimes technology independent.  The Reference View should contain applicable mission needs statements, use cases and reference architecture.  
* **Technical Guidance View**:  A set of one or more base standards, and where applicable, the definition of chosen classes, subsets, options, and parameters of those base standards necessary for establishing the behaviors of a particular function or enterprise component. The Technical Guidance View is vendor independent and includes basic attributes, enterprise entities, implementation references, guidance, and compliance information.
* **Implementation Instance View**: Portrays a specific instance of an implementation and defines discrete configurations and parameters for the given instance. It includes basic attributes, enterprise entities, compliance information, and specific methods and techniques.  The Implementation Instance View may or may not be vendor independent. This is the most detailed and specific view of a profile.  
Figure 1 (below) shows a conceptual profile called “Cloud Services” which has three subordinate Technical Guidance Views:   Application Hosting, Compute, and Storage. The Application Hosting View has subordinate (nested) Technical Guidance Views for Operating System and Web Services. An Implementation Instance View for Encryption supports two different Technical Guidance Views (Storage and Operating System). The example in Figure 1 highlights the flexibility of the profile structure to adapt to particular needs.


----------------

##2. Objectives (adapted from ISO TR10000.1)
As stated in the International Organization of Standardization (ISO) TR10000.1, “Profiles are related to Base Standards, to Registration Mechanisms, and to Conformance Tests of the IT systems which implement them”.  The practical implications of these relationships which specify requirements shall be satisfied by profiles defined in the Common Profile are described in Table 1 (below).
Standards Alignment	Relationship to Common Profile 
Alignment to an Enterprise Component Business / Mission Needs through Use of Common Taxonomy to Establish Semantic Consistency	1.	Elements of functionality grouped together into a profile should correspond to identifiable, real world units of application or IT system design.
2.	The purpose of a profile is to specify the use of sets of specifications to provide clearly defined functionality. 
3.	A taxonomy is a classification scheme for referencing profiles or sets of profiles unambiguously.  From the taxonomy, identifiers for profiles are derived which indicate (in a codified form) the functional relationship of one profile to another.
Alignment to Base Standards	1.	A profile makes explicit the relationships within a set of base standards used together (relationships which can be implicit in the definitions of the base standards themselves), and may also specify particular details of each base standard being used.
2.	Profiles promote integration of base standards by defining how to use a combination of base standards for a given function and environment.
Alignment to Conformance Criteria	1.	Profiles should provide a clear identification of the specific user requirements which are satisfied by the profiles.  Occasionally, satisfaction of some of these requirements may identify functionality that is not covered by accepted base standards. This is defined as a "gap" in available standards.
2.	Serve as the basis for the establishment of commonly recognized conformance test suites and test methods.


----------------

##3. Profile Attributes


----------------


##4. Template

Below is an example which shows how a common approach would be developed to support a single template that can be used across Federal, State, Local, and Tribal jurisdictions in a common way.  It can be used to formulate your agency's reference section. The text in this template is borrowed from the Global Standards Council (GSC) of the Bureau of Justice Affairs U.S Department of Justice.
