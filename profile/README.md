# [.do](https://dotdo.ai)

### [Workflows.do](https://workflows.do) Agentic Workflows
### [Functions.do](https://functions.do) AI Functions
### [Agents.do](https://agents.do) Autonomous Workers
### [Services.do](https://services.do) Services-as-Software

---

## 🤖 Working with Claude Code

Most repositories in this organization have **Claude Code automation** enabled. Here's how to use it:

### Assign Issues to Claude

**Three ways to get Claude's help:**

1. **Mention @claude in a comment**
   ```
   @claude please implement this feature
   ```

2. **Assign the issue to yourself** (triggers Claude automatically in some repos)

3. **Add the `claude` label** to the issue (in configured repos)

### What Claude Can Do

- **Implement features** - Write code, tests, and documentation
- **Fix bugs** - Debug and resolve issues
- **Review PRs** - Provide feedback and suggestions
- **Answer questions** - Explain code and architecture
- **Refactor code** - Improve code quality and structure

### Claude's Workflow

1. Analyzes your issue/comment
2. Explores the codebase
3. Implements changes
4. Creates a PR with implementation
5. Updates issue with status

### Best Practices

- **Be specific** - Clear requirements get better results
- **Include context** - Link to related files/issues
- **Set priorities** - Use `[P0]`, `[P1]`, `[P2]` tags
- **Review PRs** - Claude code should always be reviewed
- **Provide feedback** - Help Claude improve by commenting on PRs

### POC Repository

The `poc/` repository has **full automation**:
- New issues automatically trigger Claude
- PRs auto-review and auto-merge (experimental code only)
- Great for rapid prototyping and testing

See individual repository READMEs for specific Claude Code configuration.
