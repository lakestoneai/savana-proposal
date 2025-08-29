# ARCP Document Analysis - Savana Environmental

## Document Overview

**Document Title:** FRIABLE ASBESTOS REMOVAL CONTROL PLAN  
**Document Number:** SEF-049  
**Revision:** 2  
**Pages:** 15  
**Example Job:** North Metropolitan Tafe, Leederville (Job #1003890)  
**Client:** Kineticon  

**Analysis Date:** Based on PDF review of complete document structure  
**Purpose:** Technical analysis for automation system design

## Document Structure Analysis

### Page Layout & Sections

| Page | Section | Content Type | Automation Potential |
|------|---------|--------------|---------------------|
| 1 | Cover Page | Header info, revision table | High - auto-populated |
| 2 | Table of Contents | Navigation | Medium - auto-generated |
| 3 | Contract Details | Job info, personnel, dates | High - system integration |
| 4 | Scope & Risk Summary | Job description, asbestos details | Medium - mixed sources |
| 5 | Hazard Assessment | 30+ checkboxes, risk matrix | Low - requires expertise |
| 6 | Control Measures | PPE, equipment, procedures | Medium - template-based |
| 7 | Equipment Schedule | Detailed equipment lists | Medium - job-type templates |
| 8 | Sketch Plans | Site diagrams, visual layouts | Low - manual/CAD integration |
| 9 | Location Photos | Site photography | Low - manual upload |
| 10-11 | Work Method Statement | Detailed procedures | High - standardized text |
| 12-13 | Emergency Information | Contact details, procedures | High - template-based |
| 14 | Responsibility Declaration | Management signatures | Medium - digital signatures |
| 15 | Worker Acknowledgement | 20+ operative signatures | Medium - bulk processing |

## Detailed Field Analysis

### 1. HEADER INFORMATION (Page 1)

#### Auto-Populated Fields
```markdown
Site Address: [ServiceM8 Job Address]
Job No.: [ServiceM8 Job Number]  
Client: [ServiceM8 Client Name]
```

#### Revision Tracking Table
| Field | Source | Notes |
|-------|---------|-------|
| Revision No. | Manual | Incremented with each change |
| Approved Date | System timestamp | When approved |
| Revision Comments | Manual input | Description of changes |

**Prepared by:** Fixed - Christopher Bridge  
**Plan Owner:** Fixed - Chris Bridge / Shannon Baird  
**Approved by:** Fixed - Chris Bridge / Shannon Baird

### 2. CONTRACT DETAILS (Page 3)

#### Personnel Assignment
```markdown
Site Supervisor: [Manual Selection - "best guess" per SRT]
Secondary Supervisor: [Dropdown - "Choose an item"]
```

#### Job Timing
| Field | Data Source | Calculation |
|-------|-------------|-------------|
| Estimated Start | Scheduling System | From Excel scheduling |
| Estimated Finish | Scheduling System | From Excel scheduling |
| Working Days | Calculated | Days between start/finish |
| Estimated Total Duration | Calculated | Weeks (working days / 5) |
| Weekend Variances | Manual/Template | "After 6pm Friday and weekend works" |
| Number of Operatives | Scheduling System | From job allocation |

#### Client Information
```markdown
Client: [ServiceM8 Client Name]
Site Manager/Owner: [ServiceM8 Contact Details]
```

#### Enforcing Authority
**Fixed Value:** WorkSafe – Department of Mines, Industry Regulation and Safety

### 3. SCOPE OF WORKS & RISK ASSESSMENT (Page 4)

#### Job Scope
| Field | Data Source | Example Value |
|-------|-------------|---------------|
| Scope of Works | ServiceM8 Quote | "Removal of floor tiles and blackjack from A Block Level 2" |
| Asbestos Survey Details | ServiceM8 Attachments | "Completed By: Broadspec" |
| Quantity/Extent | Survey/Quote | "Approximately: 320 Square Metres" |
| Type(s) of asbestos | Survey Data | "Chrysotile - Hydrophilic" |
| Form and Condition | Survey/Manual | "Asbestos-reinforced composites (vinyl floor tiles & Adhesive)" |

### 4. HAZARD ASSESSMENT MATRIX (Page 5)

#### Comprehensive Hazard Checklist (30+ Items)
**Format:** Three-column checkbox matrix

**Column 1 Hazards:**
- Access to Roofs ☒
- Access to Plant/Equipment/Machinery ☐
- Access to Fixed Scaffolding ☐
- Biological Agent e.g., Leptospirosis ☐
- Psittacosis, Anthrax ☐
- Chemical Agent e.g., Lead/Arsenic ☐
- Confined Spaces ☒
- Construction Sites ☐
- Live Domestic ☐
- Electrical Sub Stations ☐
- Electrical Switch Gear ☐
- Electrical Tooling ☐

**Column 2 Hazards:**
- Explosive Materials ☐
- Fire ☐
- General Dust ☒
- Hand Tooling ☒
- Hot Works (Grinding Etc) ☒
- Ionising Radiation ☐
- Lead Paint/Products ☐
- Lone Working ☒
- Manual Handling ☐
- SMF ☐
- Moving Vehicles ☐
- Needle Stick Injuries ☐
- Noise ☐
- Non-Ionising Radiation ☐

**Column 3 Hazards:**
- Pigeons/Livestock/Rats i.e., Vermin ☐
- Sewage ☐
- Slips, Trips, Falls on Level Ground ☒
- Unstable Structures ☐
- Use of Fixed Ladders ☐
- Use of Hired Mobile Elevated Work Platform's ☐
- Use of Ladders ☐
- Use of Tower Scaffolds ☐
- Vibratory Tools ☐
- Work in Hot/Cold Environment ☐
- Work on/near Water ☐
- Work near a Railway ☐
- Removal of Sprayed Asbestos ☐
- Removal of Asbestos Insulation Board ☐

**Critical Notes:**
- Requires field expertise (Cliff's knowledge per SRT analysis)
- Job-type patterns could inform AI-assisted selection
- Manual override always required for safety compliance

#### Additional Stakeholders
**Text Field:** "During the asbestos removal works the building will be closed to all personnel, including employees, contractors, and visitors. Only authorised personnel access the work area."

### 5. CONTROL MEASURES (Page 6)

#### Exposure Levels Table
| Material Type | Without Controls | With Controls |
|---------------|------------------|---------------|
| Spray Coating | - | - |
| Insulation / Lagging | - | - |
| Asbestos Debris | <100 | <0.01 |
| Blackjack | [blank] | [blank] |
| Floor Tiles | [blank] | [blank] |
| Other | - | - |

#### Risk Controls Matrix
| Control Method | Applied | Notes |
|----------------|---------|--------|
| Pre-Clean | Yes | Standard for friable work |
| Enclosure | Yes | Required for friable removal |
| Air Lock | Yes | Personnel decontamination |
| Bag Lock | No | Not required for this job type |
| Fibre Suppression – Injection | No | Alternative method |
| Fibre Suppression – Spraying | Yes | Dust control |
| Direct Shadow Vacuuming | No | Not applicable |
| Negative Pressure / Air Movement | Yes | HEPA filtration |
| Encapsulation | No | Not required |

#### Personal Protective Equipment
| PPE Item | Specification | Notes |
|----------|---------------|-------|
| Coveralls | Category 3, Type 5/6 – Disposable | Standard requirement |
| Respiratory Protective Equipment | Full Face P3 Masks | Required in enclosure |
| Eye Protection | Choose an item | Dropdown selection |
| Gloves | Choose an item | Dropdown selection |
| Safety Footwear | Choose an item | Dropdown selection |
| High Visibility Clothing | Choose an item | Site-dependent |
| Hard Hats | Choose an item | Site-dependent |
| Fall Arrest Equipment | Choose an item | Job-dependent |
| Foul Weather Gear | Choose an item | Weather-dependent |

### 6. EQUIPMENT SCHEDULE (Page 7)

#### Fibre Suppression and Control Equipment
| Equipment | Type/Size | Quantity | Notes |
|-----------|-----------|----------|--------|
| Negative Pressure Units | [Manual entry] | [Manual entry] | Savana Environmental Issue |
| Vacuum Units | [Manual entry] | [Manual entry] | H-class specification |
| Mobile Decontamination Unit (DCU) | Standard | 1 | When suitable |
| Flatpack DCU | Alternative | As needed | When Mobile unsuitable |
| Wet Strip Injection System | [Manual entry] | [Manual entry] | Liquid suppression |
| Killaspray Fibre Suppressant | 10 litres | 2 | Standard quantity |
| Encapsulation | 200 litres | Low pressure sprayer | Post-removal |

#### Access Equipment
| Equipment Type | No. | Height | Notes |
|----------------|-----|--------|--------|
| Savana Environmental Issue Alloy Tower Scaffold | [Manual] | [Manual] | Company equipment |
| Other Alloy Tower Scaffold | [Manual] | [Manual] | Hired equipment |
| Mobile Elevating Work Platform 'Scissor Lift' | [Manual] | [Manual] | Site access |
| Mobile Elevating Work Platform 'Cherry Picker' | [Manual] | [Manual] | Height access |
| Tube and Fitting or System Scaffold | [Manual] | [Manual] | Complex structures |
| Platform Ladders | [Manual] | [Manual] | Basic access |

### 7. VISUAL ELEMENTS

#### Sketch Plans (Page 8)
**Content:** Site floor plan with color-coded areas
- **Purple Areas:** Asbestos Enclosure
- **Yellow Areas:** Air Lock  
- **Orange Areas:** Decontamination Unit
- **Blue Areas:** Waste Bin
- **Black Arrows:** Waste Route

**Requirements:**
- Site-specific drawings
- Color coding system
- Equipment placement
- Traffic flow patterns

#### Location Photos (Page 9)
**Content:** Two site photographs showing:
- Corridor areas with flooring to be removed
- Visual documentation of existing conditions
- Reference for pre-work condition

### 8. WORK METHOD STATEMENT (Pages 10-11)

#### Structured Procedure Sections
1. **MOBILISATION**
   - Pre-departure checklist (SEF-001 Job File Checklist)
   - Equipment inspection procedures
   - Site introduction protocols
   - Personnel induction requirements
   - Pre-start meeting (FRM-010 Prestart)

2. **ENCLOSURE SET UP FOR FRIABLE ASBESTOS REMOVAL**
   - Enabling works procedures
   - Barrier installation
   - Decontamination unit setup
   - Service connections

3. **PRE-CLEANING, CONSTRUCTION AND TESTING**
   - Surface preparation
   - Transit route protection
   - Enclosure construction (200um plastic)
   - Quality control procedures

4. **TESTING OF ENCLOSURES**
   - Visual inspection protocols
   - Smoke testing procedures
   - Fire alarm isolation
   - Site authority notification

5. **CONNECTION OF HEPA FILTRATED EXTRACTION**
   - Negative pressure setup
   - Air change calculations (10-12 changes/hour)
   - Equipment positioning

6. **REMOVAL OF ASBESTOS MATERIALS**
   - Step-by-step removal procedures
   - Waste handling protocols
   - Fibre suppression techniques
   - Equipment-specific procedures

### 9. EMERGENCY INFORMATION (Pages 12-13)

#### Accident Plan Structure
**Comprehensive emergency procedures including:**
- First aid protocols
- Medical facility procedures
- Emergency services (000) protocols
- Incident reporting requirements
- Site isolation procedures
- Emergency services briefing requirements

#### Fire Plan
**Specific fire emergency procedures:**
- Fire extinguisher requirements (6-month inspection cycle)
- Risk assessment protocols
- Decontamination bypass procedures
- PPE maintenance during emergency evacuation

#### Contact Information
**Company Emergency Contacts:**
- Christopher Bridge (Director): 0497103772
- Email: chris@savanaenvironmental.com.au

**Client Emergency Contacts:**
- Clint Bankin (Project Manager): 0435102300

#### Waste/Transit Routes
| Element | Details |
|---------|---------|
| Location | In the car park gravel area |
| Transit Route to Skip | Direct from airlock across paths and car park |
| Transport Method | Regulation asbestos waste bags, tape sealed |
| Large Item Wrapping | 200um black plastic |
| Storage Protocol | Inside enclosure until clearance |
| Disposal Location | Licensed facility |

### 10. APPROVAL & SIGNATURES (Pages 14-15)

#### Management Responsibility Declaration
**Signatory:** Christopher Bridge (Manager)
**Requirements:**
- Full responsibility acknowledgment
- License compliance confirmation
- Method statement verification
- Equipment specification approval

#### ARCP Verification Section
**Project Details:**
- Site Address, Office Address
- Project Number, Contract Manager
- Site Supervisors, Revision Number, Date

#### External Approvals
**Two-tier approval system:**
1. **LAA Approval (if requested)**
   - Company, Name, Signature, Date fields
2. **End Client Approval**
   - Company, Name, Signature, Date fields

#### Worker Acknowledgement (Page 15)
**Comprehensive sign-off structure:**
- Supervisor signature blocks (2)
- Site Supervisor signature blocks  
- **20+ Operative signature lines** with:
  - Print Name field
  - Signature/Date field
  - Acknowledgment of plan understanding
  - Risk assessment verification
  - Substance assessment confirmation

## Data Source Mapping

### High Automation Potential (>80%)
| Field Category | Data Source | Integration Method |
|----------------|-------------|-------------------|
| Job Header Information | ServiceM8 API | Direct field mapping |
| Client Contact Details | ServiceM8 API | Contact record lookup |
| Job Dates & Duration | Scheduling System | Excel/API integration |
| Worker Numbers | Scheduling System | Daily allocation data |
| Standard Procedures | Template Library | Job-type template selection |
| Contact Information | Master Data | Fixed company information |

### Medium Automation Potential (40-80%)  
| Field Category | Data Source | Integration Method |
|----------------|-------------|-------------------|
| Supervisor Assignment | Manual + AI Suggestion | Pattern-based recommendations |
| Equipment Selection | Job Type + Manual | Template-based with override |
| PPE Requirements | Job Type + Site Rules | Rule engine with manual validation |
| Scope Description | ServiceM8 Quote | Text extraction + manual editing |
| Survey Information | ServiceM8 Attachments | Document parsing when available |

### Low Automation Potential (<40%)
| Field Category | Data Source | Integration Method |
|----------------|-------------|-------------------|
| Hazard Assessment | Field Expertise | Cliff's knowledge + AI assistance |
| Site Sketch Plans | Manual Creation | CAD integration or upload |
| Location Photos | Site Photography | Mobile app upload |
| Emergency Plan Markup | Google Maps + Manual | API + manual annotation |
| Specific Risk Variations | Site Assessment | Manual override required |

## Technical Implementation Considerations

### Document Generation Options
1. **PDF Form Filling:** Populate existing template (complex layout challenges)
2. **HTML to PDF:** Recreate layout programmatically (formatting control)
3. **Word Template Automation:** Maintain current format (user familiarity)

### Critical Design Decisions Required
1. **Hazard Assessment Interface:** Checkbox grid vs. wizard-style questions
2. **Visual Content Integration:** Upload vs. integrated creation tools
3. **Signature Workflow:** Individual vs. bulk worker processing
4. **Revision Management:** Version control vs. document replacement
5. **Mobile Compatibility:** Field data collection requirements

### Integration Complexity Assessment
| System Integration | Complexity | Priority | Notes |
|-------------------|------------|----------|--------|
| ServiceM8 API | Medium | High | Limited API functionality |
| ConnectTeam API | Low | High | Working well currently |
| Scheduling System | High | Medium | Excel-based, separate project |
| Google Maps API | Low | Medium | Emergency plan automation |
| Digital Signatures | Medium | High | Worker acknowledgment efficiency |

## Automation Workflow Recommendations

### Phase 1 Approach
1. **Template-Based Generation:** Start with job-type templates
2. **ServiceM8 Integration:** Auto-populate basic job information
3. **Manual Override Capability:** Maintain safety compliance flexibility  
4. **Simplified Signature Workflow:** Digital capture for efficiency
5. **Staged Rollout:** Begin with common job types (flooring, etc.)

### Future Enhancement Opportunities
1. **AI-Assisted Hazard Assessment:** Pattern learning from expert selections
2. **Mobile Field Data Collection:** Cliff's iPad concept for quote-stage capture
3. **Integrated CAD Tools:** Site plan creation within system
4. **Advanced Workflow Management:** Multi-stage approval routing
5. **Predictive Equipment Scheduling:** Based on job requirements and availability

---

**Document Analysis Complete**  
**Total Fields Identified:** 150+ individual data points  
**Automation Potential:** ~60% of fields can be automated or semi-automated  
**Critical Dependencies:** Field expertise (Cliff), scheduling system integration, signature workflow design