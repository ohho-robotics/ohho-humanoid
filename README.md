# OhhO Humanoid

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

Concept — not started. The working robot is [OmniBot](https://github.com/ohho-robotics/OmniBot).

This repository is a placeholder for a biped form factor. It does not contain a robot description, controllers, or a simulator.

## Modularity

Every robot class (mobile base, arm, quadruped, drone, humanoid) sits behind one common, pluggable robot interface in Ohho OS, and vendor specifics live only inside their own plugin package. The Booster T2 is the first humanoid adapter, not the only one.

## Support matrix

Booster T2: sim only, not hardware-tested.

| robot | class | sim status | hardware status | last dated run |
| --- | --- | --- | --- | --- |
| Booster T2 | humanoid | in development (simulation only, not released) | not hardware-tested | none published |

A row may change only on public evidence. A sim status may only say "passing" with a link to a public CI run, and a hardware status only with dated footage or a dated test log.

## Clone

```bash
git clone https://github.com/ohho-robotics/ohho-humanoid.git
```

## Roadmap

Nothing in this list is implemented in this repository.

- Robot description
- Simulator launch
- Bringup package

## License

Apache-2.0. See [LICENSE](LICENSE).
