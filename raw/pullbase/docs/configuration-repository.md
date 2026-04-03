Source: https://docs.pullbase.io/configuration-repository
Title: Configuration Repository Guide

Pullbase reads a Git repository to determine desired state for each environment. The repository convention centers on a config.yaml at the root, which can describe packages, services, and files to manage on a target server.

Core concepts:
- repository-backed desired state
- config.yaml at the root of the repo
- declarative packages, services, and files
- environment-specific configuration
