# Skills

Custom global skills for AI coding agents.

## Install

```bash
git clone <repo-url> ~/Developer/skills
cd ~/Developer/skills
./install.sh
```

## Adding a new skill

1. Create a new directory with a `SKILL.md` file at the root of the repo
2. Run `./install.sh`

## Skills

| Skill          | Agent  | Description                                                      |
|----------------|--------|------------------------------------------------------------------|
| `grill-me`                       | Claude | Interview you relentlessly about a plan or design                |
| `improve-codebase-architecture`  | Claude | Find and propose architectural improvements via deep modules     |
| `prd-to-issues`                  | Claude | Break a PRD into GitHub issues using vertical slices             |
| `tdd`                            | Claude | Test-Driven Development with vertical slices and tracer bullets  |
| `write-a-prd`                    | Claude | Create a PRD through user interview and submit as a GitHub issue |
