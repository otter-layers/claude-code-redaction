# claude-code-redaction

Redaction configuration and hooks for Claude Code.

## Usage

```
LAYER https://github.com/otter-layers/claude-code-redaction \
  TARGET .claude/ \
  AFTER ["./.claude/scripts/merge-redaction-settings.sh"]
```
