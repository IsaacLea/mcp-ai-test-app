# Copilot Instruction File

## Purpose
This file provides guidelines and instructions for interacting with the GitHub Copilot chat agent in this project. It ensures consistent and efficient communication while leveraging the capabilities of the AI assistant.

## Project Context
- **Project Type**: Next.js application
- **Tech Stack**: Next.js, React, TypeScript, PostgreSQL
- **Workspace Structure**: The project follows a standard Next.js folder structure with `src/` for application code and `public/` for static assets.

## Guidelines for Using Copilot

### General Instructions
1. **Be Specific**: Clearly describe the task or question. Include relevant file names, functions, or code snippets if applicable.
2. **Iterative Approach**: Break down complex tasks into smaller steps to ensure accuracy.
3. **Validation**: Always validate changes made by Copilot, especially for critical code.

### Common Tasks
- **Code Generation**: Request specific components, utilities, or functions.
- **Bug Fixing**: Provide error messages or describe the issue in detail.
- **Best Practices**: Ask for recommendations or improvements for the current tech stack.
- **Database Queries**: Specify the schema and table details for SQL-related tasks.

### File-Specific Instructions
- **`tsconfig.json`**: Ensure TypeScript configurations align with project requirements.
- **`next.config.ts`**: Use this file for Next.js-specific configurations.
- **`README.md`**: Update this file for documentation and best practices.

### Limitations
- Copilot cannot execute long-running processes or make external API calls directly.
- For database operations, ensure the database is in a writable state.

## Example Prompts
- "Generate a new React component for a user profile card."
- "Optimize the database query for fetching user data."
- "Add TypeScript types for the API response."
- "Fix the error in `page.tsx` related to state management."

## Additional Notes
- Keep this file updated as the project evolves.
- Use the `README.md` file for detailed project documentation.

By following these instructions, you can maximize the efficiency and accuracy of the Copilot chat agent in this project.