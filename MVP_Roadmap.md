# Product Roadmap & MVP Scope

**Created by:** Mismar
**Last Updated:** June 17, 2026

## Description

This document defines the **Minimum Viable Product (MVP)** scope and the long-term **Product Roadmap** for **TileVision**.

It outlines the core functionality required to validate the product idea, features intentionally excluded from the MVP, and the planned evolution of the product through future releases. The roadmap considers project dependencies, limited development resources, and incremental value delivery.

---

# MVP Scope

## Features Included in the MVP

| Feature | Business Value |
|---------|----------------|
| Room photo upload | Starting point of the main user journey, enabling visualization in the customer's own room. |
| AI surface detection | Core AI capability that identifies walls and floors for material application. |
| Manual boundary correction | Allows users to fix AI recognition errors and improve visualization accuracy. |
| Product catalog | Enables browsing real products available in the retailer's inventory. |
| Catalog filtering | Helps users quickly find materials by type, manufacturer, price, or availability. |
| Product details | Displays material information such as size, color, manufacturer, price, and availability. |
| Material selection | Allows choosing different materials for walls and floors. |
| Material visualization | Demonstrates how selected materials look inside the customer's room. |
| Replace materials without re-uploading | Enables quick experimentation with different design options. |
| Compatible material recommendations | Suggests matching products to simplify design decisions. |
| Save design variations | Allows users to keep preferred designs for later comparison. |
| Compare saved designs | Helps users evaluate multiple design alternatives before making a decision. |
| Share design with store consultant | Connects the visualization process with the purchasing workflow. |

### MVP Goal

The MVP is designed to validate not only customer interest in AI visualization but also whether the product successfully guides users from uncertainty to a confident purchase decision.

---

## Features Excluded from the MVP

The following functionality is intentionally postponed:

- AI-generated complete room designs
- Budget-based design generation
- Automatic material quantity calculation
- Total renovation cost estimation
- Grout color visualization
- Automatic tile orientation optimization
- Tile layout optimization with waste reduction
- Lighting simulation
- Augmented Reality (AR) visualization
- Native mobile application
- Online ordering and payment

These capabilities improve convenience and commercial value but are not required to validate the core concept.

---

# Product Roadmap

The roadmap was created considering the following resource constraints:

- Team consists of **2 developers**
- Maximum of **2 parallel development tasks**
- Only **one design, analytics, testing, or marketing activity** at a time
- Every task begins only after its dependencies are completed

---

# Overall Development Plan

| Phase | Goal | Expected Outcome |
|--------|------|-----------------|
| **MVP** | Validate the core value proposition | Users can upload photos, create, save, compare, and share visualizations |
| **Phase 1** | Expand visualization capabilities | Design templates, budget recommendations, lighting simulation, grout customization |
| **Phase 2** | Add calculations, optimization, and mobile technologies | Material estimation, layout optimization, AR, mobile applications |

---

# MVP Phase

## Goal

Develop the first working version of TileVision covering the complete user journey—from uploading a room photo to comparing multiple design options.

| Sprint | Development Tasks | Additional Activities | Dependencies |
|---------|-------------------|----------------------|--------------|
| MVP 1 | Web application structure, photo upload | UX/UI design | Project start |
| MVP 2 | AI surface detection, product catalog | — | Photo upload |
| MVP 3 | Manual boundary editing, product details | — | AI recognition |
| MVP 4 | Material visualization, wall & floor selection | — | Surface detection |
| MVP 5 | Replace materials, AI recommendations | Compatibility analysis | Visualization completed |
| MVP 6 | Save design | Saved designs list | Visualization |
| MVP 7 | Compare designs, share with consultant | — | Saved designs |
| MVP 8 | Bug fixing, optimization, responsive UI | MVP testing & feedback | All previous features |

---

## MVP Deliverables

After completing the MVP, users will be able to:

- Upload room photos
- Review and edit detected surfaces
- Browse the material catalog
- View product information
- Apply tiles and flooring
- Receive compatible material recommendations
- Save multiple design options
- Compare designs
- Share selected designs with store consultants

---

# Phase 1 – Enhanced Design & Visualization

## Goal

Help customers receive intelligent design suggestions instead of manually combining materials.

| Sprint | Development Tasks | Additional Activities | Dependencies |
|---------|-------------------|----------------------|--------------|
| 1.1 | Design inspiration library | Template UX/UI | MVP visualization |
| 1.2 | Apply template to room | Material replacement | Design library |
| 1.3 | Budget input | Budget filtering | Product pricing |
| 1.4 | Automatic budget-based design | Estimated project cost | Budget engine |
| 1.5 | Lighting simulation | UX/UI for lighting modes | Visualization engine |
| 1.6 | Grout color selection | Visualization updates | Tile visualization |
| 1.7 | Optimization & bug fixing | Testing | Phase completion |

---

# Phase 2 – Calculations, Optimization & Mobile

## Goal

Transform TileVision from a visualization tool into a complete renovation planning platform.

| Sprint | Development Tasks | Additional Activities | Dependencies |
|---------|-------------------|----------------------|--------------|
| 2.1 | Room dimensions input | UX/UI | Existing project |
| 2.2 | Surface area calculation | Material estimation | Room dimensions |
| 2.3 | Cost estimation | Material reserve calculation | Product prices |
| 2.4 | Tile orientation optimization | Orientation visualization | Surface dimensions |
| 2.5 | Tile layout optimization | Waste calculation | Tile orientation |
| 2.6 | AR preparation | AR UX/UI | Stable visualization |
| 2.7 | iOS application | Android application | Stable web platform |
| 2.8 | Mobile synchronization | AR optimization | Mobile apps |
| 2.9 | Performance optimization | Marketing preparation | Phase completion |

---

# Roadmap Rationale

The roadmap follows a value-driven approach.

First, TileVision validates its core value proposition by enabling customers to upload room photos, visualize materials, save designs, and compare alternatives.

Once the MVP proves successful, additional functionality focuses on improving decision-making through ready-made design templates, budget recommendations, lighting simulation, and grout customization.

Advanced features—including material estimation, tile layout optimization, and AR visualization—are introduced later because they depend on stable visualization algorithms and accurate room measurements.

Native mobile applications are intentionally scheduled last to avoid duplicating development effort before the web platform reaches maturity.

---

# Resource Constraints

The roadmap is designed to maximize delivery efficiency while respecting team limitations.

- No more than **two simultaneous development tasks**
- One supporting activity (design, analytics, testing, or marketing) at any stage
- Feature dependencies are respected throughout the roadmap

Examples include:

- Material visualization begins only after surface detection.
- Design comparison requires completed save functionality.
- Budget recommendations depend on product catalog pricing.
- Material estimation requires room dimensions.
- Tile layout optimization depends on both surface measurements and tile dimensions.
- AR and mobile applications are developed only after the web platform becomes stable.

This phased approach minimizes development risk while continuously delivering customer value.
```
