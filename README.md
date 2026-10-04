# handlab-hardware

Physical build material for the tendon-driven claw hands controlled by
[handlab](https://github.com/michiqn/handlab) (the software: control center + MuJoCo digital twin).

> **Work in progress.** This repo was split out of handlab; content is being restructured.

## Contents

| Folder | What |
|--------|------|
| `photos/` | build and tendon-routing photos (metadata stripped) |
| `cad/` | CAD sources (local only for now; see `.gitignore`) |

## TODO

- [ ] Printable parts (STL/3MF) + print settings
- [ ] Bill of materials (Dynamixel XL330 servos, U2D2, tendon, bearings, fasteners)
- [ ] Assembly + tendon-routing guide
- [ ] Wiring (servo IDs per finger, see `handlab/builds/*.yaml` in the software repo)
- [ ] License (not chosen yet)

## Credits

- **CRAFT hand** (Lin, Patel, Moon, Lazebnik, Jain — UIUC / UC Irvine, MIT) — the finger models.
  Paper: [arXiv:2603.12120](https://arxiv.org/abs/2603.12120) · code/CAD: <https://github.com/craft-hand>
- **ORCA Hand** by ORCA Dexterity, Inc. (ETH Zürich Soft Robotics Lab) — CC BY 4.0 — the
  ratchet-spool tendon tensioning idea. <https://github.com/orcahand/orcahand_hardware>
- Palm and stand: own design.
