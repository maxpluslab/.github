# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is the special `.github` repository of the `maxpluslab` GitHub organization. It holds no code. Everything committed here is public.

- `profile/README.md` is rendered on https://github.com/maxpluslab. GitHub only shows it from this exact path.
- `README.md` describes this repository itself, not the organization.
- Community health files placed here (for example `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, issue templates under `.github/ISSUE_TEMPLATE/`) become the defaults for every repository in the organization that lacks its own.

## People and projects

MaxPlusLab is a collaboration between Madeline V. Brandt (mathematician, GitHub `madeline-v-brandt`) and Igor Kuvychko (scientist and engineer, GitHub `kuvychko`).

Projects listed on the profile:

- **Tropical Puzzle Lab**: https://github.com/maxpluslab/tropical-puzzle-lab, played at https://maxpluslab.github.io/tropical-puzzle-lab/. A local checkout usually sits at `C:\Repos\tropical-puzzle-lab`; its README and `docs/` are the source of truth for what the project does and plans.
- **Tiling Solvers**: https://github.com/maxpluslab/tiling-solvers, a solver laboratory (Rust search, OR-Tools CP-SAT) for the puzzles Tropical Puzzle Lab publishes. A local checkout usually sits at `C:\Repos\tiling-solvers`; its README ("What we've learned so far", "Status") is the source of truth for findings.

## Editing the profile

- Keep claims in line with what the project repositories actually contain; check the project's README "Status" section before describing features or plans.
- Each project gets a short paragraph and a row of links. A shared findings section may hold up to three findings and must end with a caveat line (search nodes are not running time or human difficulty; results are computational evidence, not proof). Each finding must match the tiling-solvers README "What we've learned so far" and name puzzles by their public names. A short "Questions we're exploring" section is allowed.
- Use plain GitHub-flavored Markdown that renders on github.com; avoid HTML unless needed for layout.
- Write the organization name as **MaxPlusLab** in prose; only URLs are lower case.
- Refer to puzzles by their public names (Hill 16b, Corrugated 27a; `-r`/`-f` for relief/flat), not internal ids like `new2` or `cor1`. The mapping is in `tropical-puzzle-lab/docs/puzzle-format.md#names`.
- No spoilers: never show a solved puzzle (photo or render). Partly assembled, scrambled or dead-end shots are fine.
- Images live in `profile/images/` with web-safe names; shrink photos to about 1200 px on the long side before committing.
- Verify every link before committing.
