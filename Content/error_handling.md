# Error Handling

- **401 Unauthorized**: verify the token.
- **Rate limit**: headers `X-RateLimit-Remaining` and `X-RateLimit-Reset`. If `0`, wait the reset.
- Error handling in Notebook Python with `resp.raise_for_status()`.
