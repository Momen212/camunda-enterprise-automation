# Camunda Enterprise Automation – Insurance Process

Dieses Repository enthält ein Camunda-Projekt zur Modellierung und Automatisierung eines Versicherungsprozesses. Der Prozess wurde im Rahmen eines Fachprojekts im Bereich **Enterprise Automation** erstellt und kombiniert **BPMN**, **DMN** und Camunda Forms.

## Projektziel

Ziel ist die Abbildung eines Versicherungsprozesses, bei dem Kundenanfragen strukturiert verarbeitet, Risiken automatisch bewertet und bestimmte Entscheidungen über BPMN- und DMN-Modelle unterstützt werden.

## Inhalt

```text
camunda-insurance-process/
├── bpmn/
│   └── insurance_process.bpmn
├── dmn/
│   └── risk_assessment.dmn
├── forms/
│   ├── new_customer_application.form
│   └── employee_document_review.form
|
└── README.md
```

## Features

- Modellierung eines Versicherungsprozesses mit BPMN 2.0
- Risikobewertung mithilfe einer DMN-Entscheidungstabelle
- Erfassung von Kundendaten über Camunda Forms
- Manuelle Prüfung von Unterlagen durch Mitarbeitende
- Prozesslogik für Neukunden, Bestandskunden und Risikoentscheidungen
- Grundlage für Workflow-Automatisierung und Prozessdigitalisierung

## Prozessüberblick

1. Kunde stellt einen Versicherungsantrag.
2. Kundendaten werden erfasst.
3. Bei Neukunden wird das Risiko bewertet.
4. Die Risikobewertung berücksichtigt unter anderem:
   - Alter
   - Raucherstatus
   - relevante Vorerkrankungen
5. Bei moderatem Risiko erfolgt eine manuelle Prüfung.
6. Angenommene Kunden werden in den weiteren Versicherungsprozess überführt.

## Verwendete Technologien

- Camunda Web Modeler / Camunda Modeler
- BPMN 2.0
- DMN
- Camunda Forms
- Workflow Automation
- Enterprise Automation

## Dateien

| Datei | Beschreibung |
|---|---|
| `bpmn/insurance_process.bpmn` | Hauptprozess des Versicherungsworkflows |
| `dmn/risk_assessment.dmn` | Entscheidungstabelle zur Risikobewertung |
| `forms/new_customer_application.form` | Formular zur Erfassung von Kundendaten |
| `forms/employee_document_review.form` | Formular für die manuelle Prüfung durch Mitarbeitende |

## Ausführen / Öffnen

1. Camunda Modeler öffnen.
2. Datei `bpmn/insurance_process.bpmn` importieren.
3. Datei `dmn/risk_assessment.dmn` importieren.
4. Die Formulare aus dem Ordner `forms/` hinzufügen.
5. Prozess validieren und deployen.

## Lernziele

Dieses Projekt zeigt praktische Erfahrung in:

- Prozessmodellierung
- Entscheidungsautomatisierung
- Workflow-Automatisierung
- Business Process Management
- Enterprise Automation
- Modellierung mit BPMN und DMN

