Follow this structured process to perform a thorough code review of the provided changes.

## Step 1: Capture the diff
- Create a file named `diff.md`
- Execute `git diff` and store the complete output in this file
- Verify the diff content was successfully captured before proceeding

## Step 2: Analyze changes
Perform a systematic review of `diff.md` with these specific evaluation criteria:

Code Quality:
- Identify any code duplications or violations of DRY principles
- Check for proper function/method abstraction
- Ensure variable/function naming follows clarity best practices
- Verify logical flow and readability
- Confirm no excessive nesting or complexity

Maintenance Considerations:
- Evaluate code from a solo developer maintenance perspective
- Assess future maintainability and technical debt
- Identify any unclear logic that would benefit from refactoring
- Flag any potential performance bottlenecks

Correctness and Standards:
- Verify the code is free of logical errors and bugs
- Check for syntax errors or typos
- Confirm proper error handling exists where needed
- Ensure changes are lint-compliant
- Verify no trailing whitespace exists
- Validate proper indentation throughout

DO NOT:
- Suggest adding comments unless absolutely critical for understanding
- Recommend creating dedicated logging/printing methods
- Add unnecessary documentation
- Apply team-oriented practices unsuitable for a solo developer

## Step 3: Prioritize findings
- Categorize issues by severity: Critical, Important, Minor
- Rank findings by implementation effort vs. maintenance benefit
- Present only actionable feedback that provides clear value
- Include specific code examples when suggesting improvements

Provide a concise, actionable review focusing only on meaningful improvements to code quality and maintainability.k
