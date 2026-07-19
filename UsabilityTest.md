# Usability Testing Report

**Created by:** Mismar
**Date:** June 15, 2026

## Description

This document presents a usability evaluation of **TilesView AI**, one of the primary competitors of the TileVision project.

The goal of the test was to evaluate the complete user journey of creating a tile visualization—from uploading a room photo to obtaining the final design—and identify usability issues, UX pain points, and opportunities for improvement that can be considered during the development of TileVision.

The evaluation was performed manually by a Business Analyst using a desktop browser.

---

## Competitor

**TilesView AI**

---

# Test Information

**Scenario:** Visualizing tiles in a real room (from photo upload to completed design)

**Test Date:** July 7, 2026

**Tester:** Daryna Kyrylova (Business Analyst)

**Device:** Desktop

**Operating System:** macOS Tahoe 26.5.2

**Browser:** Google Chrome (latest version)

---

# Overall Metrics

| Metric | Result | Notes |
|---------|--------|------|
| Total completion time | **6 min 20 sec** | From opening the service to obtaining the final visualization |
| Overall satisfaction | **3/5** | Good concept, but the process requires too much manual work |
| Number of errors | **3** | 1 critical, 2 medium |
| Approximate number of clicks | **36** | Too many clicks required during boundary correction |
| Task completion | **Completed** | Successfully finished after manual surface corrections |

---

# Step-by-Step Evaluation

| Step | Time | Issues Identified | Severity | Recommendation |
|------|------|------------------|----------|----------------|
| Select demo room / Upload photo | 40 sec | No guidance regarding photo quality, lighting, or camera angle | Low | Add examples of good photos and short instructions |
| AI surface detection | 1 min 20 sec | AI incorrectly detected the floor and part of a wall. Some surfaces were completely missed | Critical | Improve segmentation accuracy and validate AI confidence before displaying results |
| Manual boundary editing | 2 min | Manual correction was required. Small control points were difficult to move | High | Add automatic edge snapping and zoom functionality during editing |
| Tile selection | 50 sec | Product catalog is easy to use but offers limited filtering options | Medium | Add filters by style, budget, manufacturer, and tile size |
| Applying tiles | 50 sec | Texture mapping looked unrealistic on several surfaces. Perspective and scale were inconsistent | High | Improve texture rendering and surface geometry recognition |
| Reviewing results | 40 sec | No convenient way to compare multiple designs side by side | Medium | Implement a Compare mode (before/after or multiple designs) |

---

# Identified Issues

## Critical

- AI incorrectly detected the floor boundaries.
- The resulting visualization looked unrealistic because of inaccurate segmentation.

## Medium

- Several surfaces were not detected.
- Texture placement remained inaccurate even after manual corrections.

---

# Conclusions

## UX Strengths

- Easy onboarding with no learning curve.
- Modern and intuitive interface.
- Fast visualization after AI processing is completed.

## Main UX Problems

The largest usability issues occur during the AI segmentation stage. Inaccurate surface detection forces users to spend significant time manually correcting boundaries, negatively affecting the overall user experience.

## Potential Risks

Users may lose trust in the product if:

- the visualization differs significantly from the real room;
- extensive manual corrections are required before obtaining acceptable results.

## Recommendations

Development efforts should primarily focus on:

- improving AI surface recognition accuracy;
- enhancing texture rendering quality;
- automating boundary correction;
- enabling quick comparison between multiple design alternatives.

---

# Additional UX Metrics

| Metric | Result |
|---------|--------|
| Time to First Interaction | **7 seconds** |
| Error Recovery Time | **≈ 2 minutes** |
| Cognitive Load | **4/5** |
| Estimated System Usability Scale (SUS) | **68/100** |
