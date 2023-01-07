# GIT-PAT

- Personal access token (PAT) are an alternative to using passwords for authentication to GitHub when using the GitHub API or the command line.
- Personal access tokens are intended to access GitHub resources on behalf of yourself.

- GitHub currently supports two types of personal access tokens: fine-grained personal access tokens and personal access tokens (classic).
- Fine-grained personal access tokens have several security advantages over personal access tokens (classic):

1. Each token can only access resources owned by a single user or organization.
2. Each token can only access specific repositories.
3. Each token is granted specific permissions, which offer more control than the scopes granted to personal access tokens (classic).
4. Each token must have an expiration date.
5. Organization owners can require approval for any fine-grained personal access tokens that can access resources in the organization.
6. Additionally, organization owners can restrict the access of personal access token (classic) to their organization.

- source: GitHub
