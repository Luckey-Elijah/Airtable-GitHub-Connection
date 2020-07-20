# The Airtable GitHub Connection

> 🛒 In Progess

The Airtable to Github connection to track issues and PR's.

This is a connection designed to create and manage interaction for GitHub and Airtable.

## Architecture

This section describes how the API's of services interact with each other.

Some questions in the air include:

- Will connections be one-to-one for Airtable base to GitHub repository?
- Maybe one Airtable BAse for managing multiple repositories? (This would be nice for organizations and teams!)

How to answer the questions and discussion:

> Use the [issues](https://github.com/Luckey-Elijah/Airtable-GitHub-Connection/issues) to start a discussion.

- You could add API Keys to a GitHub Action CI/CD Workflow
- You could install it on your own serverless system (Heroku, Firebase, AWS, etc.).
- What is most efficient?

### Airtable

What you'll need:

- [Airtable Account](https://airtable.com/account) and an API key for that account.
- An Airtable Base (let's design a template for other people to use!)
- A serverless service (Heroku, Firebase, AWS, etc.)

### GitHub

What you'll need:

- [GitHub Repository](https://github.com) and an API key for that repository.
- A serverless service (Heroku, Firebase, AWS, etc.)
