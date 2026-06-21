# 📚 GH-300 — Supplementary Questions (New Topics 2026)

> Bổ sung các topics mới chưa có trong practice-exam-en.md
> Tập trung vào: Copilot CLI, Agent Mode, Org-wide policies, Scenario-based questions

---

## Supplementary Set A: Copilot CLI & Agent Mode (New 2026)

### Question A1
**Q:** You are working in GitHub Copilot CLI and want to delegate a complex task to a sub-agent that will explore the codebase independently. Which command or prefix should you use?
- A) `/run TASK-DESCRIPTION`
- B) `/delegate TASK-DESCRIPTION` or prefix `&`
- C) `/agent TASK-DESCRIPTION`
- D) `/subagent TASK-DESCRIPTION`

**✅ B)** — Use `/delegate TASK-DESCRIPTION` or prefix `&` to delegate tasks to Copilot CLI sub-agents.

---

### Question A2
**Q:** In Copilot CLI, which mode allows the agent to perform multi-step tasks without requiring approval at each step?
- A) Interactive mode
- B) Plan mode
- C) Autopilot mode
- D) Review mode

**✅ C)** — Autopilot mode enables multi-step execution without requiring approval at each step.

---

### Question A3
**Q:** Which of the following is a specialized sub-agent available in Copilot CLI?
- A) Debug Agent
- B) Explore Agent
- C) Deploy Agent
- D) Monitor Agent

**✅ B)** — Copilot CLI includes specialized sub-agents: Explore, Task, Code Review, and Plan.

---

### Question A4
**Q:** You want Copilot to autonomously handle a GitHub Issue, implement the solution, and create a Pull Request. Which feature should you use?
- A) Copilot Chat
- B) Copilot Cloud Agent
- C) Copilot CLI
- D) Copilot Edit Mode

**✅ B)** — Copilot Cloud Agent can automatically receive GitHub Issues, implement solutions, and create PRs.

---

### Question A5
**Q:** In Agent Mode, what does MCP (Model Context Protocol) enable?
- A) Faster code completion
- B) Connecting Copilot to external data sources and tools without transferring context
- C) Better syntax highlighting
- D) Automatic code formatting

**✅ B)** — MCP servers allow Copilot to access external resources and tools without needing to include all context in the prompt.

---

### Question A6
**Q:** You want to use Agent Mode to refactor a multi-file project. Which feature should you use?
- A) Inline suggestions only
- B) Edit Mode for multi-file edits via natural language
- C) Copilot Chat only
- D) Duplication detection

**✅ B)** — Edit Mode allows editing multiple files simultaneously through natural language instructions.

---

### Question A7
**Q:** Which issue tracking platforms can Copilot agents receive tasks from? (Select the most complete answer)
- A) Only GitHub Issues
- B) GitHub Issues and Jira
- C) GitHub Issues, Azure Boards, Jira, Raycast, and Linear
- D) Only Azure Boards

**✅ C)** — Copilot agents can receive tasks from multiple platforms: GitHub Issues, Azure Boards, Jira, Raycast, and Linear.

---

## Supplementary Set B: Org-Wide Policies & Governance

### Question B1
**Q:** You are an organization admin and want to manage Copilot feature availability across all IDEs for your organization. Where do you configure this?
- A) In each user's personal settings
- B) In the organization's policy management settings
- C) In the `.copilotignore` file
- D) In the repository's `.github` folder

**✅ B)** — Organization-wide policy management allows admins to control feature availability across IDEs and github.com.

---

### Question B2
**Q:** Which of the following can be managed using the GitHub REST API for Copilot?
- A) Code suggestions
- B) Subscriptions and billing
- C) IDE theme settings
- D) Git commit history

**✅ B)** — The GitHub REST API can be used to manage Copilot subscriptions.

---

### Question B3
**Q:** Your organization wants to enable Copilot Code Review policies. At which level can this be configured?
- A) Only at the repository level
- B) At the organization level
- C) Only at the user level
- D) Only at the enterprise level

**✅ B)** — Copilot Code Review policies can be configured at the organization level.

---

### Question B4
**Q:** Which audit log events are available in Copilot Business/Enterprise?
- A) Only error logs
- B) Usage tracking, who used Copilot, what was accepted/rejected
- C) Only code content
- D) Only billing events

**✅ B)** — Audit logs track usage patterns, who used Copilot, and what suggestions were accepted or rejected.

---

## Supplementary Set C: Scenario-Based Questions

### Question C1
**Q:** You are a developer at a company that handles sensitive financial data. Your manager asks you to ensure that proprietary code is NOT used to train public AI models. What should you do?
- A) Use Copilot Free plan and enable telemetry
- B) Use Copilot Business or Enterprise plan, which includes contractual protections that code will NOT be used to train public models
- C) Disable Copilot Chat
- D) Use only inline suggestions

**✅ B)** — Business/Enterprise plans include contractual protections ensuring code is NOT used to train public models.

---

### Question C2
**Q:** Your team wants to exclude a folder containing API keys and secrets from being used as context by Copilot. What is the best approach?
- A) Add the folder to `.gitignore`
- B) Add the folder to `.copilotignore`
- C) Delete the folder
- D) Move the folder to a different repository

**✅ B)** — `.copilotignore` works like `.gitignore` but specifically for Copilot context exclusion.

---

### Question C3
**Q:** You are reviewing a Pull Request and want Copilot to help identify security vulnerabilities and suggest improvements. Which feature should you use?
- A) Copilot inline suggestions
- B) Copilot for Pull Requests / Copilot Code Review
- C) Copilot Chat only
- D) Duplication detection filter

**✅ B)** — Copilot for Pull Requests supports code review, identifying security vulnerabilities, and suggesting improvements.

---

### Question C4
**Q:** Your organization wants to ensure that no proprietary code leaks through Copilot suggestions. Which combination of measures is the BEST practice?
- A) Use Free plan + disable telemetry
- B) Business/Enterprise plan + content exclusions + duplication detection + audit logs
- C) Disable Copilot entirely
- D) Use only Copilot Chat

**✅ B)** — Combining multiple layers: right plan + exclusions + filter + audit logs provides the best IP protection.

---

### Question C5
**Q:** You are learning Rust and want to understand how a specific pattern works. What is the most effective way to use Copilot?
- A) Copy code from StackOverflow
- B) Use Copilot Chat to explain code, ask about syntax, and experiment with examples
- C) Only read the official documentation
- D) Disable Copilot and write everything by hand

**✅ B)** — Copilot Chat helps explain code, answer syntax questions, and experiment, accelerating learning.

---

### Question C6
**Q:** You need to generate unit tests for a function that has external database dependencies. How should you approach this with Copilot?
- A) It's not possible to test functions with external dependencies
- B) Provide mock setup or ask Copilot to generate mocks for the external dependencies
- C) Only test functions without dependencies
- D) Install a separate testing extension

**✅ B)** — You can ask Copilot to create mocks or provide a mock setup for testing functions with external dependencies.

---

### Question C7
**Q:** Your team is modernizing a legacy codebase. What is the best approach to use Copilot for this task?
- A) Rewrite everything from scratch
- B) Refactor incrementally, use Copilot Chat to explain old code and suggest improvements
- C) Refactor everything at once
- D) Don't use Copilot for legacy code

**✅ B)** — Incremental refactoring with Copilot Chat helps understand old code and suggest targeted improvements.

---

### Question C8
**Q:** You want Copilot to generate a SQL query based on your database schema. What should you provide?
- A) Only the table name
- B) Table structure + requirements → Copilot generates appropriate SQL
- C) Only `SELECT *`
- D) A database extension

**✅ B)** — Describing the schema and requirements allows Copilot to generate correct SQL queries.

---

### Question C9
**Q:** You are working on a Python project and want Copilot to generate a docstring for a function. What is the best approach?
- A) Type "write docstring" and wait
- B) Place cursor above the function and let Copilot infer from the function signature and body, or use Copilot Chat to ask for a docstring
- C) Manually write the docstring
- D) Use a separate documentation tool

**✅ B)** — Copilot can generate docstrings from the function context, or you can ask Copilot Chat directly.

---

### Question C10
**Q:** Your organization has strict compliance requirements. You need to track who is using Copilot and what suggestions are being accepted. Which plan do you need?
- A) Copilot Free
- B) Copilot Individual
- C) Copilot Business or Enterprise
- D) Any plan provides this

**✅ C)** — Audit logs are only available in Business/Enterprise plans, which track usage and compliance.

---

## Supplementary Set D: Prompt Engineering Deep Dive

### Question D1
**Q:** What is zero-shot prompting in the context of Copilot?
- A) Providing multiple examples before asking for code
- B) Asking Copilot to generate code without providing any examples
- C) Using only comments as prompts
- D) Typing code without any context

**✅ B)** — Zero-shot prompting means asking Copilot to generate code without providing examples, relying on its pre-trained knowledge.

---

### Question D2
**Q:** What is few-shot prompting?
- A) Providing no examples
- B) Providing a few examples to guide Copilot's output
- C) Using only function names
- D) Typing very short prompts

**✅ B)** — Few-shot prompting provides a few examples to guide Copilot toward the desired output format or behavior.

---

### Question D3
**Q:** How does chat history affect Copilot Chat responses?
- A) It has no effect
- B) Previous messages in the chat provide context that influences subsequent responses
- C) It only affects the first response
- D) It slows down the model

**✅ B)** — Chat history provides context that helps Copilot understand the conversation flow and provide more relevant responses.

---

### Question D4
**Q:** What is the purpose of prompt file reuse in Copilot Chat?
- A) To save disk space
- B) To provide consistent context and instructions for repeated tasks
- C) To speed up code completion
- D) To disable suggestions

**✅ B)** — Prompt files allow reusing consistent instructions and context for repeated tasks, ensuring consistent responses.

---

### Question D5
**Q:** When crafting a prompt for Copilot Chat, which approach is most effective?
- A) "fix code"
- B) "I need a Python function that takes a list of integers and returns the sum of even numbers. Handle the empty list edge case by returning 0."
- C) "code please"
- D) "function"

**✅ B)** — Specific prompts with clear input/output descriptions and edge cases produce the best results.

---

## Supplementary Set E: Data Handling & Architecture

### Question E1
**Q:** How does Copilot build context for generating suggestions?
- A) Only from the current file
- B) From the active file, project structure, imports, and open files
- C) Only from the clipboard
- D) From the entire repository

**✅ B)** — Copilot collects context from multiple sources: active file, project structure, imports, and open files.

---

### Question E2
**Q:** What happens during proxy filtering in Copilot's data flow?
- A) Code is sent to a third-party service
- B) Suggestions are filtered for toxicity, duplication, and security before being shown to the user
- C) Code is encrypted
- D) Suggestions are cached locally

**✅ B)** — Proxy filtering applies toxicity filters, duplication detection, and security checks before presenting suggestions.

---

### Question E3
**Q:** What is a limitation of LLMs that affects Copilot's suggestions?
- A) They always produce perfect code
- B) They may generate plausible-looking but incorrect code, especially for complex business logic
- C) They only work with Python
- D) They don't understand syntax

**✅ B)** — LLMs can generate code that looks correct but contains logical errors, especially for complex business logic. Always review.

---

### Question E4
**Q:** How long does GitHub retain Copilot data for Business and Enterprise customers?
- A) Forever
- B) Data is not retained for training public models; telemetry retention follows GitHub's data retention policy
- C) 30 days
- D) 1 year

**✅ B)** — Business/Enterprise plans have contractual protections: code is NOT used to train public models.

---

### Question E5
**Q:** What is the code suggestion lifecycle in Copilot?
- A) Type code → Get suggestion → Accept
- B) Build context → Send to model → Receive suggestion → Apply filters → Present to user
- C) Send entire codebase → Get suggestion → Accept
- D) Type comment → Get suggestion → Accept

**✅ B)** — The lifecycle includes context building, model inference, filtering, and presentation.

---

## Supplementary Set F: Testing with Copilot

### Question F1
**Q:** You want Copilot to generate tests that cover edge cases. What should you do?
- A) Just ask for "tests"
- B) Ask Copilot to generate tests and specifically mention edge cases to cover
- C) Only test happy paths
- D) Write tests manually

**✅ B)** — Explicitly mentioning edge cases in your prompt helps Copilot generate more comprehensive tests.

---

### Question F2
**Q:** In a TDD workflow with Copilot, what is the correct order?
- A) Write code → Write tests → Refactor
- B) Write tests → Copilot generates code to pass tests → Refactor
- C) Write code → Refactor → Write tests
- D) Copilot writes everything

**✅ B)** — TDD + Copilot: write tests first, then Copilot generates implementation code to pass those tests.

---

### Question F3
**Q:** Copilot can help identify security vulnerabilities in code by:
- A) Automatically fixing all vulnerabilities
- B) Suggesting security improvements and identifying potential vulnerabilities during code review
- C) Only checking syntax
- D) Only formatting code

**✅ B)** — Copilot can suggest security improvements and identify potential vulnerabilities during code review.

---

## Quick Reference: Key CLI Commands & Features

| Feature | Command/Usage |
|---------|--------------|
| Delegate task | `/delegate TASK` or `& TASK` |
| Plan mode | Multi-step planning before execution |
| Autopilot mode | Multi-step without per-step approval |
| Sub-agents | Explore, Task, Code Review, Plan |
| Content exclusions | `.copilotignore` file |
| Org policies | Organization settings → Copilot policies |
| Audit logs | Business/Enterprise only |
| REST API | Manage subscriptions programmatically |

---

## Quick Reference: Exam Day Tips

1. **Read carefully** — Many questions have subtle differences between options
2. **Eliminate wrong answers** — Narrow down to 2 options, then choose the BEST
3. **Scenario questions** — Focus on what the question is really asking (privacy? security? productivity?)
4. **Know your plans** — Free vs Individual vs Business vs Enterprise features
5. **CLI is new** — Expect 2-3 questions on Copilot CLI commands
6. **Agent Mode** — Understand MCP, sub-agents, and delegation
7. **Don't overthink** — If you know the material, trust your first instinct
8. **Time management** — ~1 min per question, flag and return to hard ones
