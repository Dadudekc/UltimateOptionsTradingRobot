# Config Directory

The Config directory contains configuration files used throughout the project. This includes settings files, environment variables, and any configuration scripts necessary for initializing the system.

## Contents
- `config.yaml`: Main configuration file for system-wide settings.
- `secrets.env`: Environment variables file for sensitive information (e.g., API keys).
- Additional configuration files for individual components as needed.

## Guidelines
1. Keep sensitive information (like API keys) in `secrets.env` and avoid hardcoding secrets in code.
2. Use standardized formats (e.g., YAML or JSON) for all configuration files to maintain consistency.
3. Update and document all changes in configuration files to prevent misconfigurations.