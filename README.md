# Specs2Action

A mono-repo to turn living Specs into action and market impact. It unifies:
- **Specs** (Renaissance, Professional, Foresight)
- **VCA System** (Visión–Causa–Acción): daily distillation and execution
- **Outputs**: posts, pitches, and artifacts
- **Ops**: backlog, rituals, and governance

## Why
Bridge **vision** and **ground**: beauty + clarity + verifiability.

## Structure
```
specs/              # Source of truth for your Specs
  renaissance/      # Spec Renaissance (ex Vital)
  professional/     # Spec Profesional y de Negocios
  foresight/        # Spec Foresight / Futurológico
vca/                # VCA templates + daily entries
outputs/            # Public-facing artifacts (LinkedIn posts, 1-pagers)
ops/                # Backlog, rituals, project notes
.github/ISSUE_TEMPLATE/  # Templates for issues
```

## Rituals
- **Daily**: 15' *VCA Reflection* + 60' *VCA Acción*
- **Weekly**: choose 1 VCA to publish/convert into a concrete deliverable
- **Rule**: *Sin VCA, no hay publicación ni proyecto*

## Getting Started
1. Fill `vca/TEMPLATE_VCA.md` and create your first entry in `vca/VCA.md`.
2. Place your current Specs in `specs/*/current/` and tag `v1.0-M1` when DoD is met.
3. Use Issue templates to create actionable items from VCA entries.
