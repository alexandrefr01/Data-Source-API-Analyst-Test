# Documentation of GitHub´s API

## Endpoints:

- GET /users/{user}/repos → return publics repos
- GET /repos/{owner}/{repo}/commits →  return commits (use query params per_page e page).

## Headers:
- Authorization: Bearer <TOKEN>
- Accept: application/vnd.github.v3+json

## Paginação:
- Use parameter `page`.
- Verify header `link` with `rel="next"` for new pages :contentReference[oaicite:12]{index=12}.
