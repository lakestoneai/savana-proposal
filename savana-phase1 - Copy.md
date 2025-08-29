# Phase 1: Intelligent Quote System

**Project Duration:** 10 Weeks  
**Implementation Period:** Phase 1 - Data Quality Foundation for Digital Supply Chain Readiness  
**Start Date:** October 1, 2025  
**End Date:** December 10, 2025

## Executive Summary

**Project Goal**: Establish quality data at source by transforming Savana's quoting process from manual estimates to intelligent, structured quote generation that captures complete job specifications, enabling accurate downstream operations and eliminating data quality issues that propagate through all subsequent phases.

**Client Profile:**
- **Company:** Savana Environmental (asbestos removal contractor)
- **Location:** Perth, Western Australia
- **Client Types Served:**
  - Property management companies
  - Insurance companies  
  - Principal builders (subcontracting demolition)
  - Local government/councils
  - Individual homeowners
  - Federal facilities (Defence bases - special permit requirements)

**Expected Impact**:
- **15% Quote Win Rate Improvement**: Higher quality, more accurate quotes
- **Eliminate Data Quality Issues**: Structured capture prevents downstream errors
- **2-3 Hour Quote Time Reduction**: From manual estimates to intelligent generation
- **95% Cost Estimation Accuracy**: Automated calculations with historical data
- **Complete Job Specification**: Equipment, hazards, resources defined upfront
- **Enable Phase 2 Automation**: Structured data feeds intelligent safety documentation
- **Enable Phase 3 Precision**: Complete job specifications enable accurate scheduling
- **Foundation for Phases 2-4**: Quality data at source eliminates error propagation

## Critical Quoting Process Analysis

### Current Quoting Limitations

- **Manual Estimation**: Quotes rely on estimator experience and memory
- **Inconsistent Specifications**: Job requirements poorly defined at quote stage
- **Resource Guesswork**: Equipment and personnel requirements estimated roughly
- **Poor Hazard Assessment**: Site hazards identified late in process, not at quote stage
- **Disconnected Systems**: Quote data doesn't flow to scheduling or safety documentation

### Data Quality Problems at Source

- **ServiceM8 Limitations**: Basic quote fields don't capture job complexity
- **Incomplete Job Specifications**: Equipment, permits, hazards not systematically captured
- **Downstream Data Recreation**: Information re-entered multiple times across systems
- **Error Propagation**: Poor quote data creates problems in scheduling and safety documentation
- **Lost Contextual Information**: Site visit insights not captured in structured format

### Integration Opportunities

**ConnectTeam Resource Data:**
- Worker qualifications and availability
- Training records and expiry dates
- Site-specific inductions already completed
- Award rates and cost calculations

**MYOB Financial Integration:**
- Historical job costing data
- Accurate margin calculations
- Cost centre allocation
- Real-time pricing updates

## Intelligent Quote System Requirements

### Data Capture Framework

**Core Job Specification Fields:**
- Job type and scope definition with standardised categories
- Site access requirements and constraints
- Hazard pre-identification from site assessment
- Required equipment and specialised tools
- Personnel requirements with qualification specifications
- Timeline and scheduling constraints
- Client-specific requirements and standards

**Financial Integration Requirements:**
- Real-time MYOB integration for accurate costing
- Historical job data analysis for cost prediction
- Margin calculation with automatic markup application
- Resource cost tracking and allocation
- Quote approval workflow with escalation rules

### Quote-to-Job Lifecycle Transformation

**New Intelligent Process:**

1. **Structured Site Assessment**: Systematic hazard identification and resource requirements capture
2. **Intelligent Quote Generation**: Automated calculations using historical data and real-time costs
3. **Resource Validation**: ConnectTeam integration verifies worker availability and qualifications
4. **Quote Approval Workflow**: Automated routing based on job value and complexity
5. **Accept-to-Job Conversion**: Structured data flows directly to scheduling and safety systems
6. **Phase 2 Enablement**: Complete job specifications feed intelligent safety documentation
7. **Phase 3 Integration**: Resource requirements enable precision scheduling

### System Integration Architecture

**Primary Integrations:**
- **MYOB**: Real-time costing, historical analysis, margin management
- **ConnectTeam**: Resource availability, qualifications, cost rates
- **ServiceM8 Migration Planning**: Data export and transition strategy
- **OneDrive**: Document templates and quote archive storage

**Data Quality Standards:**
- Mandatory field validation to prevent incomplete quotes
- Standardised job categorisation for consistent data
- Automated calculation verification and error checking
- Historical data analysis for continuous improvement

## Current State Analysis

### Quoting Process Pain Points

| Area                 | Current Process                                                                           | Time Impact                           | Risk Level                                |
| -------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------- | ----------------------------------------- |
| Manual Estimation    | Experience-based guesswork for costs, resources, and timelines                           | 2-3 hours per quote                   | High - profit margin risk                 |
| Data Re-entry        | Same information entered multiple times across different systems                          | 1-2 hours per accepted quote          | High - error propagation                  |
| Resource Availability| No real-time visibility of worker/equipment availability when quoting                     | Scheduling conflicts post-acceptance  | Critical - delivery commitment risk       |
| Hazard Assessment    | Site hazards identified late in process, not captured systematically in quotes            | Rework and cost overruns             | Critical - safety and financial risk     |
| Incomplete Specifications | Job requirements poorly defined, leading to scope creep and disputes                 | Project delays and disputes          | High - client relationship risk          |
| Historical Data Loss | No systematic capture of lessons learned from completed jobs                              | Repeated estimation errors           | Medium - continuous margin erosion       |

### Fragmented Quote Data Sources

Current quoting process relies on multiple disconnected information sources:
- **ServiceM8**: Basic client details and minimal job scope (inadequate for complex quotes)
- **MYOB**: Historical cost data accessible but not integrated into quoting process
- **ConnectTeam**: Worker qualifications and rates but no real-time availability
- **Staff Experience**: Estimator knowledge of previous similar jobs and pricing
- **Manual Site Visits**: Hazard identification and resource requirements noted informally
- **Email/Phone**: Client requirements and special conditions captured ad-hoc
- **Spreadsheets**: Equipment costs and availability tracked separately
- **Memory/Notes**: Supplier pricing and lead times remembered rather than systematised

**Impact**: Inconsistent quote quality; missed opportunities; pricing errors; resource conflicts

## Proposed Solution: Intelligent Quote System

### Core Philosophy: Quality Data at Source

Rather than fixing poor data downstream, our approach establishes **comprehensive job specifications at the quote stage**, creating structured, quality data that flows seamlessly through all subsequent phases. This eliminates error propagation and enables true operational intelligence.

### Current Manual Quoting Process
1. **Site Visit**: Estimator assesses job manually, taking notes
2. **Experience-Based Pricing**: Rough estimates based on memory and intuition  
3. **Basic ServiceM8 Entry**: Minimal job details with poor structure
4. **Manual Resource Planning**: Equipment and personnel guessed roughly
5. **Quote Delivery**: Often lacks comprehensive specifications

### Proposed Intelligent Quote Generation

#### **Structured Data Capture Engine**
- **Job Specification Framework**: Systematic capture of all job requirements
- **Site Assessment Integration**: Structured hazard identification and resource requirements
- **Client Requirement Matrix**: Standardised capture of client-specific needs
- **Historical Pattern Analysis**: Learning from previous similar jobs

#### **Smart Quote Generation Process**
```
Site Assessment → Intelligent Analysis → Resource Matching → Cost Calculation → Structured Quote
```

**Phase 1 Workflow:**
1. **Site Assessment Capture**: Structured data entry for hazards, access, requirements, site conditions
2. **Intelligent Resource Matching**: ConnectTeam integration identifies qualified available workers
3. **Cost Calculation Engine**: MYOB integration provides real-time accurate costing with margin management
4. **Equipment Requirement Planning**: Systematic identification of tools, equipment, and specialised resources
5. **Quote Generation**: Professional quote with complete job specifications and T&Cs
6. **Approval Workflow**: Automated routing based on job value and risk assessment
7. **Phase 2 Data Handoff**: Complete specifications flow to safety documentation automation

#### **Technology Architecture**

**Web-Based Platform (Optimal for 10-week timeline)**
- Cloud-hosted intelligent form system
- Real-time API integrations with MYOB and ConnectTeam
- Mobile-responsive for field estimators and site assessments
- Structured data validation and quality assurance
- Quote approval workflow with electronic signatures

#### **ServiceM8 Integration Strategy**

**Phase 1 Implementation:**
- **Quote Data Extraction**: Automatic population of job details, client information, work scope
- **Document Triggers**: Automated alerts for jobs approaching documentation requirements
- **Future Enhancement Readiness**: Architecture designed for expanded field data capture from future quoting system improvements

**Integration Challenges Acknowledged:**
- ServiceM8 API limitations require workaround strategies
- Manual supervisor assignment until scheduling system integration (separate future project)
- Equipment availability remains manual estimation until inventory system implementation

#### **Intelligent Guidance System**

**High-Match Scenarios (80%+ similarity):**
- Template automatically pre-populated
- User reviews 5-8 key difference fields

**Medium-Match Scenarios (50-80% similarity):**
- System suggests closest template with highlighted variations
- Guided prompts for key differences

**Low-Match/Complex Scenarios (<50% similarity or high-value jobs):**
- Guided form completion with intelligent field suggestions
- Manual expert review maintained for quality assurance
- Full manual override capability preserved

#### **Quality Assurance Framework**

**Automated Validation:**
- WorkSafe 5-day notification compliance checking
- Training requirement verification via ConnectTeam integration
- PPE requirement validation based on job parameters
- Site-specific permit requirement flagging

**Expert Review Workflow:**
- Hazard assessment validation (cannot be fully automated for safety compliance)
- Final compliance approval before document release
- Hygienist: Mandatory review process maintained
- Client Review: Flexible workflow based on client preferences

#### **Compliance Integration**

**ISO 45001:2018 Safety Management System:**
- All templates aligned with SMS requirements
- Systematic hazard identification preserved
- Risk assessment methodology maintained
- Continuous improvement metrics captured

**ISO 27001:2013 Information Security:**
- Encrypted data handling for all integrations
- Australian-hosted infrastructure
- Role-based access controls
- Complete audit trail maintenance

### Implementation Benefits

**Immediate Value:**
- Reduces quote preparation time from 2-3 hours to 45 minutes
- Eliminates manual cost estimation errors and improves accuracy to 95%
- Provides real-time resource availability and qualification matching
- Creates comprehensive job specifications at source
- **Enables Phase 2**: Structured data feeds intelligent safety documentation

**Long-term Advantages:**
- 15% quote win rate improvement through higher quality, more accurate quotes
- Eliminates data quality issues that propagate through all subsequent phases
- **Digital Transformation Foundation**: Quality data at source enables precision in mobile operations (Phase 2), intelligent scheduling (Phase 3), and integrated platform (Phase 4)
- Positions business for major infrastructure project opportunities with comprehensive digital capability
- Creates systematic capture of historical job patterns and lessons learned

**Risk Mitigation:**
- Builds on proven workflow rather than replacing it
- Maintains expert review processes for safety compliance
- Provides manual override capability for all automated functions
- Uses existing approved templates as foundation

### Document Types Required

1. **ARCP (Asbestos Removal Control Plan)**
   - Required for every licensed removal job
   - Must differentiate between friable and bonded asbestos removal
   - Currently uses same templates despite different safety protocols required
   - Different SWMS selection needed based on material type
   - 15-20 pages typical
   - Must be submitted to WorkSafe 5 days before work 
   - Emergency jobs handled with temporary exemptions
   - Includes emergency evacuation plans (manually created from Google Maps)
   - **Hygienist Survey Integration**:
     - Not all jobs have pre-work surveys (especially private residential)
     - When present, attached to ServiceM8 but no systematic workflow
     - System must handle both surveyed and non-surveyed jobs

2. **SWMS (Safe Work Method Statement)**
   - Organised template library in OneDrive with job-type specific folders
   - Existing categorisation system (e.g., "Vinyl Tiles and Adhesive" folder)
   - Multi-factor template selection beyond simple job type matching
   - Daily risk assessments
   - Task-by-task hazard controls
   - Daily sign-on requirements
   - PPE assessments and equipment lists
   - Training requirements verification
   - Site-specific permit requirements

3. **Pre-starts**
   - Daily safety briefings
   - 20-30 minutes per supervisor to complete
   - Currently handwritten

4. **Additional Documents**
   - Emergency evacuation plans (manual Google Maps markup)
   - Supervisor checklists
   - Notification forms for WorkSafe
   - Hygienist review documentation

5. **Equipment Management Limitations**
   - No real-time inventory tracking of equipment check-in/check-out
   - Equipment list selection based on availability assumptions, not live data
   - Risk of equipment unavailability affecting job planning
   - **Note**: Equipment inventory system is separate future project

## Implementation Plan (October 1 - December 10, 2025)

### Objectives

- Establish intelligent quote system with structured data capture
- Integrate MYOB for real-time costing and historical analysis
- Integrate ConnectTeam for resource availability and qualification matching
- Develop quote approval workflow with electronic signatures
- Create ServiceM8 migration strategy and data export planning
- Reduce quote preparation time by 70% while improving accuracy
- Enable Phase 2 automation through structured job specifications

### Implementation Priorities

#### Immediate Wins (October 1-29, 2025)

1. **Template Intelligence**: Train AI on existing jobs to recognise patterns
   - Currently relies entirely on Jess's memory ("we did this exact job three days ago")
   - No systematic capture of which SWMS templates match which job types
   - Pattern recognition needed for flooring vs fence vs eaves work
   - Build knowledge base to replace individual memory dependency

2. **Smart Copy Function**: Enhanced template selection
   - Automatically find most similar previous job
   - Pre-populate based on job type
   - Only require updates to address, date, operatives

3. **Emergency Plan Generation**
   - Current process: Google Maps screenshot → manual markup → document insertion
   - Manual identification: evacuation points, muster points, site first aid locations
   - Time-consuming: "Jess has to do every single time"
   - Automation opportunity: Google Maps API + intelligent markup suggestions

4. **Field Expertise Integration**
   - Hazard identification currently requires manual field expertise
   - Cliff's knowledge essential for site-specific risk assessment
   - Future digital field capability project will improve quote-stage data capture
   - System must work with current manual processes until field digitisation complete

#### Critical Integrations (October 29 - November 26, 2025)

1. **Automated Document Creation Monitoring**
   - System monitors scheduling data for jobs approaching 2-week mark
   - Automated daily report highlighting jobs requiring documentation
   - Priority queue based on scheduled start dates
   - Alert system for jobs missing ARCP/SWMS with < 5 days to start

2. **ConnectTeam Training Integration**
   - Core requirements: White card (99% jobs), asbestos removal training
   - Equipment-specific: EWP, forklift, working at heights (job-blocking if missing)
   - Site-specific: Client induction requirements (tracked separately - hundreds)
   - Critical validation: "Can't do job tomorrow without required ticket"
   - Multi-system challenge: ConnectTeam + separate induction spreadsheet

3. **Hygienist Workflow**
   - Mandatory: Hygienist review and sign-off for all jobs
   - Variable: Client review requirements (some thorough, some auto-approve, some ignore)
   - Flexible workflow routing based on client review preferences
   - Revision tracking with draft number incrementation
   - Copy provision for hygienist clearance process requirements

4. **Permit Logic Engine**
   - Site-specific permit requirements:
     - Royal Perth Hospital: Hot works permits for grinding
     - UWA: Working at heights permits
     - Defence bases: Asbestos removal permits required
     - Residential: Generally no permits required
   - Automated permit requirement flagging based on client and work type
   - Integration with site condition assessment

### Detailed Deliverables

#### October 1-15: Discovery & Setup

- [ ] Map current processes to ISO 45001:2018 SMS requirements
- [ ] Document ISO 27001 security controls for data handling
- [ ] Identify SMS gaps and compliance improvements
- [ ] Document all current templates (ARCP, SWMS, MRP, Lead plans)
- [ ] Map ServiceM8 data fields to document requirements
- [ ] Map ConnectTeam qualification/training data structure
- [ ] Document hygienist review workflow
- [ ] Identify compliance requirements with Chris Milos
- [ ] Map site-specific permit requirements (hot works, asbestos permits, etc.)
- [ ] Audit current SWMS equipment lists 
- [ ] **Note**: Equipment inventory tracking is separate future project
- [ ] Build equipment-to-template mapping for current available items
- [ ] Define standardised document naming conventions (currently: "SWMS Friable [Address]")
- [ ] Establish job number tracking system integration
- [ ] Create automated file structure generation for OneDrive
- [ ] Set up AI training environment
- [ ] Establish Safety Management System baseline metrics

#### October 15-29: AI Model Development

- [ ] Train AI on existing templates and completed documents
- [ ] Create definitive matrix mapping 10+ job types to required SWMS templates
- [ ] Build automated SWMS selection based on job type identification
- [ ] Validate template selection logic with Jess for all job type combinations
- [ ] Build hazard identification support (not replacement) for field expertise
- [ ] Map complex template selection: job type + equipment + site conditions + access requirements
- [ ] Implement risk-based PPE assessment rather than simple site-type rules
- [ ] Create equipment-to-hazard relationship database
- [ ] Create job type recognition (flooring, fence, eaves, residential vs commercial)
- [ ] Build template selection logic aligned with SMS requirements
- [ ] Develop hazard pre-population based on job type
- [ ] Create automated emergency plan generation using mapping APIs
- [ ] Build PPE requirement logic based on job specifications
- [ ] Develop permit requirement detection (commercial sites, hospitals, defence bases)
- [ ] Implement ISO 45001 risk assessment methodology
- [ ] Build compliance validation rules for WorkSafe requirements

#### October 29 - November 12: Integration Development

- [ ] ServiceM8 API connection for job data extraction
- [ ] ConnectTeam API integration for training/qualification verification
- [ ] OneDrive API for automated document upload
- [ ] Build user interface for document generation
- [ ] Create hygienist review workflow with revision tracking
- [ ] Develop automated WorkSafe notification system (5-day requirement)
- [ ] Build emergency plan generator with evacuation points
- [ ] Build training requirement validation against job assignments
- [ ] Integration between ConnectTeam API and separate induction tracking
- [ ] Pre-scheduling validation to prevent "guys sent to job without inductions"
- [ ] Implement ISO 27001 security controls for all data transfers
- [ ] Create Safety Management System reporting dashboard
- [ ] Build compliance audit trail functionality

#### November 12-26: Testing & Refinement

- [ ] Test with 10 different job types (residential, commercial, defence, hospital)
- [ ] Validate compliance with WorkSafe requirements
- [ ] Test hygienist review and revision process
- [ ] Validate training requirement matching
- [ ] User acceptance testing with Jess
- [ ] Document training and SOPs
- [ ] Verify ISO 45001 SMS compliance across all workflows
- [ ] Test ISO 27001 security controls and access permissions
- [ ] Conduct Safety Management System audit simulation
- [ ] Validate continuous improvement tracking mechanisms

## Resource Requirements

### Internal Team

- **Chris Milos**: 4 hours/week for compliance validation
- **Jess**: 8 hours/week for testing and feedback
- **Leon**: 2 hours/week for operations oversight
- **Field Supervisor**: 2 hours/week for field testing

### External Resources

- **AI/Automation Developer**: Full-time for 8 weeks
- **Integration Specialist**: Part-time for API connections
- **UX Designer**: 20 hours for interface design
- **Change Management**: 10 hours for training materials

### Technology Stack

- **AI Platform**: OpenAI/Claude API for document generation
- **Safety Management System**: ISO 45001:2018 compliant framework
- **Security Standards**: ISO 27001:2013 compliant infrastructure
- **Integration**:
  - ServiceM8 API (job data) - **LIMITED FUNCTIONALITY**: No Android app, no job completion trigger, one-way sync to MYOB only
  - ConnectTeam API (qualifications/training) - Geo-tagging functional, award rates sync to MYOB
  - **MYOB API** - Master data source for line items and payroll
  - OneDrive API (document storage)
  - Google Maps (emergency plan generation)
- **Hosting**: Australian-based servers (ISO 27001 compliance)
- **Document Processing**: Template engine with dynamic field population
- **Workflow Management**: Revision tracking and approval system
- **Audit Trail**: Complete compliance logging for SMS requirements

**Note**: Split entity structure (Savana Environmental / Savana) must be maintained for contractor/visa management

## Risk Management

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| ServiceM8 API limitations | Medium | High | Early API testing, fallback to manual entry |
| User adoption resistance | Low | Medium | Maintain familiar interfaces, extensive training |
| Compliance rejection | Low | Critical | Chris Milos approval at each stage |
| Data security concerns | Medium | High | Australian hosting, encryption, audit trails |
| Integration complexity | High | Medium | Phased approach, maintain manual fallback |

## Budget Estimate

### Development Costs

- **Phase 1 Total**: $25,000 - $35,000
  - Discovery & Setup: $3,000 - $4,000
  - AI Model Development: $8,000 - $10,000
  - Integration Development: $10,000 - $15,000
  - Testing & Refinement: $4,000 - $6,000

### Ongoing Costs (Annual - Phase 1 portion)

- AI API usage: $2,000 - $3,000
- Hosting/Infrastructure: $1,200
- Maintenance/Updates: $5,000
- **Total Annual**: $8,200 - $9,200

### ROI Calculation

- Time saved: 15 hours/week @ $40/hour = $31,200/year
- Error reduction/compliance: $5,000/year estimated
- **Payback Period**: 10-12 months

## Success Metrics

### Phase 1 Completion (8 weeks)

- Compliance accuracy: 100%
- Template consistency: 100%
- User satisfaction: > 8/10
- ISO 45001 SMS compliance: 100% for documentation processes
- ISO 27001 security controls: Fully implemented
- Safety Management System metrics: Established and baselined

### 3-Month Post-Implementation

- Safety documentation automated for 90% of jobs
- Document creation time reduced by 75%
- Zero compliance violations
- Full integration with ServiceM8 and ConnectTeam
- ISO 45001 Safety Management System fully operational
- Continuous improvement metrics established and tracking
- WorkSafe audit readiness achieved

## Next Steps

### Immediate (This Week)

- Confirm Phase 1 approval and budget
- Schedule detailed discovery session with Jess
- Access ServiceM8 API documentation
- Collect 50 sample completed documents

### Week 2

- Begin AI model training
- Design user interface mockups
- Map integration points
- Establish project governance

### Week 3

- Start development
- Weekly progress reviews with Chris Milos
- Begin change management planning

## Key Contacts

- **Chris Milos** (Safety HSEQ): Compliance validation and requirements
- **Jess** (Project Manager): Primary user and testing
- **Leon** (Operations Manager): Operations oversight
- **Andrew @ Nalit**: IT infrastructure and permissions
- **ServiceM8 Owner**: Leon (for API access)

---

**Project Status**: Foundational phase ready to commence October 1, 2025  
**Next Review**: October 15, 2025 completion milestone  
**Phase Progression**: Digital documentation system enables Phase 2 mobile field operations, Phase 3 intelligent scheduling, and Phase 4 integrated project delivery platform. Essential foundation for major infrastructure project capability.