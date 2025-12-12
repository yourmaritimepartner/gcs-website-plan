# GCS Website Reboot Plan - Project Notes

## Project Overview

This project contains the website reboot plan for **Gulf County Shipbuilding, Inc. (GCS)** - a shipyard revitalization initiative focused on:

- **Federal MRO (Maintenance, Repair, Overhaul)** - USCG Patrol Boats, Navy support vessels
- **Commercial New Build** - Jones Act compliant Truckable Barges

The website strategy supports dual revenue streams targeting federal contracting officers and commercial B2B buyers.

---

## What We Created

### 1. Comprehensive Website Reboot Plan Document

**Location:** `/Users/jd2025/pai/scratchpad/gcs-website-reboot-plan.md`

A 600+ line Markdown document containing:
- Executive summary
- Top-level progress checklist (trackable)
- 3-phase launch strategy (6 weeks total)
  - Phase 1 (Week 1-2): Foundation - Homepage, About, Contact, Capabilities
  - Phase 2 (Week 3-4): Credibility - Compliance, Facilities, Target Vessels
  - Phase 3 (Week 5-6): Authority - People/Careers, Case Studies, News
- Detailed page templates and content requirements
- Homepage wireframe
- Contact form specifications (two-path: Federal vs Commercial)
- Compliance language guidelines (critical for federal contracts)
- Asset checklists (photography, copy, graphics)
- Technical requirements
- Stakeholder review questions

### 2. Polished HTML Presentation

**Location:** `./index.html`

A professionally styled HTML version with:
- Navy/gold color scheme (patriotic, professional)
- Interactive checklist formatting
- Responsive design for mobile
- Table of contents navigation
- Visual hierarchy for easy scanning

### 3. GitHub Gist (Secret/Unlisted)

**URL:** https://gist.github.com/yourmaritimepartner/36c8c8ccee5ef89201ab7f9bbb576786

- Raw Markdown format
- Unlisted - not searchable, only accessible via direct link
- Good for sharing with colleagues who need to review/comment

---

## Current Resource Status

| Resource | Status | Notes |
|----------|--------|-------|
| Secret Gist | **Active** | Share this link for review |
| GitHub Pages | **Disabled** | Can re-enable when ready to go public |
| Repository | **Public** | Contains HTML source code |
| Scratchpad MD | **Local only** | Original Markdown source |

---

## Key Commands

### Re-enable GitHub Pages
```bash
gh api repos/yourmaritimepartner/gcs-website-plan/pages -X POST --input - <<< '{"source":{"branch":"main","path":"/"}}'
```

### Disable GitHub Pages
```bash
gh api repos/yourmaritimepartner/gcs-website-plan/pages -X DELETE
```

### Create new secret Gist (if needed)
```bash
gh gist create /Users/jd2025/pai/scratchpad/gcs-website-reboot-plan.md -d "GCS Website Reboot Plan"
```

### Create public Gist
```bash
gh gist create /Users/jd2025/pai/scratchpad/gcs-website-reboot-plan.md --public -d "GCS Website Reboot Plan"
```

---

## Source Document Context

The plan was derived from a comprehensive Google Doc containing:

1. **Market Analysis** - MARAD funding, Jones Act, USCG ISVS program
2. **MSRA Plan** - 3-phase federal contract pursuit (Master Ship Repair Agreement Tier 3)
3. **Workforce Plan** - Apprenticeship programs, Haney Tech & GCSC partnerships
4. **MARAD SSG Grant Strategy** - Small Shipyard Grant application roadmap
5. **Target Vessel Analysis** - Patrol Boats (MRO), Truckable Barges (New Build)
6. **Mission Statement & Pitch Deck** - Stakeholder presentation structure
7. **DCAA & CMMC Compliance** - Financial audit and cybersecurity requirements
8. **Organizational Structure** - Key roles (CEO, CFO, DCC, etc.)
9. **Legal Documents** - MSRA, Job Orders, Subcontractor agreements
10. **90-Day Startup Plan** - Go/No-Go checklist

**Google Doc (requires access):** https://docs.google.com/document/d/1It0665L0cJ49ziRoMRinh7rt4AN-RwIGLQwN2qToddI/edit

---

## GCS Mission Statement

> "To serve as the Gulf Coast's precision engineering hub, dedicated to the construction and sustainment of American vessels essential for national security and the growth of domestic maritime trade."

---

## Target Audiences

### 1. Federal Contracting Officers
- USCG procurement
- Navy support vessel contracts
- Looking for: MSRA status, DCAA compliance, CMMC certification, past performance

### 2. Commercial B2B Buyers
- Barge operators
- Infrastructure/construction companies
- Looking for: Jones Act compliance, vessel specs, pricing, delivery logistics

---

## Critical Compliance Language Notes

**Use precise language for pending certifications:**

| Certification | Current Status | Correct Language |
|---------------|----------------|------------------|
| SAM.gov | Active | "SAM.gov Registered - UEI: [NUMBER]" |
| NAICS Codes | Active | "NAICS 336611 - Ship Building and Repairing" |
| MSRA Tier 3 | Pursuing | "Actively Pursuing MSRA Tier 3 Certification" |
| CMMC Level 2 | In Progress | "CMMC Level 2 Compliance Program Underway" |
| DCAA | Implemented | "DCAA-Compliant Accounting System" |

**Never claim certifications not yet achieved.**

---

## Website Page Priority

### Phase 1 - Critical (Launch with these)
1. Homepage
2. About/Leadership
3. Contact (two-path forms)
4. Capabilities

### Phase 2 - High (Add weeks 3-4)
5. Compliance & Certifications
6. Facilities & Assets
7. Target Vessels

### Phase 3 - Medium (Add weeks 5-6)
8. Our People/Careers
9. Case Studies
10. News & Resources

---

## Asset Dependencies (Blocking Items)

Before launch, need:
- [ ] CEO headshot (minimum)
- [ ] Facility exterior photo
- [ ] Pier/waterfront photo
- [ ] GCS logo files (PNG, SVG)
- [ ] Domain/hosting confirmed (gcship.com)

---

## Session History

**Date:** December 11, 2025

**Actions taken:**
1. Analyzed comprehensive GCS revitalization Google Doc
2. Created 3-phase website launch plan
3. Wrote detailed Markdown document with checklists
4. Created GitHub repo: `yourmaritimepartner/gcs-website-plan`
5. Built polished HTML presentation (`index.html`)
6. Enabled GitHub Pages (then disabled per user request)
7. Created public Gist (then converted to secret per user request)
8. Installed GitHub CLI (`gh`) via Homebrew

**Final deliverable:** Secret Gist for colleague review, with HTML version ready to publish when approved.
