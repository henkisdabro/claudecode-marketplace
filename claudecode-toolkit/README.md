# Claude Code Toolkit

Meta toolkit for working with Claude Code itself - create and improve skills.

## What's Included

### Hooks (1)
- **skill-activation-prompt** - Automatically suggests relevant skills based on user prompts and file context

### Skills (1)
- **skill-creator** - Comprehensive guide for creating effective skills that extend Claude's capabilities

## Installation

```bash
/plugin install claudecode-toolkit@wookstar
```

## Usage

### Using skill-activation-prompt Hook

This hook enables automatic skill suggestions based on your work:

1. Copy the hook files to your project:
```bash
cp claudecode-toolkit/hooks/skill-activation-prompt/skill-activation-prompt.* .claude/hooks/
chmod +x .claude/hooks/skill-activation-prompt.sh
```

2. Install dependencies:
```bash
cd .claude/hooks
npm install
```

3. Add to `.claude/settings.json`:
```json
{
  "hooks": {
    "UserPromptSubmit": [
      {
        "type": "command",
        "command": "$CLAUDE_PROJECT_DIR/.claude/hooks/skill-activation-prompt.sh"
      }
    ]
  }
}
```

See `hooks/skill-activation-prompt/README.md` for detailed setup instructions.

### Creating New Skills

This toolkit helps you create new skills for Claude Code.

```bash
# Ask for help creating a skill
"Help me create a new skill for PDF editing"
"I want to create a skill that helps with SEO analysis"
"Guide me through creating a skill for email marketing"
```

## What skill-creator Provides

- Step-by-step skill creation process
- Best practices and patterns
- SKILL.md structure guidance
- Bundled resources organization (scripts, references, assets)
- Progressive disclosure design principles
- Testing and validation tips

## When to Use

Use this toolkit when you want to:
- Create a new skill for Claude Code
- Improve an existing skill
- Understand skill structure and best practices
- Learn about progressive disclosure in skills
- Package skills for distribution

## Skill Creation Workflow

1. **Understanding** - Gather examples of how the skill will be used
2. **Planning** - Identify reusable resources (scripts, references, assets)
3. **Implementation** - Create SKILL.md and bundled resources
4. **Testing** - Validate the skill works as expected
5. **Iteration** - Refine based on usage

The skill-creator skill guides you through each step!
