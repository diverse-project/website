+++
# About/Biography widget.

date = "2016-07-20T00:00:00"
draft = false

widget = "about"

# Order that this section will appear in.
weight = 5

# List your academic interests.
[topics]
  topics = [
    "DevOps for distributed and heterogeneous system",
    "Advanced testing",
    "Modeling and Languages Engineering",
    "Variability Engineering"
  ]

+++




# Objectives

{{< diverse >}}’s research agenda is in the area of software engineering. In this broad domain we develop models, methodologies and theories to address the challenges raised by the emergence of several forms of diversity in the design, deployment and evolution of software intensive systems.
The emergence of software diversity is an essential phenomenon in all application domains that we investigate with our industrial partners. These application domains range from complex systems such as systems of systems (in collaboration with Thales and DGA) and Instrumentation and Control (with EDF) to pervasive combinations of Internet of Things and Internet of Services (with TellU and Software AG) and tactical information systems (with the firefighter department).
Even if today these systems are apparently radically different, we envision a strong convergence  of the scientific principles underpinning their construction and validation towards flexible and open yet dependable systems. In particular, we see that the required flexibility and openness raise challenges for the software layer of these systems that must deal with four dimension of diversity: the **diversity of languages** used by the stakeholders involved in the construction of these systems; the diversity of features required by the different customers; the diversity of runtime environments in which software has to run and adapt; the diversity of implementations that are necessary for resilience through redundancy.

In this context, the major software engineering challenge consists in handling diversity from variability in requirements and design to heterogeneous and dynamic execution environments. In particular this requires considering that the software system must adapt, in unpredictable ways, to changes in the requirements and environment. Conversely, explicitly handling of diversity is a great opportunity to allow software to spontaneously explore alternative design solutions. Concretely, we want to provide software engineers with the ability:

- to characterize an `envelope’ of possible variations
- to compose `envelopes’ (to discover new macro envelopes in an opportunistic manner)
- to dynamically synthesize software inside a given  envelop

The major scientific objective that we must achieve to provide such mechanisms for software engineering is synthesized below

> Automatically compose and synthesize software diversity from design to runtime to address unpredictable evolutions of software intensive systems.
Software product lines and associated variability modeling formalisms represent an essential aspect of software diversity, which we already explored in the past and that represent a major foundation of DiverSE’s research agenda. However, DiverSE  also exploits other foundations to handle new forms of diversity: type theory and models of computation for the composition of languages; distributed algorithms and pervasive computation to handle the diversity of execution platforms;  functional and qualitative randomized transformations to synthesize diversity for robust systems.


# Main axis

- **Software Language Engineering (SLE)**: Separation of concerns in the development of complex software-intensive systems leads to the use of various domain-specific modeling languages (DSMLs). SLE addresses the whole life cycle for designing, implementing and relating DSMLs to support heterogeneous modeling and analysis.
- **Variability**: The systematic modeling of variability in software systems has emerged as an effective approach to document and reason about software evolutions and heterogeneity. Variability modeling characterizes an “envelope” of possible software variations.
- **Dynamic Adaptive Systems (DAS)**: Flexible yet dependable systems have to cope with heterogeneous hardware execution platforms ranging from smart sensors to huge computation infrastructures and data centers. We need to devise formalisms to reason about the impact of an evolution and about the transition from one configuration to another.
- **Diversity**: Software diversity as the foundation for a novel software design principle and increased adaptive capacities in complex adaptive systems. Higher levels of diversity in the system provide a pool of software solutions that can eventually be used to adapt to unforeseen situations at design time.


{{< diverse >}} (formely Triskell) is a research team of {{< IRISA >}} (mixed research unit grouping {{< CNRS >}}, {{< UR1 >}}, {{< INRIA >}} {{< INSARennes >}} in Rennes / Britanny / France), defining itself as a world leader(*) of Model Driven Engineering (MDE) research.

The research domain of the Triskell project-team is the model driven development and validation of software product lines, ranging from the Internet of Things to the Internet of Services. Triskell is particularly interested in component based, dynamically adaptable systems with quality of service constraints, including reliability, performance, timeliness, etc. The long-term goal of the Triskell project-team is to investigate new ways of building and validating these systems by unifying Model Driven Engineering, Aspect Oriented Software Development, Product-Line Engineering, Component Based Software Development, and Generative Programming.

Model-Driven Engineering for Component-Based Software
- Formal manipulation of UML models with patterns, frameworks and components
- Design with contract-aware components and Aspect Oriented Modeling
- Models@runtime to control Dynamically Adaptable Systems
- Intra-component and inter-component V&V (testing)

[Introduction to Model Driven Engineering](http://www.irisa.fr/triskell/IntroMDE_fichiers/v3_document.htm)