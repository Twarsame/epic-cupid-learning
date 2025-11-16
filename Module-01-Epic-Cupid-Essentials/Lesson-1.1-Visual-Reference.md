# Lesson 1.1: Standard Cardiology Procedure Workflow

## Overview
This diagram illustrates the complete workflow for a standard cardiology procedure in an Epic Cupid environment, from initial order placement through downstream clinical impact.

## Workflow Diagram

```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#2E86AB','primaryTextColor':'#fff','primaryBorderColor':'#1a4d6d','lineColor':'#2d3748','secondaryColor':'#06A77D','tertiaryColor':'#F77F00','fontFamily':'Arial, sans-serif','fontSize':'16px'}}}%%
flowchart TD
    A["<b>1. ORDER PLACEMENT</b><br/>Clinician orders procedure in EHR system"] --> B["<b>2. ORDER ROUTING</b><br/>Order flows into EHR module and appears on scheduling worklists"]
    B --> C["<b>3. SCHEDULING</b><br/>Scheduler books appointment using EHR module"]
    C --> D["<b>4. PRE-PROCEDURE</b><br/>Patient demographics, clinical indication, and relevant history auto-populate"]
    D --> E["<b>5. PROCEDURE PERFORMANCE</b><br/>Sonographer performs exam; images acquired by modality equipment"]
    E --> F["<b>6. IMAGE TRANSFER</b><br/>Images sent to PACS via DICOM; EHR module links to these images"]
    F --> G["<b>7. INTERPRETATION</b><br/>Cardiologist views images via PACS integration, documents findings using structured templates"]
    G --> H["<b>8. REPORT FINALIZATION</b><br/>Cardiologist signs report in EHR module"]
    H --> I["<b>9. RESULT DISTRIBUTION</b><br/>Signed report automatically routes to ordering provider's inbox and patient's chart"]
    I --> J["<b>10. DOWNSTREAM IMPACT</b><br/>Results update problem lists, trigger clinical decision support, appear in EHR patient portal"]
    
    linkStyle default stroke:#2d3748,stroke-width:3px
    
    style A fill:#2E86AB,stroke:#1a4d6d,stroke-width:4px,color:#fff
    style B fill:#3D9CB8,stroke:#2b7a8f,stroke-width:4px,color:#fff
    style C fill:#4DB2C5,stroke:#3c8fa0,stroke-width:4px,color:#fff
    style D fill:#06A77D,stroke:#058565,stroke-width:4px,color:#fff
    style E fill:#05C793,stroke:#04a078,stroke-width:4px,color:#fff
    style F fill:#00D9A8,stroke:#00b58d,stroke-width:4px,color:#fff
    style G fill:#F77F00,stroke:#c56600,stroke-width:4px,color:#fff
    style H fill:#FCBF49,stroke:#ca9937,stroke-width:4px,color:#000
    style I fill:#EAE2B7,stroke:#bbb692,stroke-width:4px,color:#000
    style J fill:#D62828,stroke:#ab2020,stroke-width:4px,color:#fff
```

*Disclaimer: Not official Epic schematics. Created by Tahlil A. Warsame*















