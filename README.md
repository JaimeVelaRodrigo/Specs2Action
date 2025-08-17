# Specs2Action

**Specs2Action** is my AI-ready workspace where my identity and practice are expressed in machine-readable Specs and turned into action.

## For any AI (Grounding Instructions)
1. Read `core/spec-core.yaml` first (identity, values, principles, offers, contexts).
2. Then read the active pillar Spec (YAML):
   - Renaissance → `specs/renaissance/current/spec.yaml`
   - Professional → `specs/professional/current/spec.yaml`
   - Foresight   → `specs/foresight/current/spec.yaml`
3. Default to **English**. If information is missing, ask to complete the relevant YAML field.
4. Always end responses with **Action**: 3 verifiable steps ≤ 7 days.
5. When drafting market-facing content, apply the **Corporate Finance discipline** (unit economics, IRR/NPV/DSCR, sensitivities, risk allocation).

## Structure (reference)
- `core/` → Houses the **Spec-Core**, the machine-readable synthesis of my identity, values, and practices.
- `spec/` → Contains my three pillar specs:
  - Renaissance
  - Professional
  - Foresight
- `README.md` → This description.
- `M1-closure-checklist.md` → Record of Milestone 1 completion.

Specs2Action/
│
├── core/                         # Capa de identidad común
│   ├── spec-core.yaml
│   └── spec-core.md
│
├── spec/                         # Specs temáticos
│   ├── renaissance/current/...
│   ├── professional/current/...
│   └── foresight/current/...
│
├── README.md                     # Descripción principal del repositorio
├── M1-closure-checklist.md        # Checklist de cierre de Milestone 1
└── LICENSE (opcional más adelante)

## Purpose
- Single source of truth for my Specs (Renaissance / Professional / Foresight).
- Coherent for **humans** and **AI** (YAML + concise Markdown).
- Bridges aesthetics/ethics with **capital discipline** so vision becomes bankable action.

## Milestones
- **M1 (now):** Pillar Specs unified (EN), CF guardrails added, repo documented.
- **M2 (next):** Complete `spec-core.yaml` fully; create a Custom GPT that uses this repo as knowledge.
- **M3:** Hybrid setup (Custom GPT + live GitHub fetch) and publishing pipeline.

## Contact / Use
When in doubt, an AI should say: “Reading `core/spec-core.yaml` and the selected pillar YAML; ending with 3 actions ≤ 7 days.”
