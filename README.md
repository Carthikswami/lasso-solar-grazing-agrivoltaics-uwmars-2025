# Solar Grazing Agrivoltaics Design – LASSO Competition, UW–MARS (2025)

This repository documents a dual-use agrivoltaic system developed for the LASSO Agrivoltaics Competition at the University of Wisconsin’s Marshfield Agricultural Research Station (UW–MARS). The design enables ground-mounted photovoltaic deployment alongside rotational livestock grazing, supporting both power generation and forage production on the same land.

Unlike standard solar grazing projects that focus exclusively on sheep, this work evaluates a system that can serve both **sheep** and **dairy heifers**, which introduces additional welfare, shading, equipment access, and structural design constraints.

---

## System Summary

| Attribute | Specification |
|-----------|---------------|
| PV Module | Longi LR5-72HBD-540M (540 W) |
| Orientation | Fixed tilt, 30° | 
| Azimuth | 180° (south-facing) |
| Array Count | 464 modules |
| Estimated Annual Output | 300.5 MWh |
| Row Spacing | 18 ft |
| Minimum Panel Clearance | 10 ft at lowest point |

*Technical specifications sourced from competition narrative submission* 

---

## Livestock Approach

### Sheep (Conventional Solar Grazing)
Sheep grazing is common in solar projects due to low clearance requirements and minimal structural stress. They reduce mowing needs and tolerate fenced movement patterns across narrow PV corridors.

### Dairy Heifers (Site-Specific UW–MARS Case)
This design also accommodates **dairy heifers**, including pregnant heifers in the 1000–1400 lb class, which require:
- Increased shade footprint under high heat conditions  
- Wider movement corridors  
- Higher-clearance structural design  
- Attention to shelter placement and egress routes  

These considerations require a **greater minimum PV height and access clearances** than sheep-only systems, which informs the 10-foot minimum clearance decision. 

---

## Grazing and Forage Recovery Strategy

The rotational grazing plan is based on forage regrowth rather than fixed-duration cycles. The system avoids overgrazing by moving animals based on **grass recovery rates**, with documented shade and forage interactions. 

The design supports:
- Seasonal variation in pasture growth
- Shade-linked microclimate effects
- Reduced heat stress for livestock under panel structures

---

## Repository Contents

```text
lasso-solar-grazing-agrivoltaics-uwmars-2025/
├── design/              # PV layout, height, fencing concepts, movement corridors
├── field-interactions/  # Notes on shade effects, forage recovery, microclimate
├── figures/             # Exported diagrams from slides and technical binder
├── reports/             # Competition narrative, technical binder, and slides
└── documentation/       # Assumptions, rationale tables, supporting site info
