<div align="center">

# Harshil Dalal

### Digitalization Engineer · Industry 4.0 & IIoT · IT/OT Integration
**M.Eng. Industrial Informatics** (Hochschule Emden/Leer, final grade 1.9 · master's thesis 1.3)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshildalal)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dalalharshil2@gmail.com)
![Location](https://img.shields.io/badge/Emden,_Germany-available_at_short_notice-20B2AA?style=for-the-badge)

</div>

---

## About me

I connect the shop floor with software. My master's thesis turned **Asset Administration Shell (AAS)** models into operator interfaces that build themselves for real machines in a modular digital factory. My projects cover the whole IT/OT path: industrial protocols (OPC UA, Modbus TCP, MQTT), backend and database design, web HMIs, containerised deployment and the security testing of industrial software.

I am looking for graduate roles in **Industry 4.0, IIoT, IT/OT integration, manufacturing IT / MES and industrial software development** in Germany, and I am open to relocating anywhere in the country.

---

## Selected work

### AAS-Driven Dynamic Operator Interface Framework for a Modular Digital Factory
*Master's thesis · Institute I2AR, Hochschule Emden/Leer · 03/2026 – 10/2026 · **graded 1.3***

- A framework that generates operator HMIs dynamically from AAS submodels, so new machines need no machine-specific UI development.
- Commissioned with a laser engraver, delta robot, injection moulding machine and transport robot via **Eclipse BaSyx** (AAS Part 2 REST API) and **OPC UA**.
- **98.8 %** of all data elements (1,000 of 1,012) are visualised automatically.
- Docker deployment on a Debian lab server with role-based access control; architecture mapped to **RAMI 4.0**; latency measured on three data paths; validated in two independent stakeholder reviews.
- `React` `TypeScript` `Node.js / Express` `PostgreSQL / Prisma` `Docker` `Eclipse BaSyx` `OPC UA`
- Code: being prepared for publication.

### Stateful Fuzzing of OPC UA Implementations
*Master Project II · Hochschule Emden/Leer · 01/2026 – 05/2026*

- Session-aware fuzzing harnesses for the OPC UA stacks **open62541** (C) and **asyncua** (Python), built on an 8-state model of the OPC UA client session.
- Code coverage **+36 %** (8,178 → 11,157 edges); found **21 undefined-behaviour defects, a heap double-free and a race condition**.
- `C` `Python` `libFuzzer` `AFL++` `Atheris` `ASAN / UBSan`
- Code: being prepared for publication.

### Digital Execution of the Final Inspection Process – Concept and Prototype
*Master Project I · industry cooperation with ORGADATA AG (Forterro), Leer · 09/2024 – 05/2025*

- Analysed the paper-based final inspection within the factory production control (WPK) and designed the digital target process.
- Built an offline-capable **Angular** prototype that produces time-stamped, audit-compliant PDF inspection records with full traceability.
- Agile sprints with weekly stakeholder reviews; completion confirmed in writing by the company.
- `Angular` `TypeScript` `PDF.js` `pdf-lib`

### Real-Time Control of a Modular Manufacturing Plant
*Lab course Industrial Data Transport Technologies · SS 2024*

- Control and data acquisition of an eleven-module **Festo Didactic** production line (goods entrance, processing, high-bay storage, sorting) via **Modbus TCP** in Python, at register and bit level.

### IIoT Sensor Network
*Project · 2025*

- Sensor data over **CoAP / CBOR** with retry logic, visualised in a Flask/Dash dashboard.

---

## Tech stack

**Industry 4.0 & IIoT**
![AAS](https://img.shields.io/badge/Asset_Administration_Shell-2C2255?style=flat-square)
![Eclipse BaSyx](https://img.shields.io/badge/Eclipse_BaSyx-2C2255?style=flat-square&logo=eclipse&logoColor=white)
![OPC UA](https://img.shields.io/badge/OPC_UA-0057A8?style=flat-square)
![Modbus TCP](https://img.shields.io/badge/Modbus_TCP-555555?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![CoAP](https://img.shields.io/badge/CoAP_/_CBOR-4CAF50?style=flat-square)
![RAMI 4.0](https://img.shields.io/badge/RAMI_4.0_·_IEC_62264-777777?style=flat-square)

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C_/_C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Web & backend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_/_Express-339933?style=flat-square&logo=node.js&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square)
![Flask](https://img.shields.io/badge/Flask_/_Dash-000000?style=flat-square&logo=flask&logoColor=white)

**Data & DevOps**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Security testing**
![libFuzzer](https://img.shields.io/badge/libFuzzer_·_AFL++-B22222?style=flat-square)
![Sanitizers](https://img.shields.io/badge/ASAN_/_UBSan-B22222?style=flat-square)

**Methods:** Agile/Scrum · requirements engineering · stakeholder reviews · technical documentation

---

## Education

| Degree | Institution | Period | Result |
|---|---|---|---|
| M.Eng. Industrial Informatics | Hochschule Emden/Leer, Germany | 03/2023 – 10/2026 | Final grade **1.9** · thesis **1.3** |
| B.Sc. Information Technology | CHARUSAT, India | 06/2019 – 05/2022 | CGPA **9.5/10** |

**Work experience:** Teaching Assistant, Web & Frontend Development, Navrachana University, India (06/2022 – 12/2022, full-time). I ran lab sessions for 150+ students and supervised 15+ projects.

---

## Certifications

- **Intel®** Certified Edge AI Developer
- **Anthropic** AI Engineering track: Claude Code, Model Context Protocol, agentic workflows, Claude with Amazon Bedrock and Google Vertex AI

---

## Languages

English: fluent (C1) · German: basic (A2), currently improving · Hindi: fluent · Gujarati: native

---

<div align="center">

*Available at short notice · open to relocation anywhere in Germany*

</div>
