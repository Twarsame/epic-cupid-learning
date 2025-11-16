# Lesson 1.1: What Cupid Is and Is Not

**Module:** 1 - Epic & Cupid Essentials  
**Lesson Completed:** November 16, 2025  
**Status:** ✅ Complete

---

## 🎯 Learning Objectives

By the end of this lesson, I can:
- Define Epic Cupid's primary purpose in cardiovascular care delivery
- Distinguish between Cupid's actual capabilities and common misconceptions
- Identify which cardiovascular workflows Cupid manages
- Explain Cupid's role in the broader Epic ecosystem

---
## 📊 Visual Overview

![Epic Cupid Overview Infographic](assets/lesson-1.1/cupid-is-is-not-infographic.png)
*Figure 1: Comprehensive overview of Epic Cupid capabilities and limitations*


---

## 📖 Key Concepts

### What Cupid **IS**

✅ **Cardiovascular Information System**
- Comprehensive workflow management platform for cardiology services
- Manages orders, scheduling, documentation, and reporting
- Supports multiple subspecialties: echo, cath lab, EP, nuclear, vascular

✅ **Clinical Workflow Engine**
- Streamlines order-to-report processes
- Enables structured data capture at point of care
- Facilitates multidisciplinary team coordination

✅ **Integration Hub**
- Connects with PACS/VNA for image management
- Communicates with modalities via DICOM (MWL/MPPS)
- Shares data seamlessly across Epic modules

✅ **Quality Data Platform**
- Captures discrete elements for NCDR registry reporting
- Supports quality metric tracking and performance improvement
- Enables compliance and accreditation reporting

---

### What Cupid **IS NOT**

❌ **Not a PACS System**
- Does not store DICOM images directly
- Relies on external PACS/VNA for image archiving
- Integrates with viewers but is not a primary image display platform

❌ **Not an Automated Diagnostic Tool**
- Does not replace clinical judgment or physician interpretation
- May display device-generated ECG interpretations but requires physician over-read
- Not a standalone AI diagnostic platform

❌ **Not Cardiology-Department-Only**
- Data accessible across Epic ecosystem to authorized users
- Primary care, emergency, and other departments can view results
- Supports enterprise-wide cardiovascular care coordination

❌ **Not a Billing System**
- While it captures procedure details, it integrates with (not replaces) revenue cycle systems
- Charge capture requires proper configuration and workflow design

---

## 🏥 Supported Cardiovascular Workflows

| Subspecialty | Procedures Managed in Cupid |
|--------------|----------------------------|
| **Non-Invasive Imaging** | TTE, TEE, Stress Echo, Cardiac CT, Cardiac MRI |
| **Nuclear Cardiology** | SPECT, PET, Stress Testing with Imaging |
| **Invasive Procedures** | Cardiac Catheterization, PCI, Structural Heart |
| **Electrophysiology** | EP Studies, Ablations, Device Implants (PPM, ICD, CRT) |
| **Vascular** | Carotid Ultrasound, ABI, Venous Studies |
| **Cardiovascular Diagnostics** | ECG, Holter, Event Monitors, Stress Testing |

---

## 🔄 Cupid's Role in the Epic Ecosystem
![Integration Architecture](assets/lesson-1.1/cupid-integration-architecture.png)
*Figure 2: Epic Cupid integration points with PACS, modalities, and other Epic modules*


```
┌─────────────────────────────────────────────────────┐
│  CLINICAL USERS (via Hyperspace)                    │
│  Cardiologists • Sonographers • Nurses • Schedulers │
└────────────────┬────────────────────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────────────────────┐
│  EPIC CUPID                                         │
│  • Order Management                                 │
│  • Workflow Tracking                                │
│  • Documentation & Reporting                        │
│  • Quality Data Capture                             │
└─────┬─────────────────────────────────────┬─────────┘
      │                                     │
      ▼                                     ▼
┌─────────────────┐              ┌──────────────────┐
│  PACS/VNA       │              │  OTHER EPIC      │
│  • Image Storage│              │  MODULES         │
│  • DICOM        │              │  • Orders        │
│  • Viewers      │              │  • ADT           │
└─────────────────┘              │  • Beaker (Lab)  │
                                 │  • Radiant (Rad) │
                                 └──────────────────┘
```
## 🏥 Supported Cardiovascular Workflows

![Workflow Diagram](assets/lesson-1.1/cupid-workflow-overview.png)
*Figure 3: Order-to-report workflow across cardiovascular subspecialties*
---

## ✅ Knowledge Check Results

**Assessment Date:** November 16, 2025  
**Score:** 8/8 (100%)

### Questions Mastered:
1. ✅ Primary purpose of Epic Cupid
2. ✅ DICOM image storage (False - Cupid does NOT store images)
3. ✅ Cardiovascular procedures managed
4. ✅ NCDR registry relationship
5. ✅ Integration capabilities
6. ✅ What Cupid is NOT designed to do
7. ✅ User groups served
8. ✅ Quality improvement support

---

## 💡 Key Takeaways

1. **Cupid is a workflow platform, not an image archive** - Always integrate with PACS/VNA
2. **Structured data = Quality reporting** - Discrete capture enables NCDR and quality metrics
3. **Team-based platform** - Serves entire cardiovascular care team, not just physicians
4. **Integration is core** - Success depends on proper connectivity with modalities, PACS, and Epic modules

---

## 🔗 Related Resources

- Epic Cupid Product Overview (Official Documentation)
- NCDR Registry Requirements
- DICOM Standards for Cardiovascular Imaging
- Lesson 1.2: Epic Ecosystem Orientation →

---

## 📝 Reflection Notes

**What I found most valuable:**
Understanding that Cupid is a workflow engine, not a diagnostic tool or PACS replacement. This clarifies its role in the broader cardiovascular informatics ecosystem.

**Questions for further exploration:**
- How do different MEA regions configure Cupid differently?
- What are the most common implementation challenges in cardiovascular departments?
- How does Cupid handle multilingual documentation requirements in MEA?

**Next Steps:**
- Complete Lesson 1.2: Epic Ecosystem Orientation
- Explore Chronicles → Clarity → Caboodle data flow
- Research MEA-specific Cupid implementations

---

*Documented by: Tahlil A. Warsame*  
*Last Updated: November 16, 2025*
