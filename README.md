# Cleanup GitHub Action

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/cleanup-action/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/Scalified/cleanup-action?style=flat-square)](https://github.com/Scalified/cleanup-action/releases/latest)

## Overview

A simple GitHub Action to clean the workspace, user-defined paths, and Docker containers/images

## Usage

```yaml
- name: Cleanup
  uses: scalified/cleanup-action@v1
  with:
    paths: >-
      /opt/storage
      /home/.npmrc
    docker-image: my-docker-image:latest
```

## Inputs

| Input          | Description                                       | Required | Default |
|----------------|---------------------------------------------------|----------|---------|
| `workspace`    | Whether to clean up the workspace directory       | No       | `true`  |
| `paths`        | List of files and directories to remove           | No       | `""`    |
| `docker-image` | Docker image to remove, along with its containers | No       | `""`    |

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
