<h1 align="center">Thomas Bernecker</h1>
<p align="center">Software-Entwickler — Enterprise-Systeme & autonome Agent-Plattformen</p>

## Aktuell im Fokus

**Cat & Bob** — deterministische Multi-Agent-Plattform für Software-Engineering-Prozesse:
Planung (Cat) und Umsetzung inkl. Test/QA (Bob), getrennt durch ein Risikomodell mit
gestufter Governance-Aufsicht. Python/FastAPI-Backend, React-Frontend, Docker-isolierte
Codeausführung.
→ [github.com/Eangelus/catandbob](https://github.com/Eangelus/catandbob) · Live: [catandbob.de](https://catandbob.de)

**DX12 AI Runtime** — leichtgewichtige Transformer-Inferenz auf DirectX-12-Compute-Shadern
für Windows-Enterprise-Software, ohne Python-, CUDA- oder Cloud-Abhängigkeit zur Laufzeit.
→ [github.com/Eangelus/dx12-ai-runtime-overview](https://github.com/Eangelus/dx12-ai-runtime-overview)

Beide Projektübersichten enthalten je einen konkreten Architektur-Ausschnitt mit Code
und Begründung (Deep Dive), nicht nur Beschreibung.

## Wie ich baue

Deterministisch statt Blackbox: nachvollziehbare Entscheidungswege statt "die KI macht
das schon", Sicherheitsmechanismen als austauschbare, unabhängig testbare Bausteine statt
verwoben mit der Fachlogik, RAII/Guard-Pattern statt defensiver Einzelfall-Checks. Governance
und Testbarkeit sind Design-Entscheidungen von Anfang an, keine nachträgliche Ergänzung.

## Tech-Stack

- **Backend:** Python (FastAPI), C# (.NET 8+, Clean Architecture)
- **Systems/GPU:** C++, DirectX 12 / HLSL Compute Shader
- **Frontend:** React, Vite
- **Daten:** SQL Server, SQLite, Dapper
- **Betrieb:** Docker, GitHub Actions / GitLab CI/CD

## Hintergrund

Hauptberuflich Software-Entwickler bei der **Lindner Group** (Bayern), Schwerpunkt
Enterprise-Systeme: .NET/C#, Clean Architecture, ERP-Integration, Datenbank-Design.

Ein Beispiel aus diesem Umfeld ist **PriceCube** (intern als "Preiswürfel" bekannt), ein
Enterprise-Kalkulationssystem mit ERP-Anbindung — fachlich gegengeprüft, seitdem deutlich
weiter fortgeschritten. Repository ist privat (Arbeitgeber-Projekt, nicht öffentlich einsehbar).

## Kontakt

- [bernecker.thomas@gmx.de](mailto:bernecker.thomas@gmx.de)
- [linkedin.com/in/thomas-bernecker](https://www.linkedin.com/in/thomas-bernecker)
