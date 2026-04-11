# Pipe Bending App — AI-Assisted Development

## Purpose

Deterministic pipe calculation tool for field use.
Geometry engine calculates marks and cut length consistently.
Safety layer prevents common human measurement and tool errors.
System is execution-driven and must preserve physical correctness.
Only `index.html` and `README.md` are public deployment files.

## Files

- `todo.md`: implementation source of truth for the current release.
- `CLAUDE.md`: AI execution constraints — priority order, geometry rules, output rules.
- `index.html`: single-file app implementation.

### v0.5.5
- `v0.5.5.rules.md`: hard behavior rules (physical correctness, warning hierarchy, rounding).

### v0.5.6
- `v0.5.6.md`: full design document — Simple/Advanced Mode + Visual Instick.
- `v0.5.6.rules.md`: behavior rules for UI mode logic and instick visualization.

## How to prompt Claude

- `Implement ONLY S-böj from todo.md. Output only code.`
- `Implement ONLY Takoffset warning persistence from todo.md. No redesign.`
- `Implement ONLY requested section from todo.md. If unclear, ask first.`