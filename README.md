# Website Design & Development Professional Skill

This package contains a GitHub Copilot Agent Skill for VS Code.

## Install as a workspace skill
Copy the `website-design-development` folder into the root of your project at:
`.github/skills/website-design-development/`

The final structure should be:
```
your-project/
└── .github/
    └── skills/
        └── website-design-development/
            ├── SKILL.md
            ├── references/
            │   ├── design-checklist.md
            │   └── testing-checklist.md
            └── examples/
                └── request-templates.md
```

## Use
1. Open the project folder in VS Code.
2. Open GitHub Copilot Chat and use Agent mode.
3. Reload the VS Code window if the skill is not discovered immediately.
4. Type `/website-design-development` and add your task, or ask Copilot naturally to design/build/debug a website.
5. Approve terminal commands or file changes according to your normal safety preferences.

## Personal install
For a skill usable across projects, copy the folder to:
- Linux/macOS: `~/.copilot/skills/website-design-development/`
- Windows: `%USERPROFILE%\.copilot\skills\website-design-development\`

Use the exact location supported by your VS Code/Copilot version. The skill's folder name must match the `name` in the SKILL.md frontmatter.
