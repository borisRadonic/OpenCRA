# OpenCRA

> **Practical Cyber Resilience Act Documentation for Industrial Embedded Systems**

OpenCRA is an open-source project providing practical documentation templates for manufacturers of industrial embedded products that must comply with the European **Cyber Resilience Act (CRA)**.

The project focuses on products with a **limited cyber attack surface**, including industrial controllers, servo drives, motor controllers, sensors and other embedded devices that:

* are **not connected to the Internet**;
* provide **no wireless communication**;
* operate inside controlled industrial environments;
* communicate only through local industrial interfaces (e.g. CAN, CAN-FD, RS-485, RS-232);
* require physical access for commissioning, maintenance and firmware updates.

The primary objective of this project is to demonstrate that cybersecurity documentation can remain **proportionate to the actual cybersecurity risk** of the product.

---

# Why OpenCRA?

Many publicly available examples of CRA documentation are either:

* focused on Internet-connected consumer or IoT devices;
* overly theoretical;
* excessively complex;
* difficult for small and medium-sized manufacturers to apply.

Industrial embedded systems often have a fundamentally different cybersecurity profile.

For many such products, cybersecurity is achieved primarily through:

* intentionally limited functionality;
* controlled operating environments;
* restricted physical access;
* minimized communication interfaces;
* deterministic embedded software.

OpenCRA attempts to document this engineering reality.

---

# Project Philosophy

OpenCRA follows a simple engineering principle:

> **Cybersecurity documentation should reflect the actual cyber attack surface of the product—not a generic checklist.**

The goal is **not** to produce the largest possible collection of documents.

The goal is to produce documentation that is:

* technically meaningful;
* understandable;
* proportionate;
* practical;
* easy to maintain.

---

# Repository Contents

| Document | Description                                |
| -------- | ------------------------------------------ |
| CRA-001  | Cybersecurity Risk Assessment              |
| CRA-002  | EU Declaration of Conformity               |
| CRA-003  | Vulnerability Disclosure Policy            |
| CRA-004  | Website Security Information               |
| CRA-005  | User Cybersecurity Information             |
| CRA-006  | Software Bill of Materials (SBOM) Template |
| CRA-007  | Technical Documentation Checklist          |

---

# Intended Scope

These templates are primarily intended for products such as:

* Servo Controllers
* Motor Controllers
* PLC I/O Modules
* Industrial Sensors
* Industrial Actuators
* Embedded Control Units
* Robotics Controllers
* Industrial Measurement Devices

The templates may also be useful for other embedded products with similar cybersecurity characteristics.

---

# What OpenCRA Is

OpenCRA is:

* an engineering example;
* an open-source documentation template;
* a practical starting point for CRA documentation;
* a community project intended to encourage discussion and improvement.

---

# What OpenCRA Is Not

OpenCRA is **not**:

* legal advice;
* regulatory guidance;
* certification documentation;
* an official interpretation of the Cyber Resilience Act;
* a substitute for a product-specific cybersecurity assessment.

Every manufacturer remains responsible for determining the regulatory obligations applicable to their own products.

---

# Disclaimer

The documentation contained in this repository has been prepared in good faith with the intention of helping engineers, developers and manufacturers better understand and discuss practical documentation related to the European Cyber Resilience Act (CRA).

The documents are provided solely as engineering examples and reusable templates.

This repository has been developed with the assistance of **Artificial Intelligence (AI)** and has subsequently been reviewed by the author. Although every reasonable effort has been made to improve the quality and technical accuracy of the documents, they may still contain errors, omissions or inaccurate interpretations.

Users are strongly encouraged to review, verify and adapt every document before using it within their own development process or technical documentation.

The author makes **no representations or warranties**, express or implied, regarding the completeness, correctness or suitability of the information contained in this repository.

To the maximum extent permitted by applicable law, the author accepts **no liability whatsoever** for any direct, indirect, incidental or consequential loss, damage or regulatory non-compliance arising from the use of these documents.

Use of this repository is entirely at your own risk.

---

# Contributions

Constructive criticism, corrections and improvements are always welcome.

If you believe:

* a document can be improved;
* a CRA requirement has been misunderstood;
* an important document is missing;
* a section is unnecessarily complicated;
* a simpler engineering solution exists,

please open an Issue or submit a Pull Request.

The goal of this project is continuous improvement through contributions from the embedded engineering community.

---

# License

Unless otherwise stated, all documentation contained in this repository is released under the **MIT License**.

Copyright © Boris Radonic
