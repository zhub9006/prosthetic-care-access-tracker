# Search Methodology Documentation

This document describes the data collection methods, search strategies, and limitations.

## Clinical Trials Data

- **Source:** ClinicalTrials.gov API
- **Search terms:** "prosthetic" (broad, 2,162 studies) and "prosthetic limb" (focused, 509 studies)
- **Analyses:** countByStatus, countByCountry, countByPhase

## Provider Gap Analysis

- **Source:** OpenStreetMap (OSM)
- **Regions:** Rural West Virginia (37.78°N, 81.19°W), Eastern Kentucky (37.48°N, 82.52°W), Mississippi Delta (33.41°N, 91.06°W)
- **Radius:** 50 km

## Region Selection Basis

Based on CDC Social Vulnerability Index and Amputee Coalition prevalence data for:
- High amputation rates
- High diabetes prevalence
- Low healthcare access
- Rural/underserved populations

## Limitations

- OSM healthcare data may not capture all private-practice prosthetists/orthotists
- No validation against state licensure databases
- 50 km radius may be too conservative for rural areas
- Seasonal factors not accounted for

## Recommended Updates

- State licensure database queries
- Amputee Coalition cross-referencing
- Medicaid reimbursement rate analysis
- CDC county-level amputation data
- FQHC location integration
- Drive-time routing analysis
