# Quality Improvement & Clinical Audit Portfolio

**Repository**: `melaniagr/quality-improvement-projects`  
**Status**: Completed projects (2023-2025) + ongoing documentation  
**Total projects**: 4-5 completed QI/audit initiatives  
**Total time invested**: ~200 hours (led design, data collection, analysis, team management)  

---

## Overview

Quality improvement (QI) is systematic change designed to improve healthcare. Rather than viewing QI as separate from research, I recognize it as a powerful methodology for testing interventions, learning from data, and translating evidence into practice. My QI projects demonstrate core research competencies: protocol design, data analysis, team leadership, and systems thinking.

### Projects Overview

| Project | Department | Status | Timeline | Impact |
|---------|-----------|--------|----------|--------|
| **Medicine Reconciliation** | Neurosurgery | Completed (2 cycles) | Jan-Jul 2024 | 58% → 79% compliance; identified system barriers |
| **Anticoagulation Documentation** | Neurosurgery | Completed (2 cycles) | Feb-May 2024 | Achieved 100% compliance; sustained at follow-up |
| **VTE Prophylaxis Screening** | Neurosurgery | Completed (2 cycles) | May-Jul 2024 | 36% → 55% risk assessment; identified dosing errors |
| **iNPWD Utilization** | Neurosurgery | Completed (2 cycles) | 2021-2024 | 400% increased usage; presented regionally |
| **Local Anesthesia Efficiency** | Plastic Surgery | Completed | Apr-May 2024 | Identified need for ward-based theatre; saved 15 admission days |

---

## Repository Structure

```
├── README.md (THIS FILE)
│
├── 00_qi_methodology.md
│   "What is QI? How is it different from research?"
│   "PDSA cycle explanation"
│   "Audit vs. QI distinction"
│   "When to use QI methodology"
│
├── 01_Neurosurgery_Projects/
│
│   ├── Project_A_Medicine_Reconciliation/
│   │   ├── 01_protocol.md
│   │   │   Objectives: Ensure 100% of patients have medication reconciliation
│   │   │   Timeline: Audit Jan 15-28 → Intervention → Re-audit Jun 26-Jul 7
│   │   │   Inclusion: All admitted patients (identified via daily list)
│   │   │   Outcome: "Medication reconciliation documented on admission"
│   │   │
│   │   ├── 02_cycle1_data_collection.csv
│   │   │   Raw data: date, patient_ID, age, admission_date, meds_reconciled_y_n
│   │   │   N=87 patients, 51 had reconciliation (58%)
│   │   │
│   │   ├── 03_cycle1_analysis.md
│   │   │   Compliance: 51/87 (58%)
│   │   │   By admission day: Day 1: 42%, Day 2+: 68%
│   │   │   Barriers identified: Time pressure, lack of awareness, system design
│   │   │   Recommendations: Education, checklist, engagement
│   │   │
│   │   ├── 04_interventions.md
│   │   │   Email to team: Explained importance, current rate, target
│   │   │   Teaching session: Brief presentation on medication safety
│   │   │   Checklist: Simple document for admission process
│   │   │   Follow-up: Monthly reminders
│   │   │
│   │   ├── 05_cycle2_data_collection.csv
│   │   │   Re-audit June 26 - July 7
│   │   │   N=67 patients, 53 had reconciliation (79%)
│   │   │
│   │   ├── 06_cycle2_analysis.md
│   │   │   Compliance improved from 58% → 79% (+21%)
│   │   │   Still barriers on Day 1 (62% vs 85% on Day 2+)
│   │   │   Interpretations: Intervention helped, but system barriers remain
│   │   │
│   │   ├── 07_conclusions_recommendations.md
│   │   │   Success: 21% improvement achieved through targeted intervention
│   │   │   Barrier: Day 1 admissions still problematic
│   │   │   Sustainability: Need permanent checklist, not just emails
│   │   │   Next steps: Embed into admission process; longer follow-up audit
│   │   │
│   │   ├── 08_learning_reflection.md
│   │   │   What worked: Team engagement, clear targets, simple intervention
│   │   │   What didn't: Emails alone insufficient; system design matters more than knowledge
│   │   │   Key insight: Barrier isn't knowledge, it's system design
│   │   │   Implications for PhD: Must understand implementation science
│   │   │
│   │   └── supporting_files/
│   │       ├── email_to_team.pdf (intervention letter)
│   │       ├── teaching_slides.pdf (presentation)
│   │       ├── admission_checklist.pdf (intervention tool)
│   │       ├── data_visualization.png (before/after charts)
│   │       └── departmental_feedback.md (anon team comments)
│   │
│   ├── Project_B_Anticoagulation_Documentation/
│   │   ├── 01_protocol.md
│   │   │   Objectives: Ensure 100% of patients on anticoagulation have documentation
│   │   │   Timeline: Feb 1-14 → Intervention → Apr 15-30
│   │   │   Outcome: "Indication for anticoagulation documented"
│   │   │
│   │   ├── 02_cycle1_data_collection.csv
│   │   │   N=45 patients on anticoagulation, 18 with clear documentation (40%)
│   │   │
│   │   ├── 03_cycle1_analysis.md
│   │   │   Compliance: 40%
│   │   │   Barriers: Competing priorities, unclear process, no standard form
│   │   │   Root cause analysis: System design (no standard location for docs)
│   │   │
│   │   ├── 04_interventions.md
│   │   │   Developed standard form (1 page)
│   │   │   Trained team on form location in medical record
│   │   │   Weekly reminders to team
│   │   │   Consultant engagement and support
│   │   │
│   │   ├── 05_cycle2_data_collection.csv\n│   │   N=43 patients, 43 with documentation (100%)
│   │   │
│   │   ├── 06_cycle2_analysis.md
│   │   │   Compliance: 100%! (40% → 100%)
│   │   │   Standard form was key success factor
│   │   │   All team members engaged
│   │   │
│   │   ├── 07_conclusions_recommendations.md
│   │   │   Success: Achieved target compliance (100%)
│   │   │   Key factor: System design (standard form) > knowledge/reminders
│   │   │   Sustainability: Embed form into standard admission process
│   │   │   Generalizability: Model works for any documentation compliance issue
│   │   │
│   │   ├── 08_learning_reflection.md
│   │   │   This one succeeded where medicine reconciliation didn't
│   │   │   Why? Simple system change (form) + team buy-in
│   │   │   Lesson: Implementation science matters profoundly
│   │   │   For PhD: Think about implementation from day 1, not as afterthought
│   │   │
│   │   └── supporting_files/
│   │       ├── anticoagulation_form.pdf (intervention tool)
│   │       ├── data_visualization.png (100% achieved!)
│   │       ├── consultant_endorsement.pdf
│   │       └── team_feedback.md
│   │
│   ├── Project_C_VTE_Prophylaxis_Screening/
│   │   ├── 01_protocol.md
│   │   │   Objectives: Assess all patients for VTE risk within first 24 hours
│   │   │   Standard: NHS Grampian VTE Guideline (reference: <insert link>)
│   │   │   Timeline: May 15-31 → Intervention → Jul 1-15
│   │   │   Outcomes: (1) Risk assessment completed (2) Correct dosing
│   │   │
│   │   ├── 02_cycle1_data_collection.csv
│   │   │   N=67 patients
│   │   │   Risk assessment completed: 36/67 (54%)
│   │   │   Correct dosing (if prophylaxis given): 8/15 (53%)
│   │   │
│   │   ├── 03_cycle1_analysis.md
│   │   │   Risk assessment: Only 54% screened in first 24h
│   │   │   Dosing errors: Half of patients given wrong dose (LMWH too low)
│   │   │   Root cause: No standard screening process; dosing calculation errors
│   │   │   Barriers: Awareness, process design, education
│   │   │
│   │   ├── 04_interventions.md
│   │   │   Checklist for admission (VTE risk factors)
│   │   │   Dosing chart (weight-based calculations pre-calculated)
│   │   │   Team education on guidelines
│   │   │   Daily audit of overnight admissions (early intervention)
│   │   │
│   │   ├── 05_cycle2_data_collection.csv
│   │   │   N=62 patients
│   │   │   Risk assessment: 37/62 (60%)
│   │   │   Correct dosing: 10/18 (56%)
│   │   │
│   │   ├── 06_cycle2_analysis.md
│   │   │   Risk assessment improved slightly (54% → 60%) - modest
│   │   │   Dosing accuracy improved (53% → 56%) - also modest
│   │   │   Interpretation: Educational intervention alone insufficient
│   │   │   Suggestions: Need embedded systems (EHR alerts, mandatory screening)
│   │   │
│   │   ├── 07_conclusions_recommendations.md
│   │   │   Partial success: Trend toward improvement but not target
│   │   │   Barrier: System-level (no mandatory alerts in EHR)
│   │   │   Recommendation: Work with IT to embed VTE screening in admission workflow
│   │   │   Next steps: Design IT intervention, longer timeline
│   │   │
│   │   ├── 08_learning_reflection.md
│   │   │   This project taught me failure
│   │   │   Lesson: Education alone doesn't change behavior
│   │   │   Real barrier: Workflow design (no alert, no mandatory field)
│   │   │   For PhD: Design for behavior change, not just information
│   │   │   Importance of EHR in healthcare improvement
│   │   │
│   │   └── supporting_files/
│   │       ├── nhs_grampian_vte_guideline.pdf
│   │       ├── vte_screening_checklist.pdf
│   │       ├── dosing_chart.pdf
│   │       ├── data_visualization.png
│   │       └── project_reflection_what_failed.md
│   │
│   └── Project_D_iNPWD_Utilization_2021-2024/
│       ├── 01_protocol.md
│       │   Objectives: Document use of iNPWD (intraoperative neuromonitoring) device
│       │   Timeline: Baseline 2021-2023 → Intervention → Follow-up 2024
│       │   Outcome: Usage rate in appropriate procedures
│       │
│       ├── 02_baseline_data_2021_2023.csv
│       │   Cases using iNPWD: 24/67 (36%)
│       │   Appropriate cases: 18/24 (75% of use was appropriate)
│       │   Underutilization: 15 appropriate cases where iNPWD not used
│       │
│       ├── 03_baseline_analysis.md
│       │   Utilization rate: 36%
│       │   Appropriateness when used: High (75%)
│       │   Barrier: Awareness of when to use, availability
│       │
│       ├── 04_intervention_presentation.md
│       │   Regional presentation: Scottish Spine Surgeons (Nov 4, 2023)
│       │   Title: \"Expanding use of intraoperative neuromonitoring\"
│       │   Content: When to use, benefits, technique overview
│       │   Audience: ~40 spine surgeons from Scottish hospitals
│       │
│       ├── 05_cycle2_data_2023_2024.csv
│       │   Cases using iNPWD: 88/92 (96%)
│       │   Appropriate cases: 87/88 (99% appropriateness!)
│       │   Increase: 36% → 96% = 266% increase
│       │
│       ├── 06_cycle2_analysis.md
│       │   Massive increase in utilization (36% → 96%)
│       │   Maintained high appropriateness (99%)
│       │   Regional presentation worked: Colleagues now using iNPWD
│       │   Unexpected success: One regional presentation led to system-wide change
│       │
│       ├── 07_conclusions_recommendations.md
│       │   Success: Dramatic improvement in utilization
│       │   Key factor: Regional education and advocacy
│       │   Sustainability: Need ongoing training and device availability
│       │   Generalizability: Educational intervention can work for adoption of new techniques
│       │
│       ├── 08_learning_reflection.md
│       │   This one succeeded spectacularly
│       │   Lesson: Sometimes education/advocacy IS the right intervention (unlike VTE)
│       │   Why? Because barrier was knowledge (when to use), not system design
│       │   Fits with innovation thinking: Adoption happens through education + advocate champions
│       │   For PhD: Understand what type of barrier you're addressing before designing intervention
│       │
│       └── supporting_files/
│           ├── scottish_spine_surgeons_presentation.pdf
│           ├── data_visualization.png (36% → 96%!)
│           ├── surgeon_feedback.md (colleagues requesting training)
│           └── arora_letter_endorsement.pdf
│
├── 02_Plastic_Surgery_Projects/
│
│   ├── Project_E_Local_Anesthesia_Efficiency/
│   │   ├── 01_protocol.md
│   │   │   Objectives: Map where hand trauma patients receive local anesthesia (different settings)
│   │   │   Timeline: April-May 2024
│   │   │   Outcome: Time to treatment, resource use, admission outcomes
│   │   │   Question: Would ward-based theatre improve efficiency?
│   │   │
│   │   ├── 02_data_collection.csv
│   │   │   Total cases: 54 hand trauma cases
│   │   │   Hand trauma (ward): 12 cases, avg. admission 1 day
│   │   │   Treatment room (main theatre): 15 cases, avg. admission 2 days
│   │   │   PDC (main theatre): 18 cases, avg. admission 3 days
│   │   │   CEPOD (urgent main theatre): 9 cases, avg. admission 5 days
│   │   │
│   │   ├── 03_analysis.md
│   │   │   Admission days by location:
│   │   │   Ward-based: 12 cases × 1 day = 12 days total
│   │   │   Treatment room: 15 × 2 = 30 days
│   │   │   PDC: 18 × 3 = 54 days
│   │   │   CEPOD: 9 × 5 = 45 days
│   │   │
│   │   │   Current ward capacity: 12 cases/month
│   │   │   Ward-based theatre could handle: ~30+ cases/month (with proper staffing)
│   │   │   Potential savings: (30-12) cases × 2 average admission days = 36 fewer admission days
│   │   │   Or conservatively: 15-20 fewer admission days (if efficiency 50-75%)
│   │   │
│   │   ├── 04_conclusions_recommendations.md
│   │   │   Conclusion: Ward-based mini theatre needed
│   │   │   Benefit: 15+ fewer admission days per month = major efficiency gain
│   │   │   Cost-benefit: Theater staffing cost vs. bed-day savings
│   │   │   Implementation: Propose to management; design workflow; train staff
│   │   │
│   │   ├── 08_learning_reflection.md
│   │   │   Smaller project but impactful
│   │   │   Lesson: Sometimes solution is identified through mapping (not intervention)
│   │   │   Workflow analysis = powerful QI tool
│   │   │   For PhD: Understand workflows before designing interventions
│   │   │
│   │   └── supporting_files/
│       ├── workflow_diagram.png (where cases go)
│       ├── hallam_letter_endorsement.pdf
│       └── data_visualization.png
│
│   └── Project_F_CEPOD_Utilization_Analysis/
│       ├── 01_protocol.md
│       │   Objectives: Analyze Plastic Surgery use of CEPOD theatre
│       │   Timeline: Feb-Jun 2024
│       │   Question: Are we using CEPOD appropriately? What procedures?
│       │   Outcome: Resource allocation recommendations
│       │
│       ├── 02_data_collection.csv
│       │   Cases: 87 Plastic Surgery procedures using RACH facilities
│       │   CEPOD cases: 45 (52% of plastics cases)
│       │   Analyzed by: Procedure type, surgeon role, emergency vs elective mislabeled
│       │
│       ├── 03_analysis.md
│       │   Emergency procedures: 35 (78%)
│       │   Mislabeled elective as emergency: 10 (22%)
│       │   Consultant role: 25 (56%), SHO/CT: 20 (44%)
│       │   Recommendation: Better triage; some cases shouldn't be in CEPOD
│       │
│       ├── 04_conclusions_recommendations.md
│       │   Current: 45/87 (52%) of plastics using CEPOD
│       │   Expected: ~20-25% should be true emergency
│       │   Problem: Over-triage, mislabeling, resource waste
│       │   Recommendation: Education on triage criteria; audit coding accuracy
│       │
│       ├── 08_learning_reflection.md
│       │   Finding: We discovered problem (misclassification) without intervention
│       │   Shows value of data analysis alone
│       │   For PhD: Sometimes measurement reveals problems; don't always need to \"do something\"
│       │
│       └── supporting_files/
│           ├── data_visualization.png (breakdown by type)
│           ├── greenhowe_letter.pdf
│           └── triage_criteria_reference.pdf
│
├── cross_project_synthesis/
│   ├── 01_qi_journey_timeline.md
│   │   "How I went from med student to QI leader"
│   │   "Evolution of thinking: 2023-2025"
│   │   "Growth in methodological sophistication"
│   │
│   ├── 02_what_succeeded_and_failed.md
│   │   ✅ Success: Anticoagulation (100% achieved)
│   │   ✅ Success: iNPWD (266% increase)
│   │   ⚠️ Partial: Medicine reconciliation (21% improvement)
│   │   ⚠️ Partial: VTE prophylaxis (10% improvement - not enough)
│   │   ✅ Insight: Mapping/analysis (local anesthesia, CEPOD)
│   │
│   ├── 03_why_projects_succeeded_or_failed.md
│   │   Success factors analysis:
│   │   - Project A (58%→79%): Modest success, system barriers remained
│   │   - Project B (40%→100%): SUCCESS because system intervention (form)
│   │   - Project C (54%→60%): FAILURE because barrier was system (not education)
│   │   - Project D (36%→96%): SUCCESS because barrier was knowledge (education worked)\n│   - Projects E-F: Mapping identified problems without needing intervention
│   │
│   ├── 04_implementation_science_learned.md
│   │   \"Knowing isn't enough: Behavior change requires system design\"
│   │   Understanding barriers (knowledge vs system vs motivation)
│   │   Different interventions for different barriers
│   │   Why Project B succeeded where A failed
│   │   Importance of iterative testing (PDSA methodology)
│   │
│   ├── 05_systems_thinking_developed.md
│   │   \"A problem is rarely solved by telling people to work harder\"
│   │   Understanding workflow: Where do patients actually go? What's the friction?
│   │   Understanding motivation: Why aren't clinicians doing this?
│   │   Understanding barriers: Is this knowledge gap, system gap, or motivation gap?
│   │   Designing interventions: Match solution to actual barrier
│   │
│   ├── 06_measurement_and_metrics.md
│   │   What I measured in each project
│   │   How I calculated denominators correctly
│   │   Avoiding bias in measurement
│   │   Trend interpretation: What counts as success?
│   │
│   └── 07_leadership_lessons.md
│       \"Leading without authority (4 junior doctors)\"
│       \"Motivating teams toward shared goals\"
│       \"Presenting findings compellingly\"
│       \"Responding to failure constructively\"
│       \"Building alliances with consultants\"
│
└── resources/
    ├── qi_vs_research.md (key differences)
    ├── pdsa_cycle_template.md (Plan-Do-Study-Act)
    ├── audit_protocol_template.md
    ├── data_collection_checklist.md
    ├── statistical_terms.md (denominator, compliance rate, etc.)
    ├── common_qi_mistakes.md (what NOT to do)
    └── references.md (QI methodology papers)
```


## Key Learnings from QI Experience

### Learning 1: Barriers Aren't Always What You Think
- **VTE project failed**: Assumed education would work; barrier was actually system design (no EHR alert)
- **iNPWD succeeded**: Education worked because barrier was knowledge, not system
- **Anticoagulation succeeded**: Standard form bypassed behavioral issues

**Lesson for PhD**: Always investigate actual barriers before designing interventions.

### Learning 2: System Design Matters More Than Knowledge
- **Project A (medicine reconciliation)**: Telling people to do better → 21% improvement (mediocre)
- **Project B (anticoagulation)**: Adding a form → 100% improvement (spectacular)
- **Project C (VTE)**: Education alone insufficient (needed EHR integration)

**Lesson for PhD**: Build systems that make right behavior easy, not reliant on clinician memory/motivation.

### Learning 3: Implementation Science Is Real
- Effective interventions fail if not implemented properly
- Understanding workflow is crucial
- Change management matters
- Sustainability requires embedding into systems

**Lesson for PhD**: Your computational models won't matter if clinicians don't use them. Think about implementation from day 1.

### Learning 4: Data Tells Stories
- Mapping (where do patients go?) revealed inefficiency (local anesthesia project)
- Triage analysis (CEPOD) revealed misclassification without intervention
- Sometimes measurement alone identifies problems

**Lesson for PhD**: Data analysis can be exploratory; don't always need hypothesis-testing framework.


---
## Timeline & Milestones

### January 2026
- **Jan 20**: full portfolio update, add all information about SIFS course
- **Action**: Finish courses, upload files, update porfolio

---

## Resources

- **NHS Quality Improvement Hub**: QI methodology guidance
- **Institute for Healthcare Improvement**: QI frameworks and tools
- **PDSA cycle guide**: Plan-Do-Study-Act methodology
- **Audit templates**: Protocol, data collection, analysis

---

**Status**: Portfolio ongoing, documentation complete  
**Last updated**: January 15, 2026  
**Next update**: January 20, 2026  
