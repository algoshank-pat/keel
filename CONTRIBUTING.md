# Contributing

Thanks for your interest in improving <PROJECT NAME>! This project welcomes issues and pull requests.

## Getting started

1. Fork the repo and clone your fork.
2. Set up the dev environment:
   ```bash
   python -m venv .venv && source .venv/bin/activate
   pip install -r requirements.txt
   pip install -r requirements-dev.txt   # linting, tests
   ```
3. Create a branch: `git checkout -b feat/your-feature`.

## Before you open a PR

- **Open an issue first** for anything larger than a typo or small fix, so we can align on the approach.
- Run the checks locally:
  ```bash
  ruff check .        # lint
  ruff format .       # format
  pytest              # tests
  ```
- Add tests for new behavior. Keep PRs focused — one logical change per PR.
- Write a clear PR description: what changed, why, and how you verified it.

## Commit style

Use clear, present-tense messages. Conventional Commits are appreciated but not required:

```
feat: add hybrid reranking step
fix: handle empty retrieval results
docs: clarify ingestion command
```

## Code of conduct

Be respectful and constructive. We're all here to build something good.

## Questions?

Open a [discussion](https://github.com/algoshank-pat/<REPO>/discussions) or reach out at <EMAIL>.
