# Cleanup GitHub Action

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/cleanup-action/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/Scalified/cleanup-action?style=flat-square)](https://github.com/Scalified/cleanup-action/releases/latest)

## Overview

A simple GitHub Action to clean the workspace and user-defined paths

## Usage

```yaml
- name: Cleanup
  uses: scalified/cleanup-action@v1
  with:
    paths: >-
      /opt/storage
      /home/.npmrc

```

## Inputs

| Input   | Description                             | Required | Default |
|---------|-----------------------------------------|----------|---------|
| `paths` | List of files and directories to remove | No       | `""`    |

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
