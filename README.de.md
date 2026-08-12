# Whitepaper Labs - KI-Gedaechtnis & Kontextforschung

**Whitepaper Labs** ist ein oeffentliches Forschungs-Repository fuer konzeptionelle Architekturen, technische Whitepaper und Experimente rund um persistentes Gedaechtnis, kontextuelle Relevanz und Long-Horizon-AI-Agenten.

## Aktuelles Whitepaper

### Metadata-Driven Memory Control for Long-Horizon AI Agents - v1.0

Das Paper beschreibt eine **metadata-first Memory Control Plane**. Semantische Interpretation soll vor allem dann stattfinden, wenn sich ein Memory-Zustand veraendert. Danach steuern persistente Metadaten - unter anderem Tags, Gewichte, Persistenzklassen, Trigger, Polling, Lifecycle-State, Provenance und Relationen - die laufende Relevanz moeglichst guenstig. Vollstaendige Memories werden erst reaktiviert, wenn diese Kontrollschicht einen Anlass erkennt.

Der Ansatz wird gegen verwandte Arbeiten wie MemGPT, CoALA, MemoryBank, Memory-R1, SwiftMem, MemOS, RecMem, proaktive Memory-Systeme, temporale Memory-Architekturen und Long-Horizon-Benchmarks abgegrenzt. Aussagen zu Effizienz und Recall bleiben ausdruecklich Hypothesen, bis sie empirisch getestet wurden.

- [v1.0 als Markdown lesen](papers/metadata-driven-memory-control-v1.0.md)
- [v1.0 als PDF herunterladen](papers/metadata-driven-memory-control-v1.0.pdf)

## Fruehere Whitepaper

- **Polling-Based Flagging System for Context Relevance in AI Memory Development** - strukturierte Relevanzbewertung und proaktives kontextuelles Flagging.
- **Memory Management & Personality Layering in AI Systems** - geschichtete persistente Memory-Strukturen fuer Nutzer-, Projekt- und Kontinuitaetszustand.

Die bisherigen PDFs bleiben unter [`papers/`](papers/) erhalten.

## Forschungsziele

- Praktische Architekturen fuer Langzeit-Memory in KI-Systemen untersuchen.
- Memory-Speicherung von Relevanz- und Steuerungsentscheidungen trennen.
- Alte, aber objektiv wichtige Informationen verlaesslicher reaktivieren.
- Wiederholte teure semantische Verarbeitung reduzieren.
- Transparente Lifecycle-, Persistenz-, Trigger- und Konfliktmechanismen entwickeln.
- Benchmarks und Evaluationskriterien vorschlagen, ohne ungetestete Performance-Claims als erwiesen darzustellen.

## Status

Dieses Repository enthaelt unabhaengige konzeptionelle Forschung. Die aktuelle metadata-driven Architektur ist ein **technischer Vorschlag** und kein Nachweis experimentell bestaetigter Performance oder patentrechtlicher Freedom-to-Operate.

## Autor und KI-Unterstuetzung

**Marco Rapp** - Autor / Independent Researcher

Recherche, Literaturreview, Strukturierung und redaktionelle Ausarbeitung wurden mit **ChatGPT von OpenAI** unterstuetzt. Diese KI-Unterstuetzung wird transparent offengelegt und nicht als eigenstaendige wissenschaftliche Autorenschaft dargestellt.

## Zitation

Eine maschinenlesbare Repository-Zitation liegt in [`CITATION.cff`](CITATION.cff).

---

[English version](README.md)
