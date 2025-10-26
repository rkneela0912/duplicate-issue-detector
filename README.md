# Duplicate Issue Detector 🔍

[![GitHub release](https://img.shields.io/github/v/release/rkneela0912/duplicate-issue-detector)](https://github.com/rkneela0912/duplicate-issue-detector/releases) [![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Detect duplicate issues

## Quick Start

```yaml
name: Duplicate Issue Detector
on:
  pull_request:
    types: [opened, synchronize]

jobs:
  run:
    runs-on: ubuntu-latest
    permissions:
      pull-requests: write
      issues: write
    steps:
      - uses: rkneela0912/duplicate-issue-detector@v1
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```

## Features

- Automated GitHub Actions workflow
- Easy to configure
- Production-ready
- MIT licensed

## Inputs

| Input | Description | Required |
|-------|-------------|----------|
| `github_token` | GitHub token for API access | ✅ Yes |

## License

[MIT License](LICENSE)

## Support

⭐ Star this repo if you find it helpful!

For issues, [open an issue](https://github.com/rkneela0912/duplicate-issue-detector/issues).

## 💡 🔍 Reduce duplicate work

Make your workflow more efficient with automation!
