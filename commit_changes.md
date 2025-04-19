Generate a series of structured git commit messages that document the implementation of a new or updated features. Each commit should represent a single logical step in the development process.

Requirements for each commit message:
- Begin with a standard prefix: [FEAT], [FIX], [REFACTOR], [TEST], [DOCS], or [CHORE]
- Follow with a concise, present-tense title (under 72 characters)
- Include a brief explanation that describes WHAT changed and WHY
- Maintain atomic, focused changes that represent one logical unit of work
- Preserve a logical progression from initial implementation to completion

The sequence should:
- Show clear progression from setup/scaffolding to final implementation
- Separate concerns (e.g., refactoring from feature addition)
- Include appropriate test coverage commits where applicable
- Follow a narrative that reviewers can easily understand

DO NOT:
- Use past tense verbs
- Create overly large or unfocused commits
- Include irrelevant implementation details
- Reference ticket numbers without context
- Include any signature, name, or attribution in the commit message
- Include any reference to Claude, AI, LLM, or any AI assistant in the commit messages

The output should facilitate efficient code review by providing clear signposts for how the feature evolved through development.
