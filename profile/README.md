<p align="center"><img src="https://raw.githubusercontent.com/go-fem/brand/main/social/go-fem.png" alt="go-fem" width="720"></p>

# go-fem

🌐 **[Website](https://go-fem.github.io)** · 📚 **[Documentation](https://go-fem.github.io/docs/)** · 🗺️ **[Roadmap](https://github.com/go-scikit/roadmap)**

**Finite elements and PDE solvers in pure Go (CGO=0): P1/P2 elements, Poisson, heat and elasticity. Planned, wave 3.**

**Status: planned (wave 3).** This organization holds no library yet: only
its landing, its documentation and its brand. Its scope is finite elements and PDE solvers. The plan is in
[PLAN.md](https://github.com/go-scikit/roadmap/blob/main/PLAN.md), where it is
item 13 of wave 3 (go-geometry meshing and go-fem: P1/P2 elements, Poisson, heat, elasticity, validated by manufactured solutions); its progress is in
[STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md).

## Planned packages

The names are working names; none exists as a repository yet.

| Package | Status | What it will provide |
|---------|--------|----------------------|
| §fem§ | planned (wave 3), no repository yet | Lagrange finite elements, quadrature, assembly, boundary conditions and the first PDE solvers. |
| §mms§ | planned (wave 3), no repository yet | The shared method-of-manufactured-solutions convergence harness. |

## Repositories

| Repo | What it is |
|------|------------|
| [**docs**](https://github.com/go-fem/docs) | the documentation site (Hugo + Hextra), served at [/docs/](https://go-fem.github.io/docs/) |
| [**go-fem.github.io**](https://github.com/go-fem/go-fem.github.io) | the landing page (Hugo) |
| [**brand**](https://github.com/go-fem/brand) | logo, icons and social images |

Every package will be pure Go (CGO=0), tested on the architectures the fleet's
CI covers, and validated against the reference tool of its domain.
