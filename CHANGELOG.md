# Changelog

## 1.0.0

First release.

- Interactive state flow graph for Riverpod (manual and riverpod_generator), Bloc and Cubit (with events and states), Provider, GetX and MobX, plus the widgets that use them.
- Findings: dependency cycles, unhandled Bloc events, states never emitted, family providers never disposed, `ref.read` during build, unused state, Provider models nobody provides, models created in `.value`, GetX controllers nobody registers, MobX stores used without an `Observer`.
- Live mode: one-click observer for Riverpod 2, Riverpod 3, Bloc, GetX and MobX; nodes pulse with update counts and values while debugging.
- CodeLens, sidebar, status bar, Problems panel, Mermaid export, demo graph and a 4-step tour.
