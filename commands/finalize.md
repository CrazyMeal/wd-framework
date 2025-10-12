# /wd:finalize - Complete Project Finalization

## Purpose
Complete project finalization with quality gates and git workflow automation.

## Usage
```
/wd:finalize [commit-message] [--skip-docs] [--skip-lint] [--skip-build] [--dry-run] [--no-push]
```

## Workflow Pipeline
1. Update documentation (.md files) with latest changes
2. Run `bun lint` for code quality validation  
3. Run `bun type` for TypeScript type checking
4. Run `bun build` for compilation verification
5. Generate structured commit message if not provided
6. Git add, commit, and push if all gates pass

## Auto-Persona Activation
- **DevOps**: Infrastructure and deployment automation
- **QA**: Quality assurance and testing validation
- **Scribe**: Professional commit message generation

## MCP Integration
- **Sequential**: Workflow coordination and systematic validation
- **Context7**: Best practices and commit message patterns

## Arguments
- `[commit-message]` - Custom commit message (optional)
- `--skip-docs` - Skip documentation updates
- `--skip-lint` - Skip linting validation
- `--skip-build` - Skip build verification
- `--dry-run` - Show what would be done without executing
- `--no-push` - Commit locally but don't push to remote

## Examples
```bash
# Full workflow with custom message
/wd:finalize "feat: add user authentication system"

# Skip some steps
/wd:finalize --skip-docs --skip-build

# Dry run to see what would happen
/wd:finalize --dry-run

# Commit locally only
/wd:finalize "fix: resolve login bug" --no-push
```

Perfect for automating the repetitive "document + lint + build + commit + push" workflow you mentioned!