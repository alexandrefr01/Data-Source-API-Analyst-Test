# Documentation of GitHub´s API

## Endpoints:

- GET /users/{user}/repos - return all repos from user
- GET /repos/{user}/{repo}/commits - return all commits from a repository
- GET /repos/{user}/{repo}/contents - return all contents from a repository

## Headers:
- Authorization: Bearer <TOKEN>
- Accept: application/vnd.github.v3+json

## Pagination:
- Use parameter `page`.
- Verify header `link` with `rel="next"` for new pages :contentReference[oaicite:12]{index=12}.
