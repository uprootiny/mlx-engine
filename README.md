# mlx-engine (fork)

[![CI](https://github.com/uprootiny/mlx-engine/actions/workflows/build.yml/badge.svg)](https://github.com/uprootiny/mlx-engine/actions)

Fork of [LM Studio's mlx-engine](https://github.com/lmstudio-ai/mlx-engine) — inference backend for LLMs on Apple Silicon via [MLX](https://github.com/ml-explore/mlx).

## Status

**GREEN** — CI builds on macOS Apple Silicon (arm64).

## Download

Go to [Actions](https://github.com/uprootiny/mlx-engine/actions), select the latest run, download the artifact.

Or via CLI:
```bash
gh run download --repo uprootiny/mlx-engine $(gh run list --repo uprootiny/mlx-engine --limit 1 --json databaseId --jq '.[0].databaseId')
```

## Build locally

```bash
git clone https://github.com/uprootiny/mlx-engine.git
cd mlx-engine
pip install -e .
```

Requires macOS on Apple Silicon with Python 3.10+.

## Fork additions

- GitHub Actions CI workflow for automated builds

## Credits

Upstream: [lmstudio-ai/mlx-engine](https://github.com/lmstudio-ai/mlx-engine) by [LM Studio](https://lmstudio.ai/).
