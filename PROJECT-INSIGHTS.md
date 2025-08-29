# PROJECT-INSIGHTS.md - Savana Environmental Phase 1

## Project Overview

**Project:** Phase 1 Safety Documentation Automation  
**Client:** Savana Environmental (asbestos removal contractor)  
**Location:** Perth, Western Australia  
**Duration:** 8 weeks  
**Budget:** $25,000 - $35,000  
**Status:** Proposal refined and ready for client approval

## Stakeholder Mapping

### Key Personnel & Expertise

| Name | Role | Primary Responsibility | Expertise/Knowledge |
|------|------|----------------------|---------------------|
| **Chris Milos** | Safety HSEQ Manager | Decision maker, compliance validation | ISO standards, WorkSafe requirements, safety protocols |
| **Jess** | Project Manager | Primary user, creates all documentation | Institutional knowledge, template selection, scheduling priorities |
| **Leon** | Operations Manager | Operations oversight, ServiceM8 owner | API access, operational workflow, resource allocation |
| **Cliff** | Field Expert | Quotes jobs, site risk assessment | Field hazard identification, site conditions, equipment requirements |

### Client Types Served
- Property management companies
- Insurance companies  
- Principal builders (subcontracting demolition)
- Local government/councils
- Individual homeowners
- Federal facilities (Defence bases - special permit requirements)

## SRT Transcript Analysis Summary

### Source Materials Analysed
1. **`1 Job Scheduling and ARCP Documentation.srt`** - Complete workflow from quote to ARCP creation
2. **`2 SWMS Documentation.srt`** - SWMS template selection, hazard identification, and emergency planning

### Key Process Workflows Discovered

#### Job Scheduling & ARCP Process
```
Quote Creation → Acceptance → Manual Scheduling → Document Creation (2-3 weeks prior) → Review → Upload
```

**Critical Insights:**
- **Document Creation Trigger**: Jobs within 2-3 weeks of scheduled start (not at quote acceptance)
- **Template Selection**: Entirely dependent on Jess's memory ("we did this exact job 3 days ago")
- **Supervisor Assignment**: Manual best guess at document creation time, not predetermined
- **Emergency Plan Creation**: Google Maps screenshots + manual markup + document insertion
- **Time Reality**: "Can do it day before" but risky for WorkSafe 5-day rule

#### SWMS Documentation Process
```
Job Type Identification → Template Library Search → Multi-Factor Selection → Hazard Assessment → Equipment Lists → Review Workflow
```

**Critical Insights:**
- **Template Library**: Organised in OneDrive by job type (e.g., "Vinyl Tiles and Adhesive" folder)
- **Selection Complexity**: Job type + equipment required + site conditions + access requirements
- **Hazard Identification**: Requires Cliff's field expertise - "AI can't do quick hazard ID"
- **Equipment Lists**: Current templates insufficient ("only five selections, needs way more equipment")
- **Review Workflow**: Hygienist (mandatory) → Client review (variable) → Revisions with draft increments

## Critical Discoveries & Corrections

### Architecture Corrections
| Initial Assumption | Reality Discovered | Impact |
|-------------------|-------------------|---------|
| SharePoint integration | OneDrive-only architecture | Changed all storage references |
| Quote-triggered documentation | Scheduling-triggered (2-3 weeks prior) | Added job lifecycle workflow |
| Simple job-type templates | Multi-factor template selection | Enhanced selection logic |
| AI hazard identification | Manual field expertise required | Added field capability dependency |

### Process Complexities Uncovered

#### Training Requirements Matrix
- **Core Requirements**: White card (99% of jobs), asbestos removal training
- **Equipment-Specific**: EWP, forklift, working at heights (job-blocking if missing)
- **Site-Specific**: Client induction requirements (tracked separately - hundreds)
- **Critical Quote**: "Can't do job tomorrow without required ticket"
- **Multi-System Challenge**: ConnectTeam + separate induction spreadsheet

#### Client Review Variability
- **Hygienist Review**: Always mandatory for compliance
- **Client Review**: Highly variable
  - Some clients: Thorough review with multiple revisions
  - Some clients: Auto-approve without reading
  - Some clients: Complete ignore - "might never even f****** look at it"

#### Site-Specific Permit Requirements
- **Royal Perth Hospital**: Hot works permits required for grinding
- **UWA**: Working at heights permits required
- **Defence Bases**: Asbestos removal permits required
- **Residential**: Generally no permits required
- **Commercial**: Assume permit requirements until proven otherwise

### Equipment & Inventory Challenges

#### Current Limitations
- **No Real-Time Inventory**: Equipment availability based on assumptions, not live data
- **Template Inadequacy**: "Only five selections, but really doesn't fit the work... way more equipment than that"
- **Risk Factor**: Equipment unavailability can affect job planning and safety compliance

#### Optimization Opportunities
- Equipment list expansion and categorisation
- Job-type to equipment mapping
- Template refinement for better job matching

## Technical Architecture Insights

### Current System Integration Points
- **ServiceM8**: Basic job details, quotes, client info (LIMITED API functionality)
- **ConnectTeam**: Training records, qualifications, geo-tagging (WORKING WELL)
- **MYOB**: Master data source for line items and payroll
- **OneDrive**: SWMS template library, job folders, document storage
- **Excel Scheduling**: Job tracking, worker allocation, document status tracking

### Discovered Data Flow
```
ServiceM8 (Quote) → Manual Excel Entry → Scheduling System → Document Trigger → 
OneDrive Templates → Manual Creation → Hygienist Review → Client Review → 
OneDrive Storage → Physical Printing
```

### Multi-System Training Challenge
```
ConnectTeam (Formal Training) + Separate Spreadsheet (Client Inductions) = 
Complex Validation Required Before Job Assignment
```

## Friable vs Bonded Asbestos Distinction

### Current Problem
- Same SWMS templates used for both friable and bonded asbestos
- Different safety protocols required but not systematically differentiated
- Template selection doesn't account for material type distinction

### Required Solution
- Separate template workflows for friable vs bonded materials
- Different SWMS selection based on material type
- Distinct safety protocol enforcement

## Future Project Dependencies

### Phase 1 Boundaries (Current Project)
✅ **In Scope:**
- ARCP and SWMS automation
- Template intelligence and selection
- OneDrive integration
- Hygienist workflow automation
- Training requirement validation

❌ **Out of Scope (Future Projects):**

#### Equipment Inventory System
- Real-time check-in/check-out tracking
- Live equipment availability data
- Automated equipment-to-job matching

#### Digital Field Capability Project  
- Quote-stage data capture via Cliff's iPad concept
- Mobile hazard identification tools
- Field-to-office data integration

#### Excel Scheduling Integration
- Automated document creation triggers from scheduling system
- Worker allocation integration
- Dynamic scheduling updates

## Change Log - Major Proposal Updates

### Version 1.0 → 2.0 (Post-SRT Analysis)

#### Structural Changes
1. **Added Job Lifecycle Section**: Complete workflow from quote to document creation
2. **Enhanced Client Profile**: Added client type variety and stakeholder details
3. **Updated Pain Points Table**: Added document timing and worker documentation issues
4. **New Fragmented Data Sources Section**: Multi-system integration challenges

#### Technical Corrections  
1. **SharePoint → OneDrive**: 4 references corrected throughout document
2. **SWMS Template Structure**: Added organised library details
3. **Equipment Management**: New section highlighting inventory limitations
4. **Emergency Plan Process**: Realistic current process vs automation opportunity

#### Process Enhancements
1. **Template Intelligence**: Enhanced with memory dependency issues
2. **ConnectTeam Integration**: Complex training requirements matrix
3. **Hygienist Workflow**: Flexible client review requirements  
4. **Permit Logic Engine**: Site-specific examples and requirements

#### Development Scope Refinements
1. **AI Model Development**: Added field expertise support, risk-based assessments
2. **Integration Development**: Training validation, induction tracking
3. **Discovery & Setup**: Equipment audit with future project boundaries

## Risk Mitigations Identified

### High-Risk Items Addressed
1. **Manual Process Dependencies**: Acknowledged field expertise requirements
2. **Multi-System Integration**: Realistic approach to training/induction complexity
3. **Equipment Availability**: Noted as separate project to manage expectations
4. **Client Review Variability**: Flexible workflow to accommodate different requirements

### Success Factors
1. **Jess's Knowledge Capture**: Systematic documentation of template selection logic
2. **Realistic Scope**: Clear boundaries between Phase 1 and future projects
3. **Current Process Accommodation**: Work with existing manual processes until automation ready
4. **Compliance Focus**: Maintain safety standards throughout automation implementation

---

**Document Status:** Comprehensive knowledge base capturing all insights from SRT transcript analysis  
**Last Updated:** Post-implementation of all proposal refinements  
**Next Steps:** Client review and approval of refined Phase 1 proposal