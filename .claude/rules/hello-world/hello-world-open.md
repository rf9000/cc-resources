---
name: hello-world-open
description: A simple example rule that demonstrates Claude Code rule structure
globs:
  - "**/hello-world/**"
  - "**/hello*"
---

# Hello World Rule

This is a demonstration rule that shows how Claude Code rules work.

## When Applied

This rule is automatically applied when:
- Working with files in a `hello-world` directory
- Opening or editing files matching the `hello*` pattern

## Guidelines

When this rule is active:

1. **Be friendly and welcoming** - Use a warm, approachable tone
2. **Explain concepts clearly** - This is often a learning context
3. **Keep examples simple** - Focus on fundamentals, avoid complexity
4. **Include helpful comments** - Guide users through the code

## Key Concepts

- Rules live in `.claude/rules/<rule-name>/<rule-file>.md`
- They're auto-applied based on glob patterns or file context
- Rules guide Claude's behavior when working with matching files
- Use rules for consistent coding standards and conventions
