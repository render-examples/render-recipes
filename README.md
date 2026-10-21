# Render Recipes

Recipes are self-contained implementation guides for building a specific class
of application. Each guide is designed to be shared directly with a coding
agent.

A coding agent should be able to start with an empty repository, follow one
recipe, and implement the application.

## Available recipes

- [`event-to-pr.md`](event-to-pr.md): turn an authenticated external event
  into a bounded agent run in a fresh Render Sandbox and publish the validated
  result as a draft pull request.
