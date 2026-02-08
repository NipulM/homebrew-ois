# Homebrew Tap for OIS

This tap provides Homebrew formulae for [OIS (Orchestrated Infrastructure Scaffolder)](https://github.com/NipulM/oisbase).

## Installation

```bash
brew tap NipulM/ois
brew install ois
```

Or install directly:

```bash
brew install NipulM/ois/ois
```

## Available Formulae

### OIS - Orchestrated Infrastructure Scaffolder

Interactive CLI tool that scaffolds production-ready Terraform configurations for AWS infrastructure.

**Features:**

- Multi-environment support (dev/staging/prod)
- Service-specific state management
- Production-ready Terraform templates
- Incremental service addition

**Usage:**

```bash
# Initialize a new project
ois init

# Add AWS services
ois add lambda
ois add dynamodb
ois add rds
```

## Documentation

Full documentation available at the [main repository](https://github.com/NipulM/oisbase).

## Issues

Report issues at: https://github.com/NipulM/oisbase/issues

## License

MIT
