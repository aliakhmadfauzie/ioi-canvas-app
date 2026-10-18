# IOI Power Apps Canvas Application (.pa.yaml)

[![Power Apps](https://img.shields.io/badge/Power%20Apps-Canvas%20Application-742774?style=for-the-badge&logo=powerapps&logoColor=white)](https://powerapps.microsoft.com)
[![YAML Source](https://img.shields.io/badge/Source%20Code-.pa.yaml%20Screens-38B2AC?style=for-the-badge)](https://learn.microsoft.com/power-platform/alm/source-code-yaml)
[![Dataverse](https://img.shields.io/badge/Data-Microsoft%20Dataverse-0078D4?style=for-the-badge)](https://powerplatform.microsoft.com)
[![SharePoint](https://img.shields.io/badge/Lists-SharePoint%20Online-038387?style=for-the-badge&logo=microsoftsharepoint&logoColor=white)](https://microsoft.com)

**IOI Canvas App** contains the modular, source-code represented screens (`.pa.yaml`), reusable canvas components, design tokens, and SharePoint/Dataverse schema integration for the IOI Acidchem modernized Power Platform applications.

---

## 🌟 Key Features

- **Source-Controlled Canvas Screens**: Fully authored in modern `.pa.yaml` specification for Git version control and team PR reviews.
- **Enterprise Design System**: Standardized corporate color tokens, typography scales, header layouts, and navigation sidebars.
- **Offline Data Sync**: Built-in `SaveData()` and `LoadData()` local collection caching for reliable factory floor operation.
- **Traceability Matrix**: Every screen links directly to its legacy Lotus Domino form counterpart.

---

## 📁 Architecture Directory

- `design/00-project-control/`: Decision logs, build order, migration status, and missing info registers.
- `design/01-source-reference/`: Domino source index, traceability matrices, and TSX component index.
- `design/02-sharepoint-schema/`: SharePoint List schemas, column definitions, and view configurations.

---

## 📄 License
Enterprise solution developed by **Ali Akhmad Fauzie** ([@aliakhmadfauzie](https://github.com/aliakhmadfauzie)).
