# CONTRIBUTING.md

Thank you for contributing to Supabase! We’re a big, exciting open source project and we’d love to have you contribute! Here’s some resources and guidance to help you get started:

[1. Getting Started](#getting-started)
[2. Finding Issues to Work On](#finding-issues-to-work-on)
[3. Issues](#issues)
[4. Pull Requests](#pull-requests)

## Getting Started

To ensure a positive and inclusive environment, please read our [code of conduct](https://github.com/supabase/.github/blob/main/CODE_OF_CONDUCT.md) before contributing. For help setting up the code in this repo, please follow our [DEVELOPERS.md](https://github.com/supabase/supabase/blob/master/DEVELOPERS.md) file. For the [docs](https://supabase.com/docs) site, follow this [CONTRIBUTING.md](https://github.com/supabase/supabase/blob/master/apps/docs/CONTRIBUTING.md) guide.

## Finding Issues to Work On

We welcome contributions from developers of all skill levels! Here's how to find issues that match your interests and expertise:

### Browse Issues by Label

GitHub labels help categorize issues by type, difficulty, and area:

- **[good first issue](https://github.com/supabase/supabase/labels/good%20first%20issue)** - Perfect for newcomers! These issues are well-defined, have clear acceptance criteria, and are great for getting familiar with the codebase.
- **[help wanted](https://github.com/supabase/supabase/labels/help%20wanted)** - Issues where we'd especially appreciate community contributions.
- **[documentation](https://github.com/supabase/supabase/labels/documentation)** - Documentation improvements, typo fixes, or adding examples.
- **[bug](https://github.com/supabase/supabase/labels/bug)** - Confirmed bugs that need fixing.
- **[enhancement](https://github.com/supabase/supabase/labels/enhancement)** - New features or improvements to existing functionality.

### Search Issues by Technology

You can filter issues by the technology or component you're interested in:

```
is:issue is:open label:"good first issue" studio
is:issue is:open label:documentation postgres
is:issue is:open label:bug authentication
```

### Using AI to Find and Understand Issues

AI tools can help you discover relevant issues and understand them better:

#### 1. **Finding Relevant Issues with AI Search**

Use GitHub's search with natural language queries:
- "authentication bug" 
- "typescript error in studio"
- "improve documentation for realtime"

You can also use AI assistants like ChatGPT or GitHub Copilot to help formulate better search queries:
```
Ask your AI: "Help me find beginner-friendly issues in Supabase 
related to React components"

AI might suggest: is:issue is:open label:"good first issue" 
label:documentation React OR component
```

#### 2. **Understanding Issue Context**

When you find an issue that interests you:
- Copy the issue description and ask an AI assistant to explain it in simpler terms
- Ask the AI to break down the technical requirements
- Request suggestions for where to start looking in the codebase

Example prompt:
```
"I found this issue in Supabase: [paste issue description]. 
Can you explain what needs to be done and suggest where in the 
codebase I should start looking?"
```

#### 3. **Planning Your Contribution**

Use AI to help plan your approach:
- Ask for a step-by-step implementation plan
- Request code examples for similar features
- Get suggestions for test cases you should write

#### 4. **GitHub Copilot for Code Exploration**

If you have GitHub Copilot:
- Use it to understand existing code patterns in the repository
- Ask it to explain complex functions or components
- Get suggestions for implementing your fix or feature

### What Contributions Are Needed?

Supabase welcomes various types of contributions:

1. **Bug Fixes** - Fix reported issues or bugs you discover while using Supabase
2. **Documentation** - Improve guides, add examples, fix typos, or clarify confusing sections
3. **Features** - Add new functionality (discuss in [Discussions](https://github.com/orgs/supabase/discussions/new/choose) first!)
4. **Tests** - Increase test coverage or add missing test cases
5. **Performance** - Optimize slow operations or reduce bundle sizes
6. **Accessibility** - Improve keyboard navigation, screen reader support, or ARIA labels
7. **Translations** - Help translate documentation to other languages
8. **Developer Experience** - Improve error messages, add helpful warnings, or enhance tooling

### Tips for Success

- **Start small** - Your first contribution doesn't need to be a major feature
- **Communicate early** - Comment on the issue to let others know you're working on it
- **Ask questions** - Use the issue comments, [Discord](https://discord.supabase.com), or [Discussions](https://github.com/supabase/supabase/discussions) if you need help
- **Check existing PRs** - Make sure someone else hasn't already submitted a fix
- **Read the code** - Spend time understanding the existing patterns and conventions
## Issues

If you find a bug, please create an Issue and we’ll triage it.

- Please search [existing Issues](https://github.com/supabase/supabase/issues) before creating a new one.
- Please include a clear description of the problem along with steps to reproduce it. Exact steps with screenshots and urls really help here.

## Pull Requests

We actively welcome your Pull Requests! A couple of things to keep in mind before you submit:

- If you’re fixing an Issue, make sure someone else hasn’t already created a PR fixing the same issue. Likewise, make sure to link your PR to the related Issue(s).
- We will always try to accept the first viable PR that resolves the Issue.
- If you're new, we encourage you to take a look at issues tagged with [good first issue](https://github.com/supabase/supabase/labels/good%20first%20issue).
- If you’re submitting a new feature, make sure you have opened a [Discussion](https://github.com/orgs/supabase/discussions/new/choose) to discuss the new feature before opening a PR. We’d love to accept your hard work, but unfortunately if a feature hasn’t gone through a proper design process, your PR will be closed.
- Please use the PR message template and provide detailed context for quicker review. PRs without clear problem statements will be closed.

Prior to submitting your PR, please conduct the following pre-flight checks:

- Run `npm run build` locally to ensure that your code builds successfully without having to wait on us to approve Vercel Preview deploys.
- Ensure that the Prettier tests run successfully on your PR.

Running these before you create the PR will help reduce back and forth with the team.
