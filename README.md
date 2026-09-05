## Jonathan Sánchez — Backend Lead & Engineering Manager

I lead an 8-person engineering team and design the backends we ship, mostly in Python.
What interests me is software that is still cheap to change in year three: the domain before
the framework, explicit API contracts, and a test suite you trust enough to deploy on a Friday.

### How I work

- **API-first** — the OpenAPI contract is hand-written and is the source of truth. The typed
  client and the mocks are generated from it, never the other way round.
- **Domain before framework** — structure by domain and layer, ports and adapters, the ORM
  confined to the repository layer and kept there by an import linter rather than by good intentions.
- **Tests are part of the design** — unit tests with doubles, integration against a real
  Postgres (testcontainers, never a mocked database), E2E as the merge gate.
- **Quality measured, not asserted** — a quality gate in CI, and Sonar at zero before merging.

### Projects

| Project | What it is |
| --- | --- |
| **[engineering-notes](https://github.com/jonaas-dev/engineering-notes)** | A reading notebook on engineering and technical leadership, kept since 2023: architecture, code quality, backend, delivery and career. 63 notes, consolidated from eight separate repositories. |

Most of what I work on is private — a client's product, or my own not yet ready to show.
This list grows as that changes rather than being padded to look longer.

### Stack

Python · FastAPI · SQLAlchemy 2 · PostgreSQL · Redis · Docker · TypeScript · Angular

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/jonathan-sanchez-peiris/) · [jonas-blog.es](https://jonas-blog.es/)
