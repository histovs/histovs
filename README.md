<div align="center">

# TerraFleet

### Everything about your equipment. In one place.

A modern fleet management platform for construction and heavy equipment.

![TerraFleet Banner](.github/assets/banner.png)

![Platform](https://img.shields.io/badge/macOS-15%2B-black?style=for-the-badge&logo=apple)
![Swift](https://img.shields.io/badge/Swift-6-orange?style=for-the-badge&logo=swift)
![SwiftUI](https://img.shields.io/badge/SwiftUI-Native-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active%20Development-2E8B57?style=for-the-badge)

</div>

---

## Overview

TerraFleet is a modern fleet management platform designed for construction and heavy equipment.

It combines equipment records, repair history, warehouse inventory, documents, maps, analytics and intelligent workflows in one application.

TerraFleet is being developed with an offline-first approach, allowing essential fleet information to remain available even without an internet connection.

---

## Core Features

| Module | Description |
|---|---|
| Equipment | Fleet inventory, identification, status and machine history |
| Repairs | Failures, maintenance records, costs and downtime |
| Warehouse | Spare parts, materials and stock movement |
| Documents | Manuals, inspections, reports and technical files |
| Maps | Equipment locations, work sites and routes |
| OCR Import | Create equipment and repair records from photographs |
| Analytics | Fleet condition, costs, downtime and performance |
| AI Assistant | Intelligent analysis and operational recommendations |

---

## Design Principles

TerraFleet is built around a small set of product principles:

- Clean and focused interface
- Offline-first operation
- Fast navigation
- Privacy-focused local storage
- Native Apple platform experience
- Modern and maintainable Swift architecture
- Minimal actions for common operational tasks

---

## Screenshots

Real application screenshots will be added as development progresses.

| Dashboard | Equipment | Repairs |
|---|---|---|
| Coming soon | Coming soon | Coming soon |

---

## Architecture

```text
TerraFleet
│
├── Dashboard
│
├── Equipment
│   ├── Equipment records
│   ├── Operators
│   ├── Photos
│   └── Change history
│
├── Repairs
│   ├── Repair journal
│   ├── Status tracking
│   ├── Costs
│   └── Downtime
│
├── Warehouse
│   ├── Spare parts
│   └── Inventory movement
│
├── Documents
│
├── Maps
│
├── OCR Import
│
├── Analytics
│
└── AI Assistant
```

---

## Development Roadmap

### Completed

- [x] SwiftUI application structure
- [x] Sidebar navigation
- [x] Equipment model
- [x] Equipment local storage
- [x] Equipment detail view
- [x] Photo storage foundation
- [x] OCR foundation
- [x] Repair model
- [x] Repair journal foundation
- [x] Repair local storage

### In Progress

- [ ] Complete repair store integration
- [ ] Equipment and repair synchronization
- [ ] Dashboard repair statistics
- [ ] Equipment photo editing
- [ ] Repair OCR import
- [ ] Warehouse module
- [ ] Documents module
- [ ] Offline maps

### Planned

- [ ] Advanced analytics
- [ ] AI-assisted diagnostics
- [ ] Maintenance scheduling
- [ ] Cloud synchronization
- [ ] Mobile companion application
- [ ] Telemetry integration
- [ ] Multi-user access

---

## Technology

TerraFleet currently uses:

- Swift
- SwiftUI
- Observation
- Vision
- Codable
- JSON local storage
- App Support file storage
- Native macOS frameworks

Planned technologies include:

- MapKit or an offline mapping engine
- Swift Charts
- Cloud synchronization
- Mobile platform support

---

## Product Philosophy

> Every click should matter.

TerraFleet is designed around real operational workflows rather than complex database forms.

The goal is to provide fleet managers, mechanics and equipment operators with the information they need using the fewest practical actions.

---

## Project Status

TerraFleet is currently under active development.

The application structure, equipment database, OCR foundation and repair journal are already being implemented.

The public repository will gradually receive updated screenshots, documentation and release information.

---

## Author

<div align="center">

Designed and developed by

**Vladislav Mikheenko**

</div>

---

## License

A project license will be selected before the first public release.
