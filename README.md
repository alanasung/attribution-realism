<p align="center">
  <h1 align="center">When Data Attribution Breaks Outside Toy Settings</h1>
  <p align="center"><strong>Measure where influence-style attribution degrades as data and model settings become more realistic.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **When Data Attribution Breaks Outside Toy Settings**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Measure where influence-style attribution degrades as data and model settings become more realistic.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
