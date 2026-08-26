# P5 System and Process Models

This repository collects the visual models supporting the [P5 Governed Agentic RCM Intelligence case study](https://github.com/AmrThabetA/p5-agentic-rcm-intelligence).

> **Status:** Draft/pre-baseline portfolio evidence. The models describe a synthetic-data product concept and do not represent stakeholder approval, UAT acceptance, or production readiness.

[View the P5 UI design in Figma](https://www.figma.com/design/SqbwqJfu9AD5mTz3aHrRzs/P5-UI-Design?node-id=0-1&p=f) · [Browse the BA documentation library](https://github.com/AmrThabetA/p5-agentic-rcm-intelligence/blob/main/docs/documentation-library.md)

## UML model catalogue

| ID | Model | Type | Rendering |
|---|---|---|---|
| UML-02 | System context and component view | Structured component-style view; see notation caveat | [PNG](uml/UML-02_system_context_component.png) |
| UML-03 | Executive question | Sequence diagram | [PNG](uml/UML-03_executive_question_sequence.png) |
| UML-04 | Denial investigation and appeal | Sequence diagram | [PNG](uml/UML-04_denial_appeal_sequence.png) |
| UML-05 | Data onboarding | Sequence diagram | [PNG](uml/UML-05_data_onboarding_sequence.png) |
| UML-06 | Audit and compliance | Sequence diagram | [PNG](uml/UML-06_audit_compliance_sequence.png) |
| UML-07 | Core domain model | Class diagram | [PNG](uml/UML-07_core_domain_class_model.png) |
| UML-08 | Appeal lifecycle | State machine | [PNG](uml/UML-08_appeal_state_machine.png) |
| UML-09 | Data-generation lifecycle | State machine | [PNG](uml/UML-09_data_generation_state_machine.png) |

UML-02 uses a structured Mermaid flowchart because Mermaid does not provide formal UML component-diagram notation. The other listed models use Mermaid-supported UML diagram types.

UML-01, the use-case diagram, is embedded in Confluence as a draw.io object and is not included in this first public export. Its editable `.drawio.xml` source or an SVG/PDF export should be added before the catalogue is treated as complete.

## Process maps

| Model | Purpose | File |
|---|---|---|
| Current-state RCM process | Documents the assumed manual denial, appeal, and executive-reporting flow | [PDF](process/P5-current-state-process-map.pdf) |
| Future-state P5 process | Shows the intended P5-enabled denial, insight, and audit flow | [PDF](process/P5-future-state-process-map.pdf) |

These are conceptual process maps created in Miro. They are **not formal BPMN 2.0 models** and do not yet define pools, lanes, message flows, standard events, or validated responsibility boundaries. The written process statuses in the BA documentation remain authoritative.

## Source and review rule

The images in this repository are review renderings. Editable Mermaid, draw.io, Miro, or BPMN source files should remain the authoritative versions whenever they are available. Changes should be made in the source and then re-exported to prevent drift.

Preferred future additions:

- UML-01 as `.drawio.xml` plus SVG or PNG
- UML-02 to UML-09 as `.mmd` source files
- Formal BPMN models as `.bpmn` or editable draw.io XML, plus PDF/SVG renderings

PNG screenshots are acceptable as a fallback, but editable source files are more useful for review and version control.
