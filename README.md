# Skills

A collection of Claude Agent Skills for specialized tasks.

## What are Skills?

Skills are folders of instructions and resources that Claude loads dynamically to improve performance on specialized tasks. Each skill lives in its own folder under `skills/` with a `SKILL.md` file containing instructions and metadata.

For more information:
- [What are skills?](https://support.claude.com/en/articles/12512176-what-are-skills)
- [Using skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude)
- [How to create custom skills](https://support.claude.com/en/articles/12512198-creating-custom-skills)

## Skills in This Repository

| Skill | Description |
|-------|-------------|
| [hk-school-selection](./skills/hk-school-selection/) | 香港选校顾问 — Structured decision support for choosing kindergartens, primary, and secondary schools in Hong Kong. Covers school types, admission mechanisms (POA/SSPA), school nets, Band 1 progression, and cross-stage planning. |

## Usage

Install any skill via the [skills.sh](https://skills.sh) registry or by pointing Claude Code at this repository.

## Contributing

Each skill is self-contained. To add a new skill:

1. Create a folder under `skills/<skill-name>/`
2. Add a `SKILL.md` with the required frontmatter (`name`, `description`)
3. Add any reference files or scripts your skill needs
4. Update the table above in this README

## License

Apache 2.0 — see [LICENSE](./LICENSE) for details.
