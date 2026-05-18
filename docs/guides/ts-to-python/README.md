# From TS to Python — A Field Guide

A practical, opinionated guide for TypeScript/Node.js developers crossing into Python. Not a language tutorial — a *transition* guide: the runtime mental model first, then a 4-week plan, the tooling translations, the survival syntax, and the gotchas that actually bite JS developers.

## [View the live guide →](https://ivaylo1987.github.io/hands-on-ai/guides/ts-to-python/)

## What's inside

| Part | Topic | What you get |
|------|-------|--------------|
| 1 | **Two Worlds** | 12 runtime/architecture differences (event loop, GIL, concurrency, packaging) with code |
| 2 | **The Map** | A four-week crossing plan, week by week |
| 3 | **The Plan, Unpacked** | Day-to-day steps with snippets and a weekly deliverable |
| 4 | **Translations** | npm→uv, tsc→pyright, zod→pydantic, express→fastapi, and more |
| 5 | **Survival Syntax** | Six idioms with no clean JS equivalent: slicing, unpacking, `enumerate`/`zip`, f-strings, `__main__`, truthiness |
| 6 | **Side by Side** | The same program in TS and Python |
| 7 | **The Starter** | A 60-second `uv` setup and a curated stack |
| 8 | **Things That'll Trip You** | Nine gotchas, including `is` vs `==`, no block scope, integer division |
| 9 | **Build to Learn** | Three projects, increasing in depth |

## Audience

Mid-to-senior TS/JS engineers who already think in code and want to be productive in Python fast — not absolute beginners.

## Sources

Technical claims are fact-checked against current official documentation:

- [Python 3.14 — What's New](https://docs.python.org/3/whatsnew/3.14.html) and [free-threading HOWTO](https://docs.python.org/3/howto/free-threading-python.html) (PEP 779, free-threaded build now officially supported, opt-in)
- [uv documentation](https://docs.astral.sh/uv/) (project init, `uv add`, dependency groups)
- [FastAPI CLI](https://fastapi.tiangolo.com/fastapi-cli/) (`fastapi dev` requires `fastapi[standard]`)
- [Pydantic documentation](https://docs.pydantic.dev/) (`EmailStr` requires the `email` extra)
- [Ruff](https://docs.astral.sh/ruff/) · [Pyright](https://microsoft.github.io/pyright/) · [pytest](https://docs.pytest.org/) · [httpx](https://www.python-httpx.org/)

## License

This guide is for educational purposes. Content is based on publicly available official documentation for Python and the listed tools.
