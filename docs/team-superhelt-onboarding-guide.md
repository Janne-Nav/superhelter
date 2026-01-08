# Team Superhelt Onboarding Guide: Using Copilot Spaces

## Welcome to Team Superhelt!

This guide will help you get started with GitHub Copilot Spaces for onboarding and collaboration. Team Superhelt uses Copilot Spaces to centralize knowledge, streamline onboarding, and enhance team collaboration around our repository at [navikt/historisk-superhelt](https://github.com/navikt/historisk-superhelt).

## What is Copilot Spaces?

GitHub Copilot Spaces is a collaborative environment that helps teams:
- Organize and share context about repositories, code, and documentation
- Get AI-powered answers grounded in your team's specific codebase
- Support self-service onboarding for new team members
- Maintain living, evergreen documentation that stays synchronized with your repositories

## Prerequisites

Before you begin, ensure you have:
- A GitHub account with access to the [navikt/historisk-superhelt](https://github.com/navikt/historisk-superhelt) repository
- Access to GitHub Copilot Spaces (available with GitHub Copilot plans)
- Basic familiarity with GitHub

## Step 1: Access the Team Superhelt Copilot Space

### Option A: Join an Existing Space (Recommended for New Members)

1. Ask your team lead for an invitation to the **Team Superhelt Knowledge Hub** Copilot Space
2. Navigate to [GitHub Copilot Spaces](https://github.com/copilot/spaces)
3. You should see "Team Superhelt Knowledge Hub" in your list of spaces
4. Click on the space to open it

### Option B: Create Your Personal Onboarding Space

If you want to create your own space for learning:

1. Navigate to [GitHub Copilot Spaces](https://github.com/copilot/spaces)
2. Click **Create Space**
3. Name your space: `Team Superhelt - My Onboarding`
4. Add a description: `Personal onboarding space for learning about Team Superhelt processes and the historisk-superhelt repository`
5. Click **Save**

## Step 2: Add the historisk-superhelt Repository as a Source

1. In your Copilot Space, click **Add sources**
2. Type or paste: `navikt/historisk-superhelt`
3. Select the repository from the search results
4. Choose which folders/files to include:
   - Select the entire repository for comprehensive context
   - Or select specific folders like `docs/`, `src/`, and `README.md` for focused context
5. Click **Add** to confirm

The repository will now be indexed and available as context for your conversations.

## Step 3: Add Instructions to Your Space

Instructions help Copilot understand your team's context and provide better answers.

1. Click the **Instructions** button in your space
2. Add the following instructions (customize as needed):

```markdown
## Team Superhelt Context

- This space is for onboarding and collaboration on the historisk-superhelt project
- Repository: https://github.com/navikt/historisk-superhelt
- Documentation is stored in the `docs/` folder
- Follow Norwegian public sector development standards

### Purpose of this Space

- Support new team member onboarding
- Provide quick access to project knowledge and decisions
- Enable self-service answers to common questions
- Document team processes and conventions
- Maintain institutional knowledge as the team evolves

### When answering questions:

- Reference specific files and line numbers when possible
- Explain both the "what" and the "why"
- Connect answers to relevant documentation
- Suggest related topics new members should explore
```

3. Click **Save**

## Step 4: Onboarding Activities with Copilot Spaces

### Activity 1: Explore the Repository Structure

Start by understanding the codebase structure:

**Prompt to use:**
```
Please provide an overview of the navikt/historisk-superhelt repository structure. 
What are the main folders and their purposes? What programming languages and 
frameworks are used?
```

### Activity 2: Understand Team Processes

Learn about how the team works:

**Prompt to use:**
```
What development processes and workflows does Team Superhelt follow? 
Look for information about:
- How to contribute code (branching strategy, PR process)
- Testing requirements
- Code review practices
- Documentation standards
```

### Activity 3: Review Recent Changes

Get up to speed with recent work:

**Prompt to use:**
```
What are the most significant changes or features added to historisk-superhelt 
recently? Can you summarize the recent development activity?
```

### Activity 4: Find Answers to Common Questions

Use the space to answer typical onboarding questions:

**Example prompts:**
```
How do I set up my local development environment for historisk-superhelt?

Where can I find the API documentation?

What are the coding conventions used in this project?

Who should I contact for questions about [specific area]?
```

## Step 5: Collaboration Workflows

### Daily Collaboration

Use Copilot Spaces for:

1. **Code Understanding**: Ask questions about specific functions, classes, or modules
   ```
   Can you explain how the authentication module works in historisk-superhelt?
   ```

2. **Debugging Help**: Get context-aware debugging suggestions
   ```
   I'm seeing an error in [file]. Based on the codebase, what might be causing this?
   ```

3. **Architecture Decisions**: Understand why things are built a certain way
   ```
   Why is the data layer structured this way? What were the design considerations?
   ```

### Creating Issues with Context

When you identify work items:

1. Attach relevant files to your conversation
2. Draft the issue using Copilot
3. Use prompts like:
   ```
   Create an issue for adding unit tests to the authentication module. 
   Include acceptance criteria and reference existing test patterns in the codebase.
   ```

### Knowledge Capture

When you learn something valuable:

1. Document it in a conversation
2. Create a summary
3. Consider adding it to the repository documentation:
   ```
   Based on our discussion about [topic], create a documentation update 
   for docs/[relevant-file].md
   ```

## Step 6: Advanced Usage

### Using Copilot Coding Agent

The Copilot coding agent can help create pull requests:

1. Create an issue or define the work needed
2. Attach the issue to your conversation: `@navikt/historisk-superhelt/issues/#`
3. Prompt:
   ```
   Using the github-coding-agent tool, create a pull request to implement this issue.
   ```

### Sharing Knowledge with the Team

When you discover something useful:

1. Share the Copilot Space with team members
2. Create reusable prompt templates for common questions
3. Document tribal knowledge in the space instructions

### Keeping Context Fresh

- Spaces automatically sync with repository changes
- Periodically review and update space instructions
- Remove outdated sources and add new documentation as it's created

## Best Practices for Team Superhelt

1. **Ask Specific Questions**: The more specific your question, the better the answer
   - ❌ "How does this work?"
   - ✅ "How does the user authentication flow work in src/auth/login.ts?"

2. **Provide Context**: Help Copilot help you
   - Reference specific files, functions, or issues
   - Explain what you've already tried
   - Share error messages or logs when debugging

3. **Verify and Validate**: Always review Copilot's suggestions
   - Cross-reference with actual code
   - Test suggested solutions
   - Ask for clarification if something seems off

4. **Document Learnings**: Turn conversations into documentation
   - Update README files with common setup issues
   - Add FAQs to the repository
   - Create runbooks for operational procedures

5. **Collaborate Openly**: Share your spaces when helpful
   - Invite team members to collaborative problem-solving
   - Use spaces for pair programming sessions
   - Create team-wide spaces for shared knowledge

## Usage Considerations

### Request Limits

- Copilot Free: Questions count toward monthly chat limit
- Premium models: Each question counts as one request × model multiplier
- See [GitHub Copilot Plans](https://docs.github.com/en/copilot/get-started/plans) for details

### Privacy and Security

- Spaces use the same privacy and security model as GitHub Copilot
- Your code and conversations stay within GitHub
- Follow your organization's policies for sensitive information
- Never share credentials or secrets in conversations

## Getting Help

If you have questions or issues:

1. **First**: Try asking in your Copilot Space
2. **Team Chat**: Reach out in the Team Superhelt channel
3. **Documentation**: Review the [Copilot Spaces documentation](https://docs.github.com/en/copilot/how-tos/provide-context/use-copilot-spaces/)
4. **Team Lead**: Contact your team lead for access or usage questions

## Next Steps

Now that you've set up Copilot Spaces:

1. ✅ Complete all onboarding activities above
2. ✅ Ask at least 3 questions about the historisk-superhelt codebase
3. ✅ Document one thing you learned in the repository
4. ✅ Share your onboarding experience with the team

Welcome to Team Superhelt! We're excited to have you on board. 🎉

---

## Additional Resources

- [GitHub Copilot Spaces Documentation](https://docs.github.com/en/copilot/how-tos/provide-context/use-copilot-spaces/)
- [Understanding Copilot Requests and Usage](https://docs.github.com/en/copilot/managing-copilot/understanding-and-managing-copilot-usage/understanding-and-managing-requests-in-copilot)
- [navikt/historisk-superhelt Repository](https://github.com/navikt/historisk-superhelt)
- [Team Superhelt Wiki](#) (Add your team wiki link here)
