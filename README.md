# Industrial Contamination Tracking System (Showcase)
> **Note:** This repository serves as a visual showcase and technical overview.
## Project Overview
This is a specialised software solution designed for a slaughterhouse to track contamination data. The system replaced manual paperwork, streamlining the inspection process on the production line.
### Technical Evolution & Migration
This project represents a significant architectural journey driven by the need for scalability and real-time performance:
1.  **PHP Prototype:** Initial proof-of-concept.
2.  **Analog.js:** First iteration of a modern SPA.
3.  **Next.js (Current Production):** Migrated to Next.js to ensure maximum production stability and ecosystem maturity.
    * **Key Upgrade:** With this migration, the legacy **polling mechanism** was replaced with **WebSockets**, enabling true real-time data synchronisation across all devices on the factory floor.
## Tech Stack
- **Framework:** Next.js / React
- **Language:** TypeScript / SQL
- **Real-time:** WebSockets
- **Styling:** Tailwind CSS, SCSS
- **Database:** MySQL
## Key Functionalities

### 1. Real-time Operations
- **Batch Management:** Seamless creation and switching between production batches.
- **Live Synchronization:** Using WebSockets, changes made by one inspector are immediately reflected on all other devices. This allows multiple people to inspect the same batch simultaneously without data conflicts.
- **Granular Tracking:** Ability to increment/decrement specific contaminant types in determined carcass areas.

### 2. Analytics & Reporting
- **Historic Data:** View detailed logs of all past inspections.
- **Daily Reports:** Comprehensive reports for previous days.
- **Flexible Views:** Ability to toggle between a summary of a single batch or aggregated daily reports.

## Gallery
Below are screenshots of the production environment UI:

| Dashboard without selected batch | Batch selection |
|:---:|:---:|
| ![screenshot](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/1.png) | ![screenshot](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/2.png) |

| Clicking on a carcas | Decrement mode & changing click ammount |
|:---:|:---:|
| ![screenshot](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/3.png) | ![Inspection](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/4.png) |

| History list | Report page |
|:---:|:---:|
| ![screenshot](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/5.png) | ![screenshot](https://github.com/Sefanovskis-Artjoms/carcas-counters-public/blob/main/imgs/6.png) |
